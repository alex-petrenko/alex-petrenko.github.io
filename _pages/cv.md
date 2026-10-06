---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 5
description: Brief timeline of my education, work, and life.
---

<p class="cv-download"><a href="/assets/cv.pdf" download="Aleksei_Petrenko_CV.pdf"><i class="fa-solid fa-file-pdf"></i> Download full CV (PDF)</a></p>

<script>
  // Opening the CV tab starts the PDF download right away (the button above stays as a fallback).
  window.addEventListener("load", () => {
    const a = document.createElement("a");
    a.href = "/assets/cv.pdf";
    a.download = "Aleksei_Petrenko_CV.pdf";
    document.body.appendChild(a);
    a.click();
    a.remove();
  });
</script>

<ul class="cv-timeline">
  <li><span class="yr">2026</span><span>My son <a href="/assets/leo.jpg">Leo</a> was born ❤️</span></li>
  <li><span class="yr">2023</span><span>Joined Apple as a research scientist to work with <a href="https://vladlen.info/">Vladlen Koltun</a>, now working on RLVR for interactive digital agents</span></li>
  <li><span class="yr">2022</span><span>Defended my PhD, thesis titled "High-Throughput Methods for Simulation and Deep Reinforcement Learning"</span></li>
  <li><span class="yr">2021–2022</span><span>AI & Robotics Intern at NVIDIA, working with Viktor Makoviychuk, Ankur Handa, and Gavriel State</span></li>
  <li><span class="yr">2020</span><span>PhD Research Intern at Intel Labs, Los Angeles (remote) with Vladlen Koltun</span></li>
  <li><span class="yr">2019</span><span>PhD Research Intern at Intel Labs, Santa Clara with Vladlen Koltun</span></li>
  <li><span class="yr">2018</span><span>Started a PhD program at the University of Southern California</span></li>
  <li><span class="yr">2018</span><span>Deep learning and computer vision summer school <a href="http://iplab.dmi.unict.it/icvss2018/">ICVSS 2018</a></span></li>
  <li><span class="yr">2017</span><span>Development of <a href="https://avatarsdk.com/">Avatar SDK</a>, presented this work at conferences such as SIGGRAPH Asia, GDC, and VRX</span></li>
  <li><span class="yr">2015</span><span>Tech lead at the computer vision startup <a href="https://itseez3d.com/">itSeez3D</a></span></li>
  <li><span class="yr">2014</span><span>Graduated summa cum laude with M.Sc. in Computer Science from Nizhny Novgorod State Technical University (<a href="http://www.nntu.ru/">NNSTU</a>)</span></li>
  <li><span class="yr">2013</span><span>Senior software engineer at itSeez, Inc.</span></li>
  <li><span class="yr">2012</span><span>Graduated summa cum laude with B.Sc. in Computer Science from NNSTU</span></li>
  <li><span class="yr">2012</span><span><a href="http://codeforces.com/blog/entry/4632?locale=en">Summer School</a> on Olympiad Programming at Saratov State University</span></li>
  <li><span class="yr">2012</span><span>Awarded a scholarship of the President of the Russian Federation</span></li>
  <li><span class="yr">2010</span><span>Software engineer at Tecom LLC</span></li>
  <li><span class="yr">2010–2012</span><span>Competed and won prizes in ACM ICPC and other programming competitions</span></li>
  <li><span class="yr">2008</span><span>Started studying computer science at NNSTU</span></li>
</ul>
