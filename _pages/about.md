---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
:root {
  --accent: #2563eb;
  --accent-light: #3b82f6;
  --accent-bg: rgba(37,99,235,0.08);
  --badge-oral: #dc2626;
  --badge-conf: #1e40af;
  --badge-arxiv: #6b7280;
  --card-bg: #ffffff;
  --card-border: #e5e7eb;
  --card-shadow: 0 1px 3px rgba(0,0,0,0.06), 0 1px 2px rgba(0,0,0,0.04);
  --card-shadow-hover: 0 10px 25px rgba(0,0,0,0.08);
  --section-title: #111827;
  --text-primary: #1f2937;
  --text-secondary: #6b7280;
  --text-link: #2563eb;
  --bg-body: #f9fafb;
  --tag-bg: #f3f4f6;
  --tag-text: #374151;
  --highlight-bg: #fef3c7;
  --highlight-text: #92400e;
  --divider: #e5e7eb;
}
[data-theme="dark"] {
  --accent: #60a5fa;
  --accent-light: #93c5fd;
  --accent-bg: rgba(96,165,250,0.1);
  --badge-oral: #f87171;
  --badge-conf: #93c5fd;
  --badge-arxiv: #9ca3af;
  --card-bg: #1e293b;
  --card-border: #334155;
  --card-shadow: 0 1px 3px rgba(0,0,0,0.2);
  --card-shadow-hover: 0 10px 25px rgba(0,0,0,0.3);
  --section-title: #f1f5f9;
  --text-primary: #e2e8f0;
  --text-secondary: #94a3b8;
  --text-link: #60a5fa;
  --bg-body: #0f172a;
  --tag-bg: #1e293b;
  --tag-text: #cbd5e1;
  --highlight-bg: rgba(251,191,36,0.15);
  --highlight-text: #fbbf24;
  --divider: #334155;
}
.theme-toggle{position:fixed;top:20px;right:20px;z-index:1000;background:var(--card-bg);border:1px solid var(--card-border);border-radius:50%;width:44px;height:44px;cursor:pointer;display:flex;align-items:center;justify-content:center;font-size:1.2rem;box-shadow:var(--card-shadow);transition:all .3s ease}
.theme-toggle:hover{transform:scale(1.1);box-shadow:var(--card-shadow-hover)}
.section-heading{font-family:'Source Serif 4','Georgia',serif;font-size:1.6rem;font-weight:700;color:var(--section-title);margin:2.5rem 0 1.2rem;padding-bottom:.5rem;border-bottom:2px solid var(--accent);display:flex;align-items:center;gap:.5rem}
.section-heading .icon{font-size:1.3rem}
.bio-text{font-family:'Inter',sans-serif;font-size:.95rem;line-height:1.75;color:var(--text-primary);margin-bottom:.8rem}
.bio-text a{color:var(--text-link);text-decoration:none;border-bottom:1px solid transparent;transition:border-color .2s}
.bio-text a:hover{border-bottom-color:var(--text-link)}
.research-interests{display:flex;flex-wrap:wrap;gap:.5rem;margin:.8rem 0}
.research-tag{background:var(--accent-bg);color:var(--accent);padding:.35rem .85rem;border-radius:20px;font-family:'Inter',sans-serif;font-size:.82rem;font-weight:500;transition:all .2s}
.research-tag:hover{transform:translateY(-1px);box-shadow:0 2px 8px rgba(37,99,235,0.15)}
.hiring-notice{background:var(--highlight-bg);color:var(--highlight-text);padding:.75rem 1rem;border-radius:8px;font-family:'Inter',sans-serif;font-size:.88rem;font-weight:500;margin:1rem 0;border-left:3px solid var(--highlight-text)}
.cv-link{display:inline-flex;align-items:center;gap:.3rem;background:var(--accent);color:#fff !important;padding:.35rem .9rem;border-radius:6px;font-family:'Inter',sans-serif;font-size:.82rem;font-weight:500;text-decoration:none !important;transition:all .2s;margin-left:.5rem}
.cv-link:hover{opacity:.9;transform:translateY(-1px)}
.pub-note{font-family:'Inter',sans-serif;font-size:.8rem;color:var(--text-secondary);font-style:italic;margin-bottom:1rem}
.pub-card{display:flex;gap:1rem;background:var(--card-bg);border:1px solid var(--card-border);border-radius:10px;padding:1rem;margin-bottom:1rem;box-shadow:var(--card-shadow);transition:all .3s ease}
.pub-card:hover{box-shadow:var(--card-shadow-hover);transform:translateY(-2px)}
.pub-thumb{flex-shrink:0;width:180px;height:110px;border-radius:6px;overflow:hidden;background:var(--tag-bg);display:flex;align-items:center;justify-content:center}
.pub-thumb img{width:100%;height:100%;object-fit:cover}
.pub-thumb-placeholder{font-size:2rem;color:var(--text-secondary);opacity:.4}
.pub-info{flex:1;min-width:0}
.pub-title{font-family:'Source Serif 4','Georgia',serif;font-size:.95rem;font-weight:650;color:var(--section-title);line-height:1.4;margin-bottom:.3rem}
.pub-authors{font-family:'Inter',sans-serif;font-size:.8rem;color:var(--text-secondary);line-height:1.5;margin-bottom:.3rem}
.pub-authors .me{color:var(--accent);font-weight:600}
.pub-venue{display:inline-flex;align-items:center;gap:.4rem;margin-bottom:.4rem}
.pub-badge{display:inline-block;padding:.15rem .55rem;border-radius:4px;font-family:'Inter',sans-serif;font-size:.7rem;font-weight:600;letter-spacing:.3px;color:#fff}
.pub-badge.conf{background:var(--badge-conf)}
.pub-badge.oral{background:var(--badge-oral)}
.pub-badge.arxiv{background:var(--badge-arxiv)}
.pub-badge.new-paper{background:linear-gradient(135deg,#f59e0b,#ef4444);animation:pulse-badge 2s infinite}
@keyframes pulse-badge{0%,100%{opacity:1}50%{opacity:.7}}
.pub-links{display:flex;gap:.4rem;flex-wrap:wrap}
.pub-link-btn{display:inline-flex;align-items:center;gap:.25rem;padding:.2rem .6rem;border-radius:5px;font-family:'Inter',sans-serif;font-size:.72rem;font-weight:500;text-decoration:none !important;border:1px solid var(--card-border);color:var(--text-primary) !important;background:var(--card-bg);transition:all .2s}
.pub-link-btn:hover{border-color:var(--accent);color:var(--accent) !important;background:var(--accent-bg)}
.intern-item{display:flex;align-items:flex-start;gap:1rem;padding:.8rem 0;border-bottom:1px solid var(--divider);transition:all .2s}
.intern-item:last-child{border-bottom:none}
.intern-logo{flex-shrink:0;width:40px;height:40px;border-radius:8px;overflow:hidden;display:flex;align-items:center;justify-content:center;background:var(--tag-bg)}
.intern-logo img{width:100%;height:100%;object-fit:contain;padding:4px}
.intern-content{flex:1}
.intern-header{font-family:'Inter',sans-serif;font-size:.9rem;font-weight:600;color:var(--section-title)}
.intern-meta{font-family:'Inter',sans-serif;font-size:.78rem;color:var(--text-secondary);margin-top:.15rem}
.intern-desc{font-family:'Inter',sans-serif;font-size:.8rem;color:var(--text-secondary);margin-top:.25rem;line-height:1.5}
.award-list,.service-list{list-style:none;padding:0;margin:0}
.award-list li,.service-list li{font-family:'Inter',sans-serif;font-size:.88rem;color:var(--text-primary);padding:.45rem 0;border-bottom:1px solid var(--divider);display:flex;align-items:center;gap:.5rem}
.award-list li:last-child,.service-list li:last-child{border-bottom:none}
.award-year{font-size:.75rem;color:var(--text-secondary);font-weight:500;flex-shrink:0;width:40px}
.fade-in{opacity:0;transform:translateY(20px);transition:opacity .6s ease,transform .6s ease}
.fade-in.visible{opacity:1;transform:translateY(0)}
@media(max-width:768px){.pub-card{flex-direction:column}.pub-thumb{width:100%;height:160px}.theme-toggle{top:10px;right:10px;width:38px;height:38px;font-size:1rem}}
</style>

<button class="theme-toggle" id="themeToggle" onclick="toggleTheme()" title="Toggle dark/light mode">🌙</button>

<h2 class="section-heading fade-in"><span class="icon">✨</span> Biography <a href="files/CV_ZhengrongYue.pdf" class="cv-link">📄 CV</a></h2>

<p class="bio-text fade-in">I am a Ph.D. student at <a href="https://www.sjtu.edu.cn/">Shanghai Jiao Tong University</a> and <a href="https://github.com/OpenGVLab">Shanghai AI Lab</a>. My advisor is <a href="https://scholar.google.com/citations?hl=zh-CN&user=hD948dkAAAAJ">Prof. Yali Wang</a>. I received my B.S. degree in Computer Science and Technology from China University of Mining and Technology (Beijing) in 2024.</p>

<p class="bio-text fade-in">Currently, I am a Research Intern at <strong>Meituan LongCat M17</strong>. I have also spent wonderful time as a research intern at <strong>Alibaba</strong>,<strong>Huawei Noah's Ark Lab</strong>, <strong>Shanghai AI Lab</strong>, <strong>SIAT</strong>, and <strong>Samsung</strong>.</p>

<p class="bio-text fade-in">My research interests include:</p>
<div class="research-interests fade-in">
  <span class="research-tag">🔗 Unified Multimodal Understanding & Generation</span>
  <span class="research-tag">🌐 Omni-modal Representation Learning</span>
  <span class="research-tag">🎬 Video Understanding & Generation</span>
  <span class="research-tag">🤖 Multimodal Agents</span>
</div>

<div class="hiring-notice fade-in">🔥 I'm actively pursuing intern opportunities in Multimodal Understanding and Generation. Feel free to reach out for potential collaborations.</div>

<h2 class="section-heading fade-in"><span class="icon">📑</span> Publications</h2>
<p class="pub-note fade-in">* indicates equal contribution</p>


<div class="pub-card fade-in">
  <div class="pub-thumb"><img src="images/pae.png" onerror="this.style.display='none';this.parentElement.innerHTML='<span class=pub-thumb-placeholder>📄</span>';" alt="PAE"></div>
  <div class="pub-info">
    <div class="pub-title">What Matters for Diffusion-Friendly Latent Manifold? Prior-Aligned Autoencoders for Latent Diffusion</div>
    <div class="pub-authors"><span class="me">Zhengrong Yue</span>, Taihang Hu, Mengting Chen, Haiyu Zhang, Zihao Pan, Tao Liu, Zikang Wang, Jinsong Lan, Xiaoyong Zhu, Bo Zheng, Yali Wang</div>
    <div class="pub-venue"><span class="pub-badge arxiv">Arxiv 2026</span> <span class="pub-badge new-paper">New</span></div>
    <div class="pub-links"><a href="#" class="pub-link-btn">📄 Paper</a> <a href="#" class="pub-link-btn">💻 Code</a></div>
  </div>
</div>

<div class="pub-card fade-in">
  <div class="pub-thumb"><img src="images/uniflow.png" onerror="this.style.display='none';this.parentElement.innerHTML='<span class=pub-thumb-placeholder>📄</span>';" alt="UniFlow"></div>
  <div class="pub-info">
    <div class="pub-title">UniFlow: A Unified Pixel Flow Tokenizer for Visual Understanding and Generation</div>
    <div class="pub-authors"><span class="me">Zhengrong Yue</span>, Haiyu Zhang, Xiangyu Zeng, Boyu Chen, Chenting Wang, Shaobin Zhuang, Lu Dong, Kunpeng Du, Yi Wang, Limin Wang, Yali Wang</div>
    <div class="pub-venue"><span class="pub-badge conf">ICLR 2026</span> <span class="pub-badge new-paper">New</span></div>
    <div class="pub-links"><a href="#" class="pub-link-btn">📄 Paper</a> <a href="#" class="pub-link-btn">💻 Code</a></div>
  </div>
</div>

<div class="pub-card fade-in">
  <div class="pub-thumb"><img src="images/beyond_cot.png" onerror="this.style.display='none';this.parentElement.innerHTML='<span class=pub-thumb-placeholder>📄</span>';" alt="Beyond CoT"></div>
  <div class="pub-info">
    <div class="pub-title">Beyond Textual CoT: Interleaved Text-Image Chains with Deep Confidence Reasoning for Image Editing</div>
    <div class="pub-authors">Zhentao Zou*, <span class="me">Zhengrong Yue</span>*, Kunpeng Du, Binlei Bao, Hanting Li, Haizhen Xie, Guozheng Xu, Yue Zhou, Yali Wang, Jie Hu, Xue Jiang, Xinghao Chen</div>
    <div class="pub-venue"><span class="pub-badge arxiv">Arxiv 2025</span> <span class="pub-badge new-paper">New</span></div>
    <div class="pub-links"><a href="#" class="pub-link-btn">📄 Paper</a> <a href="#" class="pub-link-btn">💻 Code</a></div>
  </div>
</div>

<div class="pub-card fade-in">
  <div class="pub-thumb"><img src="images/videochat_m1.png" onerror="this.style.display='none';this.parentElement.innerHTML='<span class=pub-thumb-placeholder>📄</span>';" alt="VideoChat-M1"></div>
  <div class="pub-info">
    <div class="pub-title">VideoChat-M1: Collaborative Policy Planning for Video Understanding via Multi-Agent Reinforcement Learning</div>
    <div class="pub-authors">Boyu Chen*, Zikang Wang*, <span class="me">Zhengrong Yue</span>*, Kainan Yan*, Chenyun Yu, Yi Huang, Zijun Liu, Yafei Wen, Xiaoxin Chen, Yang Liu, Peng Li, Yali Wang</div>
    <div class="pub-venue"><span class="pub-badge conf">CVPR 2026</span></div>
    <div class="pub-links"><a href="#" class="pub-link-btn">📄 Paper</a> <a href="#" class="pub-link-btn">💻 Code</a></div>
  </div>
</div>

<div class="pub-card fade-in">
  <div class="pub-thumb"><img src="images/videochat_a1.png" onerror="this.style.display='none';this.parentElement.innerHTML='<span class=pub-thumb-placeholder>📄</span>';" alt="VideoChat-A1"></div>
  <div class="pub-info">
    <div class="pub-title">VideoChat-A1: Thinking with Long Videos by Chain-of-Shot Reasoning</div>
    <div class="pub-authors">Zikang Wang*, Boyu Chen*, <span class="me">Zhengrong Yue</span>*, Yi Wang, Yu Qiao, Limin Wang, Yali Wang</div>
    <div class="pub-venue"><span class="pub-badge conf">AAAI 2026</span> <span class="pub-badge oral">Oral</span></div>
    <div class="pub-links"><a href="#" class="pub-link-btn">📄 Paper</a> <a href="#" class="pub-link-btn">💻 Code</a></div>
  </div>
</div>

<div class="pub-card fade-in">
  <div class="pub-thumb"><img src="images/gubs.png" onerror="this.style.display='none';this.parentElement.innerHTML='<span class=pub-thumb-placeholder>📄</span>';" alt="G-UBS"></div>
  <div class="pub-info">
    <div class="pub-title">G-UBS: Towards Robust Understanding of Implicit Feedback via Group-Aware User Behavior Simulation</div>
    <div class="pub-authors">Boyu Chen*, Siran Chen*, <span class="me">Zhengrong Yue</span>*, Kainan Yan, Chenyun Yu, Beibei Kong, Cheng Lei, Chengxiang Zhuo, Zang Li, Yali Wang</div>
    <div class="pub-venue"><span class="pub-badge conf">AAAI 2026</span></div>
    <div class="pub-links"><a href="#" class="pub-link-btn">📄 Paper</a> <a href="#" class="pub-link-btn">💻 Code</a></div>
  </div>
</div>

<div class="pub-card fade-in">
  <div class="pub-thumb"><img src="images/vtts.png" onerror="this.style.display='none';this.parentElement.innerHTML='<span class=pub-thumb-placeholder>📄</span>';" alt="VTTS"></div>
  <div class="pub-info">
    <div class="pub-title">VTTS: Visual Test-Time Scaling to Reinforce Multimodal Reasoning by Iterative Perception</div>
    <div class="pub-authors">Ziang Yan*, Yinan He*, Xinhao Li*, <span class="me">Zhengrong Yue</span>*, Xiangyu Zeng, Yali Wang, Yu Qiao, Limin Wang, Yi Wang</div>
    <div class="pub-venue"><span class="pub-badge conf">NeurIPS 2025</span></div>
    <div class="pub-links"><a href="#" class="pub-link-btn">📄 Paper</a> <a href="#" class="pub-link-btn">💻 Code</a></div>
  </div>
</div>

<div class="pub-card fade-in">
  <div class="pub-thumb"><img src="images/lvagent.png" onerror="this.style.display='none';this.parentElement.innerHTML='<span class=pub-thumb-placeholder>📄</span>';" alt="LVAgent"></div>
  <div class="pub-info">
    <div class="pub-title">LVAgent: Dynamic Round-by-round MLLM Agent Collaboration for Long Video Understanding</div>
    <div class="pub-authors">Boyu Chen*, <span class="me">Zhengrong Yue</span>*, Siran Chen*, Zikang Wang, Yang Liu, Peng Li, Yali Wang</div>
    <div class="pub-venue"><span class="pub-badge conf">ICCV 2025</span></div>
    <div class="pub-links"><a href="#" class="pub-link-btn">📄 Paper</a> <a href="#" class="pub-link-btn">💻 Code</a></div>
  </div>
</div>

<div class="pub-card fade-in">
  <div class="pub-thumb"><img src="images/vstylist.png" onerror="this.style.display='none';this.parentElement.innerHTML='<span class=pub-thumb-placeholder>📄</span>';" alt="V-Stylist"></div>
  <div class="pub-info">
    <div class="pub-title">V-Stylist: Video Stylization via Collaboration and Reflection of MLLM Agents</div>
    <div class="pub-authors"><span class="me">Zhengrong Yue</span>, Shaobin Zhuang, Kunchang Li, Yanbo Ding, Yali Wang</div>
    <div class="pub-venue"><span class="pub-badge conf">CVPR 2025</span></div>
    <div class="pub-links"><a href="#" class="pub-link-btn">📄 Paper</a> <a href="#" class="pub-link-btn">💻 Code</a></div>
  </div>
</div>

<div class="pub-card fade-in">
  <div class="pub-thumb"><img src="images/timesuite.png" onerror="this.style.display='none';this.parentElement.innerHTML='<span class=pub-thumb-placeholder>📄</span>';" alt="TimeSuite"></div>
  <div class="pub-info">
    <div class="pub-title">TimeSuite: Improving MLLMs for Long Video Understanding via Grounded Tuning</div>
    <div class="pub-authors">Xiangyu Zeng, Kunchang Li, Chenting Wang, Xinhao Li, Tianxiang Jiang, Ziang Yan, Songze Li, Yansong Shi, <span class="me">Zhengrong Yue</span>, Yi Wang, Yali Wang, Yu Qiao, Limin Wang</div>
    <div class="pub-venue"><span class="pub-badge conf">ICLR 2025</span></div>
    <div class="pub-links"><a href="#" class="pub-link-btn">📄 Paper</a> <a href="#" class="pub-link-btn">💻 Code</a></div>
  </div>
</div>

<div class="pub-card fade-in">
  <div class="pub-thumb"><img src="images/muses.png" onerror="this.style.display='none';this.parentElement.innerHTML='<span class=pub-thumb-placeholder>📄</span>';" alt="Muses"></div>
  <div class="pub-info">
    <div class="pub-title">Muses: 3D-Controllable Image Generation via Multi-Modal Agent Collaboration</div>
    <div class="pub-authors">Yanbo Ding, Shaobin Zhuang, Kunchang Li, <span class="me">Zhengrong Yue</span>, Yu Qiao, Yali Wang</div>
    <div class="pub-venue"><span class="pub-badge conf">AAAI 2025</span></div>
    <div class="pub-links"><a href="#" class="pub-link-btn">📄 Paper</a> <a href="#" class="pub-link-btn">💻 Code</a></div>
  </div>
</div>

<h2 class="section-heading fade-in"><span class="icon">🤵🏻</span> Internships</h2>

<div class="fade-in">

<div class="intern-item">
  <div class="intern-logo"><img src="images/meituan" alt="MeiTuan"></div>
  <div class="intern-content">
    <div class="intern-header">MeiTuan — BeiDou Research Intern (LongCat M17)</div>
    <div class="intern-meta">June 2026 – Present</div>
    <div class="intern-desc">Unified MLLM; World Model.</div>
  </div>
</div>

<div class="intern-item">
  <div class="intern-logo"><img src="images/alibaba.png" alt="Alibaba"></div>
  <div class="intern-content">
    <div class="intern-header">Alibaba — T-Star Research Intern (Taotian Group)</div>
    <div class="intern-meta">Jan 2026 – June 2026</div>
    <div class="intern-desc">Representation Tokenizer; Unified Reward Model for Generation and Editing.</div>
  </div>
</div>
<div class="intern-item">
  <div class="intern-logo"><img src="images/huawei.png" alt="Huawei"></div>
  <div class="intern-content">
    <div class="intern-header">Huawei — Research Intern (Noah's Ark Lab)</div>
    <div class="intern-meta">July 2025 – Dec 2025</div>
    <div class="intern-desc">Image Editing Model Based on Text-Image Interwoven Thought Chains; Unified Multimodal Model.</div>
  </div>
</div>
<div class="intern-item">
  <div class="intern-logo"><img src="images/opengvlab.png" alt="Shanghai AI Lab"></div>
  <div class="intern-content">
    <div class="intern-header">Shanghai AI Lab — Research Intern (OpenGVLab)</div>
    <div class="intern-meta">July 2024 – June 2025</div>
    <div class="intern-desc">Unified Tokenizer; Video Understanding and Generation tasks within multimodal frameworks.</div>
  </div>
</div>
<div class="intern-item">
  <div class="intern-logo"><img src="images/siat.png" alt="SIAT"></div>
  <div class="intern-content">
    <div class="intern-header">SIAT — Research Intern (Multimedia Lab)</div>
    <div class="intern-meta">Nov 2023 – June 2024</div>
    <div class="intern-desc">Explored video style editing based on MLLM Agents.</div>
  </div>
</div>
<div class="intern-item">
  <div class="intern-logo"><img src="images/samsung.png" alt="Samsung"></div>
  <div class="intern-content">
    <div class="intern-header">Samsung — Research Intern (LUL Lab)</div>
    <div class="intern-meta">Sept 2023 – Nov 2023</div>
    <div class="intern-desc">Multilingual document question-answering large model for Galaxy Z-Fold based on RAG.</div>
  </div>
</div>
</div>

<h2 class="section-heading fade-in"><span class="icon">🏅</span> Honors & Awards</h2>
<ul class="award-list fade-in">
  <li><span class="award-year">2024</span> <strong>Outstanding Graduate</strong> of Beijing</li>
  <li><span class="award-year">2023</span> <strong>National Scholarship</strong> (Top 1%)</li>
  <li><span class="award-year">2023</span> <strong>Beijing Municipal Triple-Excellent Student</strong></li>
  <li><span class="award-year">2022</span> <strong>1st Prize</strong>, National Robot and Artificial Intelligence Competition</li>
  <li><span class="award-year">2022</span> <strong>1st Prize</strong>, National University Student Intelligent Vehicle Competition</li>
</ul>

<h2 class="section-heading fade-in"><span class="icon">🤝</span> Academic Services</h2>
<ul class="service-list fade-in">
  <li>📋 <strong>Conference Reviewer:</strong> CVPR 2026, ECCV 2026</li>
  <li>📰 <strong>Journal Reviewer:</strong> IEEE TPAMI</li>
</ul>

<script>
function toggleTheme(){var h=document.documentElement,b=document.getElementById('themeToggle');if(h.getAttribute('data-theme')==='dark'){h.removeAttribute('data-theme');b.textContent='🌙';localStorage.setItem('theme','light');}else{h.setAttribute('data-theme','dark');b.textContent='☀️';localStorage.setItem('theme','dark');}}
(function(){var s=localStorage.getItem('theme');if(s==='dark'){document.documentElement.setAttribute('data-theme','dark');setTimeout(function(){var b=document.getElementById('themeToggle');if(b)b.textContent='☀️';},0);}})();
document.addEventListener('DOMContentLoaded',function(){var els=document.querySelectorAll('.fade-in');if('IntersectionObserver' in window){var obs=new IntersectionObserver(function(entries){entries.forEach(function(e){if(e.isIntersecting){e.target.classList.add('visible');obs.unobserve(e.target);}});},{threshold:0.1,rootMargin:'0px 0px -40px 0px'});els.forEach(function(el){obs.observe(el);});}else{els.forEach(function(el){el.classList.add('visible');});}});
</script>
