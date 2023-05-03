Download Link: https://assignmentchef.com/product/solved-cpts350-hw6
<br>



<ol>

 <li>Let <em>G </em>be a DAG (a graph without loops) and <em>u,v </em>be two designated nodes (there are many other nodes in <em>G</em>). Design an efficient algorithm to count the number of paths from <em>u </em>to <em>v</em>.</li>

 <li>Let <em>G </em>be a DAG (a graph without loops) and <em>u,v </em>be two designated nodes (there are many other nodes in <em>G</em>). In particular, each node in <em>G </em>is labeled with a color and multiple nodes can share the same color. A good path is one where the number of green nodes is bigger than the number of yellow nodes. Design an efficient algorithm to count the number of good paths from <em>u </em>to <em>v</em>.</li>

 <li>Let <em>G </em>be a graph (so it may have loops) and <em>u,v </em>be two designated nodes (there are many other nodes in <em>G</em>). In particular, each node in <em>G </em>is labeled with a color and multiple nodes can share the same color. Suppose that <em>γ </em>is a regular expression on colors (e.g., (<em>green </em>+ <em>yellowyellow</em>)<sup>∗</sup><em>yellowblue</em>). An ugly path is one that the color sequence on the path satisfies the regular expression <em>γ</em>. Design an efficient algorithm to count the number of ugly paths from <em>u </em>to <em>v </em>(when the count is infinite, return ∞). (Hint: you have two cases to consider, afer using a Cartesian product construction: a. the count is infinite – where an SCC algorithm can be used to decide. b. the count is finite, where prob 1 can be used.)</li>

 <li>Let <em>G </em>be a graph that may contain loops and hence, the number of paths from a designated start node to a designated end node may be infinite. Unfortunately, you usually can’t say that one infinite number is larger than another. Here is the problem: sketch a way to compare the number of paths in two graphs (that both may contain loops). (Hint: google perron, graph, path count).</li>

 <li>Let <em>G </em>be a control flow diagram of a C-progrm (which can be automatically generated). For each node <em>u </em>in the diagram, one can obtain the total number <em>C</em>(<em>u</em>) of paths from the root of the diagram to <em>u</em>. Then, from what you got from 4 above, you may sort all the <em>C</em>(<em>u</em>)’s for all <em>u </em>(even though some of <em>C</em>(<em>u</em>)’s are infinite) and then pick a <em>u</em><sup>∗ </sup>that has the maximal <em>C</em>(<em>u</em>). Write a mini-paper on how this will address the problem of testing a C-program. (if you want, you can actully publish a paper on this get a Master degree!)</li>

 <li>(a job interview question for a top tech company) Design an efficient algorithm to compute the number of binary strings with length <em>n </em>that satisfy</li>

</ol>

1

the regular expression ((0 + 11 + 101)<sup>∗</sup>(1101))<sup>∗</sup>. (Hint: use Prob 3 above. I will talk about the solutions in class.)

2