---
title: "Lab: DH + AI = ?"
permalink: /schedule/09-models-lab/
toc: true
class_date: 2024-10-24
---

## Lab Topic

> every figure of speech, snowclone, cliché, joke, proposition, statement, and practically every linguistic structure that can be turned into a template is easily explored with a bot. Every work of literature, every writer’s body of work, every literary movement, national literature, and textual corpus is waiting to be analyzed with a Markov chain or other textual generation technique…Social interactions, conversations, calls and responses, platform-defined  interactions (retweets, favorites, and so on) are all ready to be codified into algorithms and explored via bot.
> 
> Leonardo Flores, ["I ♥ Bots"](http://iloveepoetry.org/?p=11221)

#### [Collaborative Lab Notes Doc](https://docs.google.com/document/d/1J8I3zl-dVjJ80KMspLQ3sLsAHf-Wn4l7pl00xrYU9A0/edit?usp=sharing)

### Instructions

We now turn to a topic that has been omni-present in academic and library discourse, exploring the Large Language Models (LLM)—often referred to through the shorthand "AI"—that have emerged in just the past 2-3 years. As scholars [such as Jessica Riskin explain](https://publicdomainreview.org/essay/frolicsome-engines-the-long-prehistory-of-artificial-intelligence), however, humans have sought ways to automate intellectual or creative tasks—or to simulate such automation—since well before the computer age, and indeed our current computer systems' design owes much to this history. What's more, even AI systems that may seem completely opaque have complex but knowable material bases, as scholars such as [Kate Crawford and Vladan Joler show](https://anatomyof.ai/). 

In many cases, it is neither the technology or data itself that is the "black box," so much as it is the corporate structures that prevent scholars or users from interrogating the technologies or their underlying data. It is difficult to write a [media archeology](http://www.digitalhumanities.org/dhq/vol/15/4/000578/000578.html) of an AI like ChatGPT without direct access to its training data or systems. But even the most closely-guarded systems can be studied. Increasingly researchers interested in algorithmic justice have turned to approaches such as ["algorithmic auditing"](https://personalization.ccs.neu.edu/), ["reverse engineering"](https://arxiv.org/abs/1711.01768), or ["probing"](https://thegradient.pub/othello/) to interrogate closed systems, seeking to understand programs and their training data through iterative uses or inquiries that test its boundaries and assumptions. On-the-ground investigation also helps illuminate systems, such as [Time Magazine's expose in January 2023](https://time.com/6247678/openai-chatgpt-kenya-workers/) exposing OpenAI's use of low-wage Kenyan workers to help filter toxic content from ChatGPT. 

Over the past two years, I have explored [how humanistic methods combined with the approaches above might illuminate the inner workings of LLMs](https://ryancordell.org/research/aibibliography/), as well as [how historical text technologies might inform our understanding of and responses to these new platforms](https://ryancordell.org/research/scissors-paste-LLMs). Similarly, in the [most recent issue of _PMLA_](https://www.cambridge.org/core/journals/pmla/issue/48199E7E125C2966167AB2934310A464), the premier journal of the Modern Language Association, scholars—including several prominent digital humanists—wrestle with the implications of AI to the future of our field, and some argue that the humanities will be needed more than ever to understand these deeply contextual models.

With that context, our aim today is to explore a few of the most current AI language models, considering what they might offer for research and writing tasks, but also probing their limitations. Our goal is not total understanding—which would require a chart at least as enormous as that produced by Crawford and Joler—but to ground our thoughts in practical experiment and experience.

#### LLMs for Today's Lab

+ [ChatGPT](https://chatgpt.com) (aka GPT-4)
+ [OpenAI Playground](https://platform.openai.com/playground/chat?models=gpt-4o) (note: if you sign in with your UIUC credentials you should get some free credits to work with)
+ [Claude](https://claude.ai)
+ [Llama](https://www.llama.com)
+ [Gemini](https://gemini.google.com)
+ [NovelAI](https://novelai.net)
+ [Google Notebook LM](https://notebooklm.google.com)
+ if you have some programming background and access to an LLM's API, feel free to use that directly

### Lab Tasks

#### Lab Task #1: Generation

This first task has only one practical outcome, which is: _In tandem with a large language model, produce a short poem, "literary" passage, or passage in another distinct genre that you find interesting._ 

Whether "interesting" means you find it funny, or moving, or surprising, or weird, or disturbing, or otherwise is up to you. Keep in mind what [Melanie Walsh _et al_ have found about ChatGPT's poetic style](https://arxiv.org/abs/2410.15299) (tl;dr it's pretty bad). But your text should:

+ Be a hybrid production: some combination of your prompting and a LLM's output. 
+ If a poem, be 1-2 stanzas in length; if prose, a few sentences or short paragraph. LLMs can produce longer texts, which you should feel free to explore, but the deliverable for the lab should be a shorter text

As you work, be sure to save candidates for your final choice—while you may be able to scroll up in the interface and find them, some of these online models are heavily trafficked and browser windows do crash regularly. You should save your final choice somewhere and include it in your write-up.

What is it about this text that you find "interesting," however you chose to define that parameter? Did the process of creating it teach you anything about how these technologies work, their possibilities, or their limitations?


#### Lab Task #2: Analysis

As digital humanists have begun to explore LLMs and related technologies, often their focus is less on these models' potential for text or image generation, and more on their potential for analysis and data processing. Some libraries, for example, are experimenting with image models for automatically tagging elements of historical images in their collections, while other scholars have experimented with [using LLMs for tasks such as summarization, topic identification, or classification](https://ryancordell.org/research/scissors-paste-LLMs)—such as genre classification—at scale.I will show some of the experiments I've been doing with local instances of Llama 3, for example. 

For this second task, I'd like you to explore a few models' abilities for analysis. In most cases, you would provide some seed text and ask the models to process it in some way—e.g. summarize, classify, extract information, etc. You can use texts related to your own interests, or feel free to draw on an existing resource like [Chronicling America](https://chroniclingamerica.loc.gov), the [Early Caribbean Digital Archive](https://ecda.northeastern.edu), the [Women Writers Project](https://wwp.northeastern.edu), [Founders Online](https://founders.archives.gov), or the [Wright American Fiction](https://webapp1.dlib.indiana.edu/TEIgeneral/welcome.do?brand=wright) collection. There are many other existing digital archives you might draw on. You could use, for instance, the newspaper you analyzed in Lab #1, choosing particular stories to cut & paste from the OCR view into your chosen LLM. 

Whatever texts you choose to work with, you should compare the performance of a few models across the same set of analyses. You should try different approaches too: for instance, what genre does the LLM assign if you leave the prompt open-ended, vs. when you ask it to choose from a preset list of genres? If you ask the model to summarize a text, how does it change if you specify different audiences or writing styles for the summary? You should use these outputs to begin developing hypotheses about the training data, finetuning, and other aspects of the models' construction.

#### Lab Task #3: Archaeology

Finally, our most important goal is to begin probing the boundaries and assumptions of LLMs through comparison of different inputs and outputs. Certainly in the context this lab we will not come to any large-scale conclusions about these models, which are large and complex. But we can begin to chip away at small regions of their data and models, with a goal of better understanding how algorithmic auditing might function at a larger scale.

Concretely, you might explore:

+ What outputs do different models produce in response to the same prompts? Do their differing outputs allow us to make hypotheses about their training data or the assumptions made by their respective language models? Based on their outputs, might you draw conclusions about the imagined audiences for each model?
+ How do incremental changes to your prompts to a single LLM change the output, and what might that tell us about the training data or language model? For instance, if you request poems in the styles of two different poets, does the output help you understand whose writing seems to be included in the training data, or perhaps whose is not? Are there genres the model seems better able to reproduce than others, and what might that say about the data or the model's assumptions?
+ When you provide prompts from a domain you know well, how would you evaluate an LLM's outputs? Do you find them accurate or inaccurate, up-to-date or outdated, balanced or imbalanced? Can you determine what the model is drawing from established sources and what it is creating in the moment? To put that another way, is the model reflecting existing knowledge or is it making up facts to fit your prompt?
+ Can you find a limit case: e.g. a style, or form, genre, or author the model seems incapable of reproducing? If you think you have found one, consult with a colleague in class to see whether there's another way of phrasing your prompt that might work better. But if you do find a limit case, what might that teach us about the model, its training data, or its fine-tuning?
+ Can you find cracks where the "wires" of the machine are somewhat exposed? LLMs are not simply reflections of "raw data," as the example of the Kenyan workers helping OpenAI filter offensive, gruesome, or otherwise toxic content from ChatGPT illustrates. Not only has their source data been curated, to some extent, but some explicit guidelines often seem programmed to particular kinds of outputs. For example, ChatGPT is already famous for repeatedly highlighting its limitations in its output, rebuffing, for instance, prompts that try to encourage the model to claim sentience or intention. Can you find such instances of if not transparency, then thinner opacity, that give us slant-wise peeks into the createdness of the model?

In your write-up, describe what you were able to learn about your model, at least as it reflects the small segment of language you were able to explore in our class time. For this kind of probing, it's okay to not be certain. The goal is to compare inputs and outputs and develop hypotheses about how they reflect internal workings we cannot access directly. In a larger research project, other researchers would take those hypotheses and develop additional tests to evaluate whether they do or do not hold up.

#### Other Explorations

If you have further time and interest, you might explore text-to-image models as well, such as [Dall-E](https://openai.com/index/dall-e-3/), [DreamStudio](https://beta.dreamstudio.ai/) (which is based on Stable Diffusion), [Imagen](https://imagen.research.google/), or [Midjourney](https://midjourney.com/home/). You can use similar probing techniques to begin understanding the boundaries of these models. I have [done some experiments](https://twitter.com/ryancordell/status/1575539450041733120?s=20&t=W8BkArDCrPxvtDVr6Lrv5Q) using these models to generate "woodcuts" that I can then carve into linoleum blocks and print with in the press. We will look at some examples of these later in the semester.
 
### Resources

+ Stephen Wolfram. “What Is ChatGPT Doing … and Why Does It Work?,” (2023), <https://writings.stephenwolfram.com/2023/02/what-is-chatgpt-doing-and-why-does-it-work/>.
+ [MonadGPT](https://huggingface.co/spaces/Pclanglais/MonadGPT), a model finetuned on "11,000 early modern texts in English, French and Latin, mostly coming from EEBO and Gallica"

