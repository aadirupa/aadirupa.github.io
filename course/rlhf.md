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

<h3> ---------- Ongoing course: Website is still under develpoment ---------- </h3>
  
  <div class="tab">
    <button class="tablinks" onclick="openTab(event, 'Schedule')">Schedule</button>
    <button class="tablinks" onclick="openTab(event, 'Description')">Description</button>
    <button class="tablinks" onclick="openTab(event, 'Prerequisites')">Prerequisites</button>
    <button class="tablinks" onclick="openTab(event, 'Grading')">Grading</button>
    <button class="tablinks" onclick="openTab(event, 'Resources')">Resources</button>
    <button class="tablinks" onclick="openTab(event, 'Logistics')">Logistics</button>
  </div>

  <div id="Schedule" class="tabcontent">
    <h2>📅 Course Schedule </h2>
    <table border="1" cellspacing="0" cellpadding="5">
  <tr>
      <th>Date</th>
      <th>Topic</th>
      <th>Materials</th>
      <th>Extra</th>
      <th>Announcements</th>
    </tr>
    
    <tr>
      <td>Aug 26</td>
      <td>Introduction <br>Basics of AI-Alignment</td>
      <td><a href="https://arxiv.org/pdf/2310.19852">AI-Alignment Survey</a> [Chap 1.1, 2.1]</td>
      <td></td>
      <td>Piazza up!</td>
    </tr>
    
    <tr>
      <td>Aug 28</td>
      <td>Basics of Stochastic MAB <br>ETC Algorithm</td>
      <td>SL 4.1-4.4, 6.1 <br>PG 5.1, 5.2 <br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fda5ca97e33fd34ae53cc3d4ec4cf9c1cd62abfb7f98d6b849716166b98f1a32e%2FLec1.pdf">note2</a>] <br>[<a href="https://uic.zoom.us/rec/share/HKZDHjGDcgJzag0Ppp-ZMtGF9V35dCEkIh31sKNRNA3A1enzflfbm-tVctA-G43G.j858UHb3C16yL7bm">video2</a>]</td>
      <td>
        <ul>
          <li><a href="https://ilyasergey.net/YSC2229/week-02b_notation.html">Order Notations</a></li>
          <li>Basic Distributions: <a href="http://users.stat.umn.edu/~helwig/notes/ProbabilityDistributions.pdf">[1]</a>, <a href="https://www.colorado.edu/amath/sites/default/files/attached-files/ch3_0.pdf">[2]</a></li>
        </ul>
      </td>
      <td></td>
    </tr>
    
    <tr>
      <td>Sep 2</td>
      <td>ETC Analysis <br>Basic Concentration Inequalities</td>
      <td>SL 4.5, 5.1-5.3, 6.1 <br>PG 5.2</td>
      <td>
        <ul>
          <li><a href="https://ocw.mit.edu/courses/18-s997-high-dimensional-statistics-spring-2015/resources/mit18_s997s15_chapter1/">SubGaussianity</a></li>
          <li><a href="https://cs229.stanford.edu/extra-notes/hoeffding.pdf">Hoeffding's Inequality</a></li>
        </ul>
      </td>
      <td>Instructions for Weekly Posts on Piazza!</td>
    </tr>
    
    <tr>
      <td>Sep 4</td>
      <td>SubGaussianity, Hoeffding's Inequality <br>ETC Analysis (contd)</td>
      <td>SL 5.2, 5.3, 6.1 <br>PG 5.2</td>
      <td>
        <ul>
          <li>Eps-Greedy: PG 5.4</li>
          <li><a href="https://web.stanford.edu/~bvr/pubs/TS_Tutorial.pdf?utm_source=chatgpt.com">Thompson Sampling</a></li>
        </ul>
      </td>
      <td>Sign-up Sheet up on Piazza! <br><strong>Deadline: Sept 11th</strong></td>
    </tr>
    
    <tr>
      <td>Sep 6<br><strong>[Extra Class]</strong></td>
      <td>UCB Algorithm <br>Analysis of UCB-Regret <br>Optimality</td>
      <td>SL 7.1 <br>PG 5.3 <br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F86242a91f20765ed628a8f0305e97bb4f9587fb3fcc386bb7869aeeb43ba0669%2FLec4.pdf">note5</a>] <br>[<a href="https://uic.zoom.us/rec/share/nIO-A3xTP63sRSRDjze29o1MDOc-Nh1zy04mScU_oERXh-gE-h_RSpzJVlT4BrfJ.y7fEWxTAlR1lAgU4">video5</a>]</td>
      <td>
        <ul>
          <li><a href="https://www.stat.cmu.edu/~arinaldo/Teaching/36709/S19/Scribed_Lectures/Feb5_Aleksandr.pdf">SubExp RVs and Concentrations</a></li>
          <li><a href="https://www.hse.ru/data/2016/11/24/1113029206/Concentration%20inequalities.pdf">Book: Concentration Inequalities</a></li>
        </ul>
      </td>
      <td>Scribing Instructions on Piazza!</td>
    </tr>
    
    <tr>
      <td>Sep 9</td>
      <td>Bandits on Cont. Decision Spaces <br>- Lipschitz Bandits <br>- Linear Bandits</td>
      <td>SL 19.1, 19.2, 20.1 <br>PG 6.1.2</td>
      <td>
        <ul>
          <li><a href="https://proceedings.neurips.cc/paper_files/paper/2011/hash/e1d5be1c7f2f456670de3d53c7b54f4a-Abstract.html">Original OFUL paper</a></li>
        </ul>
      </td>
      <td></td>
    </tr>
    
    <tr>
      <td>Sep 11</td>
      <td>Linear Bandits (contd)</td>
      <td>SL Lem. 19.4, Thm. 19.2 <br>PG Thm. 6.5</td>
      <td>
        Other LinB Algos:
        <ul>
          <li><a href="https://www.schapire.net/papers/bandit-lin.pdf">SupLinUCB</a>: Improved Rates with Countable actions</li>
          <li>Optimal Design Algorithms (SL 21.1,22)</li>
          <li><a href="https://www.cs.ubc.ca/~hutter/nips2011workshop/papers_and_posters/nips11_Optimal_Algo_Linear_Bandits.pdf">GeometricHedge</a>: Adversarial Setting</li>
        </ul>
      </td>
      <td></td>
    </tr>
    
    <tr>
      <td>Sep 13<br><strong>[Extra Class]</strong></td>
      <td>Adversarial Setting <br>- FTRL <br>- OMD (full feedback) <br>- OMD (bandit feedback)</td>
      <td>- FTRL: PG 2.2.2 <br>- OMD: PG 2.2.3 <br>- OMD+Bandit: PG Eqn. 4.1, Sec 4.3 <br>- <a href="https://pages.cs.wisc.edu/~yudongchen/cs726_sp24/Lecture_25_online_convex_optimization_mirror_descent.pdf">YC Notes</a> <br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F41671833bfa17fca6d0610e4ebd49bb68e8665dcb15e4876e21493883b32a124%2FLec8-OMD.pdf">note8</a>] <br>[<a href="https://uic.zoom.us/rec/share/4By1joewLDzyjAZm6hqiXWcx0-3qooX5kjSxTIg4GbjirJL6I_KBfnnQe6N1eZGT.qEWOA7O456TkTqs0">video8</a>]</td>
      <td>
        Faster Rates with Hessian:
        <ul>
          <li>Online Newton Step (ONS): PG 3.2.1</li>
          <li><a href="https://www.cis.upenn.edu/~mkearns/finread/icml.pdf">Agarwal et al'06</a>: Portfolio Management with ONS</li>
        </ul>
        Stochastic Mirror Descent
        <ul>
          <li><a href="http://sbubeck.com/COLT12_BCK.pdf">OSMD</a></li>
        </ul>
      </td>
      <td></td>
    </tr>
    
    <tr>
      <td>Sep 16 <br><strong>[Extended]</strong></td>
      <td>Contextual Bandits (mini-RL): <br>- EXP4 <br>- SqrCB</td>
      <td>- EXP4: PG 4.2.1 <br>- <a href="https://arxiv.org/pdf/2002.04926">SquareCB</a>, <a href="https://people.cs.umass.edu/~akshay/courses/coms6998-11/files/lec4.pdf">AK-notes</a> (Realizability, Online Oracle) <br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fe294ba95214a9e6745106d35ae817afab96f9ae978de29a6e6822d8da738256d%2FLec9-CDB.pdf">note9</a>] <br>[video9:<a href="https://uofi.app.box.com/file/1987906053522?s=y27ej5bki834apnc0ean5put0uw4d1rb&tc=collab-file-invite-treatment">1</a>, <a href="https://uic.zoom.us/rec/share/rZ5g_sn13UUkia4AGl-oy6dH2N4uaFoLDQkqC9M01m2rpfbSd2O4qigoSojht66E.K6EmfPc1auWuNPjA">2</a>]</td>
      <td>
        Notable CB Algos:
        <ul>
          <li><a href="https://www.schapire.net/papers/bandit-lin.pdf">MiniMonster</a> (Finite Policy Class)</li>
          <li><a href="https://arxiv.org/pdf/2003.12699">ByPassing Monster</a> (Realizability, Offline Oracle)</li>
          <li><a href="https://arxiv.org/pdf/2107.05745">SquareCB.Lin</a> (Cont. Decision)</li>
        </ul>
      </td>
      <td></td>
    </tr>
    
    <tr>
      <td>Sep 18</td>
      <td>Paper presentation</td>
      <td>
        <ul>
          <li>Ratnesh: <a href="https://proceedings.neurips.cc/paper_files/paper/2024/file/40223e204a9e18dd8b01d7d11ea97939-Paper-Conference.pdf">MAB & N/W Interference</a></li>
          <li>Aresh: <a href="https://proceedings.neurips.cc/paper_files/paper/2021/file/49ef08ad6e7f26d7f200e1b2b9e6e4ac-Paper.pdf">Worst-Case MAB Behaviour</a></li>
        </ul>
      </td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sep 30</td>
      <td>Dueling Bandits: <br>Learning from Preferences</td>
      <td><a href="https://arxiv.org/abs/1807.11398">- DB Survey</a> <br><a href="https://proceedings.mlr.press/v32/zoghi14.html">- RUCB</a> <br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Fb5a29ed9978640206efd8693553c4e68376620d1bc2d1e721e51692ba245d8ca%2FLec10-DB.pdf">note10</a>] <br>[<a href="https://uic.zoom.us/rec/share/nzzkOk_uJ2ZzHY_sS8jdx7Y66kAv_v6dsSmpIuvQTZWqx233LHUKwXx1qV4oNRE-.LdzI8lb7KAODiHQ8?startTime=1759259116000">video10</a>]</td>
      <td></td>
      <td></td>
    </tr>
    
    <tr>
      <td>Oct 2</td>
      <td>Paper presentation</td>
      <td>
        <ul>
          <li>Sumanta - <a href="https://openreview.net/pdf?id=TFXxarWZzv">Tokenized Bandit for LLM</a></li>
          <li>Romain - <a href="https://arxiv.org/pdf/2103.01955">PPO in Cooperative Multi-Agent Games</a> (<a href="https://bair.berkeley.edu/blog/2021/07/14/mappo/">blog</a>, <a href="https://sites.google.com/view/mappo">website</a>)</li>
        </ul>
      </td>
      <td></td>
      <td></td>
    </tr>
    
    <tr>
      <td>Oct 7 <br><strong>[Extended]</strong></td>
      <td>RUCB: DB Regret against CW</td>
      <td>- <a href="https://arxiv.org/pdf/1312.3393">RUCB (ArXiv)</a> <br>- <a href="https://proceedings.mlr.press/v32/zoghi14.html">RUCB (ICML)</a> <br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F66bf5fb34ad6dd6f4ee61002b241e6c48e47056511b1f0f92336644db598ad6a%2FLec11-RUCB.pdf">note11</a>] <br>[<a href="https://uic.zoom.us/rec/share/Q0I-HCuJen5HgMWr7yjQsH8ygajST3PvZaEvnxdrF12uKtrvVqybJq0gSSvP2Fl2.moZXIgd4PQiDzvQ5?startTime=1759863742000">video11</a>]</td>
      <td>
        Optimal Regret against CW:
        <ul>
          <li><a href="https://proceedings.mlr.press/v162/saha22a/saha22a.pdf">Versatile DB</a></li>
        </ul>
        K-Armed DB w/ Adversarial Prefs:
        <ul>
          <li><a href="https://arxiv.org/abs/1601.03855">REX3</a>, <a href="https://proceedings.mlr.press/v139/saha21a.html">D-EXP3</a>, <a href="https://arxiv.org/abs/2406.12475v1">MiDEX</a></li>
        </ul>
      </td>
      <td></td>
    </tr>
    
    <tr>
      <td>Oct 9</td>
      <td>Demo + Paper presentation</td>
      <td>
        <ul>
          <li>Amir - <a href="https://arxiv.org/pdf/2510.00841">LLM Routing with DB Feedback</a></li>
          <li>Adam - <a href="https://docs.chrys.app/">Chrys Demo</a></li>
        </ul>
      </td>
      <td></td>
      <td></td>
    </tr>
    
    <tr>
      <td>Oct 14<br><strong>[Extended]</strong></td>
      <td>Contextual DB</td>
      <td>- <a href="https://arxiv.org/abs/2111.12306">CDB Analysis</a> <br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F390e249d2c2ea3329ee22a8027decfc232d50690468b45f58177147d0c61e961%2Fnote12.pdf">note12</a>] <br>[<a href="https://uic.zoom.us/rec/share/hKpCC-9FFeatyejXmLH4F67Q4BbLGCjTCU8Ocdqic392KgJmV314zvgwOELS3JA.amGTkDJKmwsVqXvK">video12</a>]</td>
      <td>
        More CDB Works:
        <ul>
          <li><a href="https://proceedings.neurips.cc/paper/2021/file/fc3cf452d3da8402bebb765225ce8c0e-Paper.pdf">Lin-CDB</a> (CDB with Linear Scores)</li>
          <li><a href="https://arxiv.org/abs/2404.06013">Feel-Good-CDB</a> (TS for CDB with Linear Scores)</li>
          <li><a href="https://arxiv.org/pdf/1502.06362">VN-CDB</a> (1st Gen-CDB paper w/ EXP4 & FPL)</li>
          <li><a href="https://arxiv.org/abs/2307.11288">K-CDB</a> (Kernelized CDB)</li>
        </ul>
      </td>
      <td></td>
    </tr>
    
    <tr>
      <td>Oct 16</td>
      <td>Paper presentation</td>
      <td>
        <ul>
          <li>Amith - <a href="https://iclr.cc/virtual/2025/poster/29425">Neural Dueling Bandits</a></li>
          <li>Ali - <a href="https://arxiv.org/abs/2410.23569">RA-PbRL</a></li>
        </ul>
      </td>
      <td></td>
      <td></td>
    </tr>
    
    <tr>
      <td>Oct 18 <br><strong>[Extra Class]</strong></td>
      <td>Complex-CB</td>
      <td>- <a href="https://arxiv.org/abs/2107.05745">CB in Cont Space</a> <br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F44519c7ae747ef5d6179dc3d953ef951b973a4b26eb5663ca6cb62b323a45809%2FLec13-ContCB.pdf">note13</a>] <br>[<a href="https://uic.zoom.us/rec/share/ahnXCFREH22LjgPifN2-zATvorP9xkVyBZtq90Oz8QPbXoCvcVbq9wYUeDQxQlwj.VSEGlXMrblaRCBLW">video13</a>]</td>
      <td></td>
      <td></td>
    </tr>
    
    <tr>
      <td>Oct 21</td>
      <td>MDP Basics: Intro to RL</td>
      <td>- RLM 1.1, 1.2 <br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2Ff810626b7b727381fd8a679f0e7db4c7582abdfd8de5102fbe563d0275fb4b43%2FLec14-RLIntro.pdf">note14</a>] <br>[<a href="https://uic.zoom.us/rec/share/SvuPcc4FL81KjG3370MLw2lD9eIEHk21bwato5Lc72NrrceD_QTVzeF_I8Zt1unX.d3LlgrSqW1l8xzch">video14</a>]</td>
      <td></td>
      <td></td>
    </tr>
    
    <tr>
      <td>Oct 23</td>
      <td>Paper presentation</td>
      <td>
        <ul>
          <li>Aniket - <a href="https://arxiv.org/pdf/2502.07193v1">Efficient RLHF Pipeline</a></li>
          <li>Anahita - <a href="https://icml.cc/virtual/2025/poster/43946">Policy-labeled Preference Learning</a></li>
        </ul>
      </td>
      <td></td>
      <td></td>
    </tr>
    
    <tr>
      <td>Oct 28 <br><strong>[Extended]</strong></td>
      <td>Tabular MDP <br>- Fin/Inf H <br>- Value-It <br>- Policy-It <br>- Sample Complexity</td>
      <td>- RLM 1.1, 1.2, 1.3 <br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F77b1cef40e120a5c26ce084aa33a45d158ef45d934424e6f716c88d9e5db5de2%2FLec15-VI-PI.pdf">note15</a>] <br>[<a href="https://uic.zoom.us/rec/share/X1hwH7zPIrvY9ojwF1-tpH5LG3X4IW-fD4GghwW9BfqHqBHi7ulufaBpKO6Dx8C-.ZVqT3EopCvwHAuBq">video15</a>]</td>
      <td>
        <ul>
          <li><a href="https://arxiv.org/pdf/1703.05449">UCB-VI</a>: Unknown Dynamics, Tabular</li>
          <li><a href="https://pages.cs.wisc.edu/~yudongchen/cs839_sp22/21_linear_mdp1.pdf">Lin-MDP</a>: Cont. State-Action Space</li>
        </ul>
      </td>
      <td></td>
    </tr>
    
    <tr>
      <td>Oct 30</td>
      <td colspan="4" style="text-align: center;"><strong>—-- Quiz —--</strong></td>
    </tr>
    
    <tr>
      <td>Nov 4 <br><strong>[Extended]</strong></td>
      <td>Policy Gradient</td>
      <td>- RLM 11.1, 12.2, 12.4 <br>[<a href="/redirect/s3?bucket=uploads&prefix=paste%2Fm53oyfstnlr6gy%2F8bb6058c3c2f64fd3d7d75adab992f5ee685cf874d3c3ca00f22398a48c11d96%2FLec16-PG.pdf">note16</a>] <br>[<a href="https://uic.zoom.us/rec/share/gyveCfho5yXyw1s_CoAXrRr0zePmnS6epFttD_MIodr2NA6TrqVD78d_OYWLv3gz.JHtjZ0miSXSNdFnP">video16</a>]</td>
      <td></td>
      <td></td>
    </tr>
    
    <tr>
      <td>Nov 6</td>
      <td>Paper presentation</td>
      <td>
        <ul>
          <li>Ali - <a href="https://icml.cc/virtual/2024/poster/33661">Multi-Objective Alignment</a></li>
          <li>Yuwei - <a href="https://openreview.net/pdf?id=I8af9JdQTy">Sail into Headwind</a></li>
        </ul>
      </td>
      <td></td>
      <td></td>
    </tr>
    
    <tr>
      <td>Nov 11</td>
      <td>UCB-VI (Unknown dynamics) <br>Linear-RL (Cont RL)</td>
      <td>- RLM 7.2, 7.3 <br>- RLM 8.5, 8.6</td>
      <td></td>
      <td></td>
    </tr>
    
    <tr>
      <td>Nov 13</td>
      <td>Paper presentation</td>
      <td>
        <ul>
          <li>Vaibhav - <a href="https://openreview.net/pdf?id=5PAF7PAY2Y">R1-Zero-Like Training</a></li>
          <li>Andrea - <a href="https://arxiv.org/abs/2401.04056">Minimaximalistic RLHF</a></li>
        </ul>
      </td>
      <td></td>
      <td></td>
    </tr>
    
    <tr>
      <td>Nov 18 <br><strong>[Extended]</strong></td>
      <td>PPO, TRPO</td>
      <td>- RLM 14.1, 14.2</td>
      <td></td>
      <td></td>
    </tr>
    
    <tr>
      <td>Nov 20</td>
      <td>Project presentation-1</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    
    <tr>
      <td>Nov 22 <br><strong>[Extended]</strong></td>
      <td>Imitation Learning</td>
      <td>- RLM 15.2, 15.4</td>
      <td></td>
      <td></td>
    </tr>
    
    <tr>
      <td>Nov 25</td>
      <td>Project Presentation-2</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    
    <tr>
      <td>Nov 27</td>
      <td colspan="4" style="text-align: center;"><strong>—-- Thanksgiving Break! —-- [Extra Class?]</strong></td>
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
                        Experiments <span style="background: #f5f5f5; color: #666; padding: 0.1rem 0.4rem; border-radius: 3px; font-weight: 500;">5%</span>
                      </span>
                </div>
            </li>
            <li>
                <strong style="color: #1565c0;">Paper Presentation + Coding:</strong> <span style="background: #e3f2fd; color: #1565c0; padding: 0.2rem 0.5rem; border-radius: 6px; font-weight: 600;">15%</span>
                <div style="margin-top: 0.5rem; padding-left: 1rem; border-left: 2px solid #e3f2fd;">
                    <span style="color: #666; font-size: 0.9rem;">
                        Work Motivation <span style="background: #f5f5f5; color: #666; padding: 0.1rem 0.4rem; border-radius: 3px; font-weight: 500;">5%</span> • 
                        Theoretical explanation <span style="background: #f5f5f5; color: #666; padding: 0.1rem 0.4rem; border-radius: 3px; font-weight: 500;">10%</span> • 
                        Experiments <span style="background: #4caf50; color: white; padding: 0.3rem 0.7rem; border-radius: 4px; font-size: 0.85rem; font-weight: 600; margin-left: 0.5rem;"> +5% extra credit</span>                    
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
                <strong style="color: #1565c0;">Piazza-Weekly Problem:</strong> <span style="background: #e3f2fd; color: #1565c0; padding: 0.2rem 0.5rem; border-radius: 6px; font-weight: 600;">15%</span>
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
                <strong style="color: #1565c0;">Class Participation:</strong> <span style="background: #e3f2fd; color: #1565c0; padding: 0.2rem 0.5rem; border-radius: 6px; font-weight: 600;">10%</span>
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
              Machine Learning from Human Preferences</a> by Truong, Haupt, Koyejo
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







