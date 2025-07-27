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
        <th>Assignment</th>
        <th>Notes</th>
      </tr>
      <tr>
        <td><strong>Jan 14</strong></td>
        <td>Course Introduction<br><em>What is Machine Learning?</em></td>
        <td>Chapter 1</td>
        <td><a href="#">📊 Slides 1</a></td>
        <td>-</td>
        <td>First class</td>
      </tr>
      <tr>
        <td><strong>Jan 16</strong></td>
        <td>Linear Regression<br><em>Fundamentals & Implementation</em></td>
        <td>Chapter 2</td>
        <td><a href="#">📊 Slides 2</a></td>
        <td><a href="#">📝 HW1</a></td>
        <td>Python setup required</td>
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
