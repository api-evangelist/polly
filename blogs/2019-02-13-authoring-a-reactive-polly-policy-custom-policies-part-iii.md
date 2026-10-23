---
title: "Authoring a reactive Polly policy (Custom policies Part III)"
url: "https://thepollyproject.org/2019/02/13/authoring-a-reactive-polly-policy-custom-policies-part-iii-2.html"
date: "2019-02-13"
author: "{\"photo\"=>\"/assets/images/authors/dylan-reisenberger.png\", \"website\"=>\"http://software.reisenberger.net/\", \"bio\"=>\"Dylan is the lead contributor and architect on Polly, and the brains behind the roadmap, which is seeing Polly growing into the most robust, flexible and fully-featured resilience library for .NET!\"}"
feed_url: "https://thepollyproject.org/feed"
---
In this article we’ll build our first reactive custom Polly policy: a policy to log exceptions or fault-results. Polly polices fall into two categories: reactive (which react to configured faults) and non-reactive / proactive (which act on all executions). To author a proactive policy, see Part II: Authoring a proactive custom policy .
