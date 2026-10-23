---
title: "Authoring a proactive Polly policy (Custom policies Part II)"
url: "https://thepollyproject.org/2019/02/13/authoring-a-proactive-polly-policy-custom-policies-part-ii.html"
date: "2019-02-13"
author: "{\"photo\"=>\"/assets/images/authors/dylan-reisenberger.png\", \"website\"=>\"http://software.reisenberger.net/\", \"bio\"=>\"Dylan is the lead contributor and architect on Polly, and the brains behind the roadmap, which is seeing Polly growing into the most robust, flexible and fully-featured resilience library for .NET!\"}"
feed_url: "https://thepollyproject.org/feed"
---
In this article we’ll build our first custom Polly policy: a proactive Policy to capture execution timings. Polly polices fall into two categories: reactive (which react to faults) and non-reactive or proactive (which act on all executions). To author a policy which reacts to faults, see Part III: Authoring a reactive custom policy .
