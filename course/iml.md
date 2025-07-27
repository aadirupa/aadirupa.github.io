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

<style>
/* Only target course-specific elements to avoid affecting main site navigation */
.ml-course-header {
    background: linear-gradient(135deg, #1565c0 0%, #1976d2 50%, #42a5f5 100%);
    color: white;
    padding: 1rem 1rem;
    text-align: center;
    position: relative;
    overflow: hidden;
}

.ml-course-header::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><circle cx="20" cy="20" r="2" fill="rgba(255,255,255,0.1)"/><circle cx="80" cy="30" r="1.5" fill="rgba(255,255,255,0.1)"/><circle cx="40" cy="70" r="1" fill="rgba(255,255,255,0.1)"/><circle cx="90" cy="80" r="2.5" fill="rgba(255,255,255,0.1)"/></svg>');
    pointer-events: none;
}

.ml-course-header h1 {
    font-size: 2.8rem;
    font-weight: 700;
    margin-bottom: 0.5rem;
    text-shadow: 0 2px 4px rgba(0,0,0,0.2);
    position: relative;
    z-index: 1;
}

.ml-course-header p {
    font-size: 1.3rem;
    font-weight: 300;
    opacity: 0.95;
    position: relative;
    z-index: 1;
}

.ml-course-nav {
    background: linear-gradient(to right, #ffffff 0%, #f8f9fa 100%);
    padding: 1.2rem 0;
    box-shadow: 0 4px 12px rgba(0,0,0,0.08);
    border-bottom: 3px solid #e3f2fd;
}

.ml-nav-container {
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    justify-content: center;
    gap: 2rem;
    flex-wrap: wrap;
    padding: 0 2rem;
}

.ml-course-nav a {
    color: #1565c0;
    text-decoration: none;
    font-weight: 600;
    padding: 0.8rem 1.5rem;
    border-radius: 25px;
    transition: all 0.3s ease;
    background: rgba(21, 101, 192, 0.05);
    border: 2px solid transparent;
}

.ml-course-nav a:hover {
    background: linear-gradient(135deg, #1565c0, #1976d2) !important;
    color: white;
    text-decoration: none;
    transform: translateY(-2px);
    box-shadow: 0 4px 12px rgba(21, 101, 192, 0.3);
}

.ml-course-content {
    max-width: 1200px;
    margin: 0 auto;
    padding: 2rem;
    background: linear-gradient(to bottom, #f8f9fa 0%, #ffffff 100%);
    min-height: 100vh;
}

.ml-course-section {
    background: linear-gradient(135deg, #ffffff 0%, #f8f9fa 100%);
    margin-bottom: 2.5rem;
    padding: 2.5rem;
    border-radius: 16px;
    box-shadow: 0 8px 25px rgba(0,0,0,0.08);
    border: 1px solid rgba(21, 101, 192, 0.1);
    position: relative;
    overflow: hidden;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.ml-course-section:hover {
    transform: translateY(-2px);
    box-shadow: 0 12px 35px rgba(0,0,0,0.12);
}

.ml-course-section::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    height: 4px;
    background: linear-gradient(90deg, #1565c0, #1976d2, #42a5f5);
}

.ml-course-section h2 {
    color: #1565c0;
    font-size: 2rem;
    font-weight: 700;
    margin-bottom: 1.5rem;
    padding-bottom: 0.8rem;
    border-bottom: 2px solid rgba(66, 165, 245, 0.3);
    position: relative;
}

.ml-course-section h2::after {
    content: '';
    position: absolute;
    bottom: -2px;
    left: 0;
    width: 60px;
    height: 2px;
    background: linear-gradient(90deg, #1565c0, #42a5f5);
}

.ml-course-section p {
    margin-bottom: 1rem;
    color: #424242;
    font-size: 1rem;
    line-height: 1.7;
}

.ml-schedule-table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 1.5rem;
    background: white;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 4px 15px rgba(0,0,0,0.08);
}

.ml-schedule-table th {
    background: linear-gradient(135deg, #1565c0 0%, #1976d2 100%);
    color: white;
    padding: 1.2rem 1rem;
    text-align: left;
    font-weight: 600;
    font-size: 0.9rem;
    text-transform: uppercase;
    letter-spacing: 1px;
    text-shadow: 0 1px 2px rgba(0,0,0,0.2);
}

.ml-schedule-table td {
    padding: 1.2rem 1rem;
    border-bottom: 1px solid rgba(66, 165, 245, 0.1);
    vertical-align: top;
    font-size: 0.95rem;
    transition: background-color 0.2s ease;
}

.ml-schedule-table tr:hover {
    background: linear-gradient(135deg, rgba(66, 165, 245, 0.05) 0%, rgba(25, 118, 210, 0.05) 100%);
}

.ml-schedule-table tr:nth-child(even) {
    background: rgba(248, 249, 250, 0.7);
}

.ml-schedule-table a {
    color: #1565c0 !important;
    text-decoration: none !important;
    font-weight: 500;
    padding: 0.3rem 0.8rem;
    border-radius: 15px;
    background: rgba(66, 165, 245, 0.1);
    transition: all 0.2s ease;
}

.ml-schedule-table a:hover {
    background: linear-gradient(135deg, #1565c0, #1976d2) !important;
    color: white !important;
    text-decoration: none !important;
    transform: translateY(-1px);
    box-shadow: 0 2px 8px rgba(21, 101, 192, 0.3);
}

.ml-prereq-box {
    background: linear-gradient(135deg, #fff3e0 0%, #ffe0b2 100%);
    padding: 2rem;
    border-radius: 12px;
    border-left: 5px solid #ff9800;
    margin-bottom: 1.5rem;
    box-shadow: 0 4px 12px rgba(255, 152, 0, 0.1);
}

.ml-prereq-box h3 {
    color: #e65100;
    margin-bottom: 1rem;
    font-weight: 600;
}

.ml-prereq-box ol {
    padding-left: 1.5rem;
}

.ml-prereq-box li {
    margin-bottom: 0.8rem;
    color: #424242;
    line-height: 1.6;
}

.ml-resources-item {
    background: linear-gradient(135deg, #e8f5e8 0%, #c8e6c9 100%);
    padding: 1.5rem;
    margin-bottom: 1rem;
    border-radius: 12px;
    border-left: 5px solid #4caf50;
    box-shadow: 0 3px 10px rgba(76, 175, 80, 0.1);
    transition: transform 0.2s ease;
}

.ml-resources-item:hover {
    transform: translateX(5px);
}

.ml-resources-item strong {
    color: #2e7d32;
    font-weight: 700;
}

@media (max-width: 768px) {
    .ml-course-header h1 {
        font-size: 2.2rem;
    }
    
    .ml-course-content {
        padding: 1rem;
    }
    
    .ml-nav-container {
        gap: 1rem;
    }
    
    .ml-course-nav a {
        padding: 0.6rem 1.2rem;
        font-size: 0.9rem;
    }
}
</style>

<div class="ml-course-header">
    <h1>CS 412: Intro to Machine Learning</h1>
    <p>Spring 2025, University of Illinois Chicago</p>
</div>

<div class="ml-course-nav">
    <div class="ml-nav-container">
        <a href="#description">Description</a>
        <a href="#schedule">Schedule</a>
        <a href="#resources">Resources</a>
        <a href="#prerequisite">Prerequisites</a>
        <a href="#logistics">Logistics</a>
    </div>
</div>

<div class="ml-course-content">
    <div class="ml-course-section" id="description">
        <h2>📚 Course Description</h2>
        <p>This course provides a comprehensive introduction to machine learning concepts, algorithms, and applications. Students will explore supervised and unsupervised learning techniques, neural networks, and real-world implementations using Python and popular ML libraries.</p>
    </div>

    <div class="ml-course-section" id="schedule">
        <h2>📅 Course Schedule</h2>
        <table class="ml-schedule-table">
            <thead>
                <tr>
                    <th>Date</th>
                    <th>Topic</th>
                    <th>Reading</th>
                    <th>Materials</th>
                    <th>Assignment</th>
                    <th>Notes</th>
                </tr>
            </thead>
            <tbody>
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
            </tbody>
        </table>
    </div>

    <div class="ml-course-section" id="resources">
        <h2>📖 Resources</h2>
        <div class="ml-resources-item">
            <strong>📚 Primary Textbook:</strong> Pattern Recognition and Machine Learning by Christopher Bishop
        </div>
        <div class="ml-resources-item">
            <strong>💻 Online Platform:</strong> Course materials and submissions via Blackboard
        </div>
        <div class="ml-resources-item">
            <strong>🐍 Programming:</strong> Python 3.8+, Jupyter Notebooks, scikit-learn, pandas, numpy
        </div>
    </div>

    <div class="ml-course-section" id="prerequisite">
        <h2>⚡ Prerequisites</h2>
        <div class="ml-prereq-box">
            <h3>Required Background:</h3>
            <ol>
                <li><strong>Linear Algebra:</strong> MATH 210 or equivalent (matrices, eigenvalues, vector spaces)</li>
                <li><strong>Statistics:</strong> STAT 381 or equivalent (probability distributions, hypothesis testing)</li>
                <li><strong>Programming:</strong> Solid Python experience with data structures and algorithms</li>
                <li><strong>Calculus:</strong> Multivariable calculus for optimization concepts</li>
            </ol>
        </div>
    </div>

    <div class="ml-course-section" id="logistics">
        <h2>🎯 Course Logistics</h2>
        <p><strong>📍 Location:</strong> Science & Engineering Offices (SEO) 1000</p>
        <p><strong>⏰ Schedule:</strong> Tuesday & Thursday, 2:00 PM - 3:15 PM</p>
        <p><strong>👨‍🏫 Office Hours:</strong> Wednesdays 1:00-3:00 PM or by appointment</p>
        <p><strong>📧 Contact:</strong> Questions via Blackboard discussion forum preferred</p>
    </div>
</div>
