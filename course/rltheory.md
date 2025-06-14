---
title: 'RL Theory Reading Group'
date: 2025-06-12
permalink: /course/rltheory/
tags:
  - rl
  - theory
  - course
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Machine Learning Course</title>
    <style>
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
    <h1>CS 411: Introduction to Machine Learning</h1>
    <p>Instructor: Aadirupa Saha</p>

    <div class="tab">
        <button class="tablinks" onclick="openTab(event, 'Description')">Description</button>
        <button class="tablinks" onclick="openTab(event, 'Schedule')">Schedule</button>
        <button class="tablinks" onclick="openTab(event, 'Resources')">Resources</button>
    </div>

    <div id="Description" class="tabcontent">
        <h2>Course Description</h2>
        <p>This course provides a broad introduction to machine learning including supervised learning, unsupervised learning, and reinforcement learning.</p>
    </div>

    <div id="Schedule" class="tabcontent">
        <h2>Class Sessions</h2>
        <table border="1">
            <tr>
                <th>Date</th>
                <th>Presenter</th>
                <th>Resource</th>
                <th>Notes</th>
            </tr>
            <tr>
                <td>2025-06-20</td>
                <td>Alice</td>
                <td><a href="#">Intro Slides</a></td>
                <td>Overview of ML</td>
            </tr>
        </table>
    </div>

    <div id="Resources" class="tabcontent">
        <h2>Resources</h2>
        <ul>
            <li><a href="https://aadirupa.github.io">Back to Main Site</a></li>
        </ul>
    </div>

    <script>
        document.getElementsByClassName('tablinks')[0].click();
    </script>
</body>
</html>
