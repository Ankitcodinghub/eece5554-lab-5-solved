# eece5554-lab-5-solved
**TO GET THIS SOLUTION VISIT:** [EECE5554 LAB 5 Solved](https://www.ankitcodinghub.com/product/eece5554-lab-5-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95072&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EECE5554 LAB 5 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
In this lab we will look at the role and use of calibrated cameras for simple photomosaicing.&nbsp; We assume throughout that you will be using your camera phone for all the imaging associated with this homework.

<ol>
<li>Go through the Matlab example on feature based panoramic image stitching. We will use this as a template for our work</li>
</ol>
<a href="https://www.mathworks.com/help/vision/ug/feature-based-panoramic-image-stitching.html?searchHighlight=panorama&amp;s_tid=doc_srchtitle">https://www.mathworks.com/help/vision/ug/feature-based-panoramic-image-stitching.html?searchHighlight=panorama&amp;s_tid=doc_srchtitle</a>

<ol start="2">
<li>Camera Calibration. Take a look at the Caltech Camera Calibration toolbox. Print out a calibration pattern and stick it firmly to a really flat object. Now take pictures of the calibration object from different angles while making sure that the calibration object fills most of the image. Use the example that is provided to figure out how to calibrate your phone camera. Try and make sure that the reprojection error after calibration is reasonable.</li>
</ol>
<a href="http://www.vision.caltech.edu/bouguetj/calib_doc/">http://www.vision.caltech.edu/bouguetj/calib_doc/</a>

<ol start="3">
<li>Now go out on Forsyth street and take multiple, overlapping images of the mural on the Latino Students Center building. You should have at least five or six images.</li>
<li>Play with the harris feature detector file provided with his homework (note you also need the convolve2.m file – also provided) to get features well distributed across the image.</li>
<li>Use the Matlab example code to figure out how to make a panoramic mosaic of the entire building but make sure you use the harris detector that has been provided as opposed to the feature detector the Matlab example uses.</li>
<li>Now repeat the mosaicing exercise with images of a cinder block wall just like the example shown in class (again use 5-6 images that overlap by about 50%).</li>
<li>Collect one last set of images (of any other piece of graffiti art anywhere on campus) where the overlap is considerably smaller (say 15%). Does your mosaicing algorithm still work? What changes if any did you have to make.</li>
</ol>
<strong>Lab 5 Writeup – What we are expecting to see</strong>

Part 1. Nothing required.

Part 2. Camera Calibration. Show us the images you took for camera calibration and the resultant reprojection pixel error (as shown in the plot in the Camera Calibration Toolbox). Also output your calibration parameters and a single image before and after calibration.

&nbsp;

Part 3. Data Collection: Show us the images you are going to use for your mosaic

&nbsp;

Part 4. Show us the distribution of Harris Corners across a single (or more) representative set of images.

Part 5. Show us the final mosaic and any intermediate image steps that you deem reasonable while following along with the Matlab code.

Also all .m files you used for the lab.

Part 6. Show us how the code fails(?) in the cinder block imagery and write a couple of sentences explaining why it does so.

Part 7. Show us your initial images and the final mosaic and anything else you deem necessary to explain your results.

Please check everything (report, m files) into a folder (called Lab5) in your gitlab directory.

&nbsp;
