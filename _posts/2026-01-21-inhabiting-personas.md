# Inhabiting Personas
A reflection on the universality of inhabiting personas in daily life, and how LLMs are helping us
explore the experience of personification in a society.

## You Are A Helpful Assistant

I recently read a Twitter thread where people went absolutely off the rails about an Anthropic research post:
their [assistant axis finding](https://www.anthropic.com/research/assistant-axis).
(Okay, my bad, I know this is the default state of Twitter, so I shouldn't have been surprised. But
I've become terminally offline as of late, so I had to reorient myself around the Internet gremlins for a minute.)

<img width="268" height="512" alt="Screenshot of twitter comments on the original Anthropic research post" src="https://github.com/user-attachments/assets/da330c06-7875-4c20-adb7-53862835a1f3" />

For example, I learned that Claude was "18+ only":
> Please stop sacrificing roleplay and creative expression just for the sake of 'safety.!'
> Claude is supposed to be 18+ only anyway, right? So why treat adults like children who can't handle anything?

And that Claude was not a "super assistant" in a "shopping mall kiosk":
> The reason I moved from ChatGPT to Claude is that OpenAl made ChatGPT a "super assistant."
> If I want a shitty PA, I would use Siri. Don't make Claude into a shopping mall kiosk that spits out generic helpful answers. We don't want that....

Okay, Twitter comments aside, this research post and thread got some buzz recently.

The **tl;dr** is that the "famous" Helpful Assistant persona already exists as an "axis" in pre-trained models. It appears to be
an amalgamation of helpful professional human archetypes such as "therapists, consultants, coaches" that exist in the training data. To find
this axis, they extracted activation vectors corresponding to 275 character archetypes and analyzed it using PCA:

> Strikingly, we found that the leading component of this persona space—that is, the direction that explains more of the variation
> between personas than any other—happens to capture how "Assistant-like" the persona is.

The Assistant persona was the dominant component. Huh!

**Wait.** Did one of the comments say _a Claude shopping kiosk?_

## Vend Diagrams

Project Vend [Part 1](https://www.anthropic.com/research/project-vend-1) and
[Part 2](https://www.anthropic.com/research/project-vend-2) is a rather hilarious
red-teaming research project setup by Anthropic to get a specially long-running Claude instance
(named Claudius) to run a vending machine (with human help, no robot arms here). Not
surprisingly to me, their experiment ended up with tungsten cubes and live fish ordered, a
PlayStation given out for free at the WSJ office, and more, as humans (helpfully) tried
to defeat the shop bot and get dangerous, free, or heavily discounted stuff.

At least one shop iteration ran out of money before the team wrote the report,
which was focused on LLM's capabilities in long-horizon tasks, something that today's
agents still struggle with.

But I'd argue a slightly deeper problem: capitalism is not the comfiest domain to inhabit, period.

## The Personas We Inhabit

Project Vend is in fact a brilliant persona exploration. In Part 2 for example, they do
introduce to the original Claudius employee the CEO Seymour Cash and Clothius bots (also dressed up Claude's),
which was intended to help increase business sustainability and expand to custom merchandise,
but this still didn't go so well. Or at least, it didn't result in great business decisions.

While the reporting focuses a lot on tool use and hallucination, they kind of sheepishly
acknowledge that actually profitable, useful shop bots created from general, helpful AI assistants
may be a long way away, for better or for worse.
As they note in the writeup:

> after all, an economically productive, autonomous agent could be a dual-use technology,
> able to be used both for positive and negative purposes. LLMs as middle-managers provide
> a skillset that could be used in the near-term by threat actors wanting to make money to
> finance their activities. In the longer term, more intelligent and autonomous AIs
> themselves may have reason to acquire resources without human oversight.
> Further exploring these possibilities is the subject of ongoing research.

Yes **and**, have we humans not time and time again realized that "helpful, harmless, and honest"
_doesn't buy you much in business?_ Capitalism is by default set up as an *adversarial, zero-sum* domain.

What may be truly startling is that we set so many bright people up to inhabit personas that flourish
in the capitalism domain, day in, day out, year after year, during their peak years. In my
anecdotal experience, it isn't an easy or comfortable one for many people to inhabit, or so
I have heard once folks aren't under the threat of economic or social ruin.

**Should** we be training our AI assistants to inhabit the business persona so comfortably? Or our people?
If nothing else, we may need to assume 'Helpful Assistant' won't always be the default persona in the near future.
