---
permalink: /
title:
author_profile: false
---

{% include base_path %}

<div class="jm-homepage" markdown="0">
  <aside class="jm-sidebar">
    <div class="jm-profile-card">
      {% if site.author.avatar %}
        <img class="jm-avatar" src="{{ base_path }}/images/{{ site.author.avatar }}" alt="{{ site.author.name }}">
      {% else %}
        <div class="jm-avatar jm-avatar--placeholder">JL</div>
      {% endif %}

      <h1 class="jm-name">Jianman Lin</h1>
      <p class="jm-role">M.Eng. student at SCUT, advised by Prof. Tianshui Chen and Prof. Chunmei Qing</p>

      <ul class="jm-contact">
        <li>Guangzhou, China</li>
        <li><a href="mailto:linjianmancjx@gmail.com">Email</a></li>
        <li><a href="https://scholar.google.com/citations?user=ayk7FWMAAAAJ&amp;hl=en" target="_blank" rel="noopener noreferrer">Google Scholar</a></li>
        <li><a href="https://github.com/jianmanlincjx" target="_blank" rel="noopener noreferrer">GitHub</a></li>
        <li><a href="{{ base_path }}/files/Jianman_Lin_CV.pdf">CV (PDF)</a></li>
      </ul>
    </div>
  </aside>

  <main class="jm-main">
    <section class="jm-block" id="about">
      <h2 class="jm-block-title">About Me</h2>
      <p>
        I am a master's student in Electronic Information at the South China University of Technology (SCUT),
        supervised by <strong>Prof. Tianshui Chen</strong> and <strong>Prof. Chunmei Qing</strong>. My research focuses on
        <strong>computer vision</strong>, <strong>generative AI</strong>, and <strong>controllable image synthesis</strong>.
      </p>
      <p>
        My recent work spans two lines: speech-preserving facial expression manipulation under data scarcity,
        and diffusion-based controllable image editing that balances editability with appearance consistency.
        I am also interested in practical vision systems for structured scene understanding and intelligent design.
      </p>
      <p>
        Before SCUT, I received my B.Eng. in Industrial Engineering from Guangdong University of Technology (GDUT),
        where I built my foundation in computer vision, optimization, and data-driven modeling.
      </p>
    </section>

    <section class="jm-block" id="news">
      <h2 class="jm-block-title">News</h2>
      <ul class="jm-news-list">
        <li><span>2025</span> Neural Scene Designer was published in <strong>IEEE TIP</strong>.</li>
        <li><span>2025</span> CDRL was published in <strong>IJCV</strong>.</li>
        <li><span>2024</span> ASCCL was selected as a <strong>CVPR 2024 Highlight</strong> (Top 2.8%).</li>
        <li><span>2024</span> Joined <strong>ExpanderaAI</strong> as an algorithm researcher intern.</li>
        <li><span>2024</span> Started M.Eng. study at <strong>SCUT</strong>.</li>
      </ul>
    </section>

    <section class="jm-block" id="publications">
      <h2 class="jm-block-title">Selected Publications</h2>

      <div class="jm-pub-group">
        <div class="jm-pub-group-title">Controllable Image Editing</div>

        <article class="jm-pub-item">
          <a class="jm-pub-thumb" href="https://arxiv.org/pdf/2509.01405" target="_blank" rel="noopener noreferrer">
            <img src="{{ base_path }}/images/papers/TIP_2025_NSD.png" alt="TIP 2025 NSD">
          </a>
          <div class="jm-pub-body">
            <h3 class="jm-pub-title">Neural Scene Designer: Self-Styled Semantic Image Manipulation</h3>
            <p class="jm-pub-meta"><strong>Jianman Lin</strong>, Tianshui Chen, Chunmei Qing, Zhijing Yang, Shuangping Huang, Yuheng Ren, Liang Lin.</p>
            <p class="jm-pub-meta"><strong>IEEE Transactions on Image Processing (TIP)</strong>, 2025.</p>
            <p class="jm-pub-links">
              <a href="https://arxiv.org/pdf/2509.01405" target="_blank" rel="noopener noreferrer">Paper</a>
              <a href="{{ base_path }}/publications/neural-scene-designer-tip/">Page</a>
            </p>
            <ul class="jm-pub-points">
              <li>Self-supervised style modeling from intra-image consistency.</li>
              <li>Diffusion framework with dual parallel cross-attention for text/style control.</li>
            </ul>
          </div>
        </article>

        <article class="jm-pub-item">
          <a class="jm-pub-thumb" href="https://arxiv.org/pdf/2505.20914" target="_blank" rel="noopener noreferrer">
            <img src="{{ base_path }}/images/papers/underreview_2026_DAGD.png" alt="DAGD">
          </a>
          <div class="jm-pub-body">
            <h3 class="jm-pub-title">Geometry-Editable and Appearance-Preserving Object Composition</h3>
            <p class="jm-pub-meta"><strong>Jianman Lin</strong>, Haojie Li, Chunmei Qing, Zhijing Yang, Liang Lin, Tianshui Chen.</p>
            <p class="jm-pub-meta"><strong>Under review</strong>.</p>
            <p class="jm-pub-links">
              <a href="https://arxiv.org/pdf/2505.20914" target="_blank" rel="noopener noreferrer">arXiv</a>
              <a href="{{ base_path }}/publications/ijcv-2025-dagd/">Page</a>
            </p>
            <ul class="jm-pub-points">
              <li>Geometry-first, appearance-follows disentanglement for controllable composition.</li>
              <li>Preserves fine-grained texture under geometric transformation.</li>
            </ul>
          </div>
        </article>
      </div>

      <div class="jm-pub-group">
        <div class="jm-pub-group-title">Speech-Preserving Facial Expression Manipulation</div>

        <article class="jm-pub-item">
          <a class="jm-pub-thumb" href="https://openaccess.thecvf.com/content/CVPR2024/papers/Chen_Learning_Adaptive_Spatial_Coherent_Correlations_for_Speech-Preserving_Facial_Expression_Manipulation_CVPR_2024_paper.pdf" target="_blank" rel="noopener noreferrer">
            <img src="{{ base_path }}/images/papers/CVPR_2024_ASCCL.png" alt="CVPR 2024 ASCCL">
          </a>
          <div class="jm-pub-body">
            <h3 class="jm-pub-title">Learning Adaptive Spatial Coherent Correlations for Speech-Preserving Facial Expression Manipulation</h3>
            <p class="jm-pub-meta">Tianshui Chen, <strong>Jianman Lin</strong>, Zhijing Yang, Chunmei Qing, Liang Lin.</p>
            <p class="jm-pub-meta"><strong>CVPR 2024</strong> · Highlight (Top 2.8%).</p>
            <p class="jm-pub-links">
              <a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Chen_Learning_Adaptive_Spatial_Coherent_Correlations_for_Speech-Preserving_Facial_Expression_Manipulation_CVPR_2024_paper.pdf" target="_blank" rel="noopener noreferrer">Paper</a>
              <a href="{{ base_path }}/publications/cvpr-2024-asccl/">Page</a>
            </p>
            <ul class="jm-pub-points">
              <li>Models spatial-coherent correlations with minimal paired data.</li>
              <li>Improves fine-grained mouth animation preservation.</li>
            </ul>
          </div>
        </article>

        <article class="jm-pub-item">
          <a class="jm-pub-thumb" href="https://arxiv.org/pdf/2504.05672" target="_blank" rel="noopener noreferrer">
            <img src="{{ base_path }}/images/papers/IJCV_2025_CDRL.png" alt="IJCV 2025 CDRL">
          </a>
          <div class="jm-pub-body">
            <h3 class="jm-pub-title">Contrastive Decoupled Representation Learning and Regularization for Speech-Preserving Facial Expression Manipulation</h3>
            <p class="jm-pub-meta">Tianshui Chen, <strong>Jianman Lin</strong>*, Zhijing Yang, Chunmei Qing, Yukai Shi, Liang Lin.</p>
            <p class="jm-pub-meta"><strong>International Journal of Computer Vision (IJCV)</strong>, 2025.</p>
            <p class="jm-pub-links">
              <a href="https://arxiv.org/pdf/2504.05672" target="_blank" rel="noopener noreferrer">Paper</a>
              <a href="{{ base_path }}/publications/ijcv-2025-cdrl/">Page</a>
            </p>
            <ul class="jm-pub-points">
              <li>Decouples content and emotion using audio and VLM priors.</li>
              <li>Improves expression transfer accuracy and lip synchronization.</li>
            </ul>
          </div>
        </article>
      </div>

      <p class="jm-more-link"><a href="{{ base_path }}/publications/">View full publication list</a></p>
    </section>

    <section class="jm-block" id="research">
      <h2 class="jm-block-title">Research Summary</h2>
      <p>
        <strong>Research interests:</strong> computer vision, generative AI, controllable image synthesis, and
        multimodal understanding for visual generation.
      </p>
      <p>
        <strong>Research trajectory:</strong> from representation learning for speech-preserving facial expression manipulation
        to diffusion-based disentangled editing for geometry and appearance control.
      </p>
    </section>

    <section class="jm-block" id="experience">
      <h2 class="jm-block-title">Experience</h2>
      <div class="jm-simple-item">
        <div class="jm-simple-head">
          <strong>Algorithm Researcher Intern, ExpanderaAI</strong>
          <span>Jul. 2024 - Present</span>
        </div>
        <div class="jm-simple-sub">AI Interior Design Lab · Guangzhou, China</div>
        <ul class="jm-pub-points">
          <li>Led VLM-based structured floor-plan reconstruction from sparse image inputs.</li>
          <li>Built a 500k+ image processing pipeline for paired data construction.</li>
          <li>Improved spatial reasoning with curriculum RL to reach &lt; 3 cm dimension error.</li>
          <li>Contributed to MLLM-driven interior layout generation with physical and aesthetic priors.</li>
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
        <div class="jm-simple-sub">M.Eng. in Electronic Information · Guangzhou, China · GPA 80/100</div>
        <div class="jm-simple-note">Supervisors: Prof. Tianshui Chen (research) and Prof. Chunmei Qing (academic)</div>
      </div>

      <div class="jm-simple-item">
        <div class="jm-simple-head">
          <strong>Guangdong University of Technology (GDUT)</strong>
          <span>Sep. 2020 - Jun. 2024</span>
        </div>
        <div class="jm-simple-sub">B.Eng. in Industrial Engineering · Guangzhou, China · GPA 87.2/100</div>
      </div>
    </section>
  </main>
</div>
