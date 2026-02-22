# Waiting Without Memory

## Why waiting feels like progress

:::{admonition} What you’ll learn
:class: key-idea

- Why waiting often feels like progress, even when nothing is accumulating
- How some processes have no memory and do not “age” over time
- Why the probability of an event may remain constant, no matter how long you have already waited
- How “due” thinking emerges from confusing elapsed time with structural change
- When patience is rational—and when it is merely psychological comfort

:::

Each of the distributions we talk about in this book is used to model some uncertain situation in life. The uniform distribution is used to model processes in which every outcome has equal probablity-like the game of dice or roulette. The normal distribution is used to model processes that depend on many smaller and unpredictable factors-like the human height or average grade in school.

In this chapter, we will focus on a probability distribution that can help us model situations in which we wait for some event to occur.

Human beings have a remarkably persistent intuition about time: when something has not yet happened, and enough time has passed, we begin to feel that it is somehow closer to happening. The mere passage of time is experienced as movement toward an outcome.

Waiting, in other words, sometimes feels like progress.

Consider a simple and familiar situation. You are waiting for a bus that is known to arrive at irregular intervals (imagine a very unpredictable bus). Ten minutes pass, then fifteen, then twenty. With each passing minute, it becomes increasingly difficult to maintain the thought that your situation is unchanged. Even if you know, abstractly, that the bus operates without a precise schedule, your experience of waiting suggests that the probability of its arrival must be increasing.

The longer it has failed to appear, the more “due” it seems.

A similar pattern appears in many everyday contexts. When a customer service representative has not yet answered your email after several days, you begin to expect a reply soon because the silence itself feels like accumulated evidence. Or, when a machine has been operating without failure for years, we often assume that breakdown is imminent, as though uninterrupted functioning were storing up some latent fragility.

Even in matters of health, a person who has experienced a persistent but unexplained symptom for weeks may begin to feel that a diagnosis or event is approaching, simply because the waiting has been prolonged.

What these examples share is a subtle cause-effect implication: elapsed time is treated as information. We implicitly assume that each additional unit of waiting changes the underlying situation. The fact that the bus has not yet arrived, that the email has not yet been answered, or that the machine has not yet failed is interpreted not merely as the absence of an event, but as evidence that the event is becoming **more likely**.

This way of reasoning is deeply natural. In many areas of life, accumulation does matter. Effort accumulates into skill; the more you do something the better you are at doing it. Small changes to some system accumulate into large ones; play soccer with a single ball for years, and the ball will wear off, to the point of breaking. Repeated stress accumulates into damage. In such environments, time passing genuinely alters the structure of the system. That's why it is understandable that we generalize this pattern and apply it broadly.

However, **the intuition that waiting itself constitutes progress** rests on an assumption that may or may not be warranted. It assumes that the underlying process has memory; that the system keeps track of how long it has been since the last event and adjusts its probabilities accordingly. The psychological force of waiting comes from this assumption of accumulation. We do not merely endure time; we interpret it as building pressure toward (some kind of) resolution.

:::{admonition} Pitfall: Futile waiting
:class: pitfall

Sometimes, the fact that we're waiting for something to happen doesn't mean it will happen soon.

:::

The difficulty, and the reason this intuition deserves careful examination, is that not all processes possess such memory. In some cases, the passage of time does not alter the likelihood of what comes next. Yet our minds, shaped by experiences in which accumulation is real, continue to treat waiting as if it were evidence.

Before we can understand the structure of memoryless processes, we must first recognize how strong the opposite expectation is: that time itself carries momentum.

⸻

## When the past does not accumulate

The intuition that waiting generates progress rests on a hidden assumption: that the process we are observing **keeps track of the past**. We imagine that the system, in some way, remembers how long it has been since the last event and adjusts accordingly. Yet there are many processes in which this assumption is simply false. In such cases, the passage of time does not alter what is likely to happen next.

To see this more clearly, consider a classic example from physics: radioactive decay. A radioactive atom has a certain probability of decaying within a given interval of time. If it has survived for one hour, this survival does not make it more or less likely to decay in the next minute. Its “age” does not matter. The atom does not accumulate pressure toward decay. Each moment presents the same chance as the moment before. The process **does not remember** how long it has been waiting.

A less technical example can be found in certain mechanical failures. Imagine a simple electronic component, like a Playstation controller, that fails randomly due to microscopic fluctuations in material structure. If it has functioned without incident for three years, this longevity does not necessarily imply that failure is imminent. Provided that the failure mechanism is truly random and does not depend on wear, the probability of breakdown in the next hour is the same regardless of how long the component has already been operating. The system does not count the years behind it.

The same logic applies in more mundane settings. Suppose you are waiting for a phone call that could occur at any unpredictable moment during the day. If the phone has not rung for several hours, it is tempting to feel that it must ring soon. Yet if the call is equally likely to occur at any minute, then the probability of receiving it in the next minute is no greater at 5 p.m. than it was at noon. The hours that have passed do not accumulate into increased likelihood; each minute is _statistically fresh_.

Or consider a small shop on a quiet street. Customers enter at irregular intervals. If no one has entered for twenty minutes, the shopkeeper may begin to expect a customer momentarily. However, if arrivals occur randomly with a constant rate, the chance that someone walks in during the next minute is independent of how long the shop has been empty. The silence does not intensify the probability of interruption because the process does not build tension.

In each of these cases, nothing is “building up.” There is no hidden reservoir of likelihood growing with time. The system does not move closer to the event simply because the event has not yet occurred. Instead, it resets continuously. Each new moment begins under the same probabilistic conditions as the previous one.

This conclusion runs counter to our ordinary experience because in many other domains accumulation is real. But in memoryless processes, the past exerts no influence on the immediate future. Waiting does not bring one closer; it merely extends the interval during which the same probability applies. Recognizing this feature requires a shift in perspective: we must separate the feeling of temporal momentum from the structure of the underlying process.

:::{admonition} Key idea: memoryless process
:class: key-idea

Memoryless processes do not 'remember' the past: the fact that something hasn't happened in the immediate past, doesn't mean it's bound to happen soon.

:::

⸻

## The shape of memoryless uncertainty

This type of distribution is called the exponential distribution (because the formula for it included an exponent).

If we were to draw this kind of uncertainty, it would not resemble the symmetric hill of the normal distribution. Instead, it would begin high at the origin and then slope downward, gradually thinning as time extends. Many events occur relatively early, fewer occur later.

:::{figure} images/exponential-chart.png
:name: fig-expon
:width: "70%"
:alt: Exponential

The shape of the exponential distribution looks like a downward hill.
:::

The longer the waiting time, the smaller the fraction of cases that persist that long.

At first glance, this shape may seem to suggest that something is “winding down,” as though the system were exhausting its possibilities. But that interpretation would be misleading. The declining curve does not reflect aging or fatigue. It reflects the fact that, **at every moment, there is a constant chance that the event will occur**. Because that chance applies repeatedly over time, more and more cases resolve early, leaving fewer to extend into the far tail.

The crucial feature of this distribution is therefore not merely that it slopes downward, but that the process generating it does not age. A case that has survived for a long time is not, by virtue of that survival, closer to resolution than a case that has just begun. Lightbulbs are a good example of this: a two-year old lightbulb and a brand new lightbulb (from the same manufacturer) have exactly the same probability of failing.

<span class="highlight">The probability that the event occurs in the next short interval is the same regardless of how long one has already waited</span>.

To understand this intuitively, imagine that at every small unit of time (say, each minute) there is a fixed chance that the event occurs. If the event does not occur in one minute, the next minute begins under identical conditions. There is no accumulation or pressuer: the system does not “remember” its history.

This is what we mean, more formally, by saying that the process has a **constant risk per unit time**. The likelihood of occurrence over the next moment does not depend on how long the process has been running. Time stretches forward, but the structure of risk remains unchanged.

In this respect, memoryless uncertainty stands in contrast to the distributions we have previously examined. There is no central value toward which outcomes gravitate, as in the normal distribution. There are no accumulating streaks, as in certain binary processes. There is simply the steady application of the same probability, moment after moment.

The result is a distribution in which early occurrences are common and long waits are increasingly rare, yet the mechanism generating both is uniform over time.

⸻

## The properties of waiting without memory

Applying our property lens can further clarify the distinctive character of this form of uncertainty.

#### Typicality

There is a meaningful average waiting time, which can be computed and interpreted. It is expressed numerically, say the average wait time on a customer service call at some company.

However, this average does not correspond to a “typical” experience in the way it does under a normal distribution. In fact, most events occur sooner than the average suggests. The mean is pulled outward by relatively rare but long waits. Thus, while the average exists, it does not describe the most common case.

#### Extremeness

Long waiting times are possible, and they are not sharply cut off. The distribution thins gradually. Extremely long waits are increasingly rare, but they remain possible without abrupt boundary. This gives the tail of the distribution a different character from the thin extremes of the normal case.

#### Memory

There is none. The process does not record how long it has already been underway. A case that has persisted for a long time faces the same immediate probability as a newly initiated one. Survival does not alter risk.

#### Accumulation

Waiting does not build pressure. The mere passage of time does not increase the likelihood of resolution in the next instant. There is no stored potential, no growing tension. Each interval stands alone.

#### Predictive Horizon

The structure of the future is invariant (unchanging) with respect to the past. Knowing that the event has not yet occurred provides no additional information about what will happen in the next small interval, beyond the fixed underlying rate.

This chapter therefore marks a significant conceptual shift in understanding differen shapes of uncertainty.

In many domains of life, we rely (often correctly) on the assumption that time changes things, like experience, learning, or stress. All of these accumulate and that accumulation changes the underlying structure of reality.

But in memoryless processes, this intuition must be suspended. Time passes, yet the underlying probability remains unchanged. Recognizing this fact requires careful separation between psychological expectation and statistical structure.

## Where it appears in real life

Memoryless uncertainty is not confined to physics textbooks or abstract probability models. It appears in many ordinary situations where the risk per unit of time remains approximately constant.

Again, consider the life of a simple light bulb. Suppose it is not gradually dimming or degrading in a predictable way, but instead fails due to random microscopic defects in its filament. If the underlying failure mechanism does not depend on cumulative wear (if each moment carries roughly the same small chance of failure) then the fact that the bulb has functioned for a year does not make it more “due” to burn out tomorrow. Its survival so far does not increase the immediate probability of failure. Each additional hour carries the same risk as the hour before.

A similar structure can appear in communication. Imagine you are waiting for an email in a low-traffic inbox where messages arrive sporadically and independently. If no message has arrived for several hours, it is tempting to feel that one must appear soon. Yet if arrivals occur randomly with a stable rate, the probability that an email arrives in the next five minutes does not increase merely because the inbox has been quiet. The waiting does not accumulate toward resolution; each minute remains statistically fresh.

Public transportation can sometimes approximate this structure. If a bus arrives at random intervals, rather than on a strict timetable, then the probability of its arrival in the next minute may be independent of how long you have already waited. Although the subjective experience of waiting intensifies with time, the underlying risk per minute remains unchanged.

More serious examples can be found in survival contexts where risk is constant over time. If an individual faces a fixed probability of some bad event per year—without aging effects or cumulative damage—then surviving ten years does not make the next year more or less dangerous than the first. The hazard does not grow simply because time has passed.

Similarly, in simplified seismological models, even the time between earthquakes has sometimes been treated in this way. While real geological systems may be more complex, certain models assume that tremors occur with a constant probability per unit time. Under that assumption, a long quiet period does not mean that the next tremor is imminent. It only means that the event has not yet occurred.

What unites these examples is the **constancy of risk per unit time**. The probability of the event occurring in the next small interval does not depend on how much time has already elapsed. There is no hidden accumulation, no mounting pressure, no internal clock counting upward toward inevitability.

Yet in each of these contexts, our psychological response often tells a different story. We interpret extended waiting as progress toward an outcome, and treat silence as evidence that some resolution is near.

We assume that survival has brought us closer to failure.

Recognizing memoryless structure in the world requires separating that intuition from the statistical reality. In environments governed by constant risk, waiting does not move us forward in any probabilistic sense. It only extends the duration over which the same conditions apply.

⸻

## The trap of “due” thinking

Few intuitions are as persistent as the belief that events become more likely simply because they have not yet occurred. We speak of things being “due” as though probability were a kind of debt that must eventually be repaid. The longer we wait, the stronger this sense becomes.

If it has not rained in weeks, we say that rain is overdue. If a machine has been operating without failure for years, we remark that it is bound to break down soon. If someone has submitted multiple applications without success, they may begin to feel that acceptance is approaching as a matter of fairness, as though prior rejections increase the likelihood of the next attempt succeeding.

This pattern of reasoning is psychologically understandable. In many domains of life, repetition and accumulation genuinely matter. However, the difficulty arises when this accumulation logic is applied to processes that do not possess memory. In a memoryless system, the fact that an event has not yet happened carries no additional information about its immediate likelihood. A machine that fails randomly, without aging effects, is no closer to failure after years of operation than it was at the beginning. The probability of failure in the next hour remains unchanged. The same applies to other events governed by constant risk: survival up to this point does not alter the probability of what happens next.

The belief that one is “due” for an outcome is therefore a projection of fairness or balance onto processes that may not contain either. It treats time as if it were storing up probability, as though the universe were compensating for past deviations. But in memoryless environments, there is no such compensation. Each moment begins under the same probabilistic conditions as the one before.

The trap of “due” thinking lies in mistaking elapsed time for accumulated evidence.

⸻

## How to act under memoryless risk

Once the structure of memoryless uncertainty is understood, the practical implications follow with some clarity. If the probability of an event occurring in the next moment does not depend on how much time has already passed, then our behavior must reflect that independence. We must resist the temptation to treat elapsed time as a lever we can pull.

In such environments, merely monitoring how long something has persisted does not, by itself, reduce risk. If a failure mechanism truly operates with constant probability per unit time, then the fact that nothing has happened so far provides no additional assurance about what will happen next. Watching the clock may be psychologically reassuring, but it does not alter the underlying structure.

This has consequences for decisions such as replacement or maintenance. If a component does not age in a way that increases its failure rate, then replacing it simply because it has been functioning for a long time may not be justified. A rational replacement policy in such a case would depend on expected costs and benefits—on the trade-off between the cost of preventive replacement and the cost of unexpected failure—rather than on an intuition that the item is “due” to break. Of course, if aging genuinely exists and the risk increases with time, the analysis changes. The critical task is to determine which structure one is facing before acting.

Similarly, patience alone does not increase probability. Waiting longer for a response, a call, or an event does not improve one’s odds in a memoryless process. If action can alter the probability (by submitting another application, by making a call, by changing strategy) then action may be warranted. But passive waiting does not accumulate advantage simply through duration.

Acting wisely under memoryless risk therefore requires a certain **calmness**. One does not panic merely because time has passed without resolution; the passage of time has not altered the immediate probability. At the same time, one does not infer safety from survival so far. The absence of an event up to this point does not make its occurrence less likely in the next interval.

The discipline consists in separating emotional momentum from statistical structure. Time may feel heavy with expectation, but in a memoryless system it carries no additional weight. Rational behavior begins with recognizing that fact and aligning one’s decisions accordingly.

:::{admonition} Exercise: When You Thought You Were “Due”
:class: exercise

Think of a situation in your own life where you were waiting for something important.

Examples (choose one or use your own):
• Waiting to hear back about a job, internship, or school application
• Waiting for a medical result
• Waiting for someone to reply to a message
• Waiting for something to break, happen, or change
• Waiting for “your turn” in some competitive process

Step 1 — Describe the situation (4–6 sentences)

What were you waiting for?
How long did you wait?
What did the waiting feel like?

Step 2 — Examine your reasoning (3–5 sentences)

At some point, did you feel that the outcome was becoming more likely simply because time had passed?

Did you think you were “due”?

What assumption were you making about how the process worked?

Step 3 — Structural diagnosis (3–5 sentences)

Looking back, was the process actually accumulating toward resolution?

Or was each moment statistically independent of the previous one?

If nothing was building up, what exactly changed as time passed — the system, or just your emotional state?

⸻

Final Reflection (2–3 sentences)

What is the difference between waiting and progress?

Are they always the same?

:::
