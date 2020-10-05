# Definition

A class or module should have one, and only one, reason to change. If a class has more than one responsibility, it becomes coupled. A change to one responsibility results to modification of the other responsibility.

## Clone Example

Clone the example repository with the command `git clone https://github.com/katacoda/scenario-examples.git katacoda-scenario-examples`{{execute}}

Within the root of a repository, a course has been created called `uilayouts`. The contents of the course have been defined as `katacoda-scenario-examples/uilayouts-pathway.json`{{open}}.

Within the JSON file, the courses element defines each scenario. For example:

<pre class="file">
{
    "course_id": "uilayout-terminal",
    "title": "Scenario with Terminal UI",
    "description": "Katacoda Scenario Example"
},
</pre>

The **course_id** is the scenario name directory within the course directory. For example `ls katacoda-scenario-examples/uilayouts/uilayout-terminal`{{execute}}. The **title** and **description** are shown on the course page.