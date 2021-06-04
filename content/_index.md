---
title: "emmenflo"
type: docs
date: 2017-10-17T15:26:15Z
bookToc: false
---

## Manage your Organizational Knowledge!

We think that managing a big organisation has become a complex task. We should aim to support everyone in a best possible way to deal with that complexity. Fortunately, we could gather some experience in managing complex systems before - we talk about software management. Thus, we want to leverage business organisation with tools from the software management process. Don't worry - these tools are meanwhile usable enough that even non-technical people can work with it - often times even much more efficient than with the usual knowledge worker's toolset - Office programs and file systems.

### What is emmenflo?

emmenflo is a simple combination of a git repository, a Hugo website, the Camunda BPMN.io viewer and some few lines of automation code.

It is using the congenial hugo static web site system which creates even big web sites from a bunch of content and formatting files in some few seconds. Together with some git automation, we are capable of redistributing a complete web site without someone doing anything except for pushing the latest change into the git version maangement system. Thus, the internal website can be built in any way. It generates itself automatically from the texts that are checked in to the `gitlab` project.

Speaking of which - how do you manage your versions, and how do you organize the creation of content by many people at the same time? Our pro tipp - do it as the developers do! git has become *the* version management system of the industry, and has with github and gitlab managed to attract the Open Source community into a vivid ecosystem of great software which is available for everyone.

This does not imply that your content isn't safe in such a repository. To the contrary, using a professional text-based version management system is the safest way to keep your content - in all versions, as long as you like. And revert to whichever moment in time later on.

All texts can be edited as desired. Also the whole layout of the website can be redesigned according to the corporate specifications, as it can be equipped with custom CSS specifications. We selected the "hugo-book" theme because it supports big amounts of structured content in an optimal way.

{{< hint info >}}
Besides standard Markdown syntax, additional formatting is supported by codes of the selected theme.
{{</ hint >}}

And last but not least, Camunda as one of the leading providers of Business Process Management software, is enabling us to create a producer and consumer environment alike. Producers use Visual Studio Code as an editing system with the BPMN.io plugin that allows visual creation of correct BPMN process descriptions. A view-only plugin is then used in the web environment that we create on change.

Share and Enjoy!

emmenflo is an open source initiative of [ISR Information Products AG](https://isr.de).