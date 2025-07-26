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
    padding: 30px 40px;
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
    <a href="#logistics">Logistics</a>
  </nav>

  <div class="container">
    <section id="description">
      <h2>Course Overview</h2>
      
      <p style="font-weight: bold;"> ------- Page Under Construction ----------- </p>

      
      <p>This course provides an introduction to the fundamental concepts and algorithms in machine learning. Topics include supervised and unsupervised learning, decision trees, regression, SVMs, neural networks, and clustering techniques, with an emphasis on both theoretical foundations and practical implementation.</p>
    </section>

    <section id="schedule">
      <h2>Weekly Schedule</h2>
      <table border="1" cellpadding="8" cellspacing="0" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr style="background-color: #f2f2f2;">
      <th>Date</th>
      <th>Topic</th>
      <th>Reading</th>
      <th>Slides</th>
      <th>Notes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Jan 21</td>
      <td>
        Introduction (Course Logistics)<br>
        Basics of Supervised Learning
      </td>
      <td>
        PML 1.2<br>
        ESL 2.1, 2.2
      </td>
      <td><a href="CS412-Intro.pdf">CS412-Intro.pdf</a></td>
      <td></td>
    </tr>
    <tr>
      <td>Jan 23</td>
      <td>Understanding loss functions</td>
      <td>PML 4.3</td>
      <td>
        <a href="Lec1.pdf">Lec1.pdf*</a> (handwritten)<br>
        [<a href="scribe1.pdf">scribe1.pdf</a>, <a href="scribe1.tex">scribe1.tex</a>]
      </td>
      <td>Scribe: Edomwonyi, Uwadia</td>
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
    <a href="https://people.eecs.berkeley.edu/~adityag/E1245/plg.pdf">Local Copy from E1 245 by Aditya Gopalan</a>
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
