## Description
{:#description}

We plan a full day for this tutorial as shown in [](#planning).
The morning session will focus on the basics of Solid and Comunica,
and the afternoon will consist of hands-on sessions for building applications.
We expect participants to have basic knowledge of Web technologies such as HTML, JavaScript, RDF and SPARQL.

<figure id="planning" markdown="1" class="table">

|                                               | Topic | Duration |
|-----------------------------------------------|-------|----------|
| **Morning 1: Solid** (_1:20_)                 | Introduction | 0:10   |
|                                               | Introduction to Solid  | 0:30   |
|                                               | Getting Started with Solid  | 0:40   |
| *Break*                                       | ---  | --- |
| **Morning 2: Comunica** (_1:20_)              | Introduction to Comunica  | 0:40   |
|                                               | Getting Started with Comunica  | 0:40   |
| *Lunch Break*                                 | ---  | --- |
| **Afternoon 1: Apps** (_1:20_)                | LDflex | 0:40   |
|                                               | GraphQL-LD | 0:40   |
| *Break*                                       | ---  | --- |
| **Afternoon 1: Hackathon** (_1:20_)           | Hackathon | 1:20   |

<figcaption markdown="block">
Planning of the tutorial
</figcaption>
</figure>

In the morning, we will introduce the basic concepts behind Solid and Comunica,
and we will allow participants to get started with both of them.
For Solid, this will involve guiding the audience towards
setting up their own data pod.
For Comunica, we will allow participants to try out several example
queries via a [Web-based query engine](http://query.linkeddatafragments.org/){:.mandatory}.

In the afternoon, we will focus on building applications on top of Solid
using Comunica's querying capabilities.
We will focus on three querying APIs to interact with Comunica,
ranging from basic to advanced, as shown in [](#querying-tool-complexity).
First, we will demonstrate the usage of [LDflex](https://github.com/solid/query-ldflex){:.mandatory},
which is a simple path-based query expression language in JavaScript
that aims to [improve the developer experience](cite:cites devexperience).
After that, we will focus on [GraphQL-LD](cite:cites graphqlld),
which is a technique for querying Linked Data based on
the highly popular [GraphQL](cite:cites graphql) query language.
It is based on declarative queries, which are more expressive than LDflex.
Finally, we will briefly focus on [SPARQL queries](cite:cites spec:sparqllang),
which is an even more expressive way of querying Linked Data,
but is more difficult to use.

<figure id="querying-tool-complexity">
<center><img src="img/querying-tool-complexity.svg" alt="[Complexity versus expressivity]" style="width: 50% !important" /></center>
<figcaption markdown="block">
Perceived developer complexity versus data retrieval expressivity of Linked Data Query APIs.
</figcaption>
</figure>
