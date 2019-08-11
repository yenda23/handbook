# Data Platform Engineering Values


FIXME - we need to show how they overlap and polish ours a bit

Core DTOne values are **Be Ambitious**, **Diversity is an Asset**, **Do the right thing**, **Work smart** and **Passion with Purpose**. We have extended those with the following **Openness** (Default to transparency), **Honesty**, **Being excellent to each other**, **Delivery** (Default to action), **Personal responsibility**, **Be yourself** and **Constant learning**.

## Collaboration & Openness

Working and helping others is a priority, even if you don't see a direct relationship to the goals that you are trying to achieve. Anyone can chime in on any subject. Fact that somebody is part of a particular team doesn't mean that she cannot provide view, help or suggestion for working being done by somebody else. The person who's responsible for the work decides how to do it, but they should always take each suggestion seriously and try to respond and explain why it may or may not have been implemented.

### Openness

Being **open** and **honest** to each other is very critical component of our success. We **default to transparency**, meaning that you should make everything accessible by default and only solve for limited access rights in special cases. Place your files in shared drives (aka Team Drives). Don't just share 1:1 content, which could be generally interesting. Capture your progress in appropriate tickets.

There is a lot of information flows, we suggest you always follow [Data Platform Engineering Weekly](https://dpew.dtone.enineering) which provides summary of recent week.

Such level of openness / sharing can be counter-intuitive for new team members. Invest extra time into explaining why we are trying to exercise extreme transparency; engage in open dialogue; walk extra mile to allow sharing (for example make a private issue or post-mortem public, so we all can learn from it).

Check [sharing tips section](tech-tips/sharing.md) for couple technical tips how to improve sharing.

### WHY? WHY? WHY? and maybe WHAT? and HOW?

Always try asking yourself **why** question [multiple times](https://www.inc.com/jason-surfrapp/the-theory-of-the-3-whys.html). Number loved by many is 3, but feel free to ask 5 times or just 2. Just anything what is appropriate.

When writing ticket, try to provide complete context -- **why**, **what** and then maybe **how**. Typically, you would either skip the "how" completely or make it just suggestion to allow responsible person come up with the best solution.

### Fairness

Be Always fair to each other. Expect that others are not trying to cause harm. Always make your best to evaluate people accurately. That doesn't mean being dehonesting, always try to be kind. Give as much positive feedback as you can. Keep it concrete, focused and public. Don't bring negative feedback to public forums, keep it to the smallest setting possible (typically 1:1 call/meeting would be preferred).

#### Say thanks

Don't forget to give credit where credit is due. But also a simple "thank you" in a company/team-wide channel will do a lot.

#### Say sorry

If you made a mistake, apologize. Saying sorry is not a sign of weakness but one of strength. The people that do the most work will likely make the most mistakes. Additionally, when we share our mistakes and bring attention to them, others can learn from us, and the same mistake is less likely to be repeated by someone else.

This concept extends to post-mortems. In case of high-profile issue (e.g. downtime on production systems), always have a ticket(s) tracking issue(s) and their resolution as well as write down *post-mortem* (see below).

#### Assume positive intent

Always keep in mind, that we frequently fall victim of the [Fundamental Attribution Error](https://en.wikipedia.org/wiki/Fundamental_attribution_error). In the nutshell -- we blame circumstances for our own mistakes, but others for theirs. In order to fight this urge, you should always [assume positive intent](https://www.lifehack.org/articles/lifestyle/assuming-positive-intent-the-ultimate-productivity-driver.html) in your interactions with others. Especially when this interaction happens over elecronic channels (email, chat).

#### Giving feedback

Giving feedback is not easy thing; but receiving feedback is even more challenging. When delivering feedback, always focus on the work itself, emphasis business or technical impact, never the person. Make sure, that you provide at least one recent and clear example. Try to factor in external factors (maybe parson is going through some family crisis for example).

Nobody has 100% delivery, you should evaluate if the particular issue is even worth giving a feedback. Especially, if you are manager, keep in mind, that negative feedback is typically taken [way more (6x) seriously](https://hbr.org/2013/03/the-delicate-art-of-giving-fee) than positive one.

Always keep in mind, that we are giving feedback to **improve**.

### Blameless problem solving and post-mortems

Mistake or issue is always a learning opportunity. Result of (almost) every troubleshooting should be documented. Normally we would just update appropriate ticket in Phabricator. For high-profile issues (e.g. production affecting down-time) we always have a tracking ticket(s), but also will produce a [**blameless** post-mortem](https://codeascraft.com/2012/05/22/blameless-postmortems/). Focus of such analysis are components of the failure, what sequence of events and decisions led to an issue. It is **never** about casting a blame on a person or team. Anybody can (and should) speak up without fear of punishment or retribution.

### Get to know each other

We are spread all around the Wold and also use a lot of text-based communication tools (email, chat, tickets). We don't have "luxury" of being able to meet everybody in person, go together to lunch. Thus is very important to engage in activities which are trying to supplement random and more causal interactions. We are currently doing the following:

- [donut calls](https://www.donut.com/pairing/) organized via `#donut` Slack channel every Monday. Please make sure, that you are member of the channel as well as you schedule and participate on the call with the selected counterpart.
- Follow [Data Platform Engineering Weekly](https://dpew.dtone.enineering).
- Czech Coffee Break (CCB) are happening every day at 13:00 CET.

## Delivery

### Measure results not time

We care about your delivery and achievement. Not if you are spending 12 hours in the office. You don't need to defend how you spend your day. Everybody is most productive in different times.

Frequently, we all spend more hours, working at night or weekend. But we do it because we are passionate about what we do. On the other side, if you are working constantly too many hours, talk to your manager to find solutions.

### Do it yourself

Our collaboration value is about helping each other when we have questions, need critique, or need help. No need to brainstorm, wait for consensus, or [do with two what you can do yourself](https://www.inc.com/geoffrey-james/collaboration-is-the-enemy-of-innovation.html).

Sometimes, it is obviously important to call in multiple people to make a strategic level decision and weight different options. But we want to avoid [analysis paralysis](https://en.wikipedia.org/wiki/Analysis_paralysis). Decisions should be thoughtful, but delivering fast means that we can make mistakes. We should not fear them, but be ready to fix them quickly. That may inform our design decisions (e.g. prefer modularized design instead of monolyth).

### Ownership

We expect everybody to own what they are doing, task they have assigned to. Owning the work, means that you are responsible for that particular piece to be done. Be proactive in informing stakeholders when there is something you need help with, you are not able to solve on your own.

### Keep bigger picture in mind

When making decisions, always keep bigger picture in mind. Optimize for the whole company, not only for you team or yourself. For example if fulfilling your goal is going to have a negative impact on somebody else (other colleague, team, company or customers), you should raise the flag as such goal is probably incorrect. Help others to achieve their goals. This means, that if you are blocking somebody (e.g. they are waiting for decision, merge request review, answer to question) your top priority should be to unblock them. Unblocking can also mean, that you will help them find more appropriate person to handle the request.

## Work smart, work efficiently

We care about getting rid of work which can be replaced with automation as well as we try to avoid duplication.

[Amazon states it best](http://www.amazon.jobs/principles) with:

> Accomplish more with less. Constraints breed resourcefulness, self-sufficiency and invention. There are no extra points for growing headcount, budget size or fixed expense.

### No fashion business

IT became a fashion business, people have tendency to follow hype. Try to avoid picking a solution just because it is interesting. Evaluate if introducing it into our stack is viable *long term*. Do we have enough experience, can we run it at scale. If not, is it worth learning it and building necessary tooling around it?

### Embrace UNIX approach

One of the key aspects of UNIX systems (at least for me) is ecosystem of small utilities (and pipes). These tend to have very limited scope, but they try hard to be the best in addressing it. You can think about this on many levels -- code organized into modules / libraries, microservices (vs monoliths) etc. Even complex problems are easier to solve, when decomposed. Don't trust tools (and vendors) who are promising to solve everything in one tool / application.

### Respect others' time

Always try to be on time. People waiting for each other are basically just wasting their time.

Avoid unnecessary meetings. Don't use meetings to get permission, use it to get opinions, suggestions, fresh ideas. When is meeting necessary always

- try to make attendance optional for as many people as possible;
- try to have meeting agenda linked from your meeting invite;
- document the outcome (meeting minutes, ticket(s)).

Think about multiplication effects, when sending one-to-many communication (e.g. emails). If one needs 10 minutes to read your email, and you have send it to 15 people, you have just potentially wasted 150 minutes. Try to provide summary (famous [TL;DR](https://www.lifewire.com/what-is-tldr-2483633)) at the beginning of longer text.

### Responsibility over Rigidity

We believe, that it is better to give people freedom and responsibility to make a decisions and hold them accountable for that instead of imposing complicated rules and rigid approval processes.