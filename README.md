# cs2040s-problem-set-2-solved
**TO GET THIS SOLUTION VISIT:** [CS2040S Problem set 2 Solved](https://www.ankitcodinghub.com/product/cs2040s-problem-set-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;53128&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2040S Problem set 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (5 votes)    </div>
    </div>
<strong>&nbsp;</strong>This problem set consists of two problems closely connected to binary search.

The first is an easy optimization problem: you are given an array, and your goal is to find the largest element in the array.

The second is a more challenging load balancing problem: you have a collection of tasks and a collection of processors, and your goal is to efficiently assign a sequence of tasks to each processor.

<strong>Collaboration Policy. </strong>You are encouraged to work with other students on solving these problems. However, you <strong>must </strong>write up your solution <strong>by yourself</strong>. We may, randomly, ask you questions about your solution, and if you cannot answer them, we will assume you have cheated. In addition, when you write up your solution, you <strong>must </strong>list the names of every collaborator, that is, every other person that you talked to about the problem (even if you only discussed it briefly). You can do so in Coursemology by adding a Comment. Any deviation from this policy will be considered cheating, and will be punished severely, including referral to the NUS Board of Discipline.

<h2>Problem 1.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Optimization</h2>
Here’s a simple problem—find the maximum element in an array! Implement the following function:

<h3>public static int searchMax(int[] dataArray)</h3>
Given an array dataArray where every element is unique, return the value of the largest integer in the array.

There is one additional piece of information you need: the data in the array increases (or decreases) from one end until it reaches its maximum (or minimum), and then decreases (or increases) until it reaches the other end.

More precisely, if the data array has size <em>n</em>, there is some index <em>j </em>such that the subarray dataArray[0..j] is sorted (either increasing or decreasing) and the subarray dataArray[j..n-1] is sorted (either increasing or decreasing).

For example, the following are possible input arrays:

[2, 5, 7, 9, 15, 23, 8, 6]

[73, 42, 13, 5, -17, -324]

<h3>[100, 42, 17, 3, 8, 92, 234]</h3>
Use the most efficient algorithm you can. State the running time of your algorithm.

<strong>To think about (</strong><em>Optional</em><strong>):</strong>

<ol>
<li>What is the best way to signal an error, e.g., if the data array is empty?</li>
<li>What if all the elements in the array are not unique? How efficiently can the problem besolved then? What is the worst-case example?</li>
<li>This array changes direction once. What if it changes direction twice? Is the problem muchharder?</li>
<li>What if the array contains noisy data, so some of the entries in the array had +1 or −1 noise randomly added/subtracted from their initial value (with probability 1<em>/</em>2 in each direction). Can you solve the problem in that case? What would the expected running time be?</li>
</ol>
<h2>Problem 2.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Balancing the Load</h2>
Your boss, Paul R. Allel, storms into the office, shouting, “The system is too slow! Our users are sending me hate-tweets! Make it faster!” And then he stormed out again. What is he upset about? Well, right now, every day, your system churns through calculating dense matrix inverses for secret government agencies. And recently, there is so much work that one server just can’t keep up. So you decide to parallelize: by buying more servers, you should be able to perform the computation faster!

Today, you have <em>m </em>jobs, stored sequentially on disk, in order. Each job has a size: jobSize[i] is the size of job <em>i</em>.

You have <em>p </em>processors that can perform these jobs. Each processor can be assigned a consecutive sequence of jobs, i.e., processor 2 might be assigned jobs [4<em>,</em>5<em>,</em>6<em>,</em>7]. (For efficiency reasons<a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a>, we do not wants gaps: it would not be legal to assign processor 2 the jobs [4<em>,</em>5<em>,</em>7<em>,</em>8].) Here, for example, we have 10 tasks assigned to three processors:

<table width="589">
<tbody>
<tr>
<td width="28">0</td>
<td width="27">1</td>
<td width="82">2</td>
<td width="74">3</td>
<td width="42">4</td>
<td width="32">5</td>
<td width="85">6</td>
<td width="65">7</td>
<td width="21">8</td>
<td width="132">9</td>
</tr>
<tr>
<td width="28"></td>
<td width="27"></td>
<td width="82"></td>
<td width="74"></td>
<td width="42"></td>
<td width="32"></td>
<td width="85"></td>
<td width="65"></td>
<td width="21"></td>
<td width="132"></td>
</tr>
</tbody>
</table>
p1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; p2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; p3

The total load of a processor is the sum of the job sizes, e.g., in the above case the load of processor 2 is:

<h3>jobSize[4] + jobSize[5] + jobSize[6] + jobSize[7]</h3>
Your goal in this problem is to find an assignment of jobs to processors in a manner that minimizes the maximum load on any processor (that is, consider the processor with the highest load — we want the load on this processor to be as small as possible). In fact, for today, we will just compute the minimum possible load.

<strong>Problem 2.a.&nbsp;&nbsp; </strong>The first step is to figure out, given a specific target load, whether <em>p </em>processors is sufficient. Design and implement the most efficient algorithm you can think of for the following function:

<h3>static boolean feasibleLoad(int jobSize[], int queryLoad, int p)</h3>
Your function should return true if it is possible to schedule the jobs on <em>p </em>processors in such a way that no processor has more load than queryLoad. State the running time of your algorithm.

<strong>Problem 2.b. </strong>The second step is to determine the minimum achievable load. Suppose we have 5 processors and jobs with the following sizes:

[1, 3, 5, 7, 9, 11, 10, 8, 6, 4]

To ensure that the maximum load on any one processor is as small as possible, we can assign the jobs to the 5 processors this way:

[1, 3, 5, 7] [9] [11] [10] [8, 6, 4]

Notice that the maximum load on any processor is 18 — that’s the load on the last processor. With only 5 processors, this is the minimum achievable maximum load on any one processor, we can’t go lower than this!

Design and implement the most efficient algorithm you can think of for the following function: static int findLoad(int jobSize[], int p)

The function should return the minimum possible load for the given jobSize and p. State the running time of your algorithm.

<strong>Problem 2.c. </strong><em>Optional, theory. </em>In fact, the constraint that each processor can only handle a consecutive set of jobs simplifies the problem, but in many practical systems is not necessary. Unfortunately, even for <em>p </em>= 2, the problem is NP-hard if you allow an arbitrary assignment of jobs to processors. However, there is a very simple algorithm that guarantees that no processor is assigned more than <em>twice </em>the minimum possible load. (That is, it computes a 2-approximation of optimal.) Give a simple algorithm that guarantees a 2-approximation, and prove that it is correct. <em>Hint 1: </em>Think about a greedy algorithm that assigns each job to the least loaded processor.

<em>Hint 2: </em>Notice two facts about the “optimal” solution: its maximum load has to be at least as big as the biggest individual job, and its maximum load has to be at least as big as the sum of the job sizes divided by <em>p</em>.

<a href="#_ftnref1" name="_ftn1">[1]</a> This is obviously an artificial constraint that we have added to make the problem tractable. See part (c), below.
