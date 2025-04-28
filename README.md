# comp3270-assignment-9-solved
**TO GET THIS SOLUTION VISIT:** [COMP3270 Assignment 9 Solved](https://www.ankitcodinghub.com/product/comp3270-objective-of-this-assignment-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;118147&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP3270 Assignment 9 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
• To verify empirically Theorem 12.4 (Chapter 12, Textbook) that states:

“The expected height h(n) of a randomly built binary search tree on n distinct keys is O(lg n).” What you need to do:

1. (10 points) Implement the Tree-Insert(T,z) operation on a binary search tree.

2. Repeatedly insert 𝒏 randomly picked numbers in a binary search tree and collect the height 𝒉(𝒏) of the obtained tree.

ℎ(𝑛) is the height of the binary search tree containing n elements. For simplicity, no need to enforce that the keys are distinct. In other words, you do need to check whether a number is already in the tree. 3. (60 points = (20 points per function/plot)) Plot on three separate graphs the plots of the functions ℎ(𝑛), ℎ(𝑛), and ℎ(𝑛) versus

𝑙𝑔(𝑛) 𝑛ξ𝑛 𝑛𝑙𝑔(𝑛) n.

4. (30 points: 10 points per plot) Discuss the three plots and conclude regarding the asymptotic growth of h(n). Decide whether your measurements confirm Theorem 12.4.

Objective:

The objective of this programming assignment is to verify empirically Theorem 12.4 that states that “the expected height of a randomly built binary search tree on n distinct keys is O(lg n).”

In order to conduct this experiment, you must implement in your preferred language (available on Tux Machines) the Tree-Insert(T,z) operation. Below, I explain in pseudocode the program you must write to collect data and verify Theorem 12.4. You do not need to enforce that the keys are distinct.

Program to implement

collectData()

for n = 250 to 20,000 by 250 // 250, 500, 750, 1,000, …. 20,000

sum_heightn = 0

for j = 1 to 5 do //Take 5 measurements mj for j=1 to 5 for i = 1 to n

pick randomly a number p in the range [0-40,000]

create a node z set z.key = p

Tree-Insert(T,z)

Measure the height hj of the tree

Discard Tree (free memory)

sum_heightn += hj

collect Height(n)= sum_heightn/5 // Average height for n

Write in a file F the value n and Height(n)

Data Analysis

ℎ(𝑛) ℎ(𝑛) ℎ(𝑛)

Use any plotting software (e.g., Excel) to plot the functions , , and where ℎ(𝑛) is the value Height(n) you collected in 𝑙𝑔(𝑛) 𝑛ξ𝑛 𝑛𝑙𝑔(𝑛)

File F. File F is the file produced by the program you implemented. Discuss your results based on the plots. Decide whether Theorem 12.4 (Chapter 12, Textbook) is correct. This theorem states “The expected height h(n) of a randomly built binary search tree on n distinct keys is O(lg n).”

Start inserting your answers on the next page &gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;

Start Answering On This Page Where Indicated In Blue:

1. (10 points) Implement the Tree-Insert(T,z) operation on a binary search tree.

Insert here a snapshot of your implemented Tree-Insert(T,z) method in your preferred language…

2. Repeatedly insert 𝒏 randomly picked numbers in a binary search tree and collect the height 𝒉(𝒏). ℎ(𝑛) is the height of the binary search tree containing n elements. For simplicity, no need to enforce that the keys are distinct. In other words, you do need to check whether a number is already in the tree.

Submit/Attach your program CollectData (to collect data) separately on Canvas for this assignment. The program is your implementation of the pseudocode provided above to collect data. You can use any language as long as it is already available on Engineering Unix Tux machines. Include here the directives to compile and execute your program CollectData.

3. (60 points (20 points per function/plot)) Plot on three separate graphs the same plot of the functions ℎ(𝑛), ℎ(𝑛), and ℎ(𝑛)

𝑙𝑔(𝑛) 𝑛ξ𝑛 𝑛𝑙𝑔(𝑛) versus n.

ℎ(𝑛)

Insert here the plot for ……..

𝑙𝑔(𝑛)

ℎ(𝑛)

Insert here the plot for ……..

𝑛ξ𝑛

ℎ(𝑛)

Insert here the plot for ……..

𝑛𝑙𝑔(𝑛)

4. (30 points: 10 points per plot) Discuss the three plots and conclude regarding the asymptotic growth of h(n). Decide whether your measurements confirm Theorem 12.4.

ℎ(𝑛)

Discuss here the plot ……..

𝑙𝑔(𝑛)

ℎ(𝑛)

Discuss here the plot ……..

𝑛ξ𝑛

ℎ(𝑛)

Discuss here the plot ……..

𝑛𝑙𝑔(𝑛)

Conclude the validity of Theorem 12.4

Report

• Insert your answers where indicated. This file with your inserted answers will contain, explain, and discuss the plots.

• In addition, the above report (this file) must contain the following information: o whether your data collection program works or not (this must be just ONE sentence) o the directions to compile and execute your program

• Good writing is expected.

• Recall that answers must be well written, documented, justified, and presented to get full credit.

•

What you need to turn in:

• Electronic copy of your source data collection program (separately attached to this assignment)

• Electronic copy of this file (including your inserted answers) (separately attached). Submit the file as a Microsoft Word or PDF file.

Grading

• See points distribution with questions/tasks.
