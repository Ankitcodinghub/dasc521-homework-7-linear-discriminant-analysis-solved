# dasc521-homework-7-linear-discriminant-analysis-solved
**TO GET THIS SOLUTION VISIT:** [DASC521 Homework 7-Linear Discriminant Analysis Solved](https://www.ankitcodinghub.com/product/dasc521-homework-7-linear-discriminant-analysis-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92731&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;DASC521 Homework 7-Linear Discriminant Analysis Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="column">
In this homework, you will implement the linear discriminant analysis algorithm in Python. Here are the steps you need to follow:

1. You are given a multiclass classification data set, which contains 4000 clothing images of size 28 pixels × 28 pixels (i.e., 784 pixels). These images are from ten distinct classes, namely, “t-shirt/top”, “trouser”, “pullover”, “dress”, “coat”, “sandal”, “shirt”, “sneaker”, “bag”, and “ankle boot”. The figure below shows five sample figures from each class. You are given two data files:

a. hw07_data_set_images.csv: clothing images,

b. hw07_data_set_labels.csv: corresponding class labels.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ol start="2">
<li>Divide the data set into two parts by assigning the first 2000 images to the training set and the remaining 2000 images to the test set.</li>
<li>Calculate 𝑺! and 𝑺” matrices. Your matrices should be like the following figures. (20 points)
)&amp; )&amp;

𝑺! =$$(𝒙# −𝝁$)(𝒙# −𝝁$)%𝑦#$ 𝑺” =$$(𝝁$ −𝝁)(𝝁$ −𝝁)%𝑦#$ #'( $'( #'( $'(

<pre>  print(SW[0:5, 0:5])
</pre>
<pre>  print(SB[0:5, 0:5])
</pre>
<pre>  [[195.0531401  138.98550725 138.24154589   273.64251208]
   [138.98550725 146.68407152 137.97108222   212.80522823]
   [138.24154589 137.97108222 237.79940915   222.04558827]
   [273.64251208 212.80522823 222.04558827 10381.73114607]]
</pre>
<pre>  [[0.8488599  0.86049275  1.26145411  4.64248792]
   [0.86049275 1.07392848  2.24791778  8.49977177]
   [1.26145411 2.24791778  6.68009085 25.25691173]
   [4.64248792 8.49977177 25.25691173 97.25635393]]
</pre>
</li>
<li>Calculate the largest nine eigenvalues and their corresponding eigenvectors of 𝑺*(𝑺 !”
matrix. Your eigenvalues should be like the following figures. (10 points)

<pre>  print(values[0:9])
  [26.03085646 11.57909822 7.86259994
</pre>
<pre>    5.12082313 3.60002676  3.22503144
    2.71288241 1.3688596   1.13340931]
</pre>
</li>
<li>Using the two eigenvectors that correspond to the largest two eigenvalues, project the training and test data points in a two-dimensional subspace using 𝑧# = 𝑾% (𝒙# − 𝝁) formula. Draw these two-dimensional projections using a separate color for each class. Your figures should be like the following figures. (30 points)</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
6. Using the nine eigenvectors that correspond to the largest nine eigenvalues, project the training and test data points in a nine-dimensional subspace using 𝑧# = 𝑾% (𝒙# − 𝝁) formula. Learn a 𝑘-nearest neighbor classifier by setting 𝑘 = 11. Calculate confusion matrices on the training and test data points. Your confusion matrices should be like the following figures. (40 points)

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>     print(confusion_matrix)
     y_train   1    2    3    4    5    6    7    8    9    10
     y_hat
</pre>
<ol>
<li>
<pre>     1 &nbsp;       203    0    1    1    0    0   15    0    0    0
</pre>
</li>
<li>2 &nbsp;019201000000</li>
<li>3 &nbsp;0019803011000</li>
<li>4 &nbsp;221202304000</li>
<li>5 &nbsp;008120109000</li>
<li>6 &nbsp;000001750300</li>
<li>7 &nbsp;9026110168010</li>
<li>8 &nbsp;000003019601</li>
<li>9 &nbsp;000000001830</li>
<li>10 &nbsp;000000000184</li>
</ol>
<pre>     print(confusion_matrix)
     y_test   1    2    3    4    5    6   7    8    9    10
     y_hat
     1
     2
     3
     4
     5
     6
     7
     8
     9
     10
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
