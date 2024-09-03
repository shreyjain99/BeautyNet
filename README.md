
<h2 align= "center"><em>BeautyNet</em></h2>

<div align="center">
  <img height="400" src="https://github.com/shreyjain99/BeautyNet/blob/main/src%20files/cover%20image.jpg"/>
</div>

<hr width="100%" size="2">

<h3 align= "left"> <b> Key Project Formulation </b> </h3>

<br>

<p>
<strong>Get the data from :</strong> 

There were three datasets used in this project the links to them are below

<ol>
        <li>SCUT-FBP5500_v2.1 -- https://github.com/HCIILAB/SCUT-FBP5500-Database-Release</li>
        <li>mebeautydataset -- https://github.com/fbplab/MEBeauty-database</li>
        <li>hotornotdataset -- https://vision.cs.utexas.edu/projects/rationales/#data</li>
      
</ol>
</p>

<br>

<p>
<strong>Data Overview :</strong>
<br>
<li> For every malware, we have two files <ol> <li> .asm file (read more: https://www.reviversoft.com/file-extensions/asm) </li><li>.bytes file (the raw data contains the hexadecimal representation of the file's binary content, without the PE header)</li></ol></li>
    
<li>Total train dataset consist of 200GB data out of which 50Gb of data is .bytes files and 150GB of data is .asm files:  </li>
<li><b>Lots of Data for a single-box/computer.</b> </li>

<li>There are total 10,868 .bytes files and 10,868 asm files total 21,736 files </li>

<li>There are 9 types of malwares (9 classes) in our give data</li>
<li> Types of Malware:
    <ol>
        <li> Ramnit </li>
        <li> Lollipop </li>
        <li> Kelihos_ver3 </li>
        <li> Vundo </li>
        <li> Simda </li>
        <li> Tracur </li>
        <li> Kelihos_ver1 </li>
        <li> Obfuscator.ACY </li>
        <li> Gatak </li>
    </ol>
</li>


<br />

<br>

<p>
<strong>ML Problem Formulation :</strong>
</p>
<p> <strong>It is a binary classification problem, for a given pair of questions we need to predict if they are duplicate or not.</strong> </p>

<br>
<br>

<p>
<strong>Performance metrics :</strong>
</p>
<ol>
<li>Multi class log-loss </li>
<li>Confusion Matrix</li>
</ol>

<hr width="100%" size="2">

<br>

<body>

  <h3>Flow of Project : </h3>
  
  <br>

  <h3 align= "center">Reading Data and Basic Stats</h3>
  
  <div align= "center">|</div>
  <div align= "center">|</div>
  <div align= "center">\/</div>

  <h3 align= "center">Feature extraction from byte files</h3>

  <div align= "center">|</div>
  <div align= "center">|</div>
  <div align= "center">\/</div>

  <h3 align= "center">Feature extraction from asm files</h3>

  <div align= "center">|</div>
  <div align= "center">|</div>
  <div align= "center">\/</div>

  <h3 align= "center">Univariate and Multivariate Analysis</h3>


  <div align= "center">|</div>
  <div align= "center">|</div>
  <div align= "center">\/</div>

  <h3 align= "center">Modelling</h3>


  
</body>

<hr width="100%" size="2">

<br>

<p>
<strong>Future Scope :</strong>
</p>
<ol>
<li>Add bi-grams and n-gram features on byte files and improve the log-loss </li>
</ol>

<hr width="100%" size="2">
