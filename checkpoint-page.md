##CHECKPOINT REPORT

###As per schedule

- April 11-13: Revisited our original proposal and after discussion with Prof.
  Kayvon, we pivoted from our original idea. After lot of brainstorming, we came
  up with the new project proposal “Parallel Triangle Counting on GPU”
<br>
- April 14-18: Thoroughly went through the reference paper and understood the
  algorithm and its intricacies.
<br>
- April 19-24: Came up with a draft design of the implementation and gathered
  libraries and test cases for benchmarking
<br>

###Pending

- April 25-May 1: Implement the first version and prepare for final exam
<br>
- May 2-9: Optimize the initial implementation and perform analysis
<br>

---

###Progress So far
- After changing our initial project proposal, things went as planned. Till now
  we have gathered all the benchmarking test cases (graphs). That is:

  -------------------------------------------------------------------
  <br>
  | Dataset Names       |   #nodes    |   #edges    |   #triangles  |
  <br>
  -------------------------------------------------------------------
  <br>
  | cit-Patents         |  3,774,7683 |   3,037,896 |   7,515,023   |
  <br>
  -------------------------------------------------------------------
  <br>
  | coAuthorsCiteseer   |   227,320   |   1,628,268 |   8,100,000   |
  <br>
  -------------------------------------------------------------------
  <br>
  | coPapersDBLP        |   540,486   |  30,491,458 | 1,300,000,000 |
  <br>
  -------------------------------------------------------------------
  <br>
  | road central        | 14,081,816  |  33,866,826 |    687,000    |
  <br>
  -------------------------------------------------------------------
  <br>
  | soc-LiveJournal1    |   4,847,571 | 137,987,546 |   285,730,264 |
  <br>
  -------------------------------------------------------------------
  <br>
  | com-Orkut           |   3,072,441 | 234,370,166 |   627,584,181 |
  <br>
  -------------------------------------------------------------------
  <br>


- Further, we have spent a lot of time on understanding the k-truss approach of
  the subgraph technique mentioned in the paper. We have made a rough design on
  how to go ahead with the implementation, but we have not spent much time on
  the design part as from the assignments we understand that it is better to
  start with a simple straightforward implementation initially. 

- We are on track with respect to the goals and deliverables stated in our
  proposal. We still believe that we will be able to achieve all the things that
  we have mentioned in our goals. 

- We are planning to show performance analysis of our algorithm using graphs.
  Graphs will basically analyse performance of our algorithm wrt baseline
  implementations.