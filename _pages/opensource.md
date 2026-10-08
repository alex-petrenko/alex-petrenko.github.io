---
layout: page
permalink: /opensource/
title: Open source
nav: true
nav_order: 3
description: Libraries and tools I built.
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
  <p>High-throughput asynchronous reinforcement learning framework. At the time of release, the fastest open-source PPO implementation: ~10x faster than traditional synchronous RL implementations, with SOTA results in challenging VizDoom and DMLab environments. Agents trained with Sample Factory:</p>
  <div class="os-gallery">
    <figure><video src="/assets/img/publication_preview/sf_battle.mp4" aria-label="VizDoom battle" muted loop playsinline preload="metadata" data-autoplay></video><figcaption>VizDoom: battle</figcaption></figure>
    <figure><video src="/assets/img/publication_preview/sf_duel.mp4" aria-label="VizDoom duel" muted loop playsinline preload="metadata" data-autoplay></video><figcaption>VizDoom: self-play duel</figcaption></figure>
    <figure><video src="/assets/img/opensource/sample-factory_vizdoom.mp4" aria-label="VizDoom" muted loop playsinline preload="metadata" data-autoplay></video><figcaption>VizDoom</figcaption></figure>
    <figure><video src="/assets/img/opensource/sample-factory_dmlab.mp4" aria-label="DMLab-30" muted loop playsinline preload="metadata" data-autoplay></video><figcaption>DMLab-30</figcaption></figure>
    <figure><video src="/assets/img/opensource/sample-factory_isaac.mp4" aria-label="Isaac Gym" muted loop playsinline preload="metadata" data-autoplay></video><figcaption>Isaac Gym</figcaption></figure>
    <figure><video src="/assets/img/opensource/sample-factory_megaverse.mp4" aria-label="Megaverse" muted loop playsinline preload="metadata" data-autoplay></video><figcaption>Megaverse</figcaption></figure>
    <figure><video src="/assets/img/opensource/sample-factory_mujoco.mp4" aria-label="MuJoCo" muted loop playsinline preload="metadata" data-autoplay></video><figcaption>MuJoCo</figcaption></figure>
    <figure><video src="/assets/img/opensource/sample-factory_atari.mp4" aria-label="Atari" muted loop playsinline preload="metadata" data-autoplay></video><figcaption>Atari</figcaption></figure>
    <figure><video src="/assets/img/publication_preview/sf_bots.mp4" aria-label="VizDoom bots" muted loop playsinline preload="metadata" data-autoplay></video><figcaption>VizDoom: vs. bots</figcaption></figure>
  </div>
</div>

<div class="os-project">
  <div class="os-head">
    <h3><a href="https://github.com/alex-petrenko/megaverse">Megaverse</a></h3>
    <span class="os-meta">★ 230 · <a href="https://www.megaverse.info/">website</a> · <a href="https://arxiv.org/abs/2107.08170">paper (ICML 2021)</a></span>
  </div>
  <p>The fastest (at the time of release) embodied simulator for AI research: 1,000,000+ FPS of immersive, physics-based multi-agent experience on a single machine.</p>
  <div class="os-gallery cols-2">
    <figure><video src="/assets/img/publication_preview/megaverse_1.mp4" aria-label="Megaverse TowerBuilding" muted loop playsinline preload="metadata" data-autoplay></video><figcaption>RL agent building a tower</figcaption></figure>
    <figure><video src="/assets/img/publication_preview/megaverse_2.mp4" aria-label="Megaverse obstacle course" muted loop playsinline preload="metadata" data-autoplay></video><figcaption>Random obstacle course</figcaption></figure>
  </div>
</div>

<div class="os-project">
  <div class="os-head">
    <h3><a href="https://github.com/alex-petrenko/faster-fifo">Faster-FIFO</a></h3>
    <span class="os-meta">★ 200 · 1.3M downloads · <code>pip install faster-fifo</code></span>
  </div>
  <p>A faster alternative to Python's built-in <code>multiprocessing.Queue</code>.</p>
  <div class="os-table-wrap">
  <table class="os-table">
    <caption>Performance comparison, faster-fifo vs <code>multiprocessing.Queue</code>: execution time in seconds, lower is better. Intel Core i9-7900X @ 3.30GHz, 10 cores, Ubuntu 18.04.</caption>
    <thead><tr><th></th><th>multiprocessing<wbr>.Queue</th><th>faster-fifo, get()</th><th>faster-fifo, get_many()</th></tr></thead>
    <tbody>
      <tr><td>1 producer, 1 consumer<span class="msgs">200K msgs per producer</span></td><td>2.54</td><td>0.86</td><td>0.92</td></tr>
      <tr><td>1 producer, 10 consumers<span class="msgs">200K msgs per producer</span></td><td>4.00</td><td>1.39</td><td>1.36</td></tr>
      <tr><td>10 producers, 1 consumer<span class="msgs">100K msgs per producer</span></td><td>13.19</td><td>6.74</td><td>0.94</td></tr>
      <tr><td>3 producers, 20 consumers<span class="msgs">100K msgs per producer</span></td><td>9.30</td><td>2.22</td><td>2.17</td></tr>
      <tr><td>20 producers, 3 consumers<span class="msgs">50K msgs per producer</span></td><td>18.62</td><td>7.41</td><td>0.64</td></tr>
      <tr><td>20 producers, 20 consumers<span class="msgs">50K msgs per producer</span></td><td>36.51</td><td>1.32</td><td>3.79</td></tr>
    </tbody>
  </table>
  </div>
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
  <p>"4D video" grabber and player for Intel RealSense and Google Tango, with a fast real-time Delaunay triangulation (modified Guibas-Stolfi): 300fps on PC, 100fps on Android. More in <a href="/projects/#volumetric-video">other projects</a>.</p>
  <div class="os-gallery single">
    <figure><video src="/assets/img/opensource/4dvideo_triangulation.mp4" aria-label="Delaunay triangulation" style="aspect-ratio: 1 / 1;" muted loop playsinline preload="metadata" data-autoplay></video><figcaption>Delaunay triangulation</figcaption></figure>
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
