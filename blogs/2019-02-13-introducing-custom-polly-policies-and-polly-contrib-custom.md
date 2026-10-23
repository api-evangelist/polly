---
title: "Introducing custom Polly policies and Polly.Contrib (Custom policies Part I)"
url: "https://thepollyproject.org/2019/02/13/introducing-custom-polly-policies-and-polly-contrib-custom-policies-part-i.html"
date: "2019-02-13"
author: "{\"photo\"=>\"/assets/images/authors/dylan-reisenberger.png\", \"website\"=>\"http://software.reisenberger.net/\", \"bio\"=>\"Dylan is the lead contributor and architect on Polly, and the brains behind the roadmap, which is seeing Polly growing into the most robust, flexible and fully-featured resilience library for .NET!\"}"
feed_url: "https://thepollyproject.org/feed"
---
Introducing custom policies The Polly team have long wanted to allow users to extend Polly’s capability with custom policies. Polly v7.0 introduces a simple mechanism for authoring custom policies which integrate fully with the existing Polly architecture: the fault-handling syntax, the execution overloads, and the ability to combine policies in a PolicyWrap . This article introduces custom policies and the Polly.Contrib.
