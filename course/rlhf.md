---
layout: splash
title: "RLHF for AI-Alignment"
date: 2025-08-25
permalink: /course/rlhf/
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
  <h2 style="color:DarkBlue;">CS 594: RLHF Theory for AI-Alignment and Fine-Tuning LLMs (Fall, 2025)</h2>
  <div style="font-size: 1.05em; color: #003366; margin-bottom: 30px; line-height: 1.6;">
  <div>
    <span style="font-weight: normal;">📡 •Instructor:</span>
    <span style="color:#2a52be; font-weight:bold;">Aadirupa Saha</span>
  </div>
  </div>

<h3> ---------- This website is under construction ---------- </h3>
  
  <div class="tab">
    <button class="tablinks" onclick="openTab(event, 'Schedule')">Schedule</button>
    <button class="tablinks" onclick="openTab(event, 'Description')">Description</button>
    <button class="tablinks" onclick="openTab(event, 'Prerequisites')">Prerequisites</button>
    <button class="tablinks" onclick="openTab(event, 'Grading')">Grading</button>
    <button class="tablinks" onclick="openTab(event, 'Resources')">Resources</button>
    <button class="tablinks" onclick="openTab(event, 'Logistics')">Logistics</button>
  </div>

  <div id="Schedule" class="tabcontent">
    <h2>📅 Course Schedule (NOT FINALIZED)</h2>
    <table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <th>Date</th>
    <th>Topic</th>
    <th>Reading</th>
    <th>Materials</th>
    <th>Notes</th>
    <th>Top-3 Paper Recommendation</th>
  </tr>
  <tr>
    <td>Aug 26</td>
    <td>Introduction<br>Basics of AI-Alignment</td>
    <td></td><td></td><td></td><td></td>
  </tr>
  <tr>
    <td>Aug 28</td>
    <td>Concentration Bounds MAB</td>
    <td></td><td></td><td></td><td></td>
  </tr>
  <tr>
    <td>Sep 2</td>
    <td>UCB Algorithm</td>
    <td></td><td></td><td></td><td></td>
  </tr>
  <tr>
    <td>Sep 4</td>
    <td>Online Mirror Descent </td>
    <td></td><td></td><td></td><td></td>
  </tr>
  <tr>
    <td>Sep 9</td>
    <td>Linear Bandits</td>
    <td></td><td></td><td></td><td></td>
  </tr>
  <tr>
    <td>Sep 11</td>
    <td>Paper presentation</td>
    <td></td><td></td><td></td>
    <td>
      <ul>
        <li>Heavy-tailed bandits</li>
        <li>Bandits with side info</li>
        <li>Bandits with budgets</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>Sep 16</td>
    <td>Linear Bandits (contd)</td>
    <td></td><td></td><td></td><td></td>
  </tr>
  <tr>
    <td>Sep 18</td>
    <td>Dueling Bandits: Learning from Preferences</td>
    <td></td><td></td><td></td><td></td>
  </tr>
  <tr>
    <td>Sep 23</td>
    <td>Paper presentation</td>
    <td></td><td></td><td></td>
    <td>
      <ul>
        <li>Beyond Linear Bandits: Kernel Bandits</li>
        <li>Lipschitz bandits</li>
        <li>Neural Bandits</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>Sep 25</td>
    <td>Paper presentation</td>
    <td></td><td></td><td></td>
    <td>
      <ul>
        <li>MNL Bandits</li>
        <li>Dynamic Bandits</li>
        <li>Sleeping Bandits</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>Sep 30</td>
    <td>Dueling Bandits (contd)</td>
    <td></td><td></td><td></td><td></td>
  </tr>
  <tr>
    <td>Oct 2</td>
    <td>Paper presentation</td>
    <td></td><td></td><td></td>
    <td>
      <ul>
        <li>Robust DB</li>
        <li>Fair DB</li>
        <li>DB with correlated preferences</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>Oct 7</td>
    <td>Contextual Bandits: EXP4 (1 step RL)</td>
    <td></td><td></td><td></td><td></td>
  </tr>
  <tr>
    <td>Oct 9</td>
    <td>Paper presentation</td>
    <td></td><td></td><td></td><td></td>
  </tr>
  <tr>
    <td>Oct 14</td>
    <td>Contextual MAB (contd)</td>
    <td></td><td></td><td></td><td></td>
  </tr>
  <tr>
    <td>Oct 16</td>
    <td>Contextual - Dueling Bandits</td>
    <td></td><td></td><td></td><td></td>
  </tr>
  <tr>
    <td>Oct 21</td>
    <td>Intro to RL + MDP Basics</td>
    <td></td><td></td><td></td><td></td>
  </tr>
  <tr>
    <td>Oct 23</td>
    <td>Tabular MDP-UCB-VI</td>
    <td></td><td></td><td></td><td></td>
  </tr>
  <tr>
    <td>Oct 28</td>
    <td>Paper presentation</td>
    <td></td><td></td><td></td><td></td>
  </tr>
  <tr>
    <td>Oct 30</td>
    <td colspan="5" style="text-align:center;">—-- Happy Halloween! —--</td>
  </tr>
  <tr>
    <td>Nov 4</td>
    <td>Linear function approximation</td>
    <td></td><td></td><td></td><td></td>
  </tr>
  <tr>
    <td>Nov 6</td>
    <td>PG Methods</td>
    <td></td><td></td><td></td><td></td>
  </tr>
  <tr>
    <td>Nov 11</td>
    <td>PPO + TRPO</td>
    <td></td><td></td><td></td><td></td>
  </tr>
  <tr>
    <td>Nov 13</td>
    <td>Paper presentation</td>
    <td></td><td></td><td></td><td></td>
  </tr>
  <tr>
    <td>Nov 18</td>
    <td>Imitation Learning</td>
    <td></td><td></td><td></td><td></td>
  </tr>
  <tr>
    <td>Nov 20</td>
    <td>Paper presentation</td>
    <td></td><td></td><td></td><td></td>
  </tr>
  <tr>
    <td>Nov 25</td>
    <td>Presentation (20 mins/ team)</td>
    <td></td><td></td><td></td><td></td>
  </tr>
  <tr>
    <td>Nov 27</td>
    <td colspan="5" style="text-align:center;">—-- Thanksgiving Break! —--</td>
  </tr>
  <tr>
    <td>Dec 2</td>
    <td>Presentation (20 mins/ team)</td>
    <td></td><td></td><td></td><td></td>
  </tr>
  <tr>
    <td>Dec 4</td>
    <td>Presentation (20 mins/ team)</td>
    <td></td><td></td><td></td><td></td>
  </tr>
</table>

  </div>

  <div id="Description" class="tabcontent">
    <h2>📚 Course Description (Tentitive) </h2>
    
    <section id="overview">
      <h2>Overview</h2>
      <p style="text-align: justify;">
        This course aims to provide a rigorous mathematical foundation for understanding and implementing
        Reinforcement Learning from Human Feedback (RLHF). The curriculum is structured around interconnected modules that progress from
        theoretical foundations to practical implementation.
      </p>
    </section>

    <section id="modules">
      <h2>Modules</h2>

      <article id="alignment-formalization">
        <h3>Topics Set 1: Formalizing the Alignment Problem</h3>
        <p>
          Establishes the conceptual framework for AI alignment, examining outer versus inner alignment, reward
          misspecification, and Goodhart’s Law in human feedback systems. Students analyze real-world failure
          modes and develop intuition for how alignment can degrade in deployed systems.
        </p>
      </article>

      <article id="evaluation-verification">
        <h3>Topics Set 2: Evaluation &amp; Alignment Verification</h3>
        <p>
          Addresses measuring alignment beyond simple reward maximization, covering multi-dimensional evaluation
          frameworks (HHH: Helpfulness, Harmlessness, Honesty), human evaluation pipeline design, adversarial
          testing, and robustness verification techniques are essential for production deployment.
        </p>
      </article>

      <article id="rl-theory">
        <h3>Topics Set 3: Reinforcement Learning Theory</h3>
        <p>
          Provides the mathematical foundations underlying RLHF algorithms. Beginning with MDP fundamentals and
          Bellman equations, the module progresses through policy gradient methods, exploration strategies in
          tabular and linear settings, and advanced topics including low-rank MDPs and uniform convergence theory.
          Students master both classical results and recent theoretical developments.
        </p>
      </article>

      <article id="rlhf-theory-practice">
        <h3>Topics Set 4: RLHF Theory and Practice</h3>
        <p>
          Synthesizes preference learning, contextual bandits, and human-in-the-loop optimization. Topics include
          active learning for efficient feedback collection, handling noisy and biased human inputs, integrating
          multiple feedback sources, and maintaining safety and robustness guarantees throughout the pipeline.
        </p>
      </article>

      <article id="llm-theory">
        <h3>Topics Set 5: Large Language Model Theory</h3>
        <p>
          Bridges abstract RL theory and practical LLM deployment. Covers transformer architectures, fine-tuning
          methodologies, parameter-efficient adaptation (LoRA, adapters), preference modeling for reward extraction,
          and specialized RL algorithms (e.g., PPO with KL regularization) tailored to language model optimization.
        </p>
      </article>
    </section>

    <section id="prerequisites">
      <h2>Prerequisites</h2>
      <p>
        This course demands strong mathematical maturity and technical proficiency.
        <strong>Advanced linear algebra</strong> and <strong>probability theory</strong> are essential (matrix analysis,
        eigendecompositions, concentration inequalities, stochastic processes). Knowledge of
        <strong>machine learning theory</strong> (optimization, generalization bounds, statistical learning theory) is
        required.
      </p>
      <p>
        Programming competency in <strong>Python</strong> is required (PyTorch or similar recommended), and
        <strong>LaTeX proficiency</strong> is mandatory for assignments and the final project. The theoretical content
        assumes familiarity with measure theory, basics of functional analysis, and advanced calculus. Students unsure
        about preparation should complete prerequisite coursework before enrolling.
      </p>
    </section>

    <section id="outcomes">
      <h2>Learning Outcomes</h2>
      <p>
        Graduates will understand the mathematical principles governing preference learning, design and evaluate
        alignment verification systems, and implement production-grade RLHF pipelines. The course prepares students for
        advanced research roles in AI labs, senior engineering roles deploying large language models, and independent
        research in AI alignment. Students will be equipped to drive innovation, lead technical teams, and contribute to
        the theoretical and practical advances shaping the future of safe AI deployment.
      </p>
    </section>
    
    
  </div>

  <div id="Prerequisites" class="tabcontent">
    <h2>⚠️ Prerequisites</h2>
    <p style="text-align: justify;">Expect this to be a fairly <strong>math intensive</strong> course. Please familiarize yourself with the basics of Probability-Statistics (PS) and Linear-Algebra (LA). Recommended introductory lectures to check if you are comfortable with the basics:</p>
    
   <ul>
  <li><strong>PS review:</strong>
    <ol>
      <li><a href="https://cs229.stanford.edu/section/cs229-prob.pdf">Stanford CS229 Probability Review</a></li>
      <li><a href="https://www2.isye.gatech.edu/~sman/courses/6761/6761-1-ProbReview.pdf">Georgia Tech Probability Review</a></li>
      <li><a href="https://users.ssc.wisc.edu/~ctaber/410/statrev.pdf">UW Madison Probability Review Notes</a></li>
    </ol>
  </li>
  <li><strong>LA review:</strong>
    <ol>
      <li><a href="https://cs229.stanford.edu/section/cs229-linalg.pdf">Stanford CS229 Linear Algebra Review</a></li>
      <li><a href="https://james-chuang.github.io/notes/linalg_review.pdf">Linear Algebra Review Notes (James Chuang)</a></li>
      <li><a href="https://www.cs.cmu.edu/~jingx/docs/linearalgebra.pdf">CMU Linear Algebra Review Notes</a></li>
    </ol>
  </li>
</ul>
    
    <p style="text-align: justify;"><strong>Familiarity with LaTeX for scientific writing</strong> for scribing the lecture notes (only for MS students). You can learn the basics from <a href="https://www.youtube.com/watch?v=lgiCpA4zzGU">A Simple Quickstart Guide</a>. Many other online tutorials are available for beginners — feel free to explore and use whichever best suits your needs.</p>
    
    <p style="text-align: justify;"><strong>Programming (Experiments) </strong> (in Python). Be prepared to code: <a href="https://www.youtube.com/playlist?list=PLzMcBGfZo4-mP7qA9cagf68V06sko5otr">[Python ML Tutorials]</a>, <a href="https://colab.research.google.com/github/cs231n/cs231n.github.io/blob/master/python-colab.ipynb#scrollTo=dzNng6vCL9eP">[Google Colab]</a> (many online tutorials available for beginners).</p>
    
    <p style="text-align: justify;">A strong grasp of the foundational material outlined above is expected of all students taking the course for credit. Insufficient preparation may adversely affect your ability to engage with the course content and perform successfully in assessments, which may impact your final grades.</p>
 
  </div>

  <div id="Grading" class="tabcontent">
    <h2>🏆 Grading Policy</h2>
    <ul>
     <li>
                <strong style="color: #1565c0;">Project + Report:</strong> <span style="background: #e3f2fd; color: #1565c0; padding: 0.2rem 0.5rem; border-radius: 6px; font-weight: 600;">20%</span>
                <div style="margin-top: 0.5rem; padding-left: 1rem; border-left: 2px solid #e3f2fd;">
                    <span style="color: #666; font-size: 0.9rem;">
                        Problem selection + Motivation <span style="background: #f5f5f5; color: #666; padding: 0.1rem 0.4rem; border-radius: 3px; font-weight: 500;">5%</span> • 
                        Solution <span style="background: #f5f5f5; color: #666; padding: 0.1rem 0.4rem; border-radius: 3px; font-weight: 500;">10%</span> • 
                        Experiments 
                        <span style="background: #f5f5f5; color: #666; padding: 0.1rem 0.4rem; border-radius: 3px; font-weight: 500;"> 
                          <span style="background: #4caf50; color: white; padding: 0.3rem 0.7rem; border-radius: 4px; font-size: 0.85rem; font-weight: 600; margin-left: 0.5rem;"> +5% extra credit</span>
                        </span>
                    </span>
                </div>
            </li>
            <li>
                <strong style="color: #1565c0;">Paper Presentation + Coding:</strong> <span style="background: #e3f2fd; color: #1565c0; padding: 0.2rem 0.5rem; border-radius: 6px; font-weight: 600;">15%</span>
                <div style="margin-top: 0.5rem; padding-left: 1rem; border-left: 2px solid #e3f2fd;">
                    <span style="color: #666; font-size: 0.9rem;">
                        Work Motivation <span style="background: #f5f5f5; color: #666; padding: 0.1rem 0.4rem; border-radius: 3px; font-weight: 500;">5%</span> • 
                        Theoretical explanation <span style="background: #f5f5f5; color: #666; padding: 0.1rem 0.4rem; border-radius: 3px; font-weight: 500;">10%</span> • 
                        Experiments <span style="background: #f5f5f5; color: #666; padding: 0.1rem 0.4rem; border-radius: 3px; font-weight: 500;">5%</span>
                    </span>
                </div>
            </li>
            <li>
                <strong style="color: #1565c0;">Scribe:</strong> <span style="background: #e3f2fd; color: #1565c0; padding: 0.2rem 0.5rem; border-radius: 6px; font-weight: 600;">15%</span>
                <div style="margin-top: 0.5rem; padding-left: 1rem; border-left: 2px solid #e3f2fd;">
                    <span style="color: #666; font-size: 0.9rem;">Approximately 2 lectures</span>
                </div>
            </li>
            <li>
                <strong style="color: #1565c0;">Piazza-Weekly Problem:</strong> <span style="background: #e3f2fd; color: #1565c0; padding: 0.2rem 0.5rem; border-radius: 6px; font-weight: 600;">10%</span>
              <span style="background: #4caf50; color: white; padding: 0.3rem 0.7rem; border-radius: 4px; font-size: 0.85rem; font-weight: 600; margin-left: 0.5rem;"> +5% extra credit</span>
              <div style="margin-top: 0.5rem; padding-left: 1rem; border-left: 2px solid #e3f2fd;">
                    <span style="color: #666; font-size: 0.9rem;">Post a new unresolved problem per week (with motivation based), on that week's lectures</span>
                </div>
            </li>
            <li>
                <strong style="color: #1565c0;">Piazza-Weekly Paper:</strong> <span style="background: #e3f2fd; color: #1565c0; padding: 0.2rem 0.5rem; border-radius: 6px; font-weight: 600;">15%</span>
                <span style="background: #4caf50; color: white; padding: 0.3rem 0.7rem; border-radius: 4px; font-size: 0.85rem; font-weight: 600; margin-left: 0.5rem;"> +5% extra credit</span>
                <div style="margin-top: 0.5rem; padding-left: 1rem; border-left: 2px solid #e3f2fd;">
                    <span style="color: #666; font-size: 0.9rem;">Find a related paper per week based on the topics covered in that week</span>
                </div>
            </li>
            <li>
                <strong style="color: #1565c0;">Class Participation:</strong> <span style="background: #e3f2fd; color: #1565c0; padding: 0.2rem 0.5rem; border-radius: 6px; font-weight: 600;">15%</span>
                <span style="background: #4caf50; color: white; padding: 0.3rem 0.7rem; border-radius: 4px; font-size: 0.85rem; font-weight: 600; margin-left: 0.5rem;"> +5% extra credit</span>
                <div style="margin-top: 0.5rem; padding-left: 1rem; border-left: 2px solid #e3f2fd;">
                    <span style="color: #666; font-size: 0.9rem;">
                        Lecture questions/answers <span style="background: #f5f5f5; color: #666; padding: 0.1rem 0.4rem; border-radius: 3px; font-weight: 500;">5%</span> • 
                        Presentation questions <span style="background: #f5f5f5; color: #666; padding: 0.1rem 0.4rem; border-radius: 3px; font-weight: 500;">5%</span>
                    </span>
                </div>
            </li>
            <li>
                <strong style="color: #1565c0;">Quiz:</strong> <span style="background: #e3f2fd; color: #1565c0; padding: 0.2rem 0.5rem; border-radius: 6px; font-weight: 600;">10%</span>
                <div style="margin-top: 0.5rem; padding-left: 1rem; border-left: 2px solid #e3f2fd;">
                    <span style="color: #666; font-size: 0.9rem;">Random quizzes</span>
                </div>
            </li>
    </ul>
  </div>

  <div id="Resources" class="tabcontent">
    <h2>📖 Resources</h2>
    <p>Class lecture will be based on, but not limited to, the following books:</p>
    
    <ul>
          <li>
            <strong>[SB] </strong>
            <a href="https://www.andrew.cmu.edu/course/10-703/textbook/BartoSutton.pdf" target="_blank">
              Reinforcement Learning: An Introduction</a> by Sutton & Barto
          </li>
          <li>
            <strong>[SL] </strong>
            <a href="https://tor-lattimore.com/downloads/book/book.pdf" target="_blank">
              Bandit Algorithms</a> by Szepesvari & Lattimore
          </li>
          <li>
            <strong>[PG] </strong>
            <a href="http://pierre.gaillard.me/doc/teaching/online_learning_lecture_notes.pdf" target="_blank">
              Online Learning Notes</a> by Pierre Gaillard
          </li>
          <li>
            <strong>[FO] </strong>
            <a href="https://arxiv.org/abs/1912.13213" target="_blank">
              A Modern Introduction to Online Learning</a> by Francesco Orabona
          </li>
          <li>
            <strong>[THK] </strong>
            <a href="https://mlhp.stanford.edu/" target="_blank">
              Reinforcement Learning: An Introduction</a> by Truong, Haupt, Koyejo
          </li>
          <li>
            <strong>[RLM] </strong>
            <a href="https://rltheorybook.github.io/rltheorybook_AJKS.pdf" target="_blank">
              RL: Theory & Algorithms</a> by Agarwal, Jiang, Kakade, Sun
          </li>
          <li>
          <strong>[FRL] </strong>
          <a href="https://arxiv.org/abs/2312.16730" target="_blank">
            Foundations of Reinforcement Learning and Interactive Decision Making</a> by Foster & Rakhlin
          </li>

    
    </ul>
  </div>

  <div id="Logistics" class="tabcontent">
    <h2>🎯 Course Logistics</h2>
    <ul>
      <li><strong>📍 Location:</strong> CDRLC </li>
      <li><strong>⏰ Schedule:</strong> Tuesday & Thursday, 2:00 - 3:15 PM</li>
      <li><strong>🏛️ Office Hours:</strong> Thurdays 5:00–6:00 PM or by appointment</li>
      <li><strong>📧 Piazza:</strong> <a href="https://piazza.com/uic/fall2025/cs_594" target="_blank">CS_594</a> [Only Creditors!] </li>
    </ul>

    <h2>📌 Important Dates</h2>
    <ul>
      <li><strong>Select Project Topic:</strong> Oct 3rd, 2025 </li>
      <li><strong>Project Presentation:</strong> Nov 25th, Dec 2nd, Dec 4th, 2025 </li>
      <li><strong>Project Report:</strong> Dec 6th, 2025 </li>
    </ul>
    
  </div>

  <script>
    document.getElementsByClassName('tablinks')[0].click(); // Open first tab by default
  </script>
</body>
</html>







