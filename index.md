---
layout: default
title: About
---

<style>
  .site-wrapper {
    max-width: 980px;
    margin: 0 auto;
    padding: 20px;
    font-family: Georgia, "Times New Roman", serif;
    color: #222;
  }

  .top-nav {
    text-align: center;
    margin-bottom: 40px;
    border-bottom: 1px solid #ddd;
    padding-bottom: 12px;
  }

  .top-nav a {
    margin: 0 18px;
    text-decoration: none;
    color: #222;
    font-size: 1rem;
  }

  .top-nav a:hover {
    text-decoration: underline;
  }

  .hero {
    display: flex;
    gap: 32px;
    align-items: flex-start;
    flex-wrap: wrap;
  }

  .hero-image img {
    width: 240px;
    max-width: 100%;
    border-radius: 4px;
    display: block;
  }

  .hero-text {
    flex: 1;
    min-width: 280px;
    font-size: 1.05rem;
    line-height: 1.7;
  }

  .hero-text p {
    margin-bottom: 1.2em;
  }

  .hero-text a {
    color: #1a4f8b;
    text-decoration: none;
  }

  .hero-text a:hover {
    text-decoration: underline;
  }

  .site-title {
    text-align: center;
    font-size: 2rem;
    letter-spacing: 0.04em;
    margin-bottom: 8px;
    text-transform: uppercase;
  }

  @media (max-width: 700px) {
    .site-title {
      font-size: 1.5rem;
    }

    .top-nav a {
      display: inline-block;
      margin: 6px 10px;
    }

    .hero {
      flex-direction: column;
    }
  }
</style>

<div class="site-wrapper">
  <div class="site-title">JEFFREY PAGEL</div>

  <nav class="top-nav">
    <a href="/">About</a>
    <a href="/research">Research</a>
    <a href="/teaching">Teaching</a>
    <a href="/contact">Contact</a>
  </nav>

  <section class="hero">
    <div class="hero-image">
      <img src="/assets/img/profile.jpg" alt="Jeffrey Pagel portrait">
    </div>

    <div class="hero-text">
      <p>
        Welcome! I am a Fellow in Environmental Economics at the London School of Economics.
        My research interests lie at the intersection of development, environmental and resource
        economics with an emphasis on public policy. I use geospatial impact evaluations to
        understand human and ecological impacts of development programs and public policies.
      </p>

      <p>
        Additionally, I work as an Ethical and Project Evaluation Consultant for
        <a href="https://www.healthmedialabirb.com/" target="_blank">Health Media Labs</a>
        in Washington, D.C., which focuses on social &amp; behavioral research in public health,
        HIV/AIDS, children, education, refugee &amp; migration, WASH, agriculture and M&amp;E.
        Previously I was a Research Officer at the
        <a href="https://www.lse.ac.uk/granthaminstitute/" target="_blank">Grantham Research Institute</a>
        at the London School of Economics. I received my PhD from the University of Barcelona in 2021.
      </p>

      <p>
        Please find my <a href="/assets/files/Jeffrey_Pagel_CV.pdf" target="_blank">CV here</a>.
      </p>

      <p>
        You can contact me at
        <a href="mailto:j.pagel@lse.ac.uk">j.pagel@lse.ac.uk</a>
      </p>
    </div>
  </section>
</div>
