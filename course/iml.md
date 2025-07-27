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
    }
    body {
      font-family: sans-serif;
      margin: 0;
      padding: 0;
      background: #fff;
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
  <p>Instructor: Aadirupa Saha</p>

  <div class="tab">
    <button class="tablinks" onclick="openTab(event, 'Schedule')">Schedule</button>
    <button class="tablinks" onclick="openTab(event, 'Description')">Description</button>
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
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F43e40d119046fe4dd1970ddbd56585281098e18111604334417617958e222171%2FCS412-Intro.pdf">📊 CS412-Intro.pdf</a></td>
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fd08138670a36d8bb680654314bd90e2efec733d31cf47f41f911afee8765539a%2FHW1.pdf">HW1.pdf</a> (Self-Assessment)<br>[Submit on Gradescope]<br>Due: Jan 28</td>
      </tr>
      <tr>
        <td><strong>Jan 23</strong></td>
        <td>Understanding loss functions</td>
        <td>PML 4.3</td>
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F7f642eda43149cc1f76f269d38eb5c8a294a6cdc5b83b139530e0d171605b4da%2FLec1.pdf">Lec1.pdf</a>* (handwritten)<br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F778417adb6c63deb8a9e60d33af5d2b135da35ef1e37cf653db17f3ddd487138%2Fscribe1.pdf">scribe1.pdf</a>, <a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Ffaba61798e8e1a5031c216859bc79fc91a63ae116ad04f1e4e005084c6cec9d9%2Fscribe1.tex">scribe1.tex</a>]<br><a href="#">Scribe1</a>: Edomwonyi, Uwadia</td>
        <td></td>
      </tr>
      <tr>
        <td><strong>Jan 28</strong></td>
        <td>Hypothesis (Func) Class<br><em>ERM</em><br><em>Linear Regression</em></td>
        <td>PML 11.1, 11.2,11.3<br>ESL 3.2</td>
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F9ee16667690d2fff9fcd71eddad5dbb87cf86d755c30bc55a3ec69a4e442e72c%2FLec2.pdf">Lec2.pdf</a>* (handwritten)<br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fa726cdd7fc2f00ece82c6ec7afc54676e28b4756fccd468148f5ab19f9aab81f%2Fscribe2.pdf">scribe2.pdf</a>, <a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F035a242cb2638eac2064e46e6c54308cfda3518a79c47cce16cdc02d6cc00a34%2Fscribe2.tex">scribe2.tex</a>]<br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F242ba6860a1bb85fbea1a976dc80b83814e3d4fccebac49a7e2a9c87b2f9c16f%2Fplots2.zip">plots2.zip</a>]<br><a href="#">Scribe2</a>: Shelke, Harsh</td>
        <td>HW1 due today!</td>
      </tr>
      <tr>
        <td><strong>Jan 30</strong></td>
        <td>Overfitting & Regularizers<br><em>Lin-Reg: Linear Regression (contd)</em></td>
        <td>PML 4.3, 5.4</td>
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F3b3ce85ce8ff6b79aced9f8c6d1c304e9feefdd231d5c389aa0356a038cc6fd6%2FLec3.pdf">Lec3.pdf</a> (handwritten)<br><a href="https://drive.google.com/drive/folders/16mJ7GrYO73bJNlViyDSTFhR29vi5Z30F?usp=sharing">Lin-Reg demo</a><br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Ffc25d9c9152140df8da9cb759aad8053e0339a02f947697f4597972fa66599bc%2Fscribe3.pdf">scribe3.pdf</a>, <a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fd00656674cfffb4709a153fffccad70d9f17cd0066c4ecff2e364b17826f7950%2Fscribe3.tex">scribe3.tex</a>]<br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F65e6d014c07d360eac1f478a724273d71a320552ac3a0b90c69eb4fd25971cd7%2Fdegree_1.png">degree_1.png</a>, <a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Ffbaa7d8c6bfaa3c64d9fb3500a37eed15d3f5bf6c8d1ceb17ed70124ea68df4e%2Fdegree_15.png">degree_15.png</a>]<br><a href="#">Scribe3</a>: Hulu, Charis/ Lokesh</td>
        <td></td>
      </tr>
      <tr>
        <td><strong>Feb 4</strong></td>
        <td>Logistic Regression<br><em>Multiclass Logistic Regression (MLR)</em></td>
        <td>PML 10.2.1, 10.2.2<br>ESL 4.4.1</td>
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fe2e7e9ec05227a1618d58d1d905bd6fdcea3fa60d2eccbc44881e09e4e1e0b20%2FLec4.pdf">Lec4.pdf</a> (handwritten)<br><a href="https://drive.google.com/file/d/149BQjM7pqTwO5gMfJBjoyb_ys8tGx6WU/view?usp=sharing">MLR demo</a><br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fded0d2f602b2610f203ca90892edf29c702f61173797085dd37168986e61bec6%2Fscribe4.pdf">scribe4.pdf</a>, <a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F1fcdabac1a607c5e295d3991b8a0481b54e90f9e6fe857b710d4f935aabb0562%2Fscribe4.tex">scribe4.tex</a>]<br><a href="#">Scribe4</a>: Dahagam, Sujay</td>
        <td>HW2 out [<a href="https://drive.google.com/drive/folders/11Ih8rD8iESXepnDFFAluxTk3xqJXA3vP?usp=drive_link">link</a>]<br>(UIC credentials rqd.)<br>Finalize scribe assignment</td>
      </tr>
      <tr>
        <td><strong>Feb 6</strong></td>
        <td>Multiclass logistic (contd)<br><em>MLE (Bernoulli)</em><br><em>MAP (Bernoulli)</em></td>
        <td>PML 4.2, 4.5<br><a href="https://www.cs.cmu.edu/~aarti/Class/10701_Spring14/slides/MLE_MAP_Part1.pdf">Slides CMU 10701</a><br><a href="https://www.cs.cmu.edu/afs/cs.cmu.edu/user/mitchell/ftp/mlbook.html#:~:text=Estimating%20Probabilities%3A%20MLE%20and%20MAP">Tom Mitchell's note</a></td>
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fa0e899015f38e4d46e2000d1ec4f640be55abe36aee9611ea86f19adab8f700c%2FLec5.pdf">Lec5.pdf</a> (handwritten)<br><a href="https://colab.research.google.com/drive/1f5bPVRwAN9-iGLLKpauS3hGX8CxDyYkc?usp=sharing">Beta demo</a><br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fb2d274002402b70719ef982b5b9d8039c2ac053fe59c2ce013298e294027a59b%2Fscribe5.pdf">scribe5.pdf</a>, <a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fc3678d63bbfec3122d8b5448b621c10b2f1db8e6f2ff4f37bc48c499c75c2785%2Fscribe5.tex">scribe5.tex</a>]<br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F1f50f849f7a772498afce7bad1b6c089af342b7f94e9393467d235aa503b8187%2Fplots5.zip">plots5.zip</a>]<br><a href="#">Scribe5</a>: Bhat, Amith</td>
        <td>Bonus-Quiz [<a href="https://drive.google.com/file/d/1gWiUMzz8lrlBcbCRbx7uLitmw05BvfxL/view?usp=sharing">qz-feb6.pdf</a>]<br>(submit to gradescope)<br><a href="https://docs.google.com/forms/d/e/1FAIpQLSdYYJh6z8eeiWFltCnQmHSYx1jF1AAjJ9Aqhoct-TNkfZFsxQ/viewform?usp=dialog">Feedback form</a><br><a href="/class/m5vnz1h225x1c0/post/32">Announcements</a></td>
      </tr>
      <tr>
        <td><strong>Feb 8</strong><br><strong>[Extra Class-1]</strong></td>
        <td>MLE for Regression<br><em>MAP = Regularization</em></td>
        <td>PML 4.2.5 - 4.2.7, 4.5<br><a href="https://www.cs.cmu.edu/~10315/notes/10315_S23_Notes_MLE_draft2.pdf">CMU 10-315 notes</a><br><a href="https://bjlkeng.io/posts/probabilistic-interpretation-of-regularization/">Nice blog</a></td>
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fa7d8175676e0e4bba38684155407d36bda769bb0eb7ccf15b8cbd1393afe5d73%2FLec6.pdf">Lec6.pdf</a> (handwritten)<br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fb5055b358ca28c32dc7f3d25c3399f3f8c0f137284ca1965f4b59826158b666d%2Fscribe6.pdf">scribe6.pdf</a>, <a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F290b9eb1ad00da83bd2a57bda54499079227934efaf4ce9c20cac4949ede8056%2Fscribe6.tex">scribe6.tex</a>]<br><a href="#">Scribe6</a>: Sappidi, Yugesh</td>
        <td>Optional Reading:<br>Conjugate Priors<br>• <a href="https://www.statlect.com/fundamentals-of-statistics/conjugate-prior">Nice blog</a><br>• <a href="https://www2.stat.duke.edu/courses/Fall11/sta114/conjug.pdf">Duke STA114</a></td>
      </tr>
      <tr>
        <td><strong>Feb 11</strong></td>
        <td>Regularized logistic regression thru' MAP<br><em>Convex functions</em></td>
        <td>PML 10.1-10.3<br>CvxO 1.1-1.3<br><a href="https://mitliagkas.github.io/ift6085-2019/ift-6085-lecture-2-notes.pdf">Notes-IFT 6085</a></td>
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F1323a246fca0dba7d3235203e5086990a1926f20e5bd6dd57077b5a17a128498%2FLec7.pdf">Lec7.pdf</a> (handwritten)<br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F0f125a1e0ac9f0a7acf3e789657a1ee3bbe216cc1fed268176cade318c534b48%2Fscribe7.pdf">scribe7.pdf</a>, <a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F1e5a7d038139b162ff5bfca31f44b5d9d866438af25fa74d1cf3eb0aa1a5a3d6%2Fscribe7.tex">scribe7.tex</a>]<br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F1adf4ca20075872251a40e2c85b0c228376350086c0d3e3350dba3a4c6650ce0%2Fplots.zip">plots7.zip</a>]<br><a href="#">Scribe7</a>: Ferdowsi, Farhad</td>
        <td>HW2 due!</td>
      </tr>
      <tr>
        <td><strong>Feb 13</strong></td>
        <td>Properties of Cvx funcs<br><em>Gradient descent (GD)</em><br><em>Convergence rates</em></td>
        <td>CvxO 1.1-1.3, 3.1<br><a href="https://www.princeton.edu/~aaa/Public/Teaching/ORF523/S16/ORF523_S16_Lec7_gh.pdf">Notes by A. Ahmadi</a><br><a href="https://chunpai.github.io/assets/note/1__Gradient_Descent_and_Line_Search.pdf">Notes by C Wang</a></td>
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F855534e5eacb55b0d339b8bdbf5c0acacab82162067be3b07bdce2fd3df33d14%2FLec8.pdf">Lec8.pdf</a> (handwritten)<br><a href="https://colab.research.google.com/drive/1zZzsGg6LhyTs-TNfBXeIXrWxZiFISYYk?usp=sharing">GD demo</a><br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fb8d40c877e4c76d2fd9a14e7b3c59a69e666d0764da5460438c024b180fa2f31%2Fscribe8.pdf">scribe8.pdf</a>, <a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fa2159e8a39ba7814c7ac0fb4845dc9232d29738ca7836cd25d574d7f95e792f9%2Fscribe8.tex">scribe8.tex</a>]<br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Ffb2acd667f66c9fea9e6d47f1fcaea2f6d5e210c062a84cbb975e4ab219a1a2c%2FPicture1.jpg">plot.jpg</a>]<br><a href="#">Scribe8</a>: Ferdowsi, Farhad</td>
        <td>Extra Reading<br>1. <a href="https://www.cis.upenn.edu/~cis5150/cis515-11-sl4.pdf">Matrix Norms</a></td>
      </tr>
      <tr>
        <td><strong>Feb 18</strong></td>
        <td>Convergence of GD<br><em>Newton's method</em></td>
        <td>CvxO 3.1, 3.2, 3.4, 5.3.2<br><a href="https://cims.nyu.edu/~cfgranda/pages/OBDA_fall17/notes/convex_optimization.pdf">Nice notes on Cvx Optimization</a><br><a href="https://www.cs.cornell.edu/courses/cs6820/2020fa/handouts/dscnt.pdf">Notes-CS 6820</a></td>
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fbcdf893a7729f48a597f7f7ef7232f1c424afdf28ea6d519a95b493bcf3e77e2%2FLec9.pdf">Lec9.pdf</a> (handwritten)<br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F96a4a3bdc6003381280f03358d5f8fa79ce4b1c71ea13d6a2a59b15ce5229b1b%2Fscribe9.pdf">scribe9.pdf</a>, <a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Ff2f86248a5a61caf5c2183b8e9ccd521791e06c30158e45c4a6fb206af15d514%2Fscribe9.tex">scribe9.tex</a>]<br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F28bf63faa68c90d176fa6eee40e28a4db8c0d0c8cc981dc812b1aca73fe38c7b%2Fplots9.zip">plots9.zip</a>]<br><a href="#">Scribe9</a>: Datta Sai VVN</td>
        <td>Extra Reading:<br>1. <a href="https://web.stanford.edu/~jduchi/projects/matrix_prop.pdf">Matrix Derivative</a><br>2. <a href="https://www3.nd.edu/~apilking/Math10560/Lectures/32.TaylorMcLaurinSeries.pdf">Taylor Series</a><br>3. <a href="https://web.stanford.edu/class/ee270/scribes/lecture15.pdf">Newton's Method</a></td>
      </tr>
      <tr>
        <td><strong>Feb 20</strong></td>
        <td>GD convergence analysis<br><em>SGD + Convergence guarantees</em><br><em>Batched SGD</em><br><em>Variants of GD</em></td>
        <td>CvxO 3.1-3.2<br><a href="https://people.eecs.berkeley.edu/~jiantao/227c2022spring/scribe/227C_Lecture_24.pdf">Notes on SGD</a><br><a href="https://www.ceremade.dauphine.fr/~waldspurger/tds/22_23_s1/advanced_gradient_descent.pdf">Notes on Heavy Ball & Nesterov's Accelerated GD</a></td>
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F82a05480964241bae541557ff4538f260976ede64ad32e815ba207d961af43fe%2FLec10.pdf">Lec10.pdf</a> (handwritten)<br><a href="https://colab.research.google.com/drive/11EVJ4EzelZ8Kd4yiO-Uhaw4OO1lRkP2H?usp=sharing">SGD demo</a><br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F96d9d2bc1e2ea2226031de2bb8e470d718fd496d98ce2401d8b970a89eb5af26%2Fscribe10.pdf">scribe10.pdf</a>, <a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F73367ebd3f4b65cb006ad65512b4684fe07671dd2f187cd2f5eb0bd465cc3aa3%2Fscribe10.tex">scribe10.tex</a>]<br><a href="#">Scribe10</a>: Aniket Wagde</td>
        <td>HW3 out [<a href="https://drive.google.com/file/d/1KaMYbQotXayxSM7St8hJlfIdmn-C8i2t/view?usp=sharing">link</a>]<br><a href="/class/m5vnz1h225x1c0/post/48">Announcements</a><br>Extra Reading:<br>1. <a href="https://arxiv.org/pdf/2301.11235">Comprehensive study of SGD & Batched-SGD</a><br>2. <a href="https://www.youtube.com/watch?v=5h8yx6zalXM">Nice demo</a></td>
      </tr>
      <tr>
        <td><strong>Feb 25</strong></td>
        <td>Max-Margin Formulation<br><em>SVM objective</em><br><em>KKT conditions</em></td>
        <td>PML 17.3.1-17.3.2<br><a href="https://home.work.caltech.edu/slides/slides14.pdf">Caltech CS156 Slides</a>-1<br><a href="https://www.stat.cmu.edu/~ryantibs/convexopt-F18/scribes/Lecture_12.pdf">KKT conditions (CMU-10-725)</a><br><a href="https://www.ccs.neu.edu/home/vip/teach/MLcourse/6_SVM_kernels/lecture_notes/svm/svm.pdf">Notes by Wang & Pavlu</a></td>
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F7dd95ff254dcab5674906b7d7584369a763537e10eed397bcbae2d9fd4a91ae5%2FLec11.pdf">Lec11.pdf</a> (handwritten)<br><a href="https://www.youtube.com/watch?v=_YPScrckx28">Nice visual demo!</a><br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F28904c44351bca29dbe41639df66cf6f2dd9edbe3e74f82d7e0c4944ea6ac453%2Fscribe11.pdf">scribe11.pdf</a>, <a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F5d29af0c782af1717cdb623a02f4761728b265496a8abba9ebc3b09d2cc7752e%2Fscribe11.tex">scribe11.tex</a>]<br><a href="#">Scribe11</a>: Harsh Kothari</td>
        <td>Extra Reading:<br>1. <a href="https://www.cs.cmu.edu/~mgormley/courses/10601-s19/slides/lecture27-svm.pdf">Slides CMU 10-601</a></td>
      </tr>
      <tr>
        <td><strong>Feb 27</strong></td>
        <td>KKT conditions (contd)<br><em>Dual Optimization</em><br><em>SVM with strong duality</em></td>
        <td><a href="https://people.eecs.berkeley.edu/~elghaoui/Teaching/EE227A/lecture8.pdf">Strong Duality and Slater's Conditions</a><br><a href="https://home.work.caltech.edu/slides/slides15.pdf">Caltech CS156 Slides</a>-2</td>
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fc534db2a015104d19886f288d8ca31d03747278dcb2725e2b5896c01aec08dd6%2FLec12.pdf">Lec12.pdf</a>* (handwritten)<br><a href="https://www.youtube.com/watch?v=Q7vT0--5VII">Nice visualization!</a><br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fe2425bf2b3d39b46bf77c5e12310c9ea7ed5a040a4fea71c0da24f0ff7bca611%2Fscribe12.pdf">scribe12.pdf</a>, <a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F3271395bffc2df1cc6177552229dd548810d920185c7fe0980b6c0d56e703de1%2Fscribe12.tex">scribe12.tex</a>]<br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fdd454cf36d40f5bc910329eafd7beb6471d88aa2522ad43423d4e0fd9bd999d6%2Fplots12.zip">plots12.zip</a>]<br><a href="#">Scribe12</a>: Boggavarapu, Lokesh</td>
        <td>Extra Reading:<br>1. <a href="https://optimization.cbe.cornell.edu/index.php?title=Quadratic_programming">Primer on QP</a><br>2. <a href="https://people.eecs.berkeley.edu/~elghaoui/Teaching/EE227A/lecture8.pdf">Strong Duality</a></td>
      </tr>
      <tr>
        <td><strong>Mar 1</strong><br><strong>[Extra Class-2]</strong></td>
        <td>Kernel SVM<br><em>Kernel Properties</em><br><em>Examples</em></td>
        <td>PML 17.3.4<br><a href="https://www.cs.cmu.edu/~aarti/Class/10701_Spring21/Lecs/svm_dual_kernel_inked.pdf">CMU-10701 slides</a></td>
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fee04f70f200622c3f50e7c54bd29be4f0723973776d9d0e605d3202106bce454%2FLec13.pdf">Lec13.pdf</a> (handwritten)<br><a href="https://www.youtube.com/watch?v=3liCbRZPrZA">Kernel tricks demo</a><br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F9fb9e640a58ce97fd946af5e034617144890b506afd9b1d6085129805c163e7b%2Fscribe13.pdf">scribe13.pdf</a>, <a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fbcaee6ea29f38bf8cfc834ffb034b5d5d39504a69af05a085236c4f694ccd29b%2Fscribe13.tex">scribe13.tex</a>]<br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F6ebf7c3409788dc6bd4d1d052f6e448f156c26fd9b96c77036a933c75c998af3%2Fplots13.zip">plots13.zip</a>]<br><a href="#">Scribe13</a>: Madishetty, Aravind</td>
        <td>Extra Reading:<br>1. <a href="https://engineering.purdue.edu/ChanGroup/ECE595/files/Lecture21_SVM3.pdf">SVM-vs-Perceptron</a><br>2. <a href="https://www.youtube.com/watch?v=-Z4aojJ-pdg">Another amazing demo w/ Kernels!</a></td>
      </tr>
      <tr>
        <td><strong>Mar 4</strong></td>
        <td>Soft-Margin SVM<br><em>SVM Regression</em><br><em>Perceptron</em></td>
        <td>PML 17.3.3<br><a href="https://www.cs.mcgill.ca/~dprecup/courses/ML/Lectures/ml-lecture06.pdf">COMP-652 slides</a><br><a href="https://www.cs.cmu.edu/~avrim/ML10/lect0125.pdf">CMU-15-859</a></td>
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F3a613054d357552fe8227d7b23e1b3059b8d9d08e4f41cebaf31cc32909d6854%2FLec14.pdf">Lec14.pdf</a> (handwritten)<br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fac8ac84bfd07b51928e1f6b808a7c384db605aad648c87ae4cf34cd663d92917%2Fscribe14.pdf">scribe14.pdf</a>, <a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fa459e50eb1ab1996d4159f35acd69fd7beb1c91c9d596a60ce46e4ed18ac74cc%2Fscribe14.tex">scribe14.tex</a>]<br><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Febc649abfa27c9cc3cda05a0345501da4b5598e5d4e1e29c8c34d87feaad57c3%2Fplots14.zip">plots14.zip</a><br><a href="#">Scribe14</a>: Lukau, Please</td>
        <td>HW3 due!</td>
        <td></td>
      </tr>
      <tr>
        <td><strong>Mar 6</strong></td>
        <td>Perceptron Mistake bounds<br><em>Perceptron w/o perfect linear separator</em><br><em>Kernel Perceptron</em></td>
        <td>PML 10.2.5, 13.2<br><a href="https://www.cs.princeton.edu/courses/archive/spring16/cos495/slides/ML_basics_lecture3_Perceptron.pdf">Princeton CoS495</a><br><a href="https://www.cs.cmu.edu/~mgormley/courses/606-607-f18/slides607/lecture4-pmb.pdf">CMU 10-607</a></td>
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F40cd22feb2a69e7736cc5aec478f88b9056b3b0ec30a3302b73e1d8c59953aa2%2FLec15.pdf">Lec15.pdf</a> (handwritten)<br><a href="https://www.youtube.com/watch?v=xjKMD7T6ods">Youtube demo</a><br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Ffcf40a2d03409d46a92e029e7b0c573cde82e19d67c4536cc1807383af0c09dc%2Fscribe15.pdf">scribe15.pdf</a>, <a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F82eb8f30a5810fd7f2c63a94d0c8a841ed0ea73b98fc6f2c27741bd612cdb9ed%2Fscribe15.tex">scribe15.tex</a>]<br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fafa521f48467dd4af67633c6fec7f5deda62444f470319df9b8383eef403bd1a%2Fplots15.zip">plots15.zip</a>]<br><a href="#">Scribe15</a>: Rithish Reddy Chichili</td>
        <td>HW3 solutions posted: [<a href="https://drive.google.com/file/d/1Bha24ak9U6MWyBS3D7dvFO3elXSjLFL5/view?usp=drive_link">link</a>]</td>
        <td></td>
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
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fe22e9ce37aa565837a1c1e865c6ecf40c558938a1ea448847243854a1c694678%2FLec16.pdf">Lec16.pdf</a> (handwritten)<br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F1e2593a3281c87b3a53a352911817af03bc38c79fcf7fef403bb95708b6378a2%2Fscribe16.pdf">scribe16.pdf</a>, <a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F4f1ab0358b47f4152e751c6d956f0f369c777f9deff97b913ba97abd599f5561%2Fscribe16.tex">scribe16.tex</a>]<br><a href="#">Scribe16</a>: Nemi Chakrawarthy Bhupathiraju / Simran</td>
        <td>Extra Reading:<br>1. Proving lower bounds <a href="https://home.ttic.edu/~tewari/lectures/lecture2.pdf">CMSC 35900</a> (Sec 2)<br>2. Advanced topics on Winnow & Perceptron: PLG Chap 12</td>
      </tr>
      <tr>
        <td><strong>Mar 18</strong></td>
        <td>Boosting<br><em>Adaboost</em><br><em>Mistake Bounds</em></td>
        <td>Boosting: <a href="https://haipeng-luo.net/courses/CSCI699/lecture8.pdf">CSCI699</a><br><a href="https://media.nips.cc/Conferences/2007/Tutorials/Slides/schapire-NIPS-07-tutorial.pdf">Slides</a>, Rob Schapire</td>
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fedbb500b249aa7d231739374052d6f50291a3589dcb7ae2f023fa7dd8c71fc41%2FLec17.pdf">Lec17.pdf</a> (handwritten)<br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F8e84dad9d671dd0226dbbff0406a435dde896a3e7b4646133f5b2b2ce8f05ec6%2Fscribe17.pdf">scribe17.pdf</a>, <a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F3286f54630bac889d558e2a724b7e6ce25ada768572c768aa8191ffb7f09b310%2Fscribe17.tex">scribe17.tex</a>]<br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F0dc46305afe1916dfd7ab4964b8e8131a3e21de224916a1762218ed447cea456%2Fplots17.zip">plots17.zip</a>]<br><a href="#">Scribe17</a>: Gabriel Zhang</td>
        <td>Extra Reading:<br>1. Original paper by <a href="http://rob.schapire.net/papers/FreundSc99.pdf">Freund & Schapire'99</a><br>2. Advanced topics: <a href="https://arxiv.org/pdf/1905.12787">Tutorial (Sec 9)</a><br>3. General winnow: <a href="https://www.cs.princeton.edu/courses/archive/spring14/cos511/scribe_notes/0408.pdf">Alg1</a>, <a href="https://home.ttic.edu/~tewari/lectures/lecture2.pdf">Alg2</a></td>
      </tr>
      <tr>
        <td><strong>Mar 20</strong></td>
        <td>Midterm solutions<br><em>PCA</em></td>
        <td></td>
        <td><a href="#">Scribe18</a>: Jiachen Tao</td>
        <td></td>
      </tr>
      <tr>
        <td><strong>Mar 25</strong></td>
        <td>Spring Break!</td>
        <td></td>
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
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fc8bb71a9d69d2d8b66f9372a13764c789873697b3a9edf2204c25a003bc70a01%2FLec19.pdf">Lec19.pdf</a> (handwritten)<br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F8d13a9ed8fdfce24ad4863636cd118cba43a01538540e68a0d8019fa0b403645%2FScribe19.pdf">Scribe19.pdf</a>]<br><a href="#">Scribe19</a>: Jiachen Tao / Aksun</td>
        <td>Extra Reading:<br>• <a href="https://sgfin.github.io/files/notes/NYU_Optimization_2017.pdf">Basics of LA</a><br>• <a href="https://www.maths.tcd.ie/~pete/ma1111/chapter3.pdf">Basics of Vector Space</a></td>
      </tr>
      <tr>
        <td><strong>April 3</strong></td>
        <td>PCA (Max-Var Formulation)<br><em>Eigen Values-Vectors (EV)</em><br><em>Clustering</em></td>
        <td><a href="https://www.math.purdue.edu/~liu1957/MA262_files/eigen.pdf">MA262 EV basics</a><br>PCA: PML 20.1<br>Clustering: <a href="https://www-users.cse.umn.edu/~jwcalder/Clustering.pdf">J. Cadler Slides</a><br><a href="https://www.cs.yale.edu/homes/el327/datamining2013aFiles/10_k_means_clustering.pdf">E Liberty lecture</a></td>
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fae31c4ad4a5fb47d5796704f896e4216462acdf54259067c30854d86b76032a1%2FLec20.pdf">Lec20.pdf</a> (handwritten)<br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F93edd9e87787321657ed505d6e36ec2c626fbaad23ba4d32fe2c278c572baeec%2Fscribe20.pdf">scribe20.pdf</a>, <a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fb801359c85b618e6ba9d6a80f72c5263969100a22fc280aea91b646e399d5c1d%2Fscribe20.tex">scribe20.tex</a>]<br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fcc53a5cb0242e758c55ac3203d54a107bf0c47fab37f3c824307f9cbc231702a%2Fplots20.zip">plots20.zip</a>]<br><a href="#">Scribe20</a>: Mishra, Simran</td>
        <td>Extra Reading:<br>• <a href="https://www.youtube.com/watch?v=PFDu9oVAE-g">Nice video tutorial on EV!</a><br>• K-Medoids: <a href="https://www2.cs.arizona.edu/~pachecoj/courses/csc380_fall21/lectures/kmeans.pdf">CSC 380 slides</a><br>• KPCA: <a href="https://zstevenwu.com/courses/s20/csci5525/resources/slides/lecture20.pdf">CSCI 5512 slides</a></td>
      </tr>
      <tr>
        <td><strong>April 10</strong></td>
        <td>K-Means<br><em>Spectral Clustering (SC)</em></td>
        <td>K-Means: <a href="https://www.cse.iitb.ac.in/~swaprava/courses/cs217/references/kmeans-convergence.pdf">CS217</a><br>PML 21</td>
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fcb22a08ef0323be1ee138fc8caf8630fd7a685f365d7f1264ad7e4372a82c7eb%2FLec21.pdf">Lec21.pdf</a> (handwritten)<br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Ff7640def2e5af8ce65090931a7586a1ca02e4e571a3cb9c0a40c27e51f35eaaf%2Fscribe21.pdf">scribe21.pdf</a>, <a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fbefc1809776ef84c2791f5db04598b4a651059d49ee899874c3bf77a35b038c2%2Fscribe21.tex">scribe21.tex</a>]<br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F53e12df539ede36708f94ca520f73d6786c61bc5ccc27a6b35549b6ea8a71c0b%2Fplots21.zip">plots21.zip</a>]<br><a href="#">Scribe21</a>: Wang, Haoxuan</td>
        <td>Extra Reading:<br>• <a href="https://people.csail.mit.edu/dsontag/courses/ml14/notes/Luxburg07_tutorial_spectral_clustering.pdf">More on Graph Laplacian</a></td>
      </tr>
      <tr>
        <td><strong>April 12</strong></td>
        <td>Spectral clustering (SC)<br><em>Neural Net Intro</em></td>
        <td>SC: <a href="https://www.cs.cmu.edu/~epxing/Class/10701-12f/Lecture/lecture21-SpecClus.pdf">ML10.701</a>, <a href="https://www.cse.msu.edu/~cse902/S14/ppt/kernelClustering.pdf">CSE902</a></td>
        <td><a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F9584b37f0ee98f255110f68c96d4f6e99c6ef07f702926094349b48f18802582%2FLec22.pdf">Lec22.pdf</a> (handwritten)<br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fe5def8b9ccd0d9f4865871e5b27b8473451f9278582eff9e1920401a3782a2d8%2Fscribe22.pdf">scribe22.pdf</a>, <a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fdd0f57481d674630fcbeb6a1b08aa61de1ba22b5dcd07a51eaee0293b946e2eb%2Fscribe22.tex">scribe22.tex</a>]<br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F79ff5e490c4edcbde85e7c83c422ec9ee8b93b2e3c67c24e0b346a5bf7b21c7d%2Fplots22.zip">plots22.zip</a>]<br><a href="#">Scribe22</a>: Wang, Haoxuan</td>
        <td>Extra Reading:<br>• <a href="https://people.cs.umass.edu/~akshay/courses/cs690m/files/lec19.pdf">Advanced SC</a></td>
      </tr>
      <tr>
        <td><strong>April 15</strong></td>
        <td>Feed-Forward NN (FFNN)<br><em>Back-Propagation (BP)</em></td>
        <td>CS217: <a href="https://www.cse.iitb.ac.in/~swaprava/courses/cs217/scribes/CS217_2024_lec11.pdf">FFNN</a>, <a href="https://www.cse.iitb.ac.in/~swaprava/courses/cs217/scribes/CS217_2024_lec12.pdf">BP</a><br>COS 324: <a href="https://princeton-introml.github.io/files/ch11.pdf">FFNN & BP</a></td>
        <td>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F3981910eb0fcffd34a50fb92bf8c68a6141ba73651414cd4101f893495e59d1f%2Fscribe23.pdf">scribe23.pdf</a>, <a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fd211d704a4367b205d88663a9d10abbe703e74fc35f9412aabcd8f78758464de%2Fscribe23.tex">scribe23.tex</a>]<br><a href="#">Scribe23</a>: Pipim, Charles / Rithish</td>
        <td></td>
      </tr>
      <tr>
        <td><strong>April 17</strong></td>
        <td>Backpropagation (contd)<br><em>RNN</em><br><em>CNN (Intro)</em></td>
        <td><a href="https://www.cse.iitb.ac.in/~swaprava/courses/cs217/scribes/CS217_2024_lec13.pdf">CS217-RNN</a><br><a href="https://harvard-iacs.github.io/2019-CS109B/lectures/lecture10/presentation/cs109b_lecture10_RNN.pdf">RNN Slides</a><br>EECS-498: <a href="https://web.eecs.umich.edu/~justincj/slides/eecs498/498_FA2019_lecture12.pdf">RNN Slides</a></td>
        <td>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Ffff1686fefe7dacaccf719fa502c805fa6417047fb25e65d49b5617ef7d3841e%2Fscribe24.pdf">scribe24.pdf</a>, <a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F7723902b933508792291a9a169b3402d7145dad3d46f656a757428f06c95fc68%2Fscribe24.tex">scribe24.tex</a>]<br><a href="#">Scribe24</a>: Salvi, Yukta</td>
        <td>Extra Reading:<br>• <a href="https://www.youtube.com/playlist?list=PLeo1K3hjS3uu7CxAacxVndI4bE_o3BDtO">Detailed Applied YT course on DL</a></td>
      </tr>
      <tr>
        <td><strong>April 22</strong></td>
        <td>CNN<br><em>Dropout regularization</em><br><em>Vanishing & Exploding Gradients (VE-Grads)</em><br><em>RNN-LSTM</em></td>
        <td><a href="https://www.cse.iitb.ac.in/~swaprava/courses/cs217/scribes/CS217_2024_lec14.pdf">CS217-CNN</a><br>COS 324: <a href="https://princeton-introml.github.io/files/ch12.pdf">CNN</a><br>EECS-498: <a href="https://web.eecs.umich.edu/~justincj/slides/eecs498/498_FA2019_lecture07.pdf">CNN Slides</a><br><a href="https://www.cs.columbia.edu/~zemel/Class/Nndl/files/lec08.pdf">VE-Grads in RNN</a><br><a href="https://sebastianraschka.com/pdf/lecture-notes/stat453ss21/L15_intro-rnn__slides.pdf">LSTM slides</a></td>
        <td>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fde5c28ea6da0c376860c1f55389baccec356fd11d6e857f016dafacb6a378719%2Fscribe25.pdf">scribe25.pdf</a>]<br><a href="#">Scribe25</a>: Agnihotri, Akshun</td>
        <td>Extra Reading:<br>• <a href="https://sebastianraschka.com/pdf/lecture-notes/stat453ss21/L10_regularization__slides.pdf">Regularization in NNs</a></td>
      </tr>
    </table>
  </div>

  <div id="Description" class="tabcontent">
    <h2>📚 Course Description</h2>
    <p style="text-align: justify;">
      This course provides a comprehensive introduction to machine learning concepts, algorithms, and applications. Students will explore supervised and unsupervised learning techniques, neural networks, and real-world implementations using Python and popular ML libraries. The course emphasizes both theoretical understanding and practical skills.
    </p>
  </div>

  <div id="Resources" class="tabcontent">
    <h2>📖 Resources</h2>
    <ul>
      <li><strong>Textbook:</strong> <em>Pattern Recognition and Machine Learning</em> by Christopher Bishop</li>
      <li><strong>Platform:</strong> Course materials and submissions via Blackboard</li>
      <li><strong>Programming:</strong> Python 3.8+, Jupyter Notebooks, scikit-learn, pandas, numpy</li>
    </ul>
  </div>

  <div id="Logistics" class="tabcontent">
    <h2>🎯 Course Logistics</h2>
    <ul>
      <li><strong>📍 Location:</strong> Science & Engineering Offices (SEO) 1000</li>
      <li><strong>⏰ Schedule:</strong> Tuesday & Thursday, 2:00 PM - 3:15 PM</li>
      <li><strong>👨‍🏫 Office Hours:</strong> Wednesdays 1:00–3:00 PM or by appointment</li>
      <li><strong>📧 Contact:</strong> Questions via Blackboard discussion forum preferred</li>
    </ul>
  </div>

  <script>
    document.getElementsByClassName('tablinks')[0].click(); // Open first tab by default
  </script>
</body>
</html>
