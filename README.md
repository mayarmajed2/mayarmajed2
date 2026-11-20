<!-- ===================== PROFILE HEADER ===================== -->

<div align="center">

<img src="assets/profile-banner.svg" alt="Mayar Majed Hussien — Machine Learning, Generative AI & AI Agents" width="100%" />

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Plus+Jakarta+Sans&weight=700&size=19&duration=3200&pause=900&color=FF4D8D&center=true&vCenter=true&width=760&lines=Building+Machine+Learning+%26+Deep+Learning+Models;Exploring+Computer+Vision%2C+NLP+%26+Multimodal+GenAI;Designing+Collaborative+Multi-Agent+AI+Systems;Turning+Creative+AI+Ideas+Into+Interactive+Apps" alt="Typing Animation" />

<br/>

<a href="https://github.com/mayarmajed2">
  <img src="https://img.shields.io/badge/GitHub-mayarmajed2-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>
<a href="https://www.kaggle.com/mayarmajed">
  <img src="https://img.shields.io/badge/Kaggle-Notebooks-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle" />
</a>
<a href="https://huggingface.co/mayarmajed">
  <img src="https://img.shields.io/badge/Hugging%20Face-Models%20%26%20Spaces-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" />
</a>
<a href="mailto:m.fathallah2386@su.edu.eg">
  <img src="https://img.shields.io/badge/Email-Say%20Hello-7C5CFF?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>

</div>

<img src="assets/section-divider.svg" width="100%" alt="" />

## 👋 Get to Know Me

Hi, I'm **Mayar** — a Machine Learning Engineer and Information Technology & Computer Science student at **Sinai University**, based in **Cairo, Egypt**.

I love exploring how intelligent systems learn, perceive, and create. Most of my time goes into working with datasets, training neural networks, experimenting with **Computer Vision, NLP, and Multimodal Generative AI**, and designing **multi-agent systems** where AI models collaborate to solve practical problems.

- 🎓 **Studying:** B.Sc. in Information Technology & Computer Science at Sinai University
- 🧠 **What excites me:** Connecting creative AI (like turning human emotions into paintings) with structured engineering (like autonomous agent workflows)
- 🌱 **Currently exploring:** LLM orchestration, Model Context Protocol (MCP), and multimodal pipelines
- 🌐 **Languages:** Arabic (Native) · English (C1)

<br/>

<div align="center">
  <img src="assets/ai-pipeline-flow.svg" alt="How I Work With AI — Perception, Deep Learning, Multimodal GenAI, and Multi-Agent Systems" width="100%" />
</div>

<details>
<summary><strong>✨ Click to expand: How I approach an AI problem from idea to interactive app</strong></summary>

<br/>

1. **Understand the Data & Signal:** Start with Exploratory Data Analysis (EDA), feature engineering, and visual/text preprocessing (`Pandas`, `NumPy`, `OpenCV`).
2. **Train, Fine-Tune & Evaluate:** Select or adapt the right architecture — classical ML (`Scikit-learn`), deep vision/text models (`PyTorch`, `ViT`, `DistilRoBERTa`), or generative pipelines (`Diffusers`, `LLMs`).
3. **Orchestrate & Connect:** Combine models into cohesive workflows or multi-agent pipelines (`FastAPI`, `MCP`, `Groq`, `AsyncIO`).
4. **Make It Usable:** Wrap the intelligence inside an intuitive interface (`React`, `TypeScript`, `Streamlit`) so anyone can interact with it.

</details>

<img src="assets/section-divider.svg" width="100%" alt="" />

## 🎨 A Peek at What I Enjoy Building

Here are two projects that reflect the two sides of what I love working on — **creative multimodal AI** and **collaborative AI agents**:

### 1. [Emotion-to-Art AI — Painting Emotions in the Style of Van Gogh & the Masters](https://github.com/mayarmajed2/Emotion-Aware-Multi-Artist-Generative-Art-with-Al-Interpretation-on-Gradient1)

An offline multimodal AI application that reads human emotion from text or portrait photos, understands the visual scene, and paints original artwork inspired by **Vincent van Gogh**, **Claude Monet**, and **Leonardo da Vinci** using local Stable Diffusion.

<div align="center">
  <img src="https://raw.githubusercontent.com/mayarmajed2/Emotion-Aware-Multi-Artist-Generative-Art-with-Al-Interpretation-on-Gradient1/master/github_banner.jpg" alt="Emotion-to-Art AI Banner" width="100%" />
</div>

<br/>

<table>
  <tr>
    <td width="33%" valign="top">
      <img src="https://raw.githubusercontent.com/mayarmajed2/Emotion-Aware-Multi-Artist-Generative-Art-with-Al-Interpretation-on-Gradient1/master/depi%20project/assets/main_ui.png" alt="Main Generation Studio" width="100%" />
      <p align="center"><sub><strong>1 · Generation Studio</strong><br/>Mood input &amp; Van Gogh / Masters style selection</sub></p>
    </td>
    <td width="33%" valign="top">
      <img src="https://raw.githubusercontent.com/mayarmajed2/Emotion-Aware-Multi-Artist-Generative-Art-with-Al-Interpretation-on-Gradient1/master/depi%20project/assets/emotion_analysis.png" alt="Emotion Analysis & Artwork Rendering" width="100%" />
      <p align="center"><sub><strong>2 · Emotion &amp; Canvas</strong><br/>DistilRoBERTa / ViT emotion scores &amp; generated painting</sub></p>
    </td>
    <td width="33%" valign="top">
      <img src="https://raw.githubusercontent.com/mayarmajed2/Emotion-Aware-Multi-Artist-Generative-Art-with-Al-Interpretation-on-Gradient1/master/depi%20project/assets/cv_analytics.png" alt="Computer Vision Color & Heatmap Analytics" width="100%" />
      <p align="center"><sub><strong>3 · Visual Analytics</strong><br/>OpenCV K-Means palette, saturation heatmap &amp; critique cloud</sub></p>
    </td>
  </tr>
</table>

<details>
<summary><strong>🔍 Click to peek under the hood of Emotion-to-Art AI</strong></summary>

<br/>

- **Text Emotion Recognition:** `DistilRoBERTa` (`j-hartmann/emotion-english-distilroberta-base`) classifies text into 7 emotional dimensions.
- **Facial Emotion & Scene Understanding:** Vision Transformer (`ViT`) detects facial emotions while `Salesforce BLIP` captions visual context.
- **Artistic Style Translation & Generation:** Rule-based prompt engineering translates emotion scores into brushwork, lighting, and palette prompts for local `Stable Diffusion v1.5` (Van Gogh impasto swirls, Monet impressionism, Da Vinci sfumato).
- **Computer Vision Analytics:** `OpenCV` + `K-Means` extracts the 5 dominant hex colors, generates saturation heatmaps, outlines facial regions via Haar Cascades, and builds an art critique word cloud.

</details>

<br/>

### 2. [SYNAPSE — Multi-Agent AI Software Engineering Workspace](https://github.com/mayarmajed2/SYNAPSE-AI-Platform)

An interactive workspace where **10 specialized AI agents** (from Product Manager and System Architect to Backend, Frontend, QA, Security, and DevOps) collaborate step-by-step to turn an app idea into tested code.

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://synapse-ai-platform-inky.vercel.app">
        <img src="https://raw.githubusercontent.com/mayarmajed2/SYNAPSE-AI-Platform/main/screenshots/01-landing-playground.png" alt="SYNAPSE Interactive Playground" width="100%" />
      </a>
      <p align="center"><sub><strong>Interactive 10-Agent Playground</strong></sub></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://synapse-ai-platform-inky.vercel.app">
        <img src="https://raw.githubusercontent.com/mayarmajed2/SYNAPSE-AI-Platform/main/screenshots/02-command-center.png" alt="SYNAPSE Command Center" width="100%" />
      </a>
      <p align="center"><sub><strong>Live Command Center &amp; Agent Fleet</strong></sub></p>
    </td>
  </tr>
</table>

<details>
<summary><strong>🧠 Click to see how the 10 AI Agents collaborate in SYNAPSE</strong></summary>

<br/>

- **Live Workspace:** [**synapse-ai-platform-inky.vercel.app**](https://synapse-ai-platform-inky.vercel.app)
- **10 Agent Roles:** Supervisor → Product Manager → System Architect → *(Human Approval Gate)* → Backend Dev → Frontend Dev → Code Reviewer → QA Engineer → Security Agent → Documentation Agent → DevOps Agent.
- **Built With:** `FastAPI`, `React 19`, `TypeScript`, `Groq Llama 3.3 70B`, `SQLAlchemy 2.0`, `PostgreSQL / SQLite`, `WebSockets`, and `Docker`.

</details>

<img src="assets/section-divider.svg" width="100%" alt="" />

## 🛠️ Skills & Technical Toolkit

<div align="center">

**Programming Languages**
<br/>
<img src="https://skillicons.dev/icons?i=python,cpp,ts,js,html,css,bash" alt="Programming Languages" />
<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />

<br/><br/>

**Machine Learning, Deep Learning & Computer Vision**
<br/>
<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv" alt="ML, DL & Computer Vision" />
<br/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
<img src="https://img.shields.io/badge/TensorFlow%20%2F%20Keras-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow" />
<img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="Scikit-learn" />
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV" />
<img src="https://img.shields.io/badge/Vision%20Transformers%20(ViT)-7C5CFF?style=flat-square" alt="ViT" />
<img src="https://img.shields.io/badge/CNNs%20%26%20Transfer%20Learning-38BDF8?style=flat-square" alt="Transfer Learning" />
<img src="https://img.shields.io/badge/Feature%20Engineering%20%26%20EDA-10B981?style=flat-square" alt="Feature Engineering" />

<br/><br/>

**NLP, Generative AI, LLMs & Multi-Agent Systems**
<br/>
<img src="https://img.shields.io/badge/Hugging%20Face%20Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Transformers" />
<img src="https://img.shields.io/badge/Stable%20Diffusion%20%2F%20Diffusers-FF4D8D?style=flat-square" alt="Diffusers" />
<img src="https://img.shields.io/badge/BLIP%20%26%20DistilRoBERTa-A855F7?style=flat-square" alt="BLIP and DistilRoBERTa" />
<img src="https://img.shields.io/badge/Groq%20%26%20Llama%203-FB923C?style=flat-square" alt="Groq" />
<img src="https://img.shields.io/badge/OpenAI%20SDK%20%26%20Prompt%20Engineering-412991?style=flat-square" alt="Prompt Engineering" />
<img src="https://img.shields.io/badge/Model%20Context%20Protocol%20(MCP%20%2F%20FastMCP)-0891B2?style=flat-square" alt="MCP" />
<img src="https://img.shields.io/badge/Multi--Agent%20Orchestration-7C5CFF?style=flat-square" alt="Multi-Agent" />

<br/><br/>

**Data Science, Analytics & Visualization**
<br/>
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy" />
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas" />
<img src="https://img.shields.io/badge/Matplotlib%20%26%20Seaborn-11557C?style=flat-square" alt="Matplotlib" />
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" alt="Power BI" />
<img src="https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white" alt="Kaggle" />
<img src="https://img.shields.io/badge/Google%20Colab%20%26%20Jupyter-F9AB00?style=flat-square&logo=googlecolab&logoColor=black" alt="Colab" />

<br/><br/>

**Full-Stack Development, Databases, Cloud & IoT**
<br/>
<img src="https://skillicons.dev/icons?i=fastapi,nodejs,express,react,nextjs,vite,tailwind,postgres,mongodb,sqlite" alt="Full-Stack & Databases" />
<br/>
<img src="https://skillicons.dev/icons?i=docker,git,github,linux,aws,azure,vercel,arduino" alt="Cloud, DevOps & IoT" />
<br/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit" />
<img src="https://img.shields.io/badge/SQLAlchemy%20%26%20Alembic-D71F00?style=flat-square" alt="SQLAlchemy" />
<img src="https://img.shields.io/badge/WebSockets%20%26%20REST%20APIs-38BDF8?style=flat-square" alt="WebSockets" />
<img src="https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white" alt="Railway" />
<img src="https://img.shields.io/badge/ESP32%20%26%20Embedded%20IoT-00979D?style=flat-square&logo=arduino&logoColor=white" alt="ESP32" />

</div>

<br/>

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🧠 AI &amp; Data Focus</h4>
      <ul>
        <li><strong>Machine Learning:</strong> Classification, regression, clustering (K-Means), preprocessing, feature engineering &amp; model evaluation</li>
        <li><strong>Deep Learning &amp; Vision:</strong> CNNs, Transfer Learning, Vision Transformers (ViT), OpenCV image analytics &amp; Haar Cascades</li>
        <li><strong>NLP &amp; Multimodal GenAI:</strong> Emotion classification (DistilRoBERTa), scene captioning (BLIP), Stable Diffusion &amp; prompt engineering</li>
        <li><strong>Agentic Systems:</strong> Multi-agent workflows, Model Context Protocol (FastMCP), tool routing &amp; LLM orchestration</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>💻 Engineering &amp; Delivery</h4>
      <ul>
        <li><strong>Backend &amp; APIs:</strong> FastAPI, Node.js, Express.js, AsyncIO, WebSockets, JWT auth &amp; Swagger/OpenAPI docs</li>
        <li><strong>Frontend &amp; UI:</strong> React 19, Next.js, TypeScript, Vite, Tailwind CSS &amp; interactive Streamlit dashboards</li>
        <li><strong>Databases &amp; Analytics:</strong> PostgreSQL, MongoDB, SQLite, SQLAlchemy ORM, Pandas, Matplotlib &amp; Power BI</li>
        <li><strong>Cloud &amp; Hardware:</strong> Docker, Git/GitHub, Linux, AWS, Azure AI, Vercel, Railway &amp; ESP32/Arduino IoT</li>
      </ul>
    </td>
  </tr>
</table>

<img src="assets/section-divider.svg" width="100%" alt="" />

## 📊 GitHub Snapshot

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=mayarmajed2&show_icons=true&hide_border=true&bg_color=090910&title_color=FF4D8D&icon_color=38BDF8&text_color=E2E8F0&border_color=23233A" alt="GitHub Stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mayarmajed2&layout=compact&hide_border=true&bg_color=090910&title_color=7C5CFF&text_color=E2E8F0&border_color=23233A" alt="Top Languages" />

</div>

<img src="assets/section-divider.svg" width="100%" alt="" />

## 🤝 Let's Connect

<div align="center">

Always happy to chat about **Machine Learning**, **Generative AI**, creative coding, or new ideas.

<br/>

<a href="https://github.com/mayarmajed2">
  <img src="https://img.shields.io/badge/GitHub-mayarmajed2-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>
<a href="https://www.kaggle.com/mayarmajed">
  <img src="https://img.shields.io/badge/Kaggle-mayarmajed-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle" />
</a>
<a href="https://huggingface.co/mayarmajed">
  <img src="https://img.shields.io/badge/Hugging%20Face-mayarmajed-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" />
</a>
<a href="mailto:m.fathallah2386@su.edu.eg">
  <img src="https://img.shields.io/badge/Email-m.fathallah2386%40su.edu.eg-7C5CFF?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>

<br/><br/>

<img src="assets/profile-footer.svg" alt="Thanks for stopping by · Cairo, Egypt" width="100%" />

</div>
