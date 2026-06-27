---
layout: default
title: Home
---

<header class="nav">
  <div class="brand">
    <div class="logo-mark">N</div>
    <div>
      <strong>NexusLab</strong>
      <span>A structured learning path for embedded systems</span>
    </div>
  </div>
  <nav>
    <a href="#path">Learning Path</a>
    <a href="#modules">Modules</a>
    <a href="#resources">Resources</a>
  </nav>
  <a class="button small" href="#starter">Get started</a>
</header>

<main>
  <section class="hero">
    <div class="hero-text">
      <p class="eyebrow">NexusLab</p>
      <h1>Master Embedded Systems.<br><span>Step by Step.</span></h1>
      <p class="lead">
        NexusLab guides learners from their first embedded application
        to professional real-time software development.
      </p>
      <div class="actions">
        <a class="button" href="#starter">Start learning</a>
        <a class="button secondary" href="#modules">Browse modules</a>
      </div>
    </div>

    <div class="hero-logo">
      <div class="circuit-n">N</div>
    </div>
  </section>

  <section id="modules" class="modules">
    <p class="eyebrow center">The NexusLab learning path</p>
    <h2>Three modules. One goal: engineering competence.</h2>

    <div class="cards">
      <article id="starter" class="card blue">
        <span class="level">01</span>
        <h3>Starter</h3>
        <p class="tagline">Learn the tools.</p>
        <p>Set up the toolchain, build, flash and debug your first embedded application.</p>
        <ul>
          <li>IDE & toolchain</li>
          <li>Build and flash</li>
          <li>Debugging</li>
          <li>LEDs and buttons</li>
        </ul>
      </article>

      <article class="card teal">
        <span class="level">02</span>
        <h3>Foundations</h3>
        <p class="tagline">Learn the engineering.</p>
        <p>Understand embedded software through GPIO, timers, interrupts and state machines.</p>
        <ul>
          <li>GPIO</li>
          <li>Timers</li>
          <li>Interrupts</li>
          <li>FSM</li>
        </ul>
      </article>

      <article class="card purple">
        <span class="level">03</span>
        <h3>Real-Time Systems</h3>
        <p class="tagline">Learn the architecture.</p>
        <p>Use FreeRTOS to design responsive multitasking embedded applications.</p>
        <ul>
          <li>Tasks</li>
          <li>Queues</li>
          <li>Semaphores</li>
          <li>Scheduling</li>
        </ul>
      </article>
    </div>
  </section>
</main>

<footer id="resources">
  <div>
    <strong>Structured Learning</strong>
    <p>A clear path from beginner to real-time competence.</p>
  </div>
  <div>
    <strong>Real Hardware</strong>
    <p>Learn with practical embedded systems projects.</p>
  </div>
  <div>
    <strong>Engineering First</strong>
    <p>Technologies are examples, not the objective.</p>
  </div>
</footer>
