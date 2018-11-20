## Topic and Relevance
{:#topic}

Querying is a key aspect of the [Semantic Web Stack](cite:cites semanticweb),
and a large variety of _query algorithms_ for different kinds of Linked Data _interfaces_ already exist.
There are still plenty of open problems
that elicit research on new querying techniques and combinations of existing ones.

[Comunica](cite:cites comunica) is a _meta query engine_ that was introduced
as a tool to facilitate the development, testing, and evaluation of such querying capabilities.
As such, it is a tool with which query engines can be created,
based on a set of modules,
and a flexible configuration system to wire them together.
One example of such a query engine instantiation is [Comunica SPARQL](https://github.com/comunica/comunica/tree/master/packages/actor-init-sparql){:.mandatory},
which implements the [SPARQL 1.1](cite:cites spec:sparqllang) specification using an efficient set of modules.
This engine is able to federate queries over heterogeneous interfaces,
for example, one can execute a SPARQL query over the combination of a SPARQL endpoint
and a collection Linked Data documents on the Web.
This functionality is demonstrated via our [Web application](http://query.linkeddatafragments.org/){:.mandatory}.
Thanks to the modularity of Comunica, support for new kinds of datasources
can be added by writing a custom module, and plugging it in.

The modularity and flexibility of Comunica is useful for research purposes,
as it allows you to easily plug in different algorithms of certain query operators,
and compare their performance.
Not only does this lower the barrier towards such evaluations,
it also makes these evaluations _fair_,
because algorithms are implemented in the same engine,
instead of comparing completely different engines with a potentially different stack.

The Comunica platform is fully open-source,
which makes it easy to learn from the code when new modules need to be implemented.
Furthermore, it is written in JavaScript,
which makes it possible to run engines anywhere,
both locally on your machine, or on the Web via a browser.

This is the first tutorial that is dedicated to Comunica.
Before that, Comunica was used as a tool to demonstrate various querying capabilities in a tutorial
on [_Knowledge Representation as Linked Data_](cite:cites cikm)
([http://rml.io/cikm2018tutorial/](http://rml.io/cikm2018tutorial/)) at the CIKM conference 2018.
