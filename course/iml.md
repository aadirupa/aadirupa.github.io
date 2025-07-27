---
layout: splash
title: "CS 412: Intro to Machine Learning"
date: 2025-01-14
permalink: /course/iml/
tags:
  - ml
  - ai
  - python
  - course
author_profile: false  
sidebar: false         
classes: wide          
---

<html lang="en">
<head>
  <style>
    body .page__content {
      max-width: 100% !important;
      width: 100% !important;
      margin: 0 auto !important;
      padding-bottom: 60px;
    }
    body {
      font-family: sans-serif;
      margin: 0;
      padding: 0;
      background: #fff;
      padding-bottom: 60px;
    }
    a:link {
      color: RoyalBlue;
      text-decoration: none;
    }
    a:visited {
      color: Purple;
    }
    a:hover {
      color: RoyalBlue;
      text-decoration: underline;
    }
    a:active {
      color: DarkRed;
    }
    .tab {
      overflow: hidden;
      border-bottom: 2px solid #0074D9;
      background-color: #f1f1f1;
      border-radius: 5px 5px 0 0;
    }
    .tab button {
      background-color: #e6f0ff;
      float: left;
      border: none;
      cursor: pointer;
      padding: 10px 20px;
      font-weight: bold;
      font-size: 1em;
      border-radius: 5px 5px 0 0;
      color: #004080;
    }
    .tab button:hover {
      background-color: #cce0ff;
    }
    .tab button.active {
      background-color: #4169E1;
      color: white;
    }
    .tabcontent {
      display: none;
      padding: 15px;
      border: 1px solid #ccc;
      border-top: none;
      background-color: #ffffff;
      border-radius: 0 0 5px 5px;
    }
    table {
      width: 100%;
      border-collapse: collapse;
    }
    td, th {
      padding: 8px 10px;
      border: 1px solid #ccc;
      vertical-align: top;
    }
    td {
   font-size: 1.1em;
   line-height: 1.5;
   padding: 10px;
   }
    th {
      background-color: #f2f2f2;
      font-weight: bold;
      text-align: center;
    }
  </style>

  <script>
    function openTab(evt, tabName) {
      var i, tabcontent, tablinks;
      tabcontent = document.getElementsByClassName("tabcontent");
      for (i = 0; i < tabcontent.length; i++) {
        tabcontent[i].style.display = "none";
      }
      tablinks = document.getElementsByClassName("tablinks");
      for (i = 0; i < tablinks.length; i++) {
        tablinks[i].className = tablinks[i].className.replace(" active", "");
      }
      document.getElementById(tabName).style.display = "block";
      evt.currentTarget.className += " active";
    }
  </script>
</head>

<body>
  <h2 style="color:DarkBlue;">CS 412: Intro to Machine Learning (Spring 2025)</h2>
  <div style="font-size: 1.05em; margin-bottom: 20px; color: #003366;"> <span style="font-weight: bold;">🖍️ Instructor:</span> <span style="font-size: 1.1em; font-weight: bold;">Aadirupa Saha</span>  </div>

  <div class="tab">
    <button class="tablinks" onclick="openTab(event, 'Schedule')">Schedule</button>
    <button class="tablinks" onclick="openTab(event, 'Description')">Description</button>
    <button class="tablinks" onclick="openTab(event, 'Prerequisites')">Prerequisites</button>
    <button class="tablinks" onclick="openTab(event, 'Resources')">Resources</button>
    <button class="tablinks" onclick="openTab(event, 'Logistics')">Logistics</button>
  </div>

  <div id="Schedule" class="tabcontent">
    <h2>📅 Course Schedule</h2>
    <table>
      <tr>
        <th>Date</th>
        <th>Topic</th>
        <th>Reading</th>
        <th>Materials</th>
        <th>Notes</th>
      </tr>
      <tr>
        <td><strong>Jan 21</strong></td>
        <td>Introduction (Course Logistics)<br><em>Basics of Supervised Learning</em></td>
        <td>PML 1.2<br>ESL 2.1, 2.2</td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/Intro.pdf">📊 CS412-Intro.pdf</a></td>
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fd08138670a36d8bb680654314bd90e2efec733d31cf47f41f911afee8765539a%2FHW1.pdf">HW1.pdf</a> (Self-Assessment)<br>[Submit on Gradescope]<br>Due: Jan 28</td>
      </tr>
      <tr>
        <td><strong>Jan 23</strong></td>
        <td>Understanding loss functions</td>
        <td>PML 4.3</td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe1.pdf">Scribe1</a>: Edomwonyi, Uwadia</td>
        <td></td>
      </tr>
      <tr>
        <td><strong>Jan 28</strong></td>
        <td>Hypothesis (Func) Class<br><em>ERM</em><br><em>Linear Regression</em></td>
        <td>PML 11.1, 11.2,11.3<br>ESL 3.2</td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe2.pdf">Scribe2</a>: Shelke, Harsh</td>
        <td>HW1 due today!</td>
      </tr>
      <tr>
        <td><strong>Jan 30</strong></td>
        <td>Overfitting & Regularizers<br><em>Lin-Reg: Linear Regression (contd)</em></td>
        <td>PML 4.3, 5.4</td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe3.pdf">Scribe3</a>: Hulu, Charis/ Lokesh</td>
        <td></td>
      </tr>
      <tr>
        <td><strong>Feb 4</strong></td>
        <td>Logistic Regression<br><em>Multiclass Logistic Regression (MLR)</em></td>
        <td>PML 10.2.1, 10.2.2<br>ESL 4.4.1</td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe4.pdf">Scribe4</a>: Dahagam, Sujay</td>
        <td>HW2 out [<a href="https://drive.google.com/drive/folders/11Ih8rD8iESXepnDFFAluxTk3xqJXA3vP?usp=drive_link">link</a>]<br>(UIC credentials rqd.)<br>Finalize scribe assignment</td>
      </tr>
      <tr>
        <td><strong>Feb 6</strong></td>
        <td>Multiclass logistic (contd)<br><em>MLE (Bernoulli)</em><br><em>MAP (Bernoulli)</em></td>
        <td>PML 4.2, 4.5<br><a href="https://www.cs.cmu.edu/~aarti/Class/10701_Spring14/slides/MLE_MAP_Part1.pdf">Slides CMU 10701</a><br><a href="https://www.cs.cmu.edu/afs/cs.cmu.edu/user/mitchell/ftp/mlbook.html#:~:text=Estimating%20Probabilities%3A%20MLE%20and%20MAP">Tom Mitchell's note</a></td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe5.pdf">Scribe5</a>: Bhat, Amith</td>
        <td>Bonus-Quiz [<a href="https://drive.google.com/file/d/1gWiUMzz8lrlBcbCRbx7uLitmw05BvfxL/view?usp=sharing">qz-feb6.pdf</a>]<br>(submit to gradescope)<br><a href="https://docs.google.com/forms/d/e/1FAIpQLSdYYJh6z8eeiWFltCnQmHSYx1jF1AAjJ9Aqhoct-TNkfZFsxQ/viewform?usp=dialog">Feedback form</a><br><a href="/class/m5vnz1h225x1c0/post/32">Announcements</a></td>
      </tr>
      <tr>
        <td><strong>Feb 8</strong><br><strong>[Extra Class-1]</strong></td>
        <td>MLE for Regression<br><em>MAP = Regularization</em></td>
        <td>PML 4.2.5 - 4.2.7, 4.5<br><a href="https://www.cs.cmu.edu/~10315/notes/10315_S23_Notes_MLE_draft2.pdf">CMU 10-315 notes</a><br><a href="https://bjlkeng.io/posts/probabilistic-interpretation-of-regularization/">Nice blog</a></td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe6.pdf">Scribe6</a>: Sappidi, Yugesh</td>
        <td>Optional Reading:<br>Conjugate Priors<br>• <a href="https://www.statlect.com/fundamentals-of-statistics/conjugate-prior">Nice blog</a><br>• <a href="https://www2.stat.duke.edu/courses/Fall11/sta114/conjug.pdf">Duke STA114</a></td>
      </tr>
      <tr>
        <td><strong>Feb 11</strong></td>
        <td>Regularized logistic regression thru' MAP<br><em>Convex functions</em></td>
        <td>PML 10.1-10.3<br>CvxO 1.1-1.3<br><a href="https://mitliagkas.github.io/ift6085-2019/ift-6085-lecture-2-notes.pdf">Notes-IFT 6085</a></td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe7.pdf">Scribe7</a>: Ferdowsi, Farhad</td>
        <td>HW2 due!</td>
      </tr>
      <tr>
        <td><strong>Feb 13</strong></td>
        <td>Properties of Cvx funcs<br><em>Gradient descent (GD)</em><br><em>Convergence rates</em></td>
        <td>CvxO 1.1-1.3, 3.1<br><a href="https://www.princeton.edu/~aaa/Public/Teaching/ORF523/S16/ORF523_S16_Lec7_gh.pdf">Notes by A. Ahmadi</a><br><a href="https://chunpai.github.io/assets/note/1__Gradient_Descent_and_Line_Search.pdf">Notes by C Wang</a></td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe8.pdf">Scribe8</a>: Ferdowsi, Farhad</td>
        <td>Extra Reading<br>1. <a href="https://www.cis.upenn.edu/~cis5150/cis515-11-sl4.pdf">Matrix Norms</a></td>
      </tr>
      <tr>
        <td><strong>Feb 18</strong></td>
        <td>Convergence of GD<br><em>Newton's method</em></td>
        <td>CvxO 3.1, 3.2, 3.4, 5.3.2<br><a href="https://cims.nyu.edu/~cfgranda/pages/OBDA_fall17/notes/convex_optimization.pdf">Nice notes on Cvx Optimization</a><br><a href="https://www.cs.cornell.edu/courses/cs6820/2020fa/handouts/dscnt.pdf">Notes-CS 6820</a></td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe9.pdf">Scribe9</a>: Datta Sai VVN</td>
        <td>Extra Reading:<br>1. <a href="https://web.stanford.edu/~jduchi/projects/matrix_prop.pdf">Matrix Derivative</a><br>2. <a href="https://www3.nd.edu/~apilking/Math10560/Lectures/32.TaylorMcLaurinSeries.pdf">Taylor Series</a><br>3. <a href="https://web.stanford.edu/class/ee270/scribes/lecture15.pdf">Newton's Method</a></td>
      </tr>
      <tr>
        <td><strong>Feb 20</strong></td>
        <td>GD convergence analysis<br><em>SGD + Convergence guarantees</em><br><em>Batched SGD</em><br><em>Variants of GD</em></td>
        <td>CvxO 3.1-3.2<br><a href="https://people.eecs.berkeley.edu/~jiantao/227c2022spring/scribe/227C_Lecture_24.pdf">Notes on SGD</a><br><a href="https://www.ceremade.dauphine.fr/~waldspurger/tds/22_23_s1/advanced_gradient_descent.pdf">Notes on Heavy Ball & Nesterov's Accelerated GD</a></td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe10.pdf">Scribe10</a>: Aniket Wagde</td>
        <td>HW3 out [<a href="https://drive.google.com/file/d/1KaMYbQotXayxSM7St8hJlfIdmn-C8i2t/view?usp=sharing">link</a>]<br><a href="/class/m5vnz1h225x1c0/post/48">Announcements</a><br>Extra Reading:<br>1. <a href="https://arxiv.org/pdf/2301.11235">Comprehensive study of SGD & Batched-SGD</a><br>2. <a href="https://www.youtube.com/watch?v=5h8yx6zalXM">Nice demo</a></td>
      </tr>
      <tr>
        <td><strong>Feb 25</strong></td>
        <td>Max-Margin Formulation<br><em>SVM objective</em><br><em>KKT conditions</em></td>
        <td>PML 17.3.1-17.3.2<br><a href="https://home.work.caltech.edu/slides/slides14.pdf">Caltech CS156 Slides</a>-1<br><a href="https://www.stat.cmu.edu/~ryantibs/convexopt-F18/scribes/Lecture_12.pdf">KKT conditions (CMU-10-725)</a><br><a href="https://www.ccs.neu.edu/home/vip/teach/MLcourse/6_SVM_kernels/lecture_notes/svm/svm.pdf">Notes by Wang & Pavlu</a></td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe11.pdf">Scribe11</a>: Harsh Kothari</td>
        <td>Extra Reading:<br>1. <a href="https://www.cs.cmu.edu/~mgormley/courses/10601-s19/slides/lecture27-svm.pdf">Slides CMU 10-601</a></td>
      </tr>
      <tr>
        <td><strong>Feb 27</strong></td>
        <td>KKT conditions (contd)<br><em>Dual Optimization</em><br><em>SVM with strong duality</em></td>
        <td><a href="https://people.eecs.berkeley.edu/~elghaoui/Teaching/EE227A/lecture8.pdf">Strong Duality and Slater's Conditions</a><br><a href="https://home.work.caltech.edu/slides/slides15.pdf">Caltech CS156 Slides</a>-2</td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe12.pdf">Scribe12</a>: Boggavarapu, Lokesh</td>
        <td>Extra Reading:<br>1. <a href="https://optimization.cbe.cornell.edu/index.php?title=Quadratic_programming">Primer on QP</a><br>2. <a href="https://people.eecs.berkeley.edu/~elghaoui/Teaching/EE227A/lecture8.pdf">Strong Duality</a></td>
      </tr>
      <tr>
        <td><strong>Mar 1</strong><br><strong>[Extra Class-2]</strong></td>
        <td>Kernel SVM<br><em>Kernel Properties</em><br><em>Examples</em></td>
        <td>PML 17.3.4<br><a href="https://www.cs.cmu.edu/~aarti/Class/10701_Spring21/Lecs/svm_dual_kernel_inked.pdf">CMU-10701 slides</a></td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe13.pdf">Scribe13</a>: Madishetty, Aravind</td>
        <td>Extra Reading:<br>1. <a href="https://engineering.purdue.edu/ChanGroup/ECE595/files/Lecture21_SVM3.pdf">SVM-vs-Perceptron</a><br>2. <a href="https://www.youtube.com/watch?v=-Z4aojJ-pdg">Another amazing demo w/ Kernels!</a></td>
      </tr>
      <tr>
        <td><strong>Mar 4</strong></td>
        <td>Soft-Margin SVM<br><em>SVM Regression</em><br><em>Perceptron</em></td>
        <td>PML 17.3.3<br><a href="https://www.cs.mcgill.ca/~dprecup/courses/ML/Lectures/ml-lecture06.pdf">COMP-652 slides</a><br><a href="https://www.cs.cmu.edu/~avrim/ML10/lect0125.pdf">CMU-15-859</a></td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe14.pdf">Scribe14</a>: Lukau, Please</td>
        <td>HW3 due!</td>
      </tr>
      <tr>
        <td><strong>Mar 6</strong></td>
        <td>Perceptron Mistake bounds<br><em>Perceptron w/o perfect linear separator</em><br><em>Kernel Perceptron</em></td>
        <td>PML 10.2.5, 13.2<br><a href="https://www.cs.princeton.edu/courses/archive/spring16/cos495/slides/ML_basics_lecture3_Perceptron.pdf">Princeton CoS495</a><br><a href="https://www.cs.cmu.edu/~mgormley/courses/606-607-f18/slides607/lecture4-pmb.pdf">CMU 10-607</a></td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe15.pdf">Scribe15</a>: Rithish Reddy Chichili</td>
        <td>HW3 solutions: [<a href="https://drive.google.com/file/d/1Bha24ak9U6MWyBS3D7dvFO3elXSjLFL5/view">link</a>]</td>
      </tr>
      <tr>
        <td><strong>Mar 13</strong></td>
        <td><strong>Mid Term</strong></td>
        <td></td>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td><strong>Mar 15</strong><br><strong>[Extra Class-3]</strong></td>
        <td>Winnow's Algorithm<br><em>Mistake Bounds</em></td>
        <td>Winnow: <a href="https://santoshv.github.io/2023CS4540/Lec2_0828_0830.pdf">CS 4540</a><br>Mistake Bound: <a href="https://www.jennwv.com/courses/F11/lecture9.pdf">CS260</a><br><a href="https://www.youtube.com/watch?v=Rx9ZAHTU_N0">Winnow Example</a></td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe16.pdf">Scribe16</a>: Nemi Chakrawarthy Bhupathiraju / Simran Mishra</td>
        <td>Extra Reading:<br>1. Proving lower bounds <a href="https://home.ttic.edu/~tewari/lectures/lecture2.pdf">CMSC 35900</a> (Sec 2)<br>2. Advanced topics on Winnow & Perceptron: PLG Chap 12</td>
      </tr>
      <tr>
        <td><strong>Mar 18</strong></td>
        <td>Boosting<br><em>Adaboost</em><br><em>Mistake Bounds</em></td>
        <td>Boosting: <a href="https://haipeng-luo.net/courses/CSCI699/lecture8.pdf">CSCI699</a><br><a href="https://media.nips.cc/Conferences/2007/Tutorials/Slides/schapire-NIPS-07-tutorial.pdf">Slides</a>, Rob Schapire</td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe17.pdf">Scribe17</a>: Gabriel Zhang</td>
        <td>Extra Reading:<br>1. Original paper by <a href="http://rob.schapire.net/papers/FreundSc99.pdf">Freund & Schapire'99</a><br>2. Advanced topics: <a href="https://arxiv.org/pdf/1905.12787">Tutorial (Sec 9)</a><br>3. General winnow: <a href="https://www.cs.princeton.edu/courses/archive/spring14/cos511/scribe_notes/0408.pdf">Alg1</a>, <a href="https://home.ttic.edu/~tewari/lectures/lecture2.pdf">Alg2</a></td>
      </tr>
      <tr>
        <td><strong>Mar 20</strong></td>
        <td>Midterm solutions<br><em>PCA</em></td>
        <td></td>
        <td></td>
        <td>HW4 out: [<a href="https://drive.google.com/drive/folders/1MpYjlVDb0D0lRedh0IKpyy0fjQd_xbey?usp=drive_link">link</a>]
        <br>
        Project list out: [<a href="https://docs.google.com/document/d/1TTpS2-hkNzg_i1XrCg2LiaLrZArt_7Cq_MI5MeM55L8/edit?usp=sharing">link</a>]
       </td>
      </tr>
      <tr>
        <td><strong>Mar 25</strong></td>
        <td>Spring Break!</td>
        <td></td>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td><strong>Mar 27</strong></td>
        <td>Spring Break!</td>
        <td></td>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td><strong>April 1</strong></td>
        <td>Orthonormal Basis (OB)<br><em>PCA (Min-Error Formulation)</em></td>
        <td>OB: <a href="https://vf-tropi.com/linearalgebraanditsapplications.pdf">Gilbert Strang</a> [Chap 3.4]<br>PCA: PRML 12.1-12.2</td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe19.pdf">Scribe19</a>: Jiachen Tao / Aksun</td>
        <td>Extra Reading:<br>• <a href="https://sgfin.github.io/files/notes/NYU_Optimization_2017.pdf">Basics of LA</a><br>• <a href="https://www.maths.tcd.ie/~pete/ma1111/chapter3.pdf">Basics of Vector Space</a></td>
      </tr>
      <tr>
        <td><strong>April 3</strong></td>
        <td>PCA (Max-Var Formulation)<br><em>Eigen Values-Vectors (EV)</em><br><em>Clustering</em></td>
        <td><a href="https://www.math.purdue.edu/~liu1957/MA262_files/eigen.pdf">MA262 EV basics</a><br>PCA: PML 20.1<br>Clustering: <a href="https://www-users.cse.umn.edu/~jwcalder/Clustering.pdf">J. Cadler Slides</a><br><a href="https://www.cs.yale.edu/homes/el327/datamining2013aFiles/10_k_means_clustering.pdf">E Liberty lecture</a></td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe20.pdf">Scribe20</a>: Mishra, Simran</td>
        <td>Extra Reading:<br>• <a href="https://www.youtube.com/watch?v=PFDu9oVAE-g">Nice video tutorial on EV!</a><br>• K-Medoids: <a href="https://www2.cs.arizona.edu/~pachecoj/courses/csc380_fall21/lectures/kmeans.pdf">CSC 380 slides</a><br>• KPCA: <a href="https://zstevenwu.com/courses/s20/csci5525/resources/slides/lecture20.pdf">CSCI 5512 slides</a></td>
      </tr>
      <tr>
        <td><strong>April 10</strong></td>
        <td>K-Means<br><em>Spectral Clustering (SC)</em></td>
        <td>K-Means: <a href="https://www.cse.iitb.ac.in/~swaprava/courses/cs217/references/kmeans-convergence.pdf">CS217</a><br>PML 21</td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe21.pdf">Scribe21</a>: Wang, Haoxuan</td>
        <td>Extra Reading:<br>• <a href="https://people.csail.mit.edu/dsontag/courses/ml14/notes/Luxburg07_tutorial_spectral_clustering.pdf">More on Graph Laplacian</a></td>
      </tr>
      <tr>
        <td><strong>April 12</strong></td>
        <td>Spectral clustering (SC)<br><em>Neural Net Intro</em></td>
        <td>SC: <a href="https://www.cs.cmu.edu/~epxing/Class/10701-12f/Lecture/lecture21-SpecClus.pdf">ML10.701</a>, <a href="https://www.cse.msu.edu/~cse902/S14/ppt/kernelClustering.pdf">CSE902</a></td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe22.pdf">Scribe22</a>: Wang, Haoxuan</td>
        <td>Extra Reading:<br>• <a href="https://people.cs.umass.edu/~akshay/courses/cs690m/files/lec19.pdf">Advanced SC</a></td>
      </tr>
      <tr>
        <td><strong>April 15</strong></td>
        <td>Feed-Forward NN (FFNN)<br><em>Back-Propagation (BP)</em></td>
        <td>CS217: <a href="https://www.cse.iitb.ac.in/~swaprava/courses/cs217/scribes/CS217_2024_lec11.pdf">FFNN</a>, <a href="https://www.cse.iitb.ac.in/~swaprava/courses/cs217/scribes/CS217_2024_lec12.pdf">BP</a><br>COS 324: <a href="https://princeton-introml.github.io/files/ch11.pdf">FFNN & BP</a></td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe23.pdf">Scribe23</a>: Pipim, Charles / Rithish Reddy Chichili</td>
        <td>HW4 due!<br>
        HW5 out: [<a href="https://drive.google.com/drive/folders/1lKpb7ExcWE_1dFdB2Ohr3Z-2Btr2lB1X?usp=drive_link">link</a>]
        </td>
      </tr>
      <tr>
        <td><strong>April 17</strong></td>
        <td>Backpropagation (contd)<br><em>RNN</em><br><em>CNN (Intro)</em></td>
            <td>
                <a href="https://www.cse.iitb.ac.in/~swaprava/courses/cs217/scribes/CS217_2024_lec13.pdf">CS217-RNN</a><br>
                <a href="https://harvard-iacs.github.io/2019-CS109B/lectures/lecture10/presentation/cs109b_lecture10_RNN.pdf">RNN Slides</a><br>
                EECS-498: <a href="https://web.eecs.umich.edu/~justincj/slides/eecs498/498_FA2019_lecture12.pdf">RNN Slides</a>
            </td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe24.pdf">Scribe24</a>: Salvi, Yukta</td>
        <td>Extra Reading:<br>• <a href="https://www.youtube.com/playlist?list=PLeo1K3hjS3uu7CxAacxVndI4bE_o3BDtO">Detailed Applied YT course on DL</a></td>
      </tr>
      <tr>
        <td><strong>April 22</strong></td>
        <td>CNN<br><em>Dropout regularization</em><br><em>Vanishing & Exploding Gradients (VE-Grads)</em><br><em>RNN-LSTM</em></td>
        <td><a href="https://www.cse.iitb.ac.in/~swaprava/courses/cs217/scribes/CS217_2024_lec14.pdf">CS217-CNN</a><br>COS 324: <a href="https://princeton-introml.github.io/files/ch12.pdf">CNN</a><br>EECS-498: <a href="https://web.eecs.umich.edu/~justincj/slides/eecs498/498_FA2019_lecture07.pdf">CNN Slides</a><br><a href="https://www.cs.columbia.edu/~zemel/Class/Nndl/files/lec08.pdf">VE-Grads in RNN</a><br><a href="https://sebastianraschka.com/pdf/lecture-notes/stat453ss21/L15_intro-rnn__slides.pdf">LSTM slides</a></td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe25.pdf">Scribe25</a>: Agnihotri, Akshun</td>
        <td>Extra Reading:<br>• <a href="https://sebastianraschka.com/pdf/lecture-notes/stat453ss21/L10_regularization__slides.pdf">Regularization in NNs</a></td>
      </tr>
      <tr>
        <td><strong>April 24</strong></td>
        <td>Gaussian Processes (GP)</td>
        <td>GP: <a href="https://cs229.stanford.edu/section/cs229-gaussian_processes.pdf">CS229 notes</a><br>
<a href="https://nikolaimatni.github.io/courses/ese680-fall2019/scribe-notes/lecture24.pdf">ESE-680 notes</a></td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe26.pdf">Scribe26</a>: Bhat, Amith</td>
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F2f719a54fdbec94b5fb470a5345521762476a671b579a18f692ea1239e9455b1%2FOMD.pdf">OMD.pdf</a><br>
<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F0fc611eda0a9dbf8dd789a802aab8f41a3e5f997f4a4b12a8dac15445c373a78%2FOCO.pdf">OCO.pdf</a></td>
      </tr>
      <tr>
        <td><strong>April 26</strong><br>[<strong>Optional</strong> Extra class-1]</td>
        <td>Transformers for LMs</td>
        <td><a href="https://deeplearning.cs.cmu.edu/S24/document/slides/lec19.transformers.pdf">CMU 11-785 slides</a><br>
<a href="https://arxiv.org/pdf/1706.03762">Attention Paper (Google)</a></td>
        <td></td>
        <td>Lecture topic not included in the final exam!<br>
<a href="https://www.cs.cornell.edu/courses/cs4780/2024sp/slides/Transformers.pdf">CS4780 Slides</a></td>
      </tr>
      <tr>
        <td><strong>April 29</strong></td>
        <td>Online Learning Basics-1<br><em>- Halving (HA)<br>- Wtd-Majority (WMA)</em></td>
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F12d9a5a0db23d7dfc5f094a43b1ec479f1e5476c6b0b2ebf05eed1382a1b3708%2FHA.pdf">HA.pdf</a><br>
<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F240d2330907b4e21e71b1709bc09c6e0746df9a6f2afb5141b41efe94dbb518a%2FWMA.pdf">WMA.pdf</a></td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe28.pdf">Scribe28</a>: Kothari, Harsh</td>
        <td></td>
      </tr>
      <tr>
        <td><strong>May 1</strong></td>
        <td>Online Learning Basics-2<br><em>- EXP-Wt<br>- OMD (OCO)</em></td>
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F5da6699dd76e46cf8f487d8b9d3a3a2d3b340c8b9eecc0c26e42a5dab19fe476%2FExp-Wt.pdf">Exp-Wt.pdf</a></td>
        <td><a href="https://aadirupa.github.io//course/iml_repo/scribe29.pdf">Scribe29</a>: Datta, Sai VVN</td>
        <td>[Topic not included in the final exam]<br><br>
Extra Reading:<br>
<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F2f719a54fdbec94b5fb470a5345521762476a671b579a18f692ea1239e9455b1%2FOMD.pdf">OMD.pdf</a><br>
<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F0fc611eda0a9dbf8dd789a802aab8f41a3e5f997f4a4b12a8dac15445c373a78%2FOCO.pdf">OCO.pdf</a></td>
      </tr>
      <tr>
        <td><strong>May 3</strong></td>
        <td></td>
        <td></td>
        <td></td>
        <td>HW5 due!</td>
      </tr>
      <tr>
        <td><strong>May 6</strong></td>
        <td><strong>Final Exam</strong></td>
        <td></td>
        <td></td>
        <td>Time: 1-2:30 pm CT<br>Room: LC F6</td>
      </tr>
      <tr>
        <td><strong>May 9</strong></td>
        <td><strong>Project Presentations</strong></td>
        <td></td>
        <td></td>
        <td>Final project report due!<br>Time: 3-5:30 pm CT</td>
      </tr>
    </table>
  </div>

  <div id="Description" class="tabcontent">
    <h2>📚 Course Description</h2>
    <p style="text-align: justify;">This is a <strong>comprehensive, math-intensive</strong> machine learning course that bridges theoretical foundations with practical applications. The course covers core supervised learning algorithms including linear/logistic regression, support vector machines, neural networks, and ensemble methods like boosting. Students will dive deep into optimization techniques (gradient descent, Newton's method), convex analysis, kernel methods, dimensionality reduction (PCA), clustering, and modern topics like deep learning architectures (CNNs, RNNs, LSTMs) and online learning algorithms.</p>
    
    <p style="text-align: justify;">The course emphasizes <strong>rigorous mathematical understanding</strong> alongside <strong>hands-on implementation</strong>. Students will engage through programming assignments in Python/MATLAB, scribe detailed lecture notes using LaTeX, and work on a significant course project. Topics progress from fundamental concepts like loss functions and regularization to advanced methods including spectral clustering, Gaussian processes, and transformer architectures. The curriculum balances theoretical analysis (convergence proofs, mistake bounds, duality theory) with practical machine learning skills.</p>
    
    <p style="text-align: justify;"><strong>Upon completion</strong>, students will have a solid theoretical foundation in machine learning mathematics, practical experience implementing algorithms from scratch, and the ability to analyze and apply ML methods to real-world problems. Success requires strong backgrounds in probability, statistics, and linear algebra, along with programming proficiency. This course prepares students for advanced ML research, industry roles requiring deep technical understanding, or pursuing graduate studies in machine learning and AI.</p>
    
    
  </div>

  <div id="Prerequisites" class="tabcontent">
    <h2>⚠️ Prerequisites</h2>
    <p><strong>This course is going to be MATH-HEAVY.</strong> Please familiarize yourself with the basics of Probability-Statistics (PS) and Linear-Algebra (LA). Recommended introductory lectures to check if you are comfortable with the basics:</p>
    
    <ul>
        <li><strong>PS review:</strong>
            <ol>
                <li><a href="https://cs229.stanford.edu/section/cs229-prob.pdf">https://cs229.stanford.edu/section/cs229-prob.pdf</a></li>
                <li><a href="https://www2.isye.gatech.edu/~sman/courses/6761/6761-1-ProbReview.pdf">https://www2.isye.gatech.edu/~sman/courses/6761/6761-1-ProbReview.pdf</a></li>
                <li><a href="https://users.ssc.wisc.edu/~ctaber/410/statrev.pdf">https://users.ssc.wisc.edu/~ctaber/410/statrev.pdf</a></li>
            </ol>
        </li>
        <li><strong>LA review:</strong>
            <ol>
                <li><a href="https://cs229.stanford.edu/section/cs229-linalg.pdf">https://cs229.stanford.edu/section/cs229-linalg.pdf</a></li>
                <li><a href="https://james-chuang.github.io/notes/linalg_review.pdf">https://james-chuang.github.io/notes/linalg_review.pdf</a></li>
                <li><a href="https://www.cs.cmu.edu/~jingx/docs/linearalgebra.pdf">https://www.cs.cmu.edu/~jingx/docs/linearalgebra.pdf</a></li>
            </ol>
        </li>
    </ul>
    
    <p><strong>Familiarity with LaTeX for scientific writing</strong> (for scribing the lecture notes and writing assignments). You can learn the basics from here: <a href="https://www.youtube.com/watch?v=lgiCpA4zzGU">https://www.youtube.com/watch?v=lgiCpA4zzGU</a> (many online tutorials available for beginners.)</p>
    
    <p><strong>Programming assignments</strong> (in Python or Matlab). Be prepared to code: <a href="https://www.youtube.com/playlist?list=PLzMcBGfZo4-mP7qA9cagf68V06sko5otr">[A Simple Quickstart Guide]</a>, <a href="https://colab.research.google.com/github/cs231n/cs231n.github.io/blob/master/python-colab.ipynb#scrollTo=dzNng6vCL9eP">[Google Colab]</a> (many online tutorials available for beginners).</p>
    
    <p>Familiarity with the above basics is highly recommended for those taking the course for credit — Lack of understanding may impact your grades.</p>
 
  </div>

  <div id="Resources" class="tabcontent">
    <h2>📖 Resources</h2>
    <p>Class lecture will be based on, but not limited to, the following books:</p>
    
    <ul>
        <li><strong>[ESL]</strong> The Elements of Statistical Learning by Hastie, Tibshirani, and Friedman [<a href="https://web.stanford.edu/~hastie/ElemStatLearn/">Book website</a>]</li>
        
        <li><strong>[MLTM]</strong> Machine Learning by Tom Mitchell [<a href="https://www.cs.cmu.edu/~tom/mlbook.html">Online copy</a>]</li>
        
        <li><strong>[PML]</strong> Probabilistic Machine Learning: An Introduction, by Kevin Murphy [<a href="https://probml.github.io/pml-book/book1.html">Book website</a>]</li>
        
        <li><strong>[PLG]</strong> Prediction, Learning and Games by Nicolo Cesa-Bianchi and Gabor Lugosi, Cambridge University Press, 2006 [<a href="https://ece.iisc.ac.in/~aditya/Prediction_Learning_and_Games.pdf">Local Copy from E1 245</a> by Aditya Gopalan]</li>
        
        <li><strong>[PRML]</strong> Pattern Recognition and Machine Learning by Christopher Bishop (optional) [<a href="https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf">Free copy</a>]</li>
        
        <li><strong>[PyAG]</strong> <em>(Optional):</em> Hands-On Machine Learning with Scikit-Learn &amp; Tensorflow by Aurelien Geron [<a href="https://www.clc.hcmus.edu.vn/wp-content/uploads/2017/11/Hands_On_Machine_Learning_with_Scikit_Learn_and_TensorFlow.pdf">Online</a>, <a href="https://github.com/ageron/handson-ml">Github</a>]</li>
        
        <li><strong>[CIML]</strong> <em>(Optional):</em> A Course in Machine Learning by Hal Daume III [<a href="http://ciml.info/">Online copy</a>], [<a href="https://github.com/hal3/ciml/issues">Errata</a>]</li>
        
        <li><strong>[UML]</strong> (Optional): Understanding Machine Learning: From Theory to Algorithms by Shai Ben-David, Shai Shalev-Shwartz [<a href="https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/index.html">Online copy</a>]</li>
        
        <li><strong>[OCO]</strong> (Optional) Introduction to Online Convex Optimization by Elad Hazan [<a href="https://sites.google.com/view/intro-oco/">Book website</a>]</li>
        
        <li><strong>[CvxO]</strong> Convex Optimization: Algorithms and Complexity by Sebastien Bubeck [<a href="https://arxiv.org/abs/1405.4980">Book Website</a>]</li>
    </ul>
  </div>

  <div id="Logistics" class="tabcontent">
    <h2>🎯 Course Logistics</h2>
    <ul>
      <li><strong>📍 Location:</strong> Lecture Complex F6</li>
      <li><strong>⏰ Schedule:</strong> Tuesday & Thursday, 2:00 PM - 3:15 PM</li>
      <li><strong>🏛️ Office Hours:</strong> Thurdays 5:00–6:00 PM or by appointment</li>
      <li><strong>📧 Contact:</strong> Email or Piazza </li>
    </ul>
  </div>

  <script>
    document.getElementsByClassName('tablinks')[0].click(); // Open first tab by default
  </script>
</body>
</html>
