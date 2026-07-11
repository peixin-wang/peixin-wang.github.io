---
permalink: /
title: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div id="about"></div>

I am a **Youth Researcher Professor** at **Software Engineering Institue, East China Normal University**. My research focuses on **formal methods** and **trustworthy artificial intelligence**, with particular interests in program verification, probabilistic programming, runtime verification, safe reinforcement learning, embodied AI safety, and LLM safety.

Previously, I was a postdoctoral researcher at the **University of Oxford** and **Nanyang Technological University**. I received my Ph.D. from **Shanghai Jiao Tong University**, and my B.Sc. from **East China Normal University**.

**Prospective students:** I am always looking for self-motivated undergraduate, master’s, and Ph.D. students who are interested in formal methods, trustworthy AI, programming languages, safe intelligent systems, and AI safety. Please feel free to contact me by email.

---

<h2 id="research">Research Interests</h2>

- Formal Methods
- Program Verification
- Probabilistic Programming
- Runtime Verification
- Safe Reinforcement Learning
- Embodied AI Safety
- LLM Safety

---

<h2 id="publications">Selected Publications</h2>

<p class="pub-note"><sup>*</sup> denotes corresponding author.</p>

<div class="pub-list">

  <div class="pub-item">
    <div class="pub-title-line">
      <span class="venue-badge">ICLR 2026</span>
      <span class="pub-title">Neural Theorem Proving for Verification Conditions: A Real-World Benchmark</span>
    </div>

    <div class="pub-authors">
      Qiyuan Xu, Xiaokun Luan, Renxi Wang, Joshua Ong Jun Leang, <strong>Peixin Wang</strong>, Haonan Li, Wenda Li, and Conrad Watt.
    </div>

    <div class="pub-venue">
      International Conference on Learning Representations (ICLR), Accepted, 2026. <strong>CCF-A</strong>.
    </div>

    <div class="pub-links">
      <a href="#">arXiv</a> · <a href="#">PDF</a> · <a href="#">Code</a>
    </div>
  </div>

</div>

---

<h2 id="talks">Talks</h2>

{% for post in site.talks reversed %}
{% include archive-single-talk.html %}
{% endfor %}

---

<h2 id="teaching">Teaching</h2>

{% for post in site.teaching reversed %}
{% include archive-single.html %}
{% endfor %}

---


<h2 id="contact">Contact</h2>

Prospective students and collaborators are welcome to contact me by email.
