# csci-b505-assignment-6-expectation-maximization-algorithm-solved
**TO GET THIS SOLUTION VISIT:** [CSCI-B505 Assignment 6-Expectation maximization algorithm Solved](https://www.ankitcodinghub.com/product/csci-b505-assignment-6-expectation-maximization-algorithm-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99633&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI-B505 Assignment 6-Expectation maximization algorithm Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Problem 1: Expectation-Maximization Algorithm for Clustering [30 pt.]

Implement expectation-maximization algorithm for Gaussian mixture models (see the EM algo- rithm below) in Python and call this program Gk. As you present your code explain your protocol for

1. initializing each Gaussian 2. deciding ties

3. stopping criteria

Problem 2: Analysis of the EM over Real-world Data Sets [20 pt.]

Run your EM program, Gk, against the Ringnorm and Ionosphere data sets. Discuss your results.

• Ringnorm Data Set

• Ionosphere Data Set

Run Gk with k = 2, . . . , 5 (20 runs each for each k). Report error rates and iteration counts for each k using whisker plots. An example of whisker can be found in the appendix.

A simple error rate can be calculated as follows:

• After Gk converges, combine the clusters to ended up with two clusters for any k as follows: Since the true clusters are known for a given arbitrary blocks number, final clusters are determined by measuring the Euclidean (this is the easiest choice) distances between true cluster centers and predicted cluster centers.

In other words, you will always calculate the error for k = 2 since there are only 2 clusters in the given data sets. Below is an example of error calculation for Ionosphere data set. You can similarly calculate an error rate for Ringnorm data set. After Gk converges, partition the data points to k-clusters, C1, . . . , Ck using likelihoods (hard assignment). A data point in a cluster is classified as good if P (gi) &gt; P (bi) and bad otherwise.

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment No 6 Page 2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
For each cluster Ci form two counts (over Ionosphere Data Set): gi ← 􏰇[δj=g], good

δj ∈Ci

bi ← 􏰇[δj==b], bad

δj ∈ci .B where[x=y]returns1ifTrue,0otherwise. Forexample,[2=3]+[0=0]+[34=34]=2

We can now calculate a simple error rate. Assume Gi is good. Then the error is:

bi

bi + gi

2 Error({C1, C2}) = 􏰇 error(Ci)

i=1

Given a text D and a pattern P, describe an Ω(d+p) time method for finding the longest prefix of P that is a substring of D. The lengths of D and P are d and p, respectively.

Problem 3.2

X, Y, and Z are three arrays and each has m elements. For an arbitrary integer t, describe O(m2logm)-time algorithm to determine if there exist numbers, x in X, y in Y, and z in Z, such that t = x+y+z.

Problem 3.3

Describe an efficient algorithm for deleting a string from a compressed trie and analyze its run- ning time.

Directions

Please follow the syllabus guidelines in turning in your homework. While testing your programs, run them with a variety of inputs and discuss your findings. This homework is due Sunday, Nov 23, 2021 10:00pm. OBSERVE THE TIME. Absolutely no homework will be accepted after that time. All the work should be your own.

</div>
</div>
<div class="layoutArea">
<div class="column">
error(Ci) = We can find the total error rate easily:

</div>
</div>
<div class="layoutArea">
<div class="column">
Problem 3: Algorithm Design [30pt] Problem 3.1

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment No 6 Page 3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Appendix

The EM algorithm

This part is provided to help you implement the EM algorithm.

LetD = {xj |j = 1,…,n}bethedatasetwhereeachxj ∈ Rd (R: Reals)andDisamix- ture of a Gaussian. Given D, the number of blocks k, and convergence threshold ε, the EM-T algorithm partition data into k clusters, C = {C1, C2, . . . , Ck}, where each Ci ∈ C can be charac- terized as a Gaussian distribution. If each cluster Ci ∈ C can be represented by a multivariate normal distribution (MVN):

f (xj |μi , Σi ) = 1 ∗ exp􏰈 − 1 (xj − μi )T Σ−1 (xj − μi )􏰉 (2π)d/2|Σi|1/2 2 i

where μi ∈ Rd and Σi ∈ Rd×d denote cluster mean and covariance matrix for cluster Ci, respectively, and they are unknown parameters. f(xj|μi,Σi) represents the probability density at xj for cluster Ci. Lastly, D is a mixture of C1,C2,…,Ck.

The algorithm iteratively alternates between (1) computing log-likelihood of each data point being from each Gaussian (E-step) (2) recalculating the parameters (M-step). Iteration contin- ues until a set of means is stable.

• Initialization:

– μi is randomly selected from D for each cluster.

– Σi ← I. For each cluster, the covariance matrix is a d × d identity matrix. – P (Ci ) = k1 . The priors are uniformly initialized.

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment No 6

</div>
<div class="column">
Page 4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Assignment No 6

</div>
<div class="column">
Page 5

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 1: An example of whisker plot

</div>
</div>
</div>
