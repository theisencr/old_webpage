---
layout: page
title: "Approximating Attack Surfaces with Stack Traces"
excerpt: "Abstract for Approximating Attack Surfaces"
tags: [abstracts]
comments: false
share: false
image: 
  feature: boats.jpg
  credit: Punting boats on the Cam, Cambridge 2014
  creditlink:
---

Security testing and reviewing efforts are a necessity for software projects, but are time-consuming and expensive to apply. Identifying vulnerable code supports decision-making during all phases of software development.  An approach for identifying vulnerable code is to identify its attack surface, the sum of all paths for untrusted data into and out of a system. Identifying the code that lies on the attack surface requires expertise and significant manual effort. This paper proposes an automated technique to empirically approximate attack surfaces through the analysis of stack traces.  We hypothesize that stack traces from user-initiated crashes have several desirable attributes for measuring attack surfaces. The goal of this research is to aid software engineers in prioritizing security efforts by approximating the attack surface of a system via stack trace analysis. In a trial on Windows 8, the attack surface approximation selected 48.4% of the binaries and contained 94.6% of known vulnerabilities. Compared with vulnerability prediction models (VPMs) run on the entire codebase, VPMs run on the attack surface approximation improved recall from .07 to .1 for binaries and from .02 to .05 for source files.  Precision remained at .5 for binaries, while improving from .5 to .69 for source files.

{% highlight html %}
C. Theisen, K. Herzig, P. Morrison, B. Murphy, and L. Williams, 
“Approximating Attack Surfaces with Stack Traces”, in Companion 
Proceedings of the 37th International Conference on Software 
Engineering.
{% endhighlight %}

<div markdown="0"><a href="http://research.microsoft.com/pubs/238352/Aproximating%20Attack%20Surfaces%20with%20Stack%20Traces.pdf" class="btn">PDF</a></div>