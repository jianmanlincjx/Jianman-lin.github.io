---
permalink: /
title:
homepage: true
author_profile: false
redirect_from:
  - /cv/
  - /cv.html
  - /resume
---

<div class="jm-homepage" markdown="0">
  <aside class="jm-sidebar">
    <div class="jm-profile-card">
      {% if site.author.avatar %}
        <img class="jm-avatar" src="{{ site.author.avatar | prepend: '/images/' | relative_url }}" alt="{{ site.author.name }}">
      {% else %}
        <div class="jm-avatar jm-avatar--placeholder" aria-hidden="true">JL</div>
      {% endif %}

      <h1 class="jm-name">Jianman Lin</h1>
      <p class="jm-role">M.Eng. @ SCUT · Guangzhou, China</p>

      <ul class="jm-contact">
        <li><a href="mailto:linjianmancjx@gmail.com">Email</a></li>
        <li><a href="https://scholar.google.com/citations?user=ayk7FWMAAAAJ&amp;hl=en" target="_blank" rel="noopener noreferrer">Google Scholar</a></li>
        <li><a href="https://github.com/jianmanlincjx" target="_blank" rel="noopener noreferrer">GitHub</a></li>
      </ul>
    </div>
  </aside>

  <main class="jm-main">
    <section class="jm-block" id="about">
      <h2 class="jm-block-title">About Me</h2>
      <p>
        I received my bachelor's degree from Guangdong University of Technology. I am currently a Master's student at South China University of Technology (SCUT), supervised by <a href="https://scholar.google.com/citations?user=aNvkklMAAAAJ&amp;hl=en" target="_blank" rel="noopener noreferrer">Tianshui Chen</a> and <a href="https://scholar.google.com/citations?user=soX8e10AAAAJ&amp;hl=en" target="_blank" rel="noopener noreferrer">Chunmei Qing</a>. My research focuses on Computer Vision, Generative AI, and Controllable Image Synthesis, with work recognized as a Highlight at CVPR and published in leading journals such as International Journal of Computer Vision (IJCV) and IEEE Transactions on Image Processing (TIP).
      </p>
      <p>
        I am actively seeking opportunities for academic collaboration and research internships. Currently, I work as an Algorithm Research Intern at X-Era AI, where I lead the development of a digital human livestreaming system, an intelligent home solution (Feiliu AI mini-program), and embodied AI systems.
      </p>
    </section>

    <section class="jm-block" id="news">
      <h2 class="jm-block-title">News</h2>
      <ul class="jm-news-list">
        <li><span>2025</span> Neural Scene Designer was published in <strong>IEEE TIP</strong>.</li>
        <li><span>2025</span> CDRL was published in <strong>IJCV</strong>.</li>
        <li><span>2024</span> ASCCL was selected as a <strong>CVPR 2024 Highlight</strong> (Top 2.8%).</li>
        <li><span>2024</span> Joined <strong>X-Era AI</strong> as an algorithm research intern.</li>
        <li><span>2024</span> Started M.Eng. study at <strong>SCUT</strong>.</li>
      </ul>
    </section>

    <section class="jm-block" id="publications">
      <h2 class="jm-block-title">Selected Publications</h2>

      <div class="jm-pub-group">
        <div class="jm-pub-group-title">Controllable Image Editing</div>

        <article class="jm-pub-item">
          <a class="jm-pub-thumb" href="https://arxiv.org/pdf/2509.01405" target="_blank" rel="noopener noreferrer">
            <img src="{{ '/images/papers/TIP_2025_NSD.png' | relative_url }}" alt="TIP 2025 NSD" loading="lazy">
          </a>
          <div class="jm-pub-body">
            <h3 class="jm-pub-title">Neural Scene Designer: Self-Styled Semantic Image Manipulation</h3>
            <p class="jm-pub-meta"><strong>Jianman Lin</strong>, <a href="https://scholar.google.com/citations?user=aNvkklMAAAAJ&amp;hl=en" target="_blank" rel="noopener noreferrer">Tianshui Chen</a>, <a href="https://scholar.google.com/citations?user=soX8e10AAAAJ&amp;hl=en" target="_blank" rel="noopener noreferrer">Chunmei Qing</a>, Zhijing Yang, Shuangping Huang, Yuheng Ren, Liang Lin.</p>
            <p class="jm-pub-venue-line">
              <strong>IEEE Transactions on Image Processing (TIP)</strong>, 2025 · <span class="jm-ccf">CCF-A</span>
              <span class="jm-pub-links-inline">
                <a href="https://github.com/jianmanlincjx" target="_blank" rel="noopener noreferrer">Code</a>
                <a href="{{ '/publications/neural-scene-designer-tip/' | relative_url }}">Page</a>
              </span>
            </p>
          </div>
        </article>

        <article class="jm-pub-item">
          <a class="jm-pub-thumb" href="https://arxiv.org/pdf/2505.20914" target="_blank" rel="noopener noreferrer">
            <img src="{{ '/images/papers/underreview_2026_DAGD.png' | relative_url }}" alt="DAGD" loading="lazy">
          </a>
          <div class="jm-pub-body">
            <h3 class="jm-pub-title">Geometry-Editable and Appearance-Preserving Object Composition</h3>
            <p class="jm-pub-meta"><strong>Jianman Lin</strong>, Haojie Li, <a href="https://scholar.google.com/citations?user=soX8e10AAAAJ&amp;hl=en" target="_blank" rel="noopener noreferrer">Chunmei Qing</a>, Zhijing Yang, Liang Lin, <a href="https://scholar.google.com/citations?user=aNvkklMAAAAJ&amp;hl=en" target="_blank" rel="noopener noreferrer">Tianshui Chen</a>.</p>
            <p class="jm-pub-venue-line">
              <strong>Under review</strong> · <span class="jm-ccf">IJCV (CCF-A)</span>
              <span class="jm-pub-links-inline">
                <a href="https://github.com/jianmanlincjx" target="_blank" rel="noopener noreferrer">Code</a>
                <a href="{{ '/publications/ijcv-2025-dagd/' | relative_url }}">Page</a>
              </span>
            </p>
          </div>
        </article>
      </div>

      <div class="jm-pub-group">
        <div class="jm-pub-group-title">Speech-Preserving Facial Expression Manipulation</div>

        <article class="jm-pub-item">
          <a class="jm-pub-thumb" href="https://openaccess.thecvf.com/content/CVPR2024/papers/Chen_Learning_Adaptive_Spatial_Coherent_Correlations_for_Speech-Preserving_Facial_Expression_Manipulation_CVPR_2024_paper.pdf" target="_blank" rel="noopener noreferrer">
            <img src="{{ '/images/papers/CVPR_2024_ASCCL.png' | relative_url }}" alt="CVPR 2024 ASCCL" loading="lazy">
          </a>
          <div class="jm-pub-body">
            <h3 class="jm-pub-title">Learning Adaptive Spatial Coherent Correlations for Speech-Preserving Facial Expression Manipulation</h3>
            <p class="jm-pub-meta"><a href="https://scholar.google.com/citations?user=aNvkklMAAAAJ&amp;hl=en" target="_blank" rel="noopener noreferrer">Tianshui Chen</a>, <strong>Jianman Lin</strong>, Zhijing Yang, <a href="https://scholar.google.com/citations?user=soX8e10AAAAJ&amp;hl=en" target="_blank" rel="noopener noreferrer">Chunmei Qing</a>, Liang Lin.</p>
            <p class="jm-pub-venue-line">
              <strong>CVPR 2024</strong> · Highlight (Top 2.8%) · <span class="jm-ccf">CCF-A</span>
              <span class="jm-pub-links-inline">
                <a href="https://github.com/jianmanlincjx" target="_blank" rel="noopener noreferrer">Code</a>
                <a href="{{ '/publications/cvpr-2024-asccl/' | relative_url }}">Page</a>
              </span>
            </p>
          </div>
        </article>

        <article class="jm-pub-item">
          <a class="jm-pub-thumb" href="https://arxiv.org/pdf/2504.05672" target="_blank" rel="noopener noreferrer">
            <img src="{{ '/images/papers/IJCV_2025_CDRL.png' | relative_url }}" alt="IJCV 2025 CDRL" loading="lazy">
          </a>
          <div class="jm-pub-body">
            <h3 class="jm-pub-title">Contrastive Decoupled Representation Learning and Regularization for Speech-Preserving Facial Expression Manipulation</h3>
            <p class="jm-pub-meta"><a href="https://scholar.google.com/citations?user=aNvkklMAAAAJ&amp;hl=en" target="_blank" rel="noopener noreferrer">Tianshui Chen</a>, <strong>Jianman Lin</strong>*, Zhijing Yang, <a href="https://scholar.google.com/citations?user=soX8e10AAAAJ&amp;hl=en" target="_blank" rel="noopener noreferrer">Chunmei Qing</a>, Yukai Shi, Liang Lin.</p>
            <p class="jm-pub-venue-line">
              <strong>International Journal of Computer Vision (IJCV)</strong>, 2025 · <span class="jm-ccf">CCF-A</span>
              <span class="jm-pub-links-inline">
                <a href="https://github.com/jianmanlincjx" target="_blank" rel="noopener noreferrer">Code</a>
                <a href="{{ '/publications/ijcv-2025-cdrl/' | relative_url }}">Page</a>
              </span>
            </p>
          </div>
        </article>
      </div>

      <div class="jm-pub-group">
        <div class="jm-pub-group-title">AI4Science &amp; Interdisciplinary</div>

        <article class="jm-pub-item">
          <a class="jm-pub-thumb" href="https://aiche.onlinelibrary.wiley.com/doi/abs/10.1002/aic.18924" target="_blank" rel="noopener noreferrer">
            <img src="{{ '/images/papers/AICHE.png' | relative_url }}" alt="AIChE Journal — DES viscosity prediction" loading="lazy">
          </a>
          <div class="jm-pub-body">
            <h3 class="jm-pub-title">Multiscale Exploration of Informative Latent Features for Accurate Deep Eutectic Solvents Viscosity Prediction</h3>
            <p class="jm-pub-meta"><strong>Jianman Lin</strong>, et al.</p>
            <p class="jm-pub-venue-line">
              <strong>AIChE Journal</strong> — flagship journal of the American Institute of Chemical Engineers; <em>top-tier in chemical engineering</em>.
              <span class="jm-pub-links-inline">
                <a href="https://github.com/jianmanlincjx" target="_blank" rel="noopener noreferrer">Code</a>
                <a href="{{ '/publications/aiche-des-viscosity-2025/' | relative_url }}">Page</a>
              </span>
            </p>
          </div>
        </article>
      </div>
    </section>

    <section class="jm-block" id="experience">
      <h2 class="jm-block-title">Experience</h2>
      <div class="jm-simple-item">
        <div class="jm-simple-head">
          <strong>Algorithm Research Intern, X-Era AI</strong>
          <span>Jan. 2024 – Present</span>
        </div>
        <div class="jm-simple-sub">Guangzhou, China</div>
        <ul class="jm-exp-projects">
          <li>
            <div class="jm-exp-project-head">
              <strong>Digital Human Live Streaming</strong>
              <span>2024.01 – 2024.12</span>
            </div>
            <p class="jm-exp-project-desc">Core algorithm lead for a production-grade digital human system; managed the end-to-end pipeline from data engineering and model design to seamless deployment.</p>
          </li>
          <li>
            <div class="jm-exp-project-head">
              <strong>Intelligent Interior Design &amp; VLM</strong>
              <span>2025.01 – 2026.03</span>
            </div>
            <p class="jm-exp-project-desc">Developed a VLM-based floor plan parser achieving 98% accuracy; architected an AI Agent for automated furniture layout and user-intent alignment.</p>
          </li>
          <li>
            <div class="jm-exp-project-head">
              <strong>Embodied AI</strong>
              <span>2026.03 – Present</span>
            </div>
            <p class="jm-exp-project-desc">Serving as a core researcher focused on the intersection of multimodal perception and robotic control for Embodied Intelligence.</p>
          </li>
        </ul>
      </div>
    </section>

    <section class="jm-block" id="education">
      <h2 class="jm-block-title">Education</h2>
      <div class="jm-simple-item">
        <div class="jm-simple-head">
          <strong>South China University of Technology (SCUT)</strong>
          <span>Sep. 2024 - Present</span>
        </div>
        <div class="jm-simple-sub">M.Eng. in Electronic Information · Guangzhou, China</div>
        <div class="jm-simple-note">Supervisors: <a href="https://scholar.google.com/citations?user=aNvkklMAAAAJ&amp;hl=en" target="_blank" rel="noopener noreferrer">Prof. Tianshui Chen</a> (research) and <a href="https://scholar.google.com/citations?user=soX8e10AAAAJ&amp;hl=en" target="_blank" rel="noopener noreferrer">Prof. Chunmei Qing</a> (academic)</div>
      </div>

      <div class="jm-simple-item">
        <div class="jm-simple-head">
          <strong>Guangdong University of Technology (GDUT)</strong>
          <span>Sep. 2020 - Jun. 2024</span>
        </div>
        <div class="jm-simple-sub">B.Eng. in Industrial Engineering · Guangzhou, China</div>
      </div>
    </section>
  </main>
</div>
