---
layout: null
permalink: /
ga4_id: ""
---

{::nomarkdown}
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Hongtao Zhang | Computer Vision and Medical Imaging</title>
  <meta name="description" content="Hongtao Zhang is a postdoctoral researcher at the Shenzhen Institutes of Advanced Technology, Chinese Academy of Sciences. Biography, publications, and education.">
  <link rel="canonical" href="https://vison-eden.github.io/Hongtao-eden/">
  <link rel="icon" href="assets/img/zht.png">
  <link rel="stylesheet" href="assets/css/research-profile.css">
  {% assign ga4_id = page.ga4_id | default: site.ga4_id | default: site.google_analytics | default: "" | strip %}
  {% assign prefix = ga4_id | slice: 0, 2 %}
  {% if prefix == "G-" %}
  <script async src="https://www.googletagmanager.com/gtag/js?id={{ ga4_id | escape }}"></script>
  <script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){ window.dataLayer.push(arguments); }
    gtag('js', new Date());
    gtag('config', {{ ga4_id | jsonify }});
  </script>
  {% endif %}
</head>
<body id="top">
<a class="skip" href="#main-content">Skip to content</a>
<div class="page">
  <header class="mast">
    <a href="#top">Hongtao Zhang</a>
    <nav aria-label="Main navigation"><a href="#publications">Publications</a><a href="#education">Education</a></nav>
  </header>
    <main id="main-content">
    <section class="intro" aria-labelledby="name">
      <div class="identity">
        <div class="portrait-frame"><span aria-hidden="true">HZ</span><img class="portrait" src="assets/img/eden.jpg" width="96" height="96" alt="Hongtao Zhang" onerror="this.hidden=true;this.style.display='none'"></div>
        <div>
          <h1 id="name">Hongtao Zhang</h1>
          <p class="role">Postdoctoral Researcher</p>
          <p class="affiliation">Shenzhen Institutes of Advanced Technology, Chinese Academy of Sciences</p>
        </div>
      </div>
      <p class="bio">I earned my master’s and doctoral degrees in Intelligent Informatics at Kochi University of Technology in Japan, where I worked with <a href="https://www.kochi-tech.ac.jp/profile/en/yoshida-shinichi.html">Professor Shinichi Yoshida</a>. My doctoral studies were supported by the university’s Special Scholarship Program. Before moving to Japan, I studied network engineering at Jilin University of Zhuhai College under the supervision of <a href="https://ieeexplore.ieee.org/author/37401143200">Professor Yanchun Liang</a>.</p>
      <p class="bio">My research interests include visual cognition, computer vision, and medical imaging. I am particularly interested in what comparisons between human vision and neural networks can tell us about how we perceive images.</p>
      <div class="links">
        <a href="assets/files/cv.pdf">CV (PDF)</a>
        <a href="https://scholar.google.com/citations?user=jQvs2JIAAAAJ">Google Scholar</a>
        <a href="https://github.com/Vison-eden">GitHub</a>
        <a href="mailto:edenzht@gmail.com">Email</a>
      </div>
    </section>
    <section class="group" id="publications" aria-labelledby="pub-title">
      <h2 id="pub-title">Publications</h2>
      <ul class="pubs">
        <li class="paper-with-thumb">
          <span class="year">2026</span>
          <div>
            <a href="https://doi.org/10.1038/s41746-026-03062-x">Multimodal deep learning for preoperative invasiveness stratification of lung adenocarcinoma spectrum nodules</a>
            <span class="credit">Hongtao Zhang et al. · npj Digital Medicine · <a href="https://github.com/Vison-eden/ct-mm">Code</a></span>
          </div>
          <a class="paper-thumb" href="https://doi.org/10.1038/s41746-026-03062-x" aria-label="View the paper containing Figure 5B">
            <img src="assets/img/npj-model-workflow.png" width="611" height="248" alt="Figure 5B. CT patch and radiological features enter separate encoders before fusion and classification.">
          </a>
        </li>
        <li><span class="year">2024</span><div><a href="https://doi.org/10.1109/ACCESS.2024.3475478">Assessing brain-like characteristics of DNNs with spatiotemporal features: a study based on the Müller-Lyer illusion</a><span class="credit">Hongtao Zhang, Kiminori Matsuzaki, Shinichi Yoshida · IEEE Access</span></div></li>
        <li><span class="year">2024</span><div><a href="https://doi.org/10.3390/app14083429">Exploring deep neural networks in simulating human vision through five optical illusions</a><span class="credit">Hongtao Zhang, Shinichi Yoshida · Applied Sciences</span></div></li>
        <li><span class="year">2024</span><div><a href="https://doi.org/10.1371/journal.pone.0299083">Brain-like illusion produced by Skye’s Oblique Grating in deep neural networks</a><span class="credit">Hongtao Zhang, Shinichi Yoshida, Zhen Li · PLOS ONE</span></div></li>
        <li><span class="year">2021</span><div><a href="https://doi.org/10.3390/s21092978">3D MRI reconstruction based on 2D generative adversarial network super-resolution</a><span class="credit">Hongtao Zhang, Yuki Shinomiya, Shinichi Yoshida · Sensors</span></div></li>
      </ul>
    </section>
    <section class="group" id="education" aria-labelledby="edu-title">
      <h2 id="edu-title">Education</h2>
      <ul class="degrees">
        <li><span class="year">2024</span><div>Ph.D. in Intelligent Informatics<span class="credit">Kochi University of Technology, Japan · Special Scholarship Program</span></div></li>
        <li><span class="year">2021</span><div>M.E. in Intelligent Informatics<span class="credit">Kochi University of Technology, Japan</span></div></li>
        <li><span class="year">2019</span><div>B.E. in Network Engineering<span class="credit">Jilin University of Zhuhai College, China</span></div></li>
      </ul>
    </section>
  </main>
  <footer><a href="mailto:edenzht@gmail.com">edenzht@gmail.com</a> · <a href="https://www.researchgate.net/profile/Hongtao-Zhang-33">ResearchGate</a></footer>
</div>
</body>
</html>
{:/nomarkdown}
