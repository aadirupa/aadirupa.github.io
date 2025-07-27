---
layout: splash
title: "Intro to ML"
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
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Intro to Machine Learning - Summer 2025</title>
  <style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
  }

  .banner {
    background-color: #0b5394;
    color: white;
    padding: 20px 40px; /* Reduced padding = thinner height */
    text-align: left;
  }

  .banner h1 {
    margin: 0;
    font-size: 2em;
  }

  .banner p {
    margin: 5px 0 0;
    font-size: 1.2em;
  }

  .content {
    padding: 3px 4px;
    width: 100%;       /* Ensure full width */
    box-sizing: border-box; /* Include padding in width */
  }

  .section {
    margin-bottom: 30px;
  }

  .section h2 {
    color: #0b5394;
    border-bottom: 2px solid #0b5394;
    padding-bottom: 5px;
  }
  .schedule-container {
            max-width: 12px;
            margin: 0 auto;
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            overflow: hidden;
        }
       
        h1 {
            text-align: center;
            color: #2c3e50;
            margin: 0;
            padding: 20px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
        }
       
        table {
            width: 100%;
            border-collapse: collapse;
            font-size: 14px;
        }
       
        th {
            background: #34495e;
            color: white;
            padding: 12px 8px;
            text-align: center;
            font-weight: 600;
            border: 1px solid #2c3e50;
        }
       
        td {
            padding: 10px 8px;
            border: 1px solid #ddd;
            vertical-align: top;
        }
       
        tr:nth-child(even) {
            background-color: #f8f9fa;
        }
       
        tr:hover {
            background-color: #e8f4f8;
        }
       
        .date-col {
            text-align: center;
            font-weight: bold;
            color: #2c3e50;
            min-width: 80px;
        }
       
        .topic-col {
            max-width: 200px;
        }
       
        .reading-col {
            max-width: 150px;
            font-size: 12px;
        }
       
        .slides-col {
            max-width: 200px;
            font-size: 12px;
        }
       
        .assignment-col {
            max-width: 150px;
            font-size: 12px;
        }
       
        .notes-col {
            max-width: 200px;
            font-size: 12px;
        }
       
        ul {
            margin: 5px 0;
            padding-left: 20px;
        }
       
        li {
            margin-bottom: 3px;
        }
       
        .extra-class {
            color: #e74c3c;
            font-weight: bold;
        }
       
        .exam-row {
            background-color: #fff3cd !important;
            font-weight: bold;
        }
       
        .break-row {
            background-color: #d1ecf1 !important;
            font-style: italic;
        }

        a {
          color: #0b5394;
          text-decoration: none;
        }
      
        a:hover {
          text-decoration: underline;
        } 
</style>
</head>
<body>
  <header>
    <h1>CS 412: Intro to Machine Learning</h1>
    <p> — Spring 2025, University of Illinois Chicago</p>
  </header>

  <nav style="display: flex; gap: 20px;">
    <a href="#description">Description</a>
    <a href="#schedule">Schedule</a>
    <a href="#resources">Resources</a>
    <a href="#prerequisite">Prerequisite</a>
    <a href="#logistics">Logistics</a>
  </nav>

  <div class="container">
    <section id="description">
      <h2>Course Overview</h2>
      
      <p>This course provides an introduction to the fundamental concepts and algorithms in machine learning. Topics include supervised and unsupervised learning, decision trees, regression, SVMs, neural networks, and clustering techniques, with an emphasis on both theoretical foundations and practical implementation.</p>
    </section>

    <section id="schedule">
      <h2>Weekly Schedule</h2>
<table border="1" cellpadding="1" cellspacing="0" style="border-collapse: collapse; width: 100%; margin-top: 0px">
  <thead>
                <tr>
                    <th>Date</th>
                    <th>Topic</th>
                    <th>Reading</th>
                    <th>Slides</th>
                    <th>Assignment</th>
                    <th>Notes</th>
                </tr>
  </thead>
 <tbody>
                <tr>
                    <td class="date-col">Jan 21</td>
                    <td class="topic-col">
                        <ul>
                            <li>Introduction (Course Logistics)</li>
                            <li>Basics of Supervised Learning</li>
                        </ul>
                    </td>
                    <td class="reading-col">PML 1.2<br>ESL 2.1, 2.2</td>
                    <td class="slides-col"><a href="#" target="_blank">CS412-Intro.pdf</a></td>
                    <td class="assignment-col">
                        <a href="#" target="_blank">HW1.pdf</a> (Self-Assessment)<br>
                        [Submit on Gradescope]<br>
                        Due: Jan 28
                    </td>
                    <td class="notes-col"></td>
                </tr>
                
                <tr>
                    <td class="date-col">Jan 23</td>
                    <td class="topic-col">Understanding loss functions</td>
                    <td class="reading-col">PML 4.3</td>
                    <td class="slides-col">
                        <a href="#" target="_blank">Lec1.pdf</a> (handwritten)<br>
                        [<a href="#" target="_blank">scribe1.pdf</a>, <a href="#" target="_blank">scribe1.tex</a>]<br>
                        Scribe: Edomwonyi, Uwadia
                    </td>
                    <td class="assignment-col"></td>
                    <td class="notes-col"></td>
                </tr>
                
                <tr>
                    <td class="date-col">Jan 28</td>
                    <td class="topic-col">
                        <ul>
                            <li>Hypothesis (Func) Class</li>
                            <li>ERM</li>
                            <li>Linear Regression</li>
                        </ul>
                    </td>
                    <td class="reading-col">PML 11.1, 11.2, 11.3<br>ESL 3.2</td>
                    <td class="slides-col">
                        <a href="#" target="_blank">Lec2.pdf</a> (handwritten)<br>
                        [<a href="#" target="_blank">scribe2.pdf</a>, <a href="#" target="_blank">scribe2.tex</a>]<br>
                        [<a href="#" target="_blank">plots2.zip</a>]<br>
                        Scribe: Shelke, Harsh
                    </td>
                    <td class="assignment-col">HW1 due today!</td>
                    <td class="notes-col"></td>
                </tr>
                
                <tr>
                    <td class="date-col">Jan 30</td>
                    <td class="topic-col">
                        <ul>
                            <li>Overfitting & Regularizers</li>
                            <li>Lin-Reg: Linear Regression (contd)</li>
                        </ul>
                    </td>
                    <td class="reading-col">PML 4.3, 5.4</td>
                    <td class="slides-col">
                        <a href="#" target="_blank">Lec3.pdf</a> (handwritten)<br>
                        <a href="#" target="_blank">Lin-Reg demo</a><br>
                        [<a href="#" target="_blank">scribe3.pdf</a>, <a href="#" target="_blank">scribe3.tex</a>]<br>
                        Scribe: Hulu, Charis/ Lokesh
                    </td>
                    <td class="assignment-col"></td>
                    <td class="notes-col"></td>
                </tr>
                
                <tr>
                    <td class="date-col">Feb 4</td>
                    <td class="topic-col">
                        <ul>
                            <li>Logistic Regression</li>
                            <li>Multiclass Logistic Regression (MLR)</li>
                        </ul>
                    </td>
                    <td class="reading-col">PML 10.2.1, 10.2.2<br>ESL 4.4.1</td>
                    <td class="slides-col">
                        <a href="#" target="_blank">Lec4.pdf</a> (handwritten)<br>
                        <a href="#" target="_blank">MLR demo</a><br>
                        [<a href="#" target="_blank">scribe4.pdf</a>, <a href="#" target="_blank">scribe4.tex</a>]<br>
                        Scribe: Dahagam, Sujay
                    </td>
                    <td class="assignment-col">
                        HW2 out [<a href="#" target="_blank">link</a>]<br>
                        (UIC credentials rqd.)
                    </td>
                    <td class="notes-col">Finalize scribe assignment</td>
                </tr>
                
                <tr>
                    <td class="date-col">Feb 6</td>
                    <td class="topic-col">
                        <ul>
                            <li>Multiclass logistic (contd)</li>
                            <li>MLE (Bernoulli)</li>
                            <li>MAP (Bernoulli)</li>
                        </ul>
                    </td>
                    <td class="reading-col">
                        PML 4.2, 4.5<br>
                        <a href="#" target="_blank">Slides CMU 10701</a><br>
                        <a href="#" target="_blank">Tom Mitchell's note</a>
                    </td>
                    <td class="slides-col">
                        <a href="#" target="_blank">Lec5.pdf</a> (handwritten)<br>
                        <a href="#" target="_blank">Beta demo</a><br>
                        [<a href="#" target="_blank">scribe5.pdf</a>, <a href="#" target="_blank">scribe5.tex</a>]<br>
                        Scribe: Bhat, Amith
                    </td>
                    <td class="assignment-col">
                        Bonus-Quiz [<a href="#" target="_blank">qz-feb6.pdf</a>]<br>
                        (submit to gradescope)
                    </td>
                    <td class="notes-col">
                        <a href="#" target="_blank">Feedback form</a><br>
                        <a href="#" target="_blank">Announcements</a>
                    </td>
                </tr>
                
                <tr>
                    <td class="date-col">Feb 8<br><span class="extra-class">[Extra Class-1]</span></td>
                    <td class="topic-col">
                        <ul>
                            <li>MLE for Regression</li>
                            <li>MAP = Regularization</li>
                        </ul>
                    </td>
                    <td class="reading-col">
                        PML 4.2.5 - 4.2.7, 4.5<br>
                        <a href="#" target="_blank">CMU 10-315 notes</a><br>
                        <a href="#" target="_blank">Nice blog</a>
                    </td>
                    <td class="slides-col">
                        <a href="#" target="_blank">Lec6.pdf</a> (handwritten)<br>
                        [<a href="#" target="_blank">scribe6.pdf</a>, <a href="#" target="_blank">scribe6.tex</a>]<br>
                        Scribe: Sappidi, Yugesh
                    </td>
                    <td class="assignment-col"></td>
                    <td class="notes-col">
                        Optional Reading:<br>
                        Conjugate Priors<br>
                        <ul>
                            <li><a href="#" target="_blank">Nice blog</a></li>
                            <li><a href="#" target="_blank">Duke STA114</a></li>
                        </ul>
                    </td>
                </tr>
                
                <tr>
                    <td class="date-col">Feb 11</td>
                    <td class="topic-col">
                        <ul>
                            <li>Regularized logistic regression thru' MAP</li>
                            <li>Convex functions</li>
                        </ul>
                    </td>
                    <td class="reading-col">
                        PML 10.1-10.3<br>
                        CvxO 1.1-1.3<br>
                        <a href="#" target="_blank">Notes-IFT 6085</a>
                    </td>
                    <td class="slides-col">
                        <a href="#" target="_blank">Lec7.pdf</a> (handwritten)<br>
                        [<a href="#" target="_blank">scribe7.pdf</a>, <a href="#" target="_blank">scribe7.tex</a>]<br>
                        Scribe: Ferdowsi, Farhad
                    </td>
                    <td class="assignment-col">HW2 due!</td>
                    <td class="notes-col"></td>
                </tr>
                
                <tr>
                    <td class="date-col">Feb 13</td>
                    <td class="topic-col">
                        <ul>
                            <li>Properties of Cvx funcs</li>
                            <li>Gradient descent (GD)</li>
                            <li>Convergence rates</li>
                        </ul>
                    </td>
                    <td class="reading-col">
                        CvxO 1.1-1.3, 3.1<br>
                        <a href="#" target="_blank">Notes by A. Ahmadi</a><br>
                        <a href="#" target="_blank">Notes by C Wang</a>
                    </td>
                    <td class="slides-col">
                        <a href="#" target="_blank">Lec8.pdf</a> (handwritten)<br>
                        <a href="#" target="_blank">GD demo</a><br>
                        [<a href="#" target="_blank">scribe8.pdf</a>, <a href="#" target="_blank">scribe8.tex</a>]<br>
                        Scribe: Ferdowsi, Farhad
                    </td>
                    <td class="assignment-col"></td>
                    <td class="notes-col">
                        Extra Reading<br>
                        <ol>
                            <li><a href="#" target="_blank">Matrix Norms</a></li>
                        </ol>
                    </td>
                </tr>
                
                <tr>
                    <td class="date-col">Feb 18</td>
                    <td class="topic-col">
                        <ul>
                            <li>Convergence of GD</li>
                            <li>Newton's method</li>
                        </ul>
                    </td>
                    <td class="reading-col">
                        CvxO 3.1, 3.2, 3.4, 5.3.2<br>
                        <a href="#" target="_blank">Nice notes on Cvx Optimization</a><br>
                        <a href="#" target="_blank">Notes-CS 6820</a>
                    </td>
                    <td class="slides-col">
                        <a href="#" target="_blank">Lec9.pdf</a> (handwritten)<br>
                        [<a href="#" target="_blank">scribe9.pdf</a>, <a href="#" target="_blank">scribe9.tex</a>]<br>
                        Scribe: Datta Sai VVN
                    </td>
                    <td class="assignment-col"></td>
                    <td class="notes-col">
                        Extra Reading:<br>
                        <ol>
                            <li><a href="#" target="_blank">Matrix Derivative</a></li>
                            <li><a href="#" target="_blank">Taylor Series</a></li>
                            <li><a href="#" target="_blank">Newton's Method</a></li>
                        </ol>
                    </td>
                </tr>
                
                <tr>
                    <td class="date-col">Feb 20</td>
                    <td class="topic-col">
                        <ul>
                            <li>GD convergence analysis</li>
                            <li>SGD + Convergence guarantees</li>
                            <li>Batched SGD</li>
                            <li>Variants of GD</li>
                        </ul>
                    </td>
                    <td class="reading-col">
                        CvxO 3.1-3.2<br>
                        <a href="#" target="_blank">Notes on SGD</a><br>
                        <a href="#" target="_blank">Notes on Heavy Ball & Nesterov's Accelerated GD</a>
                    </td>
                    <td class="slides-col">
                        <a href="#" target="_blank">Lec10.pdf</a> (handwritten)<br>
                        <a href="#" target="_blank">SGD demo</a><br>
                        [<a href="#" target="_blank">scribe10.pdf</a>, <a href="#" target="_blank">scribe10.tex</a>]<br>
                        Scribe: Aniket Wagde
                    </td>
                    <td class="assignment-col">HW3 out [<a href="#" target="_blank">link</a>]</td>
                    <td class="notes-col">
                        <a href="#" target="_blank">Announcements</a><br>
                        Extra Reading:<br>
                        <ol>
                            <li><a href="#" target="_blank">Comprehensive study of SGD & Batched-SGD</a></li>
                            <li><a href="#" target="_blank">Nice demo</a></li>
                        </ol>
                    </td>
                </tr>
                
                <tr>
                    <td class="date-col">Feb 25</td>
                    <td class="topic-col">
                        <ul>
                            <li>Max-Margin Formulation</li>
                            <li>SVM objective</li>
                            <li>KKT conditions</li>
                        </ul>
                    </td>
                    <td class="reading-col">
                        PML 17.3.1-17.3.2<br>
                        <a href="#" target="_blank">Caltech CS156 Slides</a>-1<br>
                        <a href="#" target="_blank">KKT conditions (CMU-10-725)</a><br>
                        <a href="#" target="_blank">Notes by Wang & Pavlu</a>
                    </td>
                    <td class="slides-col">
                        <a href="#" target="_blank">Lec11.pdf</a> (handwritten)<br>
                        <a href="#" target="_blank">Nice visual demo!</a><br>
                        [<a href="#" target="_blank">scribe11.pdf</a>, <a href="#" target="_blank">scribe11.tex</a>]<br>
                        Scribe: Harsh Kothari
                    </td>
                    <td class="assignment-col"></td>
                    <td class="notes-col">
                        Extra Reading:<br>
                        <ol>
                            <li><a href="#" target="_blank">Slides CMU 10-601</a></li>
                        </ol>
                    </td>
                </tr>
                
                <tr>
                    <td class="date-col">Feb 27</td>
                    <td class="topic-col">
                        <ul>
                            <li>KKT conditions (contd)</li>
                            <li>Dual Optimization</li>
                            <li>SVM with strong duality</li>
                        </ul>
                    </td>
                    <td class="reading-col">
                        <a href="#" target="_blank">Strong Duality and Slater's Conditions</a><br>
                        <a href="#" target="_blank">Caltech CS156 Slides</a>-2
                    </td>
                    <td class="slides-col">
                        <a href="#" target="_blank">Lec12.pdf</a> (handwritten)<br>
                        <a href="#" target="_blank">Nice visualization!</a><br>
                        [<a href="#" target="_blank">scribe12.pdf</a>, <a href="#" target="_blank">scribe12.tex</a>]<br>
                        Scribe: Boggavarapu, Lokesh
                    </td>
                    <td class="assignment-col"></td>
                    <td class="notes-col">
                        Extra Reading:<br>
                        <ol>
                            <li><a href="#" target="_blank">Primer on QP</a></li>
                            <li><a href="#" target="_blank">Strong Duality</a></li>
                        </ol>
                    </td>
                </tr>
                
                <tr>
                    <td class="date-col">Mar 1<br><span class="extra-class">[Extra Class-2]</span></td>
                    <td class="topic-col">
                        <ul>
                            <li>Kernel SVM</li>
                            <li>Kernel Properties</li>
                            <li>Examples</li>
                        </ul>
                    </td>
                    <td class="reading-col">
                        PML 17.3.4<br>
                        <a href="#" target="_blank">CMU-10701 slides</a>
                    </td>
                    <td class="slides-col">
                        <a href="#" target="_blank">Lec13.pdf</a> (handwritten)<br>
                        <a href="#" target="_blank">Kernel tricks demo</a><br>
                        [<a href="#" target="_blank">scribe13.pdf</a>, <a href="#" target="_blank">scribe13.tex</a>]<br>
                        Scribe: Madishetty, Aravind
                    </td>
                    <td class="assignment-col"></td>
                    <td class="notes-col">
                        Extra Reading:<br>
                        <ol>
                            <li><a href="#" target="_blank">SVM-vs-Perceptron</a></li>
                            <li><a href="#" target="_blank">Another amazing demo w/ Kernels!</a></li>
                        </ol>
                    </td>
                </tr>
                
                <tr>
                    <td class="date-col">Mar 4</td>
                    <td class="topic-col">
                        <ul>
                            <li>Soft-Margin SVM</li>
                            <li>SVM Regression</li>
                            <li>Perceptron</li>
                        </ul>
                    </td>
                    <td class="reading-col">
                        PML 17.3.3<br>
                        <a href="#" target="_blank">COMP-652 slides</a><br>
                        <a href="#" target="_blank">CMU-15-859</a>
                    </td>
                    <td class="slides-col">
                        <a href="#" target="_blank">Lec14.pdf</a> (handwritten)<br>
                        [<a href="#" target="_blank">scribe14.pdf</a>, <a href="#" target="_blank">scribe14.tex</a>]<br>
                        Scribe: Lukau, Please
                    </td>
                    <td class="assignment-col">HW3 due!</td>
                    <td class="notes-col"></td>
                </tr>
                
                <tr>
                    <td class="date-col">Mar 6</td>
                    <td class="topic-col">
                        <ul>
                            <li>Perceptron Mistake bounds</li>
                            <li>Perceptron w/o perfect linear separator</li>
                            <li>Kernel Perceptron</li>
                        </ul>
                    </td>
                    <td class="reading-col">
                        PML 10.2.5, 13.2<br>
                        <a href="#" target="_blank">Princeton CoS495</a><br>
                        <a href="#" target="_blank">CMU 10-607</a>
                    </td>
                    <td class="slides-col">
                        <a href="#" target="_blank">Lec15.pdf</a> (handwritten)<br>
                        <a href="#" target="_blank">Youtube demo</a><br>
                        [<a href="#" target="_blank">scribe15.pdf</a>, <a href="#" target="_blank">scribe15.tex</a>]<br>
                        Scribe: Rithish Reddy Chichili
                    </td>
                    <td class="assignment-col">
                        HW3 solutions posted: [<a href="#" target="_blank">link</a>]
                    </td>
                    <td class="notes-col"></td>
                </tr>
                
                <tr class="exam-row">
                    <td class="date-col">Mar 13</td>
                    <td class="topic-col">Mid Term</td>
                    <td class="reading-col"></td>
                    <td class="slides-col"></td>
                    <td class="assignment-col"></td>
                    <td class="notes-col"></td>
                </tr>
                
                <tr>
                    <td class="date-col">Mar 15<br><span class="extra-class">[Extra Class-3]</span></td>
                    <td class="topic-col">
                        <ul>
                            <li>Winnow's Algorithm</li>
                            <li>Mistake Bounds</li>
                        </ul>
                    </td>
                    <td class="reading-col">
                        Winnow: <a href="#" target="_blank">CS 4540</a><br>
                        Mistake Bound: <a href="#" target="_blank">CS260</a><br>
                        <a href="#" target="_blank">Winnow Example</a>
                    </td>
                    <td class="slides-col">
                        <a href="#" target="_blank">Lec16.pdf</a> (handwritten)<br>
                        Scribe: Nemi Chakrawarthy Bhupathiraju / Simran<br>
                        [<a href="#" target="_blank">scribe16.pdf</a>, <a href="#" target="_blank">scribe16.tex</a>]
                    </td>
                    <td class="assignment-col"></td>
                    <td class="notes-col">
                        Extra Reading:<br>
                        <ol>
                            <li>Proving lower bounds <a href="#" target="_blank">CMSC 35900</a> (Sec 2)</li>
                            <li>Advanced topics on Winnow & Perceptron: PLG Chap 12</li>
                        </ol>
                    </td>
                </tr>
                
                <tr>
                    <td class="date-col">Mar 18</td>
                    <td class="topic-col">
                        <ul>
                            <li>Boosting</li>
                            <li>Adaboost</li>
                            <li>Mistake Bounds</li>
                        </ul>
                    </td>
                    <td class="reading-col">
                        Boosting: <a href="#" target="_blank">CSCI699</a><br>
                        <a href="#" target="_blank">Slides</a>, Rob Schapire
                    </td>
                    <td class="slides-col">
                        <a href="#" target="_blank">Lec17.pdf</a> (handwritten)<br>
                        Scribe: Gabriel Zhang<br>
                        [<a href="#" target="_blank">scribe17.pdf</a>, <a href="#" target="_blank">scribe17.tex</a>]
                    </td>
                    <td class="assignment-col"></td>
                    <td class="notes-col">
                        Extra Reading:<br>
                        <ol>
                            <li>Original paper by <a href="#" target="_blank">Freund & Schapire'99</a></li>
                            <li>Advanced topics: <a href="#" target="_blank">Tutorial (Sec 9)</a></li>
                            <li>General winnow: <a href="#" target="_blank">Alg1</a>, <a href="#" target="_blank">Alg2</a></li>
                        </ol>
                    </td>
                </tr>
                
                <tr>
                    <td class="date-col">Mar 20</td>
                    <td class="topic-col">
                        <ul>
                            <li>Midterm solutions</li>
                            <li>PCA</li>
                        </ul>
                    </td>
                    <td class="reading-col"></td>
                    <td class="slides-col">Scribe: Jiachen Tao</td>
                    <td class="assignment-col">
                        <a href="#" target="_blank">Project List out!</a><br>
                        HW4 (Lab2) out! [<a href="#" target="_blank">link</a>]
                    </td>
                    <td class="notes-col"></td>
                </tr>
                
                <tr class="break-row">
                    <td class="date-col">Mar 25</td>
                    <td class="topic-col">Spring Break!</td>
                    <td class="reading-col"></td>
                    <td class="slides-col"></td>
                    <td class="assignment-col"></td>
                    <td class="notes-col"></td>
                </tr>
                
                <tr class="break-row">
                    <td class="date-col">Mar 27</td>
                    <td class="topic-col">Spring Break!</td>
                    <td class="reading-col"></td>
                    <td class="slides-col"></td>
                    <td class="assignment-col"></td>
                    <td class="notes-col"></td>
                </tr>
                
                <tr>
                    <td class="date-col">April 1</td>
                    <td class="topic-col">
                        <ul>
                            <li>Orthonormal Basis (OB)</li>
                            <li>PCA (Min-Error Formulation)</li>
                        </ul>
                    </td>
                    <td class="reading-col">
                        OB: <a href="#" target="_blank">Gilbert Strang</a> [Chap 3.4]<br>
                        PCA: PRML 12.1-12.2
                    </td>
                    <td class="slides-col">
                        <a href="#" target="_blank">Lec19.pdf</a> (handwritten)<br>
                        Scribe: Jiachen Tao / Aksun<br>
                        [<a href="#" target="_blank">Scribe19.pdf</a>]
                    </td>
                    <td class="assignment-col"></td>
                    <td class="notes-col">
                        Project selection deadline.<br>
                        [<a href="#" target="_blank">add project preference</a>]<br>
                        Extra Reading:<br>
                        <ul>
                            <li><a href="#" target="_blank">Basics of LA</a></li>
                            <li><a href="#" target="_blank">Basics of Vector Space</a></li>
                        </ul>
                    </td>
                </tr>
                
                <tr>
                    <td class="date-col">April 3</td>
                    <td class="topic-col">
                        <ul>
                            <li>PCA (Max-Var Formulation)</li>
                            <li>Eigen Values-Vectors (EV)</li>
                            <li>Clustering</li>
                        </ul>
                    </td>
                    <td class="reading-col">
                        <a href="#" target="_blank">MA262 EV basics</a><br>
                        PCA: PML 20.1<br>
                        Clustering: <a href="#" target="_blank">J. Cadler Slides</a><br>
                        <a href="#" target="_blank">E Liberty lecture</a>
                    </td>
                    <td class="slides-col">
                        <a href="#" target="_blank">Lec20.pdf</a> (handwritten)<br>
                        Scribe: Mishra, Simran<br>
                        [<a href="#" target="_blank">scribe20.pdf</a>, <a href="#" target="_blank">scribe20.tex</a>]
                    </td>
                    <td class="assignment-col"></td>
                    <td class="notes-col">
                        Find a collaborator/ submit your preference latest by Apr 4th<br>
                        [<a href="#" target="_blank">Project-groups</a>]<br>
                        Extra Reading:<br>
                        <ul>
                            <li><a href="#" target="_blank">Nice video tutorial on EV!</a></li>
                            <li>K-Medoids: <a href="#" target="_blank">CSC 380 slides</a></li>
                            <li>KPCA: <a href="#" target="_blank">CSCI 5512 slides</a></li>
                        </ul>
                    </td>
                </tr>
                
                <tr>
                    <td class="date-col">April 10</td>
                    <td class="topic-col">
                        <ul>
                            <li>K-Means</li>
                            <li>Spectral Clustering (SC)</li>
                        </ul>
                    </td>
                    <td class="reading-col">
                        K-Means: <a href="#" target="_blank">CS217</a><br>
                        PML 21
                    </td>
                    <td class="slides-col">
                        <a href="#" target="_blank">Lec21.pdf</a> (handwritten)<br>
                        Scribe: Wang, Haoxuan<br>
                        [<a href="#" target="_blank">scribe21.pdf</a>, <a href="#" target="_blank">scribe21.tex</a>]
                    </td>
                    <td class="assignment-col"></td>
                    <td class="notes-col">
                        Extra Reading:<br>
                        <ul>
                            <li><a href="#" target="_blank">More on Graph Laplacian</a></li>
                        </ul>
                    </td>
                </tr>
                
                <tr>
                    <td class="date-col">April 12</td>
                    <td class="topic-col">
                        <ul>
                            <li>Spectral clustering (SC)</li>
                            <li>Neural Net Intro</li>
                        </ul>
                    </td>
                    <td class="reading-col">
                        SC: <a href="#" target="_blank">ML10.701</a>, <a href="#" target="_blank">CSE902</a>
                    </td>
                    <td class="slides-col">
                        <a href="#" target="_blank">Lec22.pdf</a> (handwritten)<br>
                        Scribe: Wang, Haoxuan<br>
                        [<a href="#" target="_blank">scribe22.pdf</a>, <a href="#" target="_blank">scribe22.tex</a>]
                    </td>
                    <td class="assignment-col"></td>
                    <td class="notes-col">
                        Extra Reading:<br>
                        <ul>
                            <li><a href="#" target="_blank">Advanced SC</a></li>
                        </ul>
                    </td>
                </tr>
                
                <tr>
                    <td class="date-col">April 15</td>
                    <td class="topic-col">
                        <ul>
                            <li>Feed-Forward NN (FFNN)</li>
                            <li>Back-Propagation (BP)</li>
                        </ul>
                    </td>
                    <td class="reading-col">
                        CS217: <a href="#" target="_blank">FFNN</a>, <a href="#" target="_blank">BP</a><br>
                        COS 324: <a href="#" target="_blank">FFNN & BP</a>
                    </td>
                    <td class="slides-col">
                        Scribe: Pipim, Charles / Rithish<br>
                        [<a href="#" target="_blank">scribe23.pdf</a>, <a href="#" target="_blank">scribe23.tex</a>]
                    </td>
                    <td class="assignment-col">HW4 due!</td>
                    <td class="notes-col"></td>
                </tr>
                
                <tr>
                    <td class="date-col">April 17</td>
                    <td class="topic-col">
                        <ul>
                            <li>Backpropagation (contd)</li>
                            <li>RNN</li>
                            <li>CNN (Intro)</li>
                        </ul>
                    </td>
                    <td class="reading-col">
                        <a href="#" target="_blank">CS217-RNN</a><br>
                        <a href="#" target="_blank">RNN Slides</a><br>
                        EECS-498: <a href="#" target="_blank">RNN Slides</a>
                    </td>
                    <td class="slides-col">
                        Scribe: Salvi, Yukta<br>
                        [<a href="#" target="_blank">scribe24.pdf</a>, <a href="#" target="_blank">scribe24.tex</a>]
                    </td>
                    <td class="assignment-col">HW5 (Lab3) out! [<a href="#" target="_blank">link</a>]</td>
                    <td class="notes-col">
                        Extra Reading:<br>
                        <ul>
                            <li><a href="#" target="_blank">Detailed Applied YT course on DL</a></li>
                        </ul>
                    </td>
                </tr>
                
                <tr>
                    <td class="date-col">April 22</td>
                    <td class="topic-col">
                        <ul>
                            <li>CNN</li>
                            <li>Dropout regularization</li>
                            <li>Vanishing & Exploding Gradients (VE-Grads)</li>
                            <li>RNN-LSTM</li>
                        </ul>
                    </td>
                    <td class="reading-col">
                        <a href="#" target="_blank">CS217-CNN</a><br>
                        COS 324: <a href="#" target="_blank">CNN</a><br>
                        EECS-498: <a href="#" target="_blank">CNN Slides</a><br>
                        <a href="#" target="_blank">VE-Grads in RNN</a><br>
                        <a href="#" target="_blank">LSTM slides</a>
                    </td>
                    <td class="slides-col">
                        Scribe: Agnihotri, Akshun<br>
                        [<a href="#" target="_blank">scribe25.pdf</a>]
                    </td>
                    <td class="assignment-col"></td>
                    <td class="notes-col">
                        Extra Reading:<br>
                        <ul>
                            <li><a href="#" target="_blank">Regularization in NNs</a></li>
                        </ul>
                    </td>
                </tr>
                
                <tr>
                    <td class="date-col">April 24</td>
                    <td class="topic-col">
                        <ul>
                            <li>Gaussian Processes (GP)</li>
                        </ul>
                    </td>
                    <td class="reading-col">
                        GP: <a href="#" target="_blank">CS229 notes</a><br>
                        <a href="#" target="_blank">ESE-680 notes</a>
                    </td>
                    <td class="slides-col">
                        <a href="#" target="_blank">Lec26.pdf</a> (handwritten)<br>
                        Scribe: Bhat, Amith<br>
                        [<a href="#" target="_blank">scribe26.pdf</a>, <a href="#" target="_blank">scribe26.tex</a>]
                    </td>
                    <td class="assignment-col"></td>
                    <td class="notes-col">
                        <a href="#" target="_blank">OMD.pdf</a><br>
                        <a href="#" target="_blank">OCO.pdf</a>
                    </td>
                </tr>
                
                <tr>
                    <td class="date-col">April 26<br><span class="extra-class">[Optional Extra class-1]</span></td>
                    <td class="topic-col">
                        <ul>
                            <li>Transformers for LMs</li>
                        </ul>
                    </td>
                    <td class="reading-col">
                        <a href="#" target="_blank">CMU 11-785 slides</a><br>
                        <a href="#" target="_blank">Attention Paper (Google)</a>
                    </td>
                    <td class="slides-col"></td>
                    <td class="assignment-col"></td>
                    <td class="notes-col">
                        Lecture topic not included in the final exam!<br>
                        <a href="#" target="_blank">CS4780 Slides</a>
                    </td>
                </tr>
                
                <tr>
                    <td class="date-col">April 29</td>
                    <td class="topic-col">
                        <ul>
                            <li>Online Learning Basics-1</li>
                            <li>- Halving (HA)</li>
                            <li>- Wtd-Majority (WMA)</li>
                        </ul>
                    </td>
                    <td class="reading-col">
                        <a href="#" target="_blank">HA.pdf</a><br>
                        <a href="#" target="_blank">WMA.pdf</a>
                    </td>
                    <td class="slides-col">
                        Scribe: Kothari, Harsh<br>
                        [<a href="#" target="_blank">scribe28.pdf</a>, <a href="#" target="_blank">scribe28.tex</a>]
                    </td>
                    <td class="assignment-col"></td>
                    <td class="notes-col"></td>
                </tr>
                
                <tr>
                    <td class="date-col">May 1</td>
                    <td class="topic-col">
                        <ul>
                            <li>Online Learning Basics-2</li>
                            <li>- EXP-Wt</li>
                            <li>- OMD (OCO)</li>
                        </ul>
                    </td>
                    <td class="reading-col">
                        <a href="#" target="_blank">Exp-Wt.pdf</a>
                    </td>
                    <td class="slides-col">
                        Scribe: Datta, Sai VVN<br>
                        [<a href="#" target="_blank">scribe29.pdf</a>]
                    </td>
                    <td class="assignment-col"></td>
                    <td class="notes-col">
                        [Topic not included in the final exam]<br>
                        Extra Reading:<br>
                        <ul>
                            <li><a href="#" target="_blank">OMD.pdf</a></li>
                            <li><a href="#" target="_blank">OCO.pdf</a></li>
                        </ul>
                    </td>
                </tr>
                
                <tr>
                    <td class="date-col">May 3</td>
                    <td class="topic-col"></td>
                    <td class="reading-col"></td>
                    <td class="slides-col"></td>
                    <td class="assignment-col">HW5 due!</td>
                    <td class="notes-col"></td>
                </tr>
                
                <tr class="exam-row">
                    <td class="date-col">May 6</td>
                    <td class="topic-col">Final Exam</td>
                    <td class="reading-col"></td>
                    <td class="slides-col"></td>
                    <td class="assignment-col"></td>
                    <td class="notes-col">Time: 1-2:30 pm CT<br>Room: LC F6</td>
                </tr>
                
                <tr class="exam-row">
                    <td class="date-col">May 9</td>
                    <td class="topic-col">Project Presentations</td>
                    <td class="reading-col"></td>
                    <td class="slides-col"></td>
                    <td class="assignment-col">Final project report due!</td>
                    <td class="notes-col">Time: 3-5:30 pm CT<br>Room: TBD</td>
                </tr>
            </tbody>
        </table>
      
    </section>

    <section id="resources">
      <h2>Resources</h2>
<p>Class lectures are based on, but not limited to, the following books:</p>

<ul>
  <li>
    <strong>[ESL]</strong> <em>The Elements of Statistical Learning</em> by Hastie, Tibshirani, and Friedman –
    <a href="https://web.stanford.edu/~hastie/ElemStatLearn/">Book website</a>
  </li>
  <li>
    <strong>[MLTM]</strong> <em>Machine Learning</em> by Tom Mitchell –
    <a href="https://www.cs.cmu.edu/~tom/mlbook.html">Online copy</a>
  </li>
  <li>
    <strong>[PML]</strong> <em>Probabilistic Machine Learning: An Introduction</em> by Kevin Murphy –
    <a href="https://probml.github.io/pml-book/">Book website</a>
  </li>
  <li>
    <strong>[PLG]</strong> <em>Prediction, Learning and Games</em> by Nicolo Cesa-Bianchi and Gabor Lugosi, Cambridge University Press, 2006 –
    <a href="https://ece.iisc.ac.in/~aditya/Prediction_Learning_and_Games.pdf">Local Copy from E1 245</a>
  </li>
  <li>
    <strong>[PRML]</strong> <em>Pattern Recognition and Machine Learning</em> by Christopher Bishop (optional) –
    <a href="https://www.microsoft.com/en-us/research/publication/pattern-recognition-machine-learning/">Free copy</a>
  </li>
  <li>
    <strong>[PyAG]</strong> (Optional) <em>Hands-On Machine Learning with Scikit-Learn & TensorFlow</em> by Aurélien Géron –
    <a href="https://github.com/ageron/handson-ml2">Online (GitHub)</a>
  </li>
  <li>
    <strong>[CIML]</strong> (Optional) <em>A Course in Machine Learning</em> by Hal Daumé III –
    <a href="http://ciml.info/">Online copy</a>,
    <a href="http://ciml.info/errata.html">Errata</a>
  </li>
  <li>
    <strong>[UML]</strong> (Optional) <em>Understanding Machine Learning: From Theory to Algorithms</em> by Shai Ben-David and Shai Shalev-Shwartz –
    <a href="https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/">Online copy</a>
  </li>
  <li>
    <strong>[OCO]</strong> (Optional) <em>Introduction to Online Convex Optimization</em> by Elad Hazan –
    <a href="https://ocobook.cs.princeton.edu/">Book website</a>
  </li>
  <li>
    <strong>[CvxO]</strong> <em>Convex Optimization: Algorithms and Complexity</em> by Sébastien Bubeck –
    <a href="https://sbubeck.com/Bubeck15-survey.pdf">Book website</a>
  </li>
</ul>

    </section>

    <section id="prerequisite">
      <h2>Prerequisite</h2>
      <p>Please familiarize yourself with the basics of <strong>Probability & Statistics (PS)</strong> and <strong>Linear Algebra (LA)</strong>. Below are recommended introductory resources to help you build a solid foundation:</p>

<ul>
  <li>
    <strong>PS Review:</strong>
    <ol>
      <li><a href="https://cs229.stanford.edu/section/cs229-prob.pdf">Stanford CS229 Probability Review</a></li>
      <li><a href="https://www2.isye.gatech.edu/~sman/courses/6761/6761-1-ProbReview.pdf">Georgia Tech Prob Review (ISYE 6761)</a></li>
      <li><a href="https://users.ssc.wisc.edu/~ctaber/410/statrev.pdf">UW-Madison Stat Review</a></li>
    </ol>
  </li>
  
  <li>
    <strong>LA Review:</strong>
    <ol>
      <li><a href="https://cs229.stanford.edu/section/cs229-linalg.pdf">Stanford CS229 Linear Algebra Review</a></li>
      <li><a href="https://james-chuang.github.io/notes/linalg_review.pdf">Linear Algebra Notes by James Chuang</a></li>
      <li><a href="https://www.cs.cmu.edu/~jingx/docs/linearalgebra.pdf">CMU Linear Algebra Review</a></li>
    </ol>
  </li>

  <li>
    <strong>LaTeX for Scientific Writing:</strong>
    <br>
    Familiarity with LaTeX is expected for scribing lecture notes and writing assignments.
    <br>
    Learn the basics: <a href="https://www.youtube.com/watch?v=lgiCpA4zzGU">LaTeX Tutorial (YouTube)</a> — many other beginner tutorials are also available online.
  </li>

  <li>
    <strong>Programming Assignments:</strong>
    <br>
    Assignments will involve coding in Python or Matlab. Be prepared to write code.
    <br>
    Python tutorial: <a href="https://www.youtube.com/playlist?list=PLzMcBGfZo4-mP7qA9cagf68V06sko5otr">Programming for Beginners (YouTube Playlist)</a>
    <br>
    Google Colab is recommended — many online tutorials are available.
  </li>
</ul>

<p><strong>Note:</strong> Familiarity with the above basics is <em>highly recommended</em> for those taking the course for credit. A lack of understanding may impact your performance and grades.</p>
    </section>

    <section id="logistics">
      <h2>Course Logistics</h2>
      <p><strong>Instructor:</strong> Prof. Aadirupa Saha<br>
         <strong>Email:</strong> aadirupa@uic.edu<br>
         <strong>Office Hours:</strong> TBD</p>
    </section>

    <footer>
      &copy; 2025 Intro to ML @ UIC — Designed by Aadirupa Saha
    </footer>
  </div>
</body>
</html>
