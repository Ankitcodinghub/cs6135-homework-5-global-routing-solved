# cs6135-homework-5-global-routing-solved
**TO GET THIS SOLUTION VISIT:** [CS6135 Homework 5-Global Routing Solved](https://www.ankitcodinghub.com/product/cs6135-homework-5-global-routing-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94611&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6135 Homework 5-Global Routing Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
1. Introduction

Routing is a crucial step in IC design. The placement stage determines the location of each cell of an IC design. Then in the routing stage, we need to connect all the placed cells with wires properly. The routing problem can be divided into two steps: global routing and detailed routing. During global routing, nets are connected on a coarse‐grain grid graph with capacity constraints. Then detailed routing follows the solution obtained in global routing to find the exact routing solution. The quality of global routing affects timing, power and density in the chip area, and thus global routing is a very important stage in the design cycle.

In this homework, you are asked to implement an existing algorithm or develop your own algorithm to solve the global routing problem with a set of 2-pin nets.

2. Problem Description (1) Input:

</div>
</div>
<div class="layoutArea">
<div class="column">
 The layout is partitioned into rectangular grids called global bins, as known as G-cells, as shown is Figure (a), and each pin is assumed to lie at the center of the gird that contains the pin.

In the grid graph G shown in Figure (b), each vertex 𝑣𝑣 ∈ 𝑉𝑉 represents a global bin, and each edge 𝑒𝑒 ∈ 𝐸𝐸 corresponds to a boundary between two adjacent global bins.

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li> &nbsp;Vertical and horizontal capacities of grids’ boundaries.</li>
<li> &nbsp;A set of nets, 𝑁𝑁 = {𝑛𝑛 , 𝑛𝑛 , … , 𝑛𝑛 }, to be routed over a grid graph 𝐺𝐺 =</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
12𝑘𝑘

(𝑉𝑉,𝐸𝐸). Each net 𝑛𝑛𝑖𝑖,1 ≤ 𝑖𝑖 ≤ 𝑘𝑘, has a set of pins to be connected.

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
(2) Output:

The critical points’ coordinates of each net after global routing is done. Notice that “critical points” means the starting point, ending point and turning points.

</div>
</div>
<div class="layoutArea">
<div class="column">
The routing problem for a net 𝑛𝑛 is to find an additional subset of vertices, 𝑖𝑖

</div>
</div>
<div class="layoutArea">
<div class="column">
(3) Objective:

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑠𝑠𝑖𝑖 ⊆ 𝑉𝑉, and a subset of edges, 𝐸𝐸𝑖𝑖 ⊆ 𝐸𝐸, to form a Steiner tree 𝑇𝑇𝑖𝑖 = (𝑉𝑉𝑖𝑖,𝐸𝐸𝑖𝑖), where 𝑉𝑉𝑖𝑖 = 𝑛𝑛𝑖𝑖 ∪ 𝑠𝑠𝑖𝑖. The supply 𝑠𝑠(𝑒𝑒) of an edge 𝑒𝑒 represents the number of available routing tracks passing through it. The number of wires that utilize an edge 𝑒𝑒 is called the demand 𝑑𝑑(𝑒𝑒) on the edge. In other hand, the demand 𝑑𝑑(𝑒𝑒) represents how many nets that pass through 𝑒𝑒. The overflow on an edge 𝑒𝑒 is defined to be the difference between its demand and supply as shown below:

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑑𝑑(𝑒𝑒) − 𝑠𝑠(𝑒𝑒), if 𝑑𝑑(𝑒𝑒) &gt; 𝑠𝑠(𝑒𝑒) 𝑜𝑜𝑣𝑣𝑒𝑒𝑜𝑜𝑜𝑜𝑜𝑜𝑜𝑜𝑜𝑜(𝑒𝑒) = � 0, otherwise (1)

</div>
</div>
<div class="layoutArea">
<div class="column">
The major optimization objective of global routing is to minimize the total overflow on all edges as shown in (2), and the second objective is to minimize the total wirelength on all edges as shown in (3).

</div>
</div>
<div class="layoutArea">
<div class="column">
min � � 𝑜𝑜𝑣𝑣𝑒𝑒𝑜𝑜𝑜𝑜𝑜𝑜𝑜𝑜𝑜𝑜(𝑒𝑒)� (2) ∀𝑒𝑒∈𝐸𝐸

</div>
</div>
<div class="layoutArea">
<div class="column">
min � � � 𝑜𝑜𝑒𝑒𝑛𝑛𝑙𝑙𝑙𝑙h(𝑒𝑒)� ∀𝑛𝑛𝑖𝑖∈𝑁𝑁 ∀𝑒𝑒∈𝐸𝐸𝑖𝑖

This homework asks you to write a global router that can route multiple nets. To simplify the global routing problem, we have some simplifications as follows:

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol>
<li>(a) &nbsp;Consider only two layers (vertical and horizontal).</li>
<li>(b) &nbsp;Consider only grid-based coordinates. The lower left corner of the global routing region in each layer is (0, 0). The width and height of grids are ignored because all x- and y-coordinates are grid-based.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
As the result, 𝑜𝑜𝑒𝑒𝑛𝑛𝑙𝑙𝑙𝑙h(𝑒𝑒) will always be 1.

(c) Consider only 2-pin nets.

(d) Consider only fixed wire width and spacing. All wire width and

</div>
</div>
<div class="layoutArea">
<div class="column">
spacing are equal to 1.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
<div class="layoutArea">
<div class="column">
(3)

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
3. Input Format

There is only an input file of each testcase. Here is an example:

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
grid 3 3

// grid # of horizontal grids # of vertical grids

vertical capacity 2

// vertical capacity vertical capacity

horizontal capacity 2

// horizontal capacity horizontal capacity

num net 3

// num net # of nets

net0 0 2

// net-name net-id # of pins

01

// pin x-grid coordinate pin y-grid coordinate

11 net1 1 2 02 11 net2 2 2 22 10

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
4. Output Format

Here is an example:

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
net0 0

// net-name net-id

(0, 1, 1)-(1, 1, 1)

// (pin x-grid coordinate, pin y-grid coordinate, 1)

!

net1 1

(0, 2, 1)-(1, 2, 1) (1, 2, 1)-(1, 1, 1) !

net2 2

(2, 2, 1)-(2, 0, 1) (2, 0, 1)-(1, 0, 1) !

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
Example:

</div>
</div>
<div class="layoutArea">
<div class="column">
net1

(0,2) (1,2) net0

(0,1) (1,1)

(0,0) (1,0)

</div>
<div class="column">
net2

</div>
<div class="column">
(2,2)

(2,1)

(2,0)

</div>
</div>
<div class="layoutArea">
<div class="column">
5. Language/Platform

<ol>
<li>(1) &nbsp;Language: C/C++</li>
<li>(2) &nbsp;Platform: Unix/Linux</li>
</ol>
6. Report

</div>
</div>
<div class="layoutArea">
<div class="column">
Your report must contain the following contents, and you can add more as you wish.

<ol>
<li>(1) &nbsp;Your name and student ID</li>
<li>(2) &nbsp;How to compile and execute your program and give an execution example.</li>
<li>(3) &nbsp;The total overflow, the total wirelength and the runtime of each testcase.Notice that the runtime contains I/O, constructing data structures, computing parts, etc. The more details your experiments have, the more clearly you will know where the runtime bottlenecks are. You can plot your results like the one shown below.</li>
</ol>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>35
30
25
20
15
10
</pre>
5 0

</div>
<div class="column">
tc1 tc2 tc3

</div>
</div>
<div class="layoutArea">
<div class="column">
testcases

time1 time2 time3

</div>
<div class="column">
time4

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
runtime(s)

</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
<ol start="4">
<li>(4) &nbsp;The details of your implementation. You have to use flow chart(s) to help elaborate your algorithm, and please follow the symbols usually used in flow charts. (If you are not familiar with the symbols, please refer to this reference: https://www.programiz.com/article/flowchart-programming)If your method is similar to some previous works/papers, please cite thepapers and reveal the difference(s).</li>
<li>(5) &nbsp;What tricks did you do to speed up your program or to enhance your solutionquality? Also plot the effects of those different settings like the ones shown below.</li>
<li>(6) &nbsp;What have you learned from this homework? What problem(s) have you encountered in this homework?</li>
</ol>
7. Required Items

Please compress HW5/ (using tar) into one with the name CS6135_HW5_${StudentID}.tar.gz before uploading it to iLMS.

<ol>
<li>(1) &nbsp;src/containsallyoursourcecode,yourMakefileandREADME.

 README must contain how to compile and execute your program. Anexample is like the one shown in HW2.</li>
<li>(2) &nbsp;output/containsallyouroutputsoftestcasesfortheTAtoverify.</li>
<li>(3) &nbsp;bin/containsyourexecutablefile.</li>
<li>(4) &nbsp;CS6135_HW5_${StudentID}_report.pdfcontainsyourreport.</li>
</ol>
You can use the following command to compress your directory on a workstation:

<pre>    $ tar -zcvf CS6135_HW5_{StudentID}.tar.gz &lt;directory&gt;
</pre>
For example:

<pre>    $ tar -zcvf CS6135_HW5_109062501.tar.gz HW5/
</pre>
8. Grading

 80%: The solution quality (total overflow and total wirelength) and the runtime of each testcase; hidden testcases included.

 20%: The completeness of your report.

 5% Bonus: Parallelization. Please specify your system specification.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
50 runtime(s) 40

30

20

10 0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
3000 Overflow/wirelength

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>2500
2000
1500
1000
</pre>
500 0

</div>
<div class="column">
w/o. method A w/o. method B w/o. method C Full

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
 5% Bonus: For each testcase, you could draw the congestion map like the following example. The congestion map and the legend are needed.

Notes:

<ul>
<li> &nbsp;Make sure the following commands can be executed. Go into directory “src/”, enter “make” to compile your program and generate the executable file, called “hw5”, which will be in directory “bin/”.  Go into directory “src/”, enter “make clean” to delete your executablefile.</li>
<li> &nbsp;Please use the following command format to run your program.
<pre>    $ ./hw5 *.modified.txt *.result
</pre>
E.g.:

<pre>    $ ./hw5 ../testcase/ibm01.modified.txt ../output/ibm01.result
</pre>
</li>
<li> &nbsp;Use arguments to read the file path. Do not write file path in your code.</li>
<li> &nbsp;Program must be terminated within 10 minutes for each testcase.</li>
<li> &nbsp;Grading is based on total overflow (primary), total wirelength (secondary) andruntime (tertiary).</li>
<li> &nbsp;We will test your program by shell script. Please make sure your program can beexecuted by HW5_grading.sh.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
