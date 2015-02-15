---
title: Home
order: 0
---
mermaid
=======

Generation of diagrams and flowcharts from text in a similar manner as markdown.

Ever wanted to simplify documentation and avoid heavy tools like Visio when explaining your code?

This is why mermaid was born, a simple markdown-like script language for generating charts from text via javascript. [Try it using our editor](http://knsv.github.io/mermaid/live_editor).

The code below would render the following image
<table>
<tr><th>Code</th><th>Rendered diagram</th></tr>
<tr><td>
<pre>
<code>
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
<code>
</pre>
</td>
<td>
<img src='http://www.sveido.com/mermaid/img/ex1.png' alt='Example 1'>
</td>
</tr>
<tr>
<td>
<pre>
<code>
sequenceDiagram
    participant Alice
    participant Bob
    Alice->John: Hello John, how are you?
    loop Healthcheck
        John->John: Fight against hypochondria
    end
    Note right of John: Rational thoughts &lt;br/>prevail...
    John-->Alice: Great!
    John->Bob: How about you?
    Bob-->John: Jolly good!
</code>
</pre>
</td>
<td>
<img src='http://www.sveido.com/mermaid/img/seq1.png' alt='Example 2'>
</td>
</tr>
</table>

Play with mermaid using this [editor](http://danielmschmidt.github.io/mermaid-demo/) or this [live editor](live_editor). You can also look at mermaid in action using [jsbin](http://jsbin.com/faxunexeku/1/edit?html,output).

## Further reading

* [Usage](http://knsv.github.io/mermaid/usage.html)
* [Flowchart syntax](http://knsv.github.io/mermaid/flowchart.html)
* [Sequence diagram syntax](http://knsv.github.io/mermaid/sequenceDiagram.html)
* [Mermaid client](http://knsv.github.io/mermaid/mermaidCLI.html)

# Credits
Many thanks to the [d3](http://d3js.org/) and [dagre-d3](https://github.com/cpettitt/dagre-d3) projects for providing
the graphical layout and drawing libraries! Thanks also to the
[js-sequence-diagram](http://bramp.github.io/js-sequence-diagrams) project for usage of the grammar for the
sequence diagrams.

*Mermaid was created by Knut Sveidqvist for easier documentation.*

Knut has not done all work by himself, here is the full list of the projects [contributors](https://github.com/knsv/mermaid/graphs/contributors).