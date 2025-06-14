---
title: "Summer25 Reading Group"
date: 2025-06-10
permalink: /course/rltheory/
tags:
  - rl
  - theory
  - course
author_profile: true
---

<html lang="en">
<head>
    <style>
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
        padding: 10px;
        }
        .tab {
            overflow: hidden;
            border-bottom: 1px solid #ccc;
        }
        .tab button {
            background-color: inherit;
            float: left;
            border: none;
            outline: none;
            cursor: pointer;
            padding: 10px 20px;
            transition: 0.3s;
        }
        .tab button:hover {
            background-color: #ddd;
        }
        .tab button.active {
            background-color: #ccc;
        }
        .tabcontent {
            display: none;
            padding: 10px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        
        th, td {
            padding: 12px 16px;
            border: 1px solid #ccc;
            text-align: left;
            vertical-align: top;
            word-break: break-word;
            white-space: normal;
        }
        
        th {
            background-color: #f2f2f2;
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
    <h2>Reinforcement Learning Theory</h2>
    <!--<p>Instructor: Aadirupa Saha</p>-->

    <div class="tab">
        <button class="tablinks" onclick="openTab(event, 'Description')">Description</button>
        <button class="tablinks" onclick="openTab(event, 'Schedule')">Schedule</button>
        <button class="tablinks" onclick="openTab(event, 'Resources')">Resources</button>
    </div>

    <div id="Description" class="tabcontent">
        <h2>Course Description</h2>
    <p>
    This summer reading group explores foundational and advanced topics in Reinforcement Learning theory, 
    following closely the 
    <a href="https://rltheorybook.github.io/rltheorybook_AJKS.pdf" target="_blank">RL Theory Monograph</a> by Agarwal, Jiang, Kakade, and Sun. Participants will take turns presenting key concepts weekly, with occasional discussions drawing from classic texts <a href="https://rltheorybook.github.io/rltheorybook_AJKS.pdf" target="_blank">Reinforcement Learning: An Introduction</a> by Sutton and Barto. 
    The group aims to build theoretical intuition while fostering informal collaboration around RL and broader ML theory.
    </p>

    <p> Timing: Tuesday-Friday, 5:30-7 PM Central </p>
    
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
                <td>RLM (Chap 1.1.1 - 1.1.3), <br> AK (Lec 5)</td>
                <td>-</td>
            </tr>
            <tr>
                <td>2025-06-17</td>
                <td>Zhengyao</td>
                <td>Bellman Optimality Equations, Value Iteration, <br> Policy Iteration, Convergence Results</td>
                <td>RLM (Thm 1.7, 1.8. Chap 1.3.1 - 1.3.3), <br> AK (Lec 5,6)</td>
                <td>-</td>
            </tr>
        </table>
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
            <strong>AK:</strong>
            <a href="https://people.cs.umass.edu/~akshay/courses/coms6998-11/index.html" target="_blank">
              COMS6998-11: RL Theory Course by Akshay Krishnamurthy
            </a>
          </li>
          <li>
            <strong>NJ:</strong>
            <a href="https://nanjiang.cs.illinois.edu/cs542/" target="_blank">
              CS 542: Reinforcement Learning by Nan Jiang (UIUC)
            </a>
          </li>
        </ul>

       
       <!-- <p><a href="https://aadirupa.github.io">Back to Main Site</a></p>-->
       
    </div>

    <script>
        document.getElementsByClassName('tablinks')[0].click();
    </script>
</body>
</html>
