---
title: "Lab: 3 Ways of Looking at DH Data"
permalink: /schedule/03-data-lab/
toc: true
class_date: 2024-09-12
---

## Lab Topic

_We can't possibly cover all the ways DH projects conceive of and operationalize "data" in a single lab. Instead, we will focus on a discrete humanistic text-object that can be modeled and used in very different ways, through different data types, and toward different project purposes. Ultimately, our goal is help you think about a core set of questions that face every DH project, which are 1. what are this project's primary outcomes/deliverables (research, pedagogical, public)?; 2. what data type(s) will facilitate those outcomes?; and 3. what resources, staffing, and expertise will we need to create those data types from our source materials?_

#### [Collaborative Lab Notes Doc](https://docs.google.com/document/d/1Sb0B0UjXyxts_VTfLVMV4LZ07235F4tz8rCCraWziLc/edit?usp=sharing)

### Preparation

Please [join my Posit Cloud space](https://posit.cloud/spaces/11704/join?access_code=5aeiqWjSoDjUD1rhC00do9LmobbvTpG6tRx5xXdp) prior to class, so that we do not have to get this set up during class.

### Instructions

Today we will look at one source of data used by lots of digital humanists working on American history, literature, religion, and culture: the Library of Congress' [Chronicling America](https://chroniclingamerica.loc.gov) archive of historical newspapers. This is the largest data source we use in the [_Viral Texts_](https://viraltexts.org) project, and because it is open-access and relatively easy to use through search or the site's [application programming interface](https://chroniclingamerica.loc.gov/about/api/), or API, many DH scholars turn to this as a resource. Chronicling America is also a great example of Collections as Data, and the LoC team—and in particular the [LC Labs](https://labs.loc.gov) group—have been leaders in CoD conversations. 

What I want to think about is how discipline, scale, and research questions shape what humanities data consists of, and how the boundaries of data shift for distinct research questions and methodologies. We will focus on 3 distinct ways of "looking at" Chronicling America's data. These 3 perspectives are by no means exhaustive, and we will at least gesture towards other approaches that would address this data disciplinarily or methodologically. For librarians in training, today's lab aims to model a kind of DH consultation, as we consider a single source of data and triangulate how to approach it based on distinct research or pedagogical questions.

#### Prework: Brainstorming

First, we're going to break into small groups. In your groups, I'd like you to look closely at [this issue of the _Jeffersonian Republican_](https://chroniclingamerica.loc.gov/lccn/sn86053954/1852-05-13/ed-1/) from May 13, 1852. Brainstorm the kinds of research questions someone might ask about a primary source like a historical newspaper, both as a qualitative ("humanistic") reader and when using the newspaper as a data source for more quantitative or computational approaches. If it's useful read about Chronicling America itself also. What methods might one use to answer the questions your group is developing, and what kind(s) of data would a research need to access or create to pursue each? Does that data seem to be available [through Chronicling America](https://chroniclingamerica.loc.gov/about/)? Make sure to take notes about this brainstorming session, so you can include this process in your lab reports.

Another way to think of this task: a researcher/student has just requested a consultation, saying they want to "do a DH project" using Chronicling America. What are some of the ways you might approach such a broad inquiry, or paths you might suggest they research further?

#### View 1: Modeling Text

One of the most long-standing approaches in digital humanities and digital libraries centers building digital editions and/or digital archives. As only one example, the [Text Encoding Iniative](https://tei-c.org) has been developing guidelines since 1994 for encoding primary texts and metadata, and is an XML standard "widely used by libraries, museums, publishers, and individual scholars to present texts for online research, teaching, and preservation." With a task like encoding, the focus is quite close, as scholars consider how to model and represent a born-analog text for digital presentation, reading, and research.

If you look at top of the fourth column from the left [on page one of that _Jeffersonian Republican_ issue](https://chroniclingamerica.loc.gov/lccn/sn86053954/1852-05-13/ed-1/seq-1/) we considered together, for example, you will find an untitled paragraph that begins "The Model Lady puts…" While this newspaper gives no indication of the fact, this piece is actually a reprint of a column written by [Fanny Fern](https://fannyfern.org/bio) for the _New York Ledger_. Fern was likely the most well-known (and renumerated) American author of the mid-19th century, primarily from her work writing for the _Ledger_, and her columns were regularly reprinted in the ways we study in the [_Viral Texts_](https://viraltexts.org) project. Fern's original column, "What is a Lady?" has been encoded and collected by the [_Fanny Fern in the New York Ledger_](https://fannyfern.org/home) project at the University of Nebraska—Lincoln. You can see ["What is a Lady"](https://fannyfern.org/columns/fern.18570117.02) in the online archive, but you can also download the TEI/XML of the text. 

Please [download the XML file](https://github.com/rccordell/is578-intro-dh/blob/gh-pages/_materials/data/fern.18570117.xml) and open it in a plain text editor, like TextEdit (mac) or Notepad (windows). If you're feeling really ambitious, you can download [the XML editor oXygen](https://www.oxygenxml.com), but that's not required for this lab. This is a pretty straightfoward TEI file and we will explore it together to discuss this very close perspective on humanities data. Our goal is not to become TEI experts, which is a task of years not minutes, but to begin seeing how specific texts can be modeled for digital editions. 

Some questions we will consider are: What aspects of this text does TEI allow scholars to model? Why would you choose to encode a text in this way, when you could post an image of the historical original instead? Consider some slightly more detailed TEI, like [this example from the Early Caribbean Digital Archive](https://github.com/NEU-DSG/ECDA/blob/master/in%20progress/BoardofTradeReport1789.xml) (more on [the ECDA here](https://ecda.northeastern.edu)). What kinds of analyses might this kind of tagging enable?

##### Lab Task 1: Outline the elements of the [_Jeffersonian Republican_](https://chroniclingamerica.loc.gov/lccn/sn86053954/1852-05-13/ed-1/seq-1/) edition of "What Is a Lady?" that you would want to tag in TEI. You don't have to know the right tags or try to make a TEI file, but simply describe what aspects of the text you think would be important to model. If you're feeling ambitious, you can try to edit the TEI I gave you to reflect this distinct newspaper edition of the text.

#### View 2: Text Analysis

Next, we're going to use [Posit Cloud](https://posit.cloud/spaces/11704/join?access_code=5aeiqWjSoDjUD1rhC00do9LmobbvTpG6tRx5xXdp) and an interactive code notebook to zoom out just a little bit, and think about historical newspaper text as data, at a slightly larger scale, using the Library of Congress' API (application programming interface). 

##### Lab Task 2: Explore a different set of texts using (and perhaps lightly adapting) the provided code. I've tried to clearly mark the best lines to edit if you are not familiar with or comfortable with writing or debugging code.

#### View 3: Metadata at Scale

In this last section, we will zoom out even further, to consider how we might use tabular historical metadata to analyze the US newspaper system over time. In addition to its Chronicling America archive of digitized newspapers, the Library of Congress also publishes [The US Newspaper Directory](https://chroniclingamerica.loc.gov/search/titles/), a database of metadata on every newspaper cataloged by the [United States Newspaper Program](https://www.neh.gov/us-newspaper-program) between 1982 and 2011. The USNP "was a cooperative national effort among the states and the federal government to locate, catalog, and preserve on microfilm newspapers published in the United States from the eighteenth century to the present" and those efforts have contributed directly to the [National Digital Newspaper Program](https://www.loc.gov/ndnp/) that underlies Chronicling America.

The US Newspaper Directory (USND) is not fully comprehensive, but it does allow researchers to trace macro trends in the newspaper ecosystem over time. In this last section we will experiment to see what that might look like. Before we experiment with this data in R, however, let's spend a few minutes looking at it together and discussing. For the _Viral Texts_ project we've compiled the USND data along with some other publicly-available sources for historical newspaper metadata [in this repository](https://github.com/ViralTexts/newspaper-metadata). Please download the [usnd-clean.csv file](https://github.com/ViralTexts/newspaper-metadata/blob/main/usnd/usnd-clean.csv) and just open it in a spreadsheet application of your choice.

In small groups, spend some time talking about what you observe in this data. You might discuss:

1. What research questions could you imagine asking of a dataset like this one?
2. What are some of the challenges evidence in this dataset, including questions of consistency, taxonomy, or data modeling?
3. Is there additional information you would need to begin pursing the research questions you identified in /#1?

Okay, now we will return to our code notebook in [Posit Cloud](https://posit.cloud/spaces/11704/join?access_code=5aeiqWjSoDjUD1rhC00do9LmobbvTpG6tRx5xXdp) to experiment more with this newspaper metadata.

##### Lab Task 3 (reach goal): develop a research question that could be answered with the American Newspaper Directory metadata we explored in the notebook above. If you are feeling _really_ ambitious, using R to begin exploring that research question, but you should at least sketch out some of the steps you would imagine following to answer that question from the data at hand.

### What to Submit

A [lab report]({{site.baseurl}}/assessments/4-lab-reports) that demonstrates completion of the tasks above. Please use screenshots, excerpts, or code snippets where appropriate. As per the lab report assignment—which you should review for this first report—you will also include prose that reflects on both the lab process and ties our activities to specific, quoted, and cited ideas from our readings in this unit.

### Resources

+ _Programming Historian_'s list of [data manipulation lessons](https://programminghistorian.org/en/lessons/?topic=data-manipulation) and [data management lessons](https://programminghistorian.org/en/lessons/?topic=data-management)
+ David J. Birnbaum, "What is XML and why should humanists care? An even gentler introduction to XML" (2021), [external link](http://dh.obdurodon.org/what-is-xml.xhtml)
+ Elisa Beshero-Bondar, Lee Skallerup Bessette, Quinn Dombrowski, and Roopika Risam, _DSC /#5: The DSC and the Impossible TEI Quandaries_ (2020), [external link](https://datasittersclub.github.io/site/dsc5.html)
+ Matthew D. Lincoln, Scott B. Weingart, and Nickoal Eichmann-Kalwara,“The Index of Digital Humanities Conferences,” (2021), [external link](https://doi.org/10.5334/johd.26)
+ "Responsible Datasets in Context" (2024), [external link](https://www.responsible-datasets-in-context.com)