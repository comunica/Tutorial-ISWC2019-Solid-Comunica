## Outline
{:#outline}

We plan a full day for this tutorial as shown in [](#planning).
In the morning, we will cover the basics of Comunica.
In the afternoon, the more advanced concepts will be handled.
Both sessions will start with presentations,
and the end will be practical.

The morning session will consist of an introductory presentation
in which the motivation and purpose of Comunica will be explained,
followed by an overview of its architecture.
Next, we will demonstrate the usage of Comunica
with several SPARQL queries in the [browser-based client](http://query.linkeddatafragments.org/){:.mandatory}.
After that, we will guide the audience through the installation
and usage of Comunica within a JavaScript application.

In the afternoon, we will focus on the configuration and extensibility of Comunica.
We will first give an overview of [Components.js](cite:cites componentsjs),
which is a dependency injection framework
that Comunica relies upon to handle the configuration of engines.
After that, we will guide the audience through plugging in a simple new querying algorithm
inside Comunica using the configuration system.

The tutorial will be guided by slides,
which will be shared online after the session.
For the hands-on coding sessions, we will provide
a git repository with separate branches for all sequantially completed tasks.
This will allow participants that are unable to complete a certain task,
to still begin with the next task by checking out a different branch.

<figure id="planning" markdown="1" class="table">

|                                  | Topic | Duration |
|----------------------------------|-------|----------|
| **Morning: basic** (_3:00_)      | Introduction | 0:15   |
|                                  | Architecture: Comunica  | 1:15   |
|                                  | Browser usage examples  | 0:15   |
|                                  | Usage inside an application | 1:15   |
| **Afternoon: advanced** (_3:00_) | Installation | 0:15   |
|                                  | Configuration with Components.js | 0:45   |
|                                  | Adding a custom algorithm | 2:00   |

<figcaption markdown="block">
Planning of the Comunica tutorial
</figcaption>
</figure>
