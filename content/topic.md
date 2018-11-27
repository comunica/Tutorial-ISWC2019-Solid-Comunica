## Topic and Relevance
{:#topic}

Decentralization is a widely discussed topic these days.
[Solid](https://solid.mit.edu/){:.mandatory} is a Web-based platform founded by Tim Berners-Lee
that enables people store data in their own personal _data pod_.
This gives users _true data ownership_,
as they can choose _where_ their data resides,
and _who_ can access it.
The _decentralized applications_
that can be built on top of Solid data pods
are not tied to specific user data.
Instead, users need to give applications explicit access to their data.
Only then can applications _query_ over one or more data pods.

[Comunica](cite:cites comunica) is a JavaScript-based _meta query engine_ that was introduced
as a flexible way of querying Linked Data on the Web.
As such, it is an ideal platform for querying over Solid data pods,
and for building truly decentralized applications.
The main functionality is demonstrated via our [Web application](http://query.linkeddatafragments.org/){:.mandatory}.
The interaction with Solid data pods is demonstrated within the
[LDflex playground](https://solid.github.io/ldflex-playground/){:.mandatory},
where Comunica is used in the back-end behind a user-friendly
[LDflex](https://github.com/solid/query-ldflex){:.mandatory} path expression.

This is the first tutorial that combines Solid and Comunica.
In the past, there were tutorials on Solid at the
[Decentralized Web Summit 2018](https://decentralizedwebsummit2018.sched.com/event/Fg5q/workshop-building-solid-apps-a-hands-on-tutorial){:.mandatory},
and at the [DeSemWeb workshop at ISWC 2018](http://iswc2018.desemweb.org/program/){:.mandatory}.
The Decentralized Web Summit tutorial ([https://solid.github.io/dweb-summit-2018/](https://solid.github.io/dweb-summit-2018/)) had 50 participants,
while the DeSemWeb workshop ([https://rubenverborgh.github.io/Solid-DeSemWeb-2018/](https://rubenverborgh.github.io/Solid-DeSemWeb-2018/))
had more than 60 participants.
There was one previous tutorial where Comunica was used
as a tool to demonstrate various querying capabilities in a tutorial
on [_Knowledge Representation as Linked Data_](cite:cites cikm)
([http://rml.io/cikm2018tutorial/](http://rml.io/cikm2018tutorial/)) at the CIKM conference 2018.
