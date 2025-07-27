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

<!-- Course content without any CSS - let your site's default styles handle navigation -->
<div class="course-header" style="background: linear-gradient(135deg, #1565c0 0%, #1976d2 50%, #42a5f5 100%); color: white; padding: 3rem 2rem; text-align: center; position: relative; overflow: hidden; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;">
    <h1 style="font-size: 2.8rem; font-weight: 700; margin-bottom: 0.5rem; text-shadow: 0 2px 4px rgba(0,0,0,0.2); color: white;">CS 412: Intro to Machine Learning</h1>
    <p style="font-size: 1.3rem; font-weight: 300; opacity: 0.95; color: white;">Spring 2025, University of Illinois Chicago</p>
</div>

<div style="background: linear-gradient(to right, #ffffff 0%, #f8f9fa 100%); padding: 1.2rem 0; box-shadow: 0 4px 12px rgba(0,0,0,0.08); border-bottom: 3px solid #e3f2fd;">
    <div style="max-width: 1200px; margin: 0 auto; display: flex; justify-content: center; gap: 2rem; flex-wrap: wrap; padding: 0 2rem;">
        <a href="#description" style="color: #1565c0; text-decoration: none; font-weight: 600; padding: 0.8rem 1.5rem; border-radius: 25px; transition: all 0.3s ease; background: rgba(21, 101, 192, 0.05); border: 2px solid transparent; display: inline-block;"
           onmouseover="this.style.background='linear-gradient(135deg, #1565c0, #1976d2)'; this.style.color='white'; this.style.transform='translateY(-2px)'; this.style.boxShadow='0 4px 12px rgba(21, 101, 192, 0.3)';"
           onmouseout="this.style.background='rgba(21, 101, 192, 0.05)'; this.style.color='#1565c0'; this.style.transform='none'; this.style.boxShadow='none';">Description</a>
        
        <a href="#schedule" style="color: #1565c0; text-decoration: none; font-weight: 600; padding: 0.8rem 1.5rem; border-radius: 25px; transition: all 0.3s ease; background: rgba(21, 101, 192, 0.05); border: 2px solid transparent; display: inline-block;"
           onmouseover="this.style.background='linear-gradient(135deg, #1565c0, #1976d2)'; this.style.color='white'; this.style.transform='translateY(-2px)'; this.style.boxShadow='0 4px 12px rgba(21, 101, 192, 0.3)';"
           onmouseout="this.style.background='rgba(21, 101, 192, 0.05)'; this.style.color='#1565c0'; this.style.transform='none'; this.style.boxShadow='none';">Schedule</a>
        
        <a href="#resources" style="color: #1565c0; text-decoration: none; font-weight: 600; padding: 0.8rem 1.5rem; border-radius: 25px; transition: all 0.3s ease; background: rgba(21, 101, 192, 0.05); border: 2px solid transparent; display: inline-block;"
           onmouseover="this.style.background='linear-gradient(135deg, #1565c0, #1976d2)'; this.style.color='white'; this.style.transform='translateY(-2px)'; this.style.boxShadow='0 4px 12px rgba(21, 101, 192, 0.3)';"
           onmouseout="this.style.background='rgba(21, 101, 192, 0.05)'; this.style.color='#1565c0'; this.style.transform='none'; this.style.boxShadow='none';">Resources</a>
        
        <a href="#prerequisite" style="color: #1565c0; text-decoration: none; font-weight: 600; padding: 0.8rem 1.5rem; border-radius: 25px; transition: all 0.3s ease; background: rgba(21, 101, 192, 0.05); border: 2px solid transparent; display: inline-block;"
           onmouseover="this.style.background='linear-gradient(135deg, #1565c0, #1976d2)'; this.style.color='white'; this.style.transform='translateY(-2px)'; this.style.boxShadow='0 4px 12px rgba(21, 101, 192, 0.3)';"
           onmouseout="this.style.background='rgba(21, 101, 192, 0.05)'; this.style.color='#1565c0'; this.style.transform='none'; this.style.boxShadow='none';">Prerequisites</a>
        
        <a href="#logistics" style="color: #1565c0; text-decoration: none; font-weight: 600; padding: 0.8rem 1.5rem; border-radius: 25px; transition: all 0.3s ease; background: rgba(21, 101, 192, 0.05); border: 2px solid transparent; display: inline-block;"
           onmouseover="this.style.background='linear-gradient(135deg, #1565c0, #1976d2)'; this.style.color='white'; this.style.transform='translateY(-2px)'; this.style.boxShadow='0 4px 12px rgba(21, 101, 192, 0.3)';"
           onmouseout="this.style.background='rgba(21, 101, 192, 0.05)'; this.style.color='#1565c0'; this.style.transform='none'; this.style.boxShadow='none';">Logistics</a>
    </div>
</div>

<div style="max-width: 1200px; margin: 0 auto; padding: 2rem; background: linear-gradient(to bottom, #f8f9fa 0%, #ffffff 100%); min-height: 50vh;">
    
    <div id="description" style="background: linear-gradient(135deg, #ffffff 0%, #f8f9fa 100%); margin-bottom: 2.5rem; padding: 2.5rem; border-radius: 16px; box-shadow: 0 8px 25px rgba(0,0,0,0.08); border: 1px solid rgba(21, 101, 192, 0.1); position: relative; overflow: hidden; border-top: 4px solid #1565c0;">
        <h2 style="color: #1565c0; font-size: 2rem; font-weight: 700; margin-bottom: 1.5rem; padding-bottom: 0.8rem; border-bottom: 2px solid rgba(66, 165, 245, 0.3);">📚 Course Description</h2>
        <p style="margin-bottom: 1rem; color: #424242; font-size: 1rem; line-height: 1.7;">This course provides a comprehensive introduction to machine learning concepts, algorithms, and applications. Students will explore supervised and unsupervised learning techniques, neural networks, and real-world implementations using Python and popular ML libraries.</p>
    </div>

    <div id="schedule" style="background: linear-gradient(135deg, #ffffff 0%, #f8f9fa 100%); margin-bottom: 2.5rem; padding: 2.5rem; border-radius: 16px; box-shadow: 0 8px 25px rgba(0,0,0,0.08); border: 1px solid rgba(21, 101, 192, 0.1); position: relative; overflow: hidden; border-top: 4px solid #1565c0;">
        <h2 style="color: #1565c0; font-size: 2rem; font-weight: 700; margin-bottom: 1.5rem; padding-bottom: 0.8rem; border-bottom: 2px solid rgba(66, 165, 245, 0.3);">📅 Course Schedule</h2>
        <table style="width: 100%; border-collapse: collapse; margin-top: 1.5rem; background: white; border-radius: 12px; overflow: hidden; box-shadow: 0 4px 15px rgba(0,0,0,0.08);">
            <thead>
                <tr>
                    <th style="background: linear-gradient(135deg, #1565c0 0%, #1976d2 100%); color: white; padding: 1.2rem 1rem; text-align: left; font-weight: 600; font-size: 0.9rem; text-transform: uppercase; letter-spacing: 1px;">Date</th>
                    <th style="background: linear-gradient(135deg, #1565c0 0%, #1976d2 100%); color: white; padding: 1.2rem 1rem; text-align: left; font-weight: 600; font-size: 0.9rem; text-transform: uppercase; letter-spacing: 1px;">Topic</th>
                    <th style="background: linear-gradient(135deg, #1565c0 0%, #1976d2 100%); color: white; padding: 1.2rem 1rem; text-align: left; font-weight: 600; font-size: 0.9rem; text-transform: uppercase; letter-spacing: 1px;">Reading</th>
                    <th style="background: linear-gradient(135deg, #1565c0 0%, #1976d2 100%); color: white; padding: 1.2rem 1rem; text-align: left; font-weight: 600; font-size: 0.9rem; text-transform: uppercase; letter-spacing: 1px;">Materials</th>
                    <th style="background: linear-gradient(135deg, #1565c0 0%, #1976d2 100%); color: white; padding: 1.2rem 1rem; text-align: left; font-weight: 600; font-size: 0.9rem; text-transform: uppercase; letter-spacing: 1px;">Assignment</th>
                    <th style="background: linear-gradient(135deg, #1565c0 0%, #1976d2 100%); color: white; padding: 1.2rem 1rem; text-align: left; font-weight: 600; font-size: 0.9rem; text-transform: uppercase; letter-spacing: 1px;">Notes</th>
                </tr>
            </thead>
            <tbody>
                <tr style="background: rgba(248, 249, 250, 0.7);" onmouseover="this.style.background='linear-gradient(135deg, rgba(66, 165, 245, 0.05) 0%, rgba(25, 118, 210, 0.05) 100%)'" onmouseout="this.style.background='rgba(248, 249, 250, 0.7)'">
                    <td style="padding: 1.2rem 1rem; border-bottom: 1px solid rgba(66, 165, 245, 0.1); font-size: 0.95rem;"><strong>Jan 14</strong></td>
                    <td style="padding: 1.2rem 1rem; border-bottom: 1px solid rgba(66, 165, 245, 0.1); font-size: 0.95rem;">Course Introduction<br><em>What is Machine Learning?</em></td>
                    <td style="padding: 1.2rem 1rem; border-bottom: 1px solid rgba(66, 165, 245, 0.1); font-size: 0.95rem;">Chapter 1</td>
                    <td style="padding: 1.2rem 1rem; border-bottom: 1px solid rgba(66, 165, 245, 0.1); font-size: 0.95rem;">
                        <a href="#" style="color: #1565c0; text-decoration: none; font-weight: 500; padding: 0.3rem 0.8rem; border-radius: 15px; background: rgba(66, 165, 245, 0.1); display: inline-block;"
                           onmouseover="this.style.background='linear-gradient(135deg, #1565c0, #1976d2)'; this.style.color='white'; this.style.transform='translateY(-1px)'; this.style.boxShadow='0 2px 8px rgba(21, 101, 192, 0.3)';"
                           onmouseout="this.style.background='rgba(66, 165, 245, 0.1)'; this.style.color='#1565c0'; this.style.transform='none'; this.style.boxShadow='none';">📊 Slides 1</a>
                    </td>
                    <td style="padding: 1.2rem 1rem; border-bottom: 1px solid rgba(66, 165, 245, 0.1); font-size: 0.95rem;">-</td>
                    <td style="padding: 1.2rem 1rem; border-bottom: 1px solid rgba(66, 165, 245, 0.1); font-size: 0.95rem;">First class</td>
                </tr>
                <tr onmouseover="this.style.background='linear-gradient(135deg, rgba(66, 165, 245, 0.05) 0%, rgba(25, 118, 210, 0.05) 100%)'" onmouseout="this.style.background='white'">
                    <td style="padding: 1.2rem 1rem; border-bottom: 1px solid rgba(66, 165, 245, 0.1); font-size: 0.95rem;"><strong>Jan 16</strong></td>
                    <td style="padding: 1.2rem 1rem; border-bottom: 1px solid rgba(66, 165, 245, 0.1); font-size: 0.95rem;">Linear Regression<br><em>Fundamentals & Implementation</em></td>
                    <td style="padding: 1.2rem 1rem; border-bottom: 1px solid rgba(66, 165, 245, 0.1); font-size: 0.95rem;">Chapter 2</td>
                    <td style="padding: 1.2rem 1rem; border-bottom: 1px solid rgba(66, 165, 245, 0.1); font-size: 0.95rem;">
                        <a href="#" style="color: #1565c0; text-decoration: none; font-weight: 500; padding: 0.3rem 0.8rem; border-radius: 15px; background: rgba(66, 165, 245, 0.1); display: inline-block;"
                           onmouseover="this.style.background='linear-gradient(135deg, #1565c0, #1976d2)'; this.style.color='white'; this.style.transform='translateY(-1px)'; this.style.boxShadow='0 2px 8px rgba(21, 101, 192, 0.3)';"
                           onmouseout="this.style.background='rgba(66, 165, 245, 0.1)'; this.style.color='#1565c0'; this.style.transform='none'; this.style.boxShadow='none';">📊 Slides 2</a>
                    </td>
                    <td style="padding: 1.2rem 1rem; border-bottom: 1px solid rgba(66, 165, 245, 0.1); font-size: 0.95rem;">
                        <a href="#" style="color: #1565c0; text-decoration: none; font-weight: 500; padding: 0.3rem 0.8rem; border-radius: 15px; background: rgba(66, 165, 245, 0.1); display: inline-block;"
                           onmouseover="this.style.background='linear-gradient(135deg, #1565c0, #1976d2)'; this.style.color='white'; this.style.transform='translateY(-1px)'; this.style.boxShadow='0 2px 8px rgba(21, 101, 192, 0.3)';"
                           onmouseout="this.style.background='rgba(66, 165, 245, 0.1)'; this.style.color='#1565c0'; this.style.transform='none'; this.style.boxShadow='none';">📝 HW1</a>
                    </td>
                    <td style="padding: 1.2rem 1rem; border-bottom: 1px solid rgba(66, 165, 245, 0.1); font-size: 0.95rem;">Python setup required</td>
                </tr>
            </tbody>
        </table>
    </div>

    <div id="resources" style="background: linear-gradient(135deg, #ffffff 0%, #f8f9fa 100%); margin-bottom: 2.5rem; padding: 2.5rem; border-radius: 16px; box-shadow: 0 8px 25px rgba(0,0,0,0.08); border: 1px solid rgba(21, 101, 192, 0.1); position: relative; overflow: hidden; border-top: 4px solid #1565c0;">
        <h2 style="color: #1565c0; font-size: 2rem; font-weight: 700; margin-bottom: 1.5rem; padding-bottom: 0.8rem; border-bottom: 2px solid rgba(66, 165, 245, 0.3);">📖 Resources</h2>
        <div style="background: linear-gradient(135deg, #e8f5e8 0%, #c8e6c9 100%); padding: 1.5rem; margin-bottom: 1rem; border-radius: 12px; border-left: 5px solid #4caf50; box-shadow: 0 3px 10px rgba(76, 175, 80, 0.1);">
            <strong style="color: #2e7d32; font-weight: 700;">📚 Primary Textbook:</strong> Pattern Recognition and Machine Learning by Christopher Bishop
        </div>
        <div style="background: linear-gradient(135deg, #e8f5e8 0%, #c8e6c9 100%); padding: 1.5rem; margin-bottom: 1rem; border-radius: 12px; border-left: 5px solid #4caf50; box-shadow: 0 3px 10px rgba(76, 175, 80, 0.1);">
            <strong style="color: #2e7d32; font-weight: 700;">💻 Online Platform:</strong> Course materials and submissions via Blackboard
        </div>
        <div style="background: linear-gradient(135deg, #e8f5e8 0%, #c8e6c9 100%); padding: 1.5rem; margin-bottom: 1rem; border-radius: 12px; border-left: 5px solid #4caf50; box-shadow: 0 3px 10px rgba(76, 175, 80, 0.1);">
            <strong style="color: #2e7d32; font-weight: 700;">🐍 Programming:</strong> Python 3.8+, Jupyter Notebooks, scikit-learn, pandas, numpy
        </div>
    </div>

    <div id="prerequisite" style="background: linear-gradient(135deg, #ffffff 0%, #f8f9fa 100%); margin-bottom: 2.5rem; padding: 2.5rem; border-radius: 16px; box-shadow: 0 8px 25px rgba(0,0,0,0.08); border: 1px solid rgba(21, 101, 192, 0.1); position: relative; overflow: hidden; border-top: 4px solid #1565c0;">
        <h2 style="color: #1565c0; font-size: 2rem; font-weight: 700; margin-bottom: 1.5rem; padding-bottom: 0.8rem; border-bottom: 2px solid rgba(66, 165, 245, 0.3);">⚡ Prerequisites</h2>
        <div style="background: linear-gradient(135deg, #fff3e0 0%, #ffe0b2 100%); padding: 2rem; border-radius: 12px; border-left: 5px solid #ff9800; margin-bottom: 1.5rem; box-shadow: 0 4px 12px rgba(255, 152, 0, 0.1);">
            <h3 style="color: #e65100; margin-bottom: 1rem; font-weight: 600;">Required Background:</h3>
            <ol style="padding-left: 1.5rem;">
                <li style="margin-bottom: 0.8rem; color: #424242; line-height: 1.6;"><strong>Linear Algebra:</strong> MATH 210 or equivalent (matrices, eigenvalues, vector spaces)</li>
                <li style="margin-bottom: 0.8rem; color: #424242; line-height: 1.6;"><strong>Statistics:</strong> STAT 381 or equivalent (probability distributions, hypothesis testing)</li>
                <li style="margin-bottom: 0.8rem; color: #424242; line-height: 1.6;"><strong>Programming:</strong> Solid Python experience with data structures and algorithms</li>
                <li style="margin-bottom: 0.8rem; color: #424242; line-height: 1.6;"><strong>Calculus:</strong> Multivariable calculus for optimization concepts</li>
            </ol>
        </div>
    </div>

    <div id="logistics" style="background: linear-gradient(135deg, #ffffff 0%, #f8f9fa 100%); margin-bottom: 2.5rem; padding: 2.5rem; border-radius: 16px; box-shadow: 0 8px 25px rgba(0,0,0,0.08); border: 1px solid rgba(21, 101, 192, 0.1); position: relative; overflow: hidden; border-top: 4px solid #1565c0;">
        <h2 style="color: #1565c0; font-size: 2rem; font-weight: 700; margin-bottom: 1.5rem; padding-bottom: 0.8rem; border-bottom: 2px solid rgba(66, 165, 245, 0.3);">🎯 Course Logistics</h2>
        <p style="margin-bottom: 1rem; color: #424242; font-size: 1rem; line-height: 1.7;"><strong>📍 Location:</strong> Science & Engineering Offices (SEO) 1000</p>
        <p style="margin-bottom: 1rem; color: #424242; font-size: 1rem; line-height: 1.7;"><strong>⏰ Schedule:</strong> Tuesday & Thursday, 2:00 PM - 3:15 PM</p>
        <p style="margin-bottom: 1rem; color: #424242; font-size: 1rem; line-height: 1.7;"><strong>👨‍🏫 Office Hours:</strong> Wednesdays 1:00-3:00 PM or by appointment</p>
        <p style="margin-bottom: 1rem; color: #424242; font-size: 1rem; line-height: 1.7;"><strong>📧 Contact:</strong> Questions via Blackboard discussion forum preferred</p>
    </div>
</div>
