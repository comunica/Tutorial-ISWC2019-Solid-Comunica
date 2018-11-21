## Outline
{:#outline}

We plan a full day for this tutorial as shown in [](#planning).
The morning session will focus on the basics of Solid and Comunica,
and the afternoon will consist of hands-on sessions for building applications.

In the morning, we will introduce the basic concepts behind Solid and Comunica,
and we will allow participants to get started with both of them.
For Solid, this will involve guiding the audience towards
setting up their own data pod.
For Comunica, we will allow participants to try out several example
queries via a [Web-based query engine](http://query.linkeddatafragments.org/){:.mandatory}.

In the afternoon, we will focus on building applications on top of Solid
using Comunica's querying capabilities.
We will focus on three querying techniques, ranging from basic to advanced.
First, we will demonstrate the usage of [LDflex](https://github.com/solid/query-ldflex){:.mandatory},
which is a simple path-based tool for querying that does not require declarative queries.
After that, we will focus on [GraphQL-LD](cite:cites graphqlld),
which is a technique for querying Linked Data based on
the highly popular [GraphQL](cite:cites graphql) query language.
It is based on declarative queries, which are more expressive than LDflex.
Finally, we will focus on [SPARQL queries](cite:cites spec:sparqllang),
which is an even more expressive way of querying Linked Data.

The tutorial will be guided by slides,
which will be shared online after the session.
For the hands-on coding sessions, we will provide
a git repository with separate branches for all sequantially completed tasks.
This will allow participants that are unable to complete a certain task,
to still begin with the next task by checking out a different branch.

<figure id="planning" markdown="1" class="table">

|                                               | Topic | Duration |
|-----------------------------------------------|-------|----------|
| **Morning: Getting started** (_2:40_)         | Introduction | 0:20   |
|                                               | Getting started with Solid  | 1:10   |
|                                               | Getting started with Comunica  | 1:10   |
| **Afternoon: Building applications** (_2:40_) | LDflex | 1:00   |
|                                               | GraphQL-LD | 0:50   |
|                                               | SPARQL | 0:50   |

<figcaption markdown="block">
Planning of the tutorial
</figcaption>
</figure>
