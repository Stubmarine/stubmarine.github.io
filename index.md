---
layout: default
title: Stubmarine
permalink: /
---

<header class="header">
  <section class="container">
    <h1 class="title">Stubmarine</h1>
    <img alt="screenshot" src="assets/screenshot.png">
    <p class="description">
      Pre-built external service stubs to improve developer experience.
      <br>
      <i>
        <small>Currently {{ site.stubmarine.currentversion }} ({{ site.stubmarine.currentsize }})</small>
      </i>
    </p>
    <div>
      <a class="button button-outline" href="{{ site.stubmarine.demourl }}" target="_blank">Try Demo</a>
      <a class="button" href="#getting-started">Getting Started</a>
    </div>
  </section>
</header>

<section class="container" id="getting-started">
  <h3 class="title">Getting Started</h3>
  <p>Get started using Stubmarine quickly by doing:</p>
  <ol class="steps">
    <li>Install a Java 8 compatable JRE</li>
    <li>
      <code class="highlighter-rouge">curl -OL {{ site.stubmarine.currentrelease }}</code>
    </li>
    <li>Run <code class="highlighter-rouge">JWTSECRET=secret java -jar {{ site.stubmarine.currentjar }}</code></li>
  </ol>
</section>

<section class="container">
  <h3 class="title">Why?</h3>
  <div class="row">
    <div class="column value-prop">
      <h4>Prevent data accidents</h4>
      <p>Stubmarine works with any email addresses - never accidentally send emails to real inboxes again</p>
    </div>
    <div class="column value-prop">
      <h4>Develop in isolation</h4>
      <p>Insulate yourself against 3rd party outages and spec changes that halt development</p>
    </div>
    <div class="column value-prop">
      <h4>Develop offline</h4>
      <p>Don't rely on internet connectivity to develop code by running Stubmarine locally</p>
    </div>
  </div>
</section>

<section class="container">
  <h3 class="title">Using Stubmarine</h3>
  <p>Using Stubmarine is easy.</p>
  <ol class="steps">
    <li>Take your existing 12-factor app</li>
    <li>Reconfigure external dependencies to point to Stubmarine</li>
    <li>Develop code with ease!</li>
  </ol>
</section>

<section class="container">
  <h3 class="title">Happy Users</h3>
  TODO
</section>
