<style>
  section.cover {
    background: linear-gradient(135deg, #0f2027 0%, #203a43 50%, #2c5364 100%);
    color: #fff !important;
    min-height: 100vh;
  }
  section.cover h1, section.cover h2, section.cover blockquote, section.cover p { color: #fff !important; }
  section.cover .avatar {
    width: 160px; height: 160px; border-radius: 50%;
    border: 4px solid transparent;
    background: linear-gradient(45deg, #f093fb, #f5576c, #4facfe) border-box;
    -webkit-mask: linear-gradient(#fff 0 0) padding-box, linear-gradient(#fff 0 0);
    -webkit-mask-composite: xor; mask-composite: exclude;
    box-shadow: 0 0 40px rgba(240,147,251,0.4), 0 0 80px rgba(79,172,254,0.4);
    animation: rotateAvatar 10s linear infinite;
  }
  @keyframes rotateAvatar {
    0% { filter: hue-rotate(0deg); }
    100% { filter: hue-rotate(360deg); }
  }
  section.cover blockquote { border-left: none !important; background: rgba(255,255,255,0.1); padding: 1rem 1.5rem; border-radius: 16px; backdrop-filter: blur(10px); border: 1px solid rgba(255,255,255,0.2); }
  section.cover a.button {
    background: linear-gradient(90deg, #4facfe 0%, #00f2fe 100%);
    border: none !important; color: #000 !important; padding: 12px 36px !important;
    border-radius: 14px !important; font-weight: 700 !important;
    box-shadow: 0 10px 30px rgba(79,172,254,0.5);
    transition: all .3s ease;
  }
  section.cover a.button:hover { transform: translateY(-4px) scale(1.05); box-shadow: 0 16px 40px rgba(0,242,254,0.6); }
  section.cover a.button.secondary {
    background: rgba(255,255,255,0.08); border: 2px solid rgba(255,255,255,0.4) !important; color: #fff !important; margin-left: 12px;
  }
</style>

<!-- 粒子背景容器（必须有，JS会往这里填粒子） -->
<div id="tsparticles"></div>

<img class="avatar" src="https://coresg-normal.trae.ai/api/ide/v1/text_to_image?prompt=a%20friendly%20young%20asian%20male%20product%20manager%20portrait%2C%20professional%2C%20tech%20industry%2C%20modern%20style%2C%20blue%20purple%20lighting%2C%20headshot&image_size=square" alt="陈辉阳头像" />

# 👋 你好，我是陈辉阳
## AI 产品经理 · 作品集

> **踩过 Vibe Coding 的坑 → 沉淀 AI 代码审查 12 条 Checklist → 懂大模型能力边界的「技术型 AI PM」**

<p style="margin-top: 1.5rem;">
  <span class="float-tag">🧠 懂 RAG / Agent / Evals</span>
  <span class="float-tag">💻 软工科班 · 听得懂开发语言</span>
  <span class="float-tag">🤝 对接过 5 家 B 端客户</span>
  <span class="float-tag">🛒 X 年电商行业背景</span>
</p>

<p style="margin-top: 1.5rem; font-size: 1.15rem; min-height: 2rem; color: #92eaff;">
  <span id="typed-strings"></span>
</p>

<hr style="border: none; height: 1px; background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent); margin: 2rem 15%;" />

<p style="margin-top: 1rem;">
  <a class="button" href="#/个人简历">📄 在线简历</a>
  <a class="button secondary" href="#/作品集案例/01-多模态发票智能识别系统">💼 3 个项目案例</a>
</p>

<p style="margin-top: 2rem; font-size: 0.9rem; color: rgba(255,255,255,0.8);">
  🔍 点击右上角搜索快速查找项目 · 📱 手机端完整适配 · ✉️ chenhuiyang_ai@163.com
</p>
