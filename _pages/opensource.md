---
layout: page
permalink: /opensource/
title: Open source
nav: true
nav_order: 3
description: Libraries and tools I wrote and maintain.
---

<div class="os-stats">
  <div class="os-stat"><span class="num">1.5K+</span><span class="lbl">GitHub stars</span></div>
  <div class="os-stat"><span class="num">220+</span><span class="lbl">forks</span></div>
  <div class="os-stat"><span class="num">1.4M+</span><span class="lbl">PyPI downloads</span></div>
  <div class="os-stat"><span class="num">870+</span><span class="lbl">public commits</span></div>
</div>

<div class="os-project">
  <div class="os-head">
    <h3><a href="https://github.com/alex-petrenko/sample-factory">Sample Factory</a></h3>
    <span class="os-meta">★ 1K · 150 forks · 120K downloads · <a href="https://www.samplefactory.dev/">docs</a> · <a href="https://arxiv.org/abs/2006.11751">paper (ICML 2020)</a></span>
  </div>
  <p>High-throughput asynchronous reinforcement learning framework. At the time of release, the fastest open-source PPO implementation: ~10x faster than traditional synchronous RL implementations, with SOTA results in challenging VizDoom and DMLab environments.</p>
  <div class="os-gallery">
    <figure><img src="/assets/img/publication_preview/sf_battle.gif" alt="VizDoom battle" loading="lazy"><figcaption>VizDoom: battle</figcaption></figure>
    <figure><img src="/assets/img/publication_preview/sf_duel.gif" alt="VizDoom duel" loading="lazy"><figcaption>VizDoom: self-play duel</figcaption></figure>
    <figure><img src="/assets/img/opensource/sample-factory_vizdoom.gif" alt="VizDoom" loading="lazy"><figcaption>VizDoom</figcaption></figure>
    <figure><img src="/assets/img/opensource/sample-factory_dmlab.gif" alt="DMLab-30" loading="lazy"><figcaption>DMLab-30</figcaption></figure>
    <figure><img src="/assets/img/opensource/sample-factory_isaac.gif" alt="Isaac Gym" loading="lazy"><figcaption>Isaac Gym</figcaption></figure>
    <figure><img src="/assets/img/opensource/sample-factory_megaverse.gif" alt="Megaverse" loading="lazy"><figcaption>Megaverse</figcaption></figure>
    <figure><img src="/assets/img/opensource/sample-factory_mujoco.gif" alt="MuJoCo" loading="lazy"><figcaption>MuJoCo</figcaption></figure>
    <figure><img src="/assets/img/opensource/sample-factory_atari.gif" alt="Atari" loading="lazy"><figcaption>Atari</figcaption></figure>
    <figure><img src="/assets/img/publication_preview/sf_bots.gif" alt="VizDoom bots" loading="lazy"><figcaption>VizDoom: vs. bots</figcaption></figure>
  </div>
</div>

<div class="os-project">
  <div class="os-head">
    <h3><a href="https://github.com/alex-petrenko/megaverse">Megaverse</a></h3>
    <span class="os-meta">★ 230 · <a href="https://www.megaverse.info/">website</a> · <a href="https://arxiv.org/abs/2107.08170">paper (ICML 2021)</a></span>
  </div>
  <p>The fastest (at the time of release) embodied simulator for AI research: 1,000,000+ FPS of immersive, physics-based multi-agent experience on a single machine.</p>
  <div class="os-gallery cols-2">
    <figure><img src="/assets/img/publication_preview/megaverse_1.gif" alt="Megaverse TowerBuilding" loading="lazy"><figcaption>RL agent building a tower</figcaption></figure>
    <figure><img src="/assets/img/publication_preview/megaverse_2.gif" alt="Megaverse obstacle course" loading="lazy"><figcaption>Random obstacle course</figcaption></figure>
  </div>
</div>

<div class="os-project">
  <div class="os-head">
    <h3><a href="https://github.com/alex-petrenko/faster-fifo">Faster-FIFO</a></h3>
    <span class="os-meta">★ 200 · 1.3M downloads · <code>pip install faster-fifo</code></span>
  </div>
  <p>A faster alternative to Python's built-in <code>multiprocessing.Queue</code>.</p>
</div>

<div class="os-project">
  <div class="os-head">
    <h3><a href="https://github.com/alex-petrenko/signal-slot">Signal-Slot</a></h3>
    <span class="os-meta"><code>pip install signal-slot-mp</code></span>
  </div>
  <p>Python implementation of the Qt-like signal &amp; slot asynchronous programming paradigm, with focus on multiprocessing applications.</p>
</div>

<div class="os-project">
  <div class="os-head">
    <h3><a href="https://github.com/alex-petrenko/4dvideo">4DVideo</a></h3>
    <span class="os-meta">★ 43</span>
  </div>
  <p>"4D video" grabber and player for Intel RealSense and Google Tango, with a fast real-time Delaunay triangulation (modified Guibas-Stolfi): 300fps on PC, 100fps on Android. More in <a href="/projects/8_4dvideo/">projects</a>.</p>
  <div class="os-gallery single">
    <figure><img src="/assets/img/opensource/4dvideo_triangulation.gif" alt="Delaunay triangulation" loading="lazy" style="aspect-ratio: 1 / 1;"><figcaption>Delaunay triangulation</figcaption></figure>
  </div>
</div>

<div class="os-project">
  <div class="os-head"><h3>Smaller projects</h3></div>
  <ul>
    <li><a href="https://github.com/alex-petrenko/tf-reinforce">tf-reinforce</a>: Tensorflow implementation of classic policy gradient algorithm for continuous control tasks.</li>
    <li><a href="https://github.com/alex-petrenko/snake-rl">snake-rl</a>: RL algorithms for classic Snake game (<a href="https://youtu.be/bh_5aIqVTUY">youtube</a>).</li>
    <li><a href="https://github.com/alex-petrenko/udacity-deep-learning/blob/master/hyperopt.py">hyperopt.py</a>: evolutionary algorithm for hyperparameter optimization in deep learning (it works!).</li>
    <li><a href="https://github.com/alex-petrenko/udacity-linear-algebra-cpp">udacity-linear-algebra-cpp</a>: small linear algebra library in C++11/14 with templates, SFINAE, etc.</li>
  </ul>
</div>
