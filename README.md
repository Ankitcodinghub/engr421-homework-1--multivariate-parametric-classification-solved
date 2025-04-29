# engr421-homework-1--multivariate-parametric-classification-solved
**TO GET THIS SOLUTION VISIT:** [ENGR421 Homework 1- multivariate parametric classification Solved](https://www.ankitcodinghub.com/product/engr-421-dasc-521-introduction-to-machine-learning-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113726&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ENGR421 Homework 1- multivariate parametric classification Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
In this homework, you will implement a multivariate parametric classification algorithm using Python. Here are the steps you need to follow:

1. Read Chapter 5 from the textbook.

2. Generate random data points from three bivariate Gaussian densities with the following parameters:

𝝁! = #++02..05) , 𝚺! = #++30..20 +0.0) ,

+1.2 𝑁! = 120

𝝁” = #−−22..50) , 𝚺” = #++10..28 +0.8) ,

+1.2 𝑁” = 80

𝝁# = #+−22..50) , 𝚺# = #+−10..28 −0.8) ,

+1.2 𝑁# = 100

Your data points should be like the following figure.

3. Estimate the parameters 𝝁1!, 𝝁1″, 𝝁1#, 𝚺2!, 𝚺2″, 𝚺2#, 𝑃4(𝑦 = 1), 𝑃4(𝑦 = 2), and 𝑃4(𝑦 = 3) using the data points you generated in the previous step. Your parameter estimations should be like the following figures.

print(sample_means)

[[-0.06002769 2.37891762]

[-2.48316966 -2.07440702]

[ 2.566945 -1.97561107]]

print(sample_covariances) [[[ 3.50095107 0.31087713]

[ 0.31087713 1.21501349]]

[[ 1.19789275 0.64059315]

[ 0.64059315 0.95264856]]

[[ 1.25199541 -0.79696973]

[-0.79696973 1.17191475]]]

print(class_priors)

[0.4, 0.26666666666666666, 0.3333333333333333]

4. Calculate the confusion matrix for the data points in your training set using the parametric classification rule you will develop using the estimated parameters from the previous step. Your confusion matrix should be like the following matrix.

y_truth 1 2 3 y_pred 1 119 1 2

2 1 79 0

3 0 0 98

5. Draw your decision boundaries that you will calculate using the parametric classification rule from the previous step together with data points and clearly mark misclassified data points. Your figure should be like the following figure.

What to submit: You need to submit your source code in a single file (.py file) and a short report explaining your approach (.doc, .docx, or .pdf file). You will put these two files in a single zip file named as STUDENTID.zip, where STUDENTID should be replaced with your 7-digit student number.

How to submit: Submit the zip file you created to Blackboard. Please follow the exact style mentioned and do not send a zip file named as STUDENTID.zip. Submissions that do not follow these guidelines will not be graded.

Cheating policy: Very similar submissions will not be graded.
