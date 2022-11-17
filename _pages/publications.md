---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<ul style="list-style-type:circle;">

<h1 class="year">2022</h1> 

 
<ul>
     <li><a href="https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0274801" style="color: #B509AC; text-decoration:none;" target="\_blank">Numerical study of magnetic hyperthermia ablation of breast tumor on an anatomically realistic breast phantom </a>
<br><strong>Reza Rahpeima</strong>, and Chao-An Lin,<br><em>Plos One, 2022, doi: 10.1371/journal.pone.0274801.</em></li>


<p><i class="fas fa-globe" style="color:Blue"></i> <a href="https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0274801" style="color: blue; text-decoration:none;" target="\_blank">Plos One</a> | <i class="fas fa-file-pdf" style="color:red"></i> <a href="https://github.com/Rahpeima/required/files/9996687/journal.pone.0274801.1.pdf" style="color: red; text-decoration:none;" target="\_blank">PDF</a> | <button onclick="myFunction()" id="myBtn">Read more</button></p>
 
<style>
#more {display: none;}
</style> 
 
<span id="dots"></span><span id="more">
 
 <p align="center">
  <img width="447" height="390" src="https://user-images.githubusercontent.com/117890455/201510899-8b91c432-c60c-4569-9f97-f878e617ee70.png">
</p>


<p align="justify"><b>Abstract:</b> Magnetic fluid hyperthermia (MFH) is a novel reliable technique with excellent potential for thermal therapies and treating breast tumours. This method involves injecting a magnetic nanofluid into the tumour and applying an external AC magnetic field to induce heat in the magnetic nanoparticles (MNPs) and raise the tumour temperature to ablation temperature ranges. Because of the complexity of considering and coupling all different physics involves in this phenomenon and also due to the intricacy of a thorough FEM numerical study, few FEM-based studies address the entire MFH process as similar to reality as possible. The current study investigates a FEM-based three-dimensional numerical simulation of MFH of breast tumours as a multi-physics problem. An anatomically realistic breast phantom (ARBP) is considered, some magnetic nanofluid is injected inside the tumour, and the diffusion phenomenon is simulated. Then, the amount of heat generated in the MNP-saturated tumour area due to an external AC magnetic field is simulated. In the end, the fraction of tumour tissue necrotized by this temperature rise is evaluated. The study’s results demonstrate that by injecting nanofluid and utilizing seven circular copper windings with each coil carrying 400 A current with a frequency of 400 kHz for generating the external AC magnetic field, the temperature in tumour tissue can be raised to a maximum of about 51.4°C, which leads to necrosis of entire tumour tissue after 30 minutes of electromagnetic field (EMF) exposure. This numerical platform can depict all four various physics involved in the MFH of breast tumours by numerically solving all different equation sets coupled together with high precision. Thus, the proposed model can be utilized by clinicians as a reliable tool for predicting and identifying the approximate amount of temperature rise and the necrotic fraction of breast tumour, which can be very useful to opt for the best MFH therapeutic procedure and conditions based on various patients. In future works, this numerical platform’s results should be compared with experimental in-vivo results to improve and modify this platform in order to be ready for clinical applications.</p></span></ul>


<script>
function myFunction() {
  var dots = document.getElementById("dots");
  var moreText = document.getElementById("more");
  var btnText = document.getElementById("myBtn");

  if (dots.style.display === "none") {
    dots.style.display = "inline";
    btnText.innerHTML = "Read more"; 
    moreText.style.display = "none";
  } else {
    dots.style.display = "none";
    btnText.innerHTML = "Read less"; 
    moreText.style.display = "inline";
  }
}
</script>
<br>

 
<ul>
     <li><a href="https://ieeexplore.ieee.org/document/9813381" style="color: #B509AC; text-decoration:none;" target="\_blank">Unsupervised Hyperspectral Denoising Based on Deep Image Prior and Least Favorable Distribution </a>
<br><strong>K. F. Niresi</strong>, and C. -Y. Chi,<br><em>IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, 2022, doi: 10.1109/JSTARS.2022.3187722.</em></li>


<p><i class="fa fa-file" style="color:blue"></i> <a href="https://ieeexplore.ieee.org/document/9813381" style="color: blue; text-decoration:none;" target="\_blank">IEEE Xplore</a> | <i class="fas fa-file-pdf" style="color:red"></i> <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9813381" style="color: red; text-decoration:none;" target="\_blank">PDF</a> | <i class="fab fa-github" style="color:green"></i> <a href="https://github.com/Keiv4n/HLF-DIP" style="color: green; text-decoration:none;" target="\_blank">Code</a> | <i class="fas fa-globe" style="color:brown"></i> <a href="https://openremotesensing.net/knowledgebase/unsupervised-hyperspectral-denoising-based-on-deep-image-prior-and-least-favorable-distribution/" style="color:brown; text-decoration:none;" target="\_blank">Open Remote Sensing</a> | <button onclick="myFunction2()" id="myBtn2">Read more</button></p>
 

 
<span id="dots2"></span><span id="more2">
 
 <p align="center">
  <img width="650" height="288" src="https://user-images.githubusercontent.com/107177894/177000820-a4c0ccea-9dc6-4c0c-9291-4b6a46c9d587.png">
</p>


<p><b>Abstract:</b> This paper considers the inverse problem under hyperspectral images (HSIs) denoising framework. Recently, it has been shown that deep learning is a promising approach to image denoising. However, deep learning to be effective usually needs a massive amount of training data. Moreover, in a practical scenario, HSIs may get contaminated by different kinds of noises such as Gaussian and/or sparse noise. Lately, it has been reported that the convolutional neural network (CNN), the core element used by deep image prior (DIP), is able to capture image statistical characteristics without the need of training, i.e., restore the clean image blindly. Nonetheless, there exists some performance gap between DIP and state-of-the-art methods in HSIs (e.g., low-rank models). By applying the Huber loss function (HLF), which is derived through a least favorable distribution in robust statistics, to DIP, we propose a novel unsupervised denoising algorithm, referred as to the HLF-DIP, free from pre-training and without involving any regularizer. Extensive experimental results are provided to demonstrate that the proposed HLF-DIP algorithm significantly outperforms seven state-of-the-art algorithms in both complexity (thanks to no regularization) and robustness against complex noise (e.g., mixed types of noises).</p></span></ul>

<script>
 
dots = document.getElementById("dots2");
dots.style.display = "inline";
moreText = document.getElementById("more2")
moreText.style.display = "none";
 
 
function myFunction2() {
  var dots = document.getElementById("dots2");
  var moreText = document.getElementById("more2");
  var btnText = document.getElementById("myBtn2");

  if (dots.style.display === "none") {
    dots.style.display = "inline";
    btnText.innerHTML = "Read more"; 
    moreText.style.display = "none";
  } else {
    dots.style.display = "none";
    btnText.innerHTML = "Read less"; 
    moreText.style.display = "inline";
  }
}
</script>
<br>

<h1 class="year">2021</h1>
<ul>
     <li><a href="https://ieeexplore.ieee.org/document/9813381" style="color: #B509AC; text-decoration:none;" target="\_blank">Unsupervised Hyperspectral Denoising Based on Deep Image Prior and Least Favorable Distribution </a>
<br><strong>K. F. Niresi</strong>, and C. -Y. Chi,<br><em>IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, 2022, doi: 10.1109/JSTARS.2022.3187722.</em></li>


<p><i class="fa fa-file" style="color:blue"></i> <a href="https://ieeexplore.ieee.org/document/9813381" style="color: blue; text-decoration:none;" target="\_blank">IEEE Xplore</a> | <i class="fas fa-file-pdf" style="color:red"></i> <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9813381" style="color: red; text-decoration:none;" target="\_blank">PDF</a> | <i class="fab fa-github" style="color:green"></i> <a href="https://github.com/Keiv4n/HLF-DIP" style="color: green; text-decoration:none;" target="\_blank">Code</a> | <i class="fas fa-globe" style="color:brown"></i> <a href="https://openremotesensing.net/knowledgebase/unsupervised-hyperspectral-denoising-based-on-deep-image-prior-and-least-favorable-distribution/" style="color:brown; text-decoration:none;" target="\_blank">Open Remote Sensing</a> | <button onclick="myFunction3()" id="myBtn3">Read more</button></p>
 

 
<span id="dots3"></span><span id="more3">
 
 <p align="center">
  <img width="650" height="288" src="https://user-images.githubusercontent.com/107177894/177000820-a4c0ccea-9dc6-4c0c-9291-4b6a46c9d587.png">
</p>


<p><b>Abstract:</b> This paper considers the inverse problem under hyperspectral images (HSIs) denoising framework. Recently, it has been shown that deep learning is a promising approach to image denoising. However, deep learning to be effective usually needs a massive amount of training data. Moreover, in a practical scenario, HSIs may get contaminated by different kinds of noises such as Gaussian and/or sparse noise. Lately, it has been reported that the convolutional neural network (CNN), the core element used by deep image prior (DIP), is able to capture image statistical characteristics without the need of training, i.e., restore the clean image blindly. Nonetheless, there exists some performance gap between DIP and state-of-the-art methods in HSIs (e.g., low-rank models). By applying the Huber loss function (HLF), which is derived through a least favorable distribution in robust statistics, to DIP, we propose a novel unsupervised denoising algorithm, referred as to the HLF-DIP, free from pre-training and without involving any regularizer. Extensive experimental results are provided to demonstrate that the proposed HLF-DIP algorithm significantly outperforms seven state-of-the-art algorithms in both complexity (thanks to no regularization) and robustness against complex noise (e.g., mixed types of noises).</p></span></ul>


<script>
function myFunction3() {
  var dots3 = document.getElementById("dots3");
  var moreText3 = document.getElementById("more3");
  var btnText3 = document.getElementById("myBtn3");

  if (dots3.style.display === "none") {
    dots3.style.display = "inline";
    btnText3.innerHTML = "Read more"; 
    moreText3.style.display = "none";
  } else {
    dots3.style.display = "none";
    btnText3.innerHTML = "Read less"; 
    moreText3.style.display = "inline";
  }
}
</script>
<br>
 
 <h1 class="year">2020</h1>
 <h1 class="year">2019</h1>


 
