---
layout: splash
title: "Summer25 Reading Group"
date: 2025-06-10
permalink: /course/rltheory/
tags:
  - rl
  - ml
  - theory
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
      a:link {
        color: RoyalBlue;
        background-color: transparent;
        text-decoration: none;
      }
      a:visited {
        color: Purple;
        background-color: transparent;
        text-decoration: none;
      }
      a:hover {
        color: RoyalBlue;
        background-color: transparent;
        text-decoration: underline;
      }
      a:active {
        color: DarkRed;
        background-color: transparent;
        text-decoration: underline;
      }
      body {
        font-family: sans-serif;
        margin: 0;
        padding: 0;
        background: #fff;
      }
      .container {
        max-width: 1500px; 
        margin: 0 auto;
        padding: 2px;
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
        outline: none;
        cursor: pointer;
        padding: 10px 20px;
        transition: 0.3s;
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
      td {
        padding: 6px 8px;
        border: 1px solid #ccc;
        text-align: left;
        font-size: 1em;
        vertical-align: top;
        white-space: normal;          
      }
      th {
        background-color: #f2f2f2;
        padding: 6px 8px;
        border: 1px solid #ccc;
        text-align: center;
        font-size: 1.1em;          
        font-weight: bold;
        vertical-align: top;
        white-space: normal;
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
    <h2 style="color:DarkBlue;">Summer25 Reading Group: Reinforcement Learning (RL) Theory</h2>
    <p>Instructor: Aadirupa Saha</p>

    <div class="tab">
        <button class="tablinks" onclick="openTab(event, 'Schedule')">Schedule</button>
        <button class="tablinks" onclick="openTab(event, 'Description')">Description</button>
        <button class="tablinks" onclick="openTab(event, 'Resources')">Resources</button>
    </div>

    <div id="Schedule" class="tabcontent">
        <h2>Sessions</h2>
        <table border="1">
            <tr>
                <th>Date</th>
                <th>Presenter</th>
                <th>Topics</th>
                <th>Resource</th>
                <th>Notes</th>
            </tr>
            <tr>
                <td>2025-06-13</td>
                <td>Zhengyao</td>
                <td>MDP Basics, Values, Policies, <br> Bellman Consistency Equation</td>
                <td>RLM (Chap 1.1.1-1.1.3), <br> AK (Lec 5)</td>
                <td>-</td>
            </tr>
            <tr>
                <td>2025-06-17</td>
                <td>Zhengyao</td>
                <td>Bellman Optimality Equations, Value Iteration, <br> Policy Iteration, Convergence Results</td>
                <td>RLM (Thm 1.7, 1.8; Chap 1.3.1-1.3.3), <br> AK (Lec 5)</td>
                <td>-</td>
            </tr>
            <tr>
                <td>2025-06-20</td>
                <td>Aniket</td>
                <td> Policy Iteration, Convergence Guarantee, Episodic, Generative and Offline RL setting <br>The performance difference lemma </td>
                <td>RLM (Thm 1.14, Lem 1.16; Chap 1.3.2, 1.4, 1.5) <br> AK (Lec 6)</td>
                <td>-</td>
            </tr>
            <tr>
                <td>2025-06-24</td>
                <td> Amir </td>
                <td> Example of Policy Classes, Policy Gradient methods,  <br>Non-convexity and Convergence of Value functions under Softmax Parameterizations</td>
                <td>RLM (Lem 11.4, 11.5, 11.6; Chap 11.1, 11.2) <br> AK (Lec 6)</td>
                <td>-</td>
            </tr>
            <tr>
                <td>2025-06-27</td>
                <td> Amir </td>
                <td> Natural Policy Gradient (NPG),  <br>NPG update with Softmax Parameterization and Fisher information</td>
                <td>RLM (Lem 12.6; Chap 12.3) <br> AK (Lem 4; Lec 6)</td>
                <td>-</td>
            </tr>
            <tr>
                <td>2025-07-01</td>
                <td> Amir </td>
                <td> Convergence of vanilla PG,  <br>Convergence of NPG </td>
                <td>RLM (Thm 12.3, Cor 12.5, Thm 12.7; Chap 12.3, 12.4) <br> AK (Lem1, Thm 2, Thm 3, Lem 4; Lec 7)</td>
                <td>-</td>
            </tr>
        </table>
    </div>

    <div id="Description" class="tabcontent">
        <h2>Course Description</h2>
        <p style="text-align: justify;">
        This summer reading group explores foundational and advanced topics in Reinforcement Learning theory, 
        following closely the 
        <a href="https://rltheorybook.github.io/rltheorybook_AJKS.pdf" target="_blank">RL Theory Monograph</a> by Agarwal, Jiang, Kakade, and Sun. Participants will take turns presenting key concepts weekly, with occasional discussions drawing from classic texts <a href="https://rltheorybook.github.io/rltheorybook_AJKS.pdf" target="_blank">Reinforcement Learning: An Introduction</a> by Sutton and Barto. 
        The group aims to build theoretical intuition while fostering informal collaboration around RL and broader ML theory.
        </p>

        <p style="color:DarkBlue;"> Timing: Tuesday-Friday, 5:30-7 PM Central </p>
    </div>

    <div id="Resources" class="tabcontent">
        <h2>Core References</h2>
        <ul>
          <li>
            <strong>SB:</strong>
            <a href="https://www.andrew.cmu.edu/course/10-703/textbook/BartoSutton.pdf" target="_blank">
              Reinforcement Learning: An Introduction</a> by Sutton & Barto
          </li>
          <li>
            <strong>RLM:</strong>
            <a href="https://rltheorybook.github.io/rltheorybook_AJKS.pdf" target="_blank">
              RL: Theory & Algorithms</a> by Agarwal, Jiang, Kakade, Sun
          </li>
          <li>
          <strong>FRL:</strong>
          <a href="https://arxiv.org/abs/2312.16730" target="_blank">
            Foundations of Reinforcement Learning and Interactive Decision Making</a> by Foster & Rakhlin
        </li>
        <li>
          <strong>MFRL:</strong>
          <a href="https://github.com/MathFoundationRL/Book-Mathematical-Foundation-of-Reinforcement-Learning/tree/main" target="_blank">
            Mathematical Foundation of Reinforcement Learning</a> by Shiyu Zhao
        </li> 
        <li>
          <strong>TFRL:</strong>
          <a href="https://rltheory.github.io/" target="_blank">
            Theoretical Foundations of Reinforcement Learning</a> by Csaba Szepesvári 
        </li>
          <li>
            <strong>AK:</strong>
            <a href="https://people.cs.umass.edu/~akshay/courses/coms6998-11/index.html" target="_blank">
              COMS6998-11: Bandits and Reinforcement Learning</a>, by Akshay Krishnamurthy
          </li>
          <li>
            <strong>NJ:</strong>
            <a href="https://nanjiang.cs.illinois.edu/cs542/" target="_blank">
              CS 542: Statistical Reinforcement Learning</a>, by Nan Jiang
          </li>
        </ul>
    </div>

    <script>
        document.getElementsByClassName('tablinks')[0].click();
    </script>
</body>
</html>
