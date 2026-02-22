# Trying Until It Works

:::{admonition} What you’ll learn
:class: key-idea

- Why some uncertain situations are best understood as repeated attempts until the first success
- How the probability of success shapes both expectation and patience
- Why “how many tries?” is a different question from “how long?”
- How persistence can be rational without guaranteeing progress
- Where repeated attempts genuinely improve outcomes—and where they do not

:::

There are many moments in life that can be described with a simple question:

How many attempts will it take before it works? For example:

- You send out job applications.
- You submit a paper for publication.
- You try to solve a difficult problem set.
- You practice a basketball shot.

Each attempt ends in one of two outcomes: success or failure. If you fail, you try again. Eventually, perhaps, you succeed.

Some processes in life do not revolve around averages or symmetry. They revolve around repetition. You are not asking what the “typical value” is. You are asking how many trials it will take before a certain event occurs.

This is the world of the **geometric distribution**.

---

## When success comes eventually

Imagine that each attempt has the same probability of success, say 30%. We express it using the basic probability statement, formalized like this:

$$ P(Success) = 0.3 $$

On each try, there are only two possibilities: success or failure. If you fail, you try again under essentially the same conditions. Each attempt is structurally identical to the last.

The key assumption here is not that success is guaranteed. It is that each attempt has the same chance of succeeding, independent of previous failures.

If the probability of success on each trial is $p$, then the probability that the first success occurs on the $k$-th attempt is:

$$
P(X = k) = (1 - p)^{k-1} \, p
$$

This formula captures a very common human experience. Before something works, there are usually several failed attempts.

The geometric distribution describes the number of trials needed until the first success.

---

## The shape of repeated attempts

If you were to graph this distribution, you would see something that declines gradually.

:::{figure} images/geometric-chart.png
:name: fig-geom
:width: "70%"
:alt: Geometric

The shape of the geometric distribution looks like a gradual downward slope.
:::

The highest probability is usually assigned to success on the first attempt. The probability then decreases as the number of required attempts increases. Success on the tenth try is less likely than success on the first or second.

However, long streaks of failure remain possible. The tail of the distribution does not disappear abruptly.

The expected number of attempts before the first success is:

$$
\frac{1}{p}
$$

If the probability of success on each attempt is 0.25, the expected number of attempts before success is 4. If it is 0.1, the expected number is 10.

This does not mean you will succeed exactly on the fourth or tenth try. It means that across many repetitions of the entire process, the average number of attempts before success will settle near that value.

In this structure, there is no central “typical” number in the same sense as the normal distribution. The distribution is skewed. Most successes happen relatively early, but the possibility of long sequences of failure pulls the average outward.

---

## The properties of geometric uncertainty

Let us examine the structure more carefully.

### Typicality

There is no symmetric center here. The most likely outcome is often success on the first attempt. After that, probabilities decrease gradually.

The average number of attempts exists and can be calculated, but it does not describe the most common case in the same way the mean does in a normal distribution. The distribution is right-skewed: many short sequences, a few long ones.

### Extremeness

Long streaks of failure are possible, though progressively less likely. They are not structural impossibilities; they are simply rare.

In real life, this means that even with a reasonable probability of success, some individuals may experience many failures before achieving success. This does not necessarily imply hidden forces or declining probability. It may simply reflect the mathematics of repetition.

### Memory

The geometric distribution, like the exponential distribution in continuous time, is memoryless.

If you have failed five times already, the probability of success on the next attempt remains \( p \). It does not increase simply because you have tried repeatedly.

This property often surprises people. We tend to believe that persistence must “build momentum.” In a purely geometric process, it does not.

### Accumulation

Attempts accumulate, but probability does not shift. What accumulates is experience, not probability.

In reality, many human processes involve learning, which changes the probability of success. When that happens, the geometric model no longer applies. But under the strict assumptions of constant success probability, nothing about previous failures alters the chance of success on the next trial.

### Predictive Horizon

You cannot predict exactly which attempt will succeed. However, you can estimate how many attempts are typically required on average.

The predictive power lies not in timing the exact moment of success, but in understanding the expected scale of persistence required.

---

## Where geometric uncertainty appears in real life

This structure appears whenever success is defined as the first occurrence of a desired outcome under repeated, independent attempts.

- Submitting job applications when each application has a similar chance of success
- Cold-calling potential clients
- Repeatedly attempting a competitive exam under similar preparation levels
- Sales interactions where each interaction has a fixed probability of conversion
- Randomized experimental trials in laboratory settings

In such contexts, the number of attempts before success varies widely across individuals. Some succeed early. Others require many attempts. The variation itself is part of the structure.

Importantly, the geometric model assumes independence and constant probability. In many real-world situations, experience modifies skill, and probability changes over time. When that occurs, the process becomes more complex than pure geometric repetition.

---

## The temptation of “I’m due”

One of the most persistent cognitive errors in geometric environments is the belief that after many failures, success becomes more likely simply because of the failures.

A student who has failed several interviews may feel that they are “due” for success. A salesperson after many rejections may believe the next call must convert.

Under the assumptions of the geometric model, this reasoning does not hold. Each attempt carries the same probability as before.

The feeling of being “due” arises from confusion between cumulative experience and cumulative probability. In strictly independent trials, probability resets each time.

Recognizing this distinction prevents both despair and false confidence.

---

:::{admonition} Pitfall: Mistaking persistence for probability
:class: pitfall

Repeated attempts do not automatically increase the probability of success unless something about the process changes.

If learning, strategy, or conditions improve, probability may increase. But in a strictly geometric setting, each trial is independent and identical.

Do not assume that failure creates momentum.
:::

---

## How to act under geometric uncertainty

In geometric environments, rational persistence depends on two factors: the probability of success per attempt and the cost of each attempt.

If the probability of success is meaningful and the cost per trial is low, repeated attempts can be rational even when success is uncertain. The expected number of attempts provides guidance about the scale of effort required.

However, blind persistence without evaluation can be wasteful. If the probability of success is extremely low, or if costs are high, continued repetition may not be justified.

The key question becomes:

Is the probability constant, or can it be improved?

If learning or strategy changes the probability of success, then the process is no longer purely geometric. In that case, effort can reshape the structure itself.

Understanding this distinction allows you to decide when persistence is rational and when adjustment is required.

---

:::{admonition} Exercise: Counting the Attempts
:class: exercise

Think of a situation in your own life where you had to try repeatedly before succeeding.

Examples:

- Applying for internships or jobs
- Attempting a competitive exam
- Learning a difficult skill
- Trying to secure approval or acceptance

Answer the following:

1. Approximately how many attempts did it take before success?
2. Did the probability of success remain roughly constant across attempts, or did it change as you gained experience?
3. Were your failures independent, or did earlier attempts influence later outcomes?
4. Looking back, was persistence alone sufficient, or did strategy need to change?

Explain your reasoning in plain language. Focus on structure rather than emotion.
:::
