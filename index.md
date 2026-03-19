---
layout: homepage
---

<div id="site-notice" class="notice">
  <button class="notice-close" onclick="closeNotice()">×</button>
  <strong>Notice</strong><br>
  We are building up a Task Force on AI Safety Topics with several university and company research labs. This TF will work on need people interested in AI, but also people with different expertise too, such as  system programming, applied crypto, and other experience. If interested, please send an email to the PI.
</div>

<style>
.notice {
  position: fixed;
  bottom: 10px;
  right: 10px;
  width: 560px;
  background: white;
  border: 1px solid #ccc;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
  padding: 16px;
  z-index: 500;
  font-size: 20px;
}

.notice-close {
  position: absolute;
  top: 8px;
  right: 10px;
  border: none;
  background: transparent;
  font-size: 24px;
  cursor: pointer;
}
</style>

<script>
function closeNotice() {
  document.getElementById("site-notice").style.display = "none";
}
</script>

<h1 id="about-me"></h1>

I am an Assistant Professor in the Department of Computer Engineering at Kyung Hee University, leading the <a href="http://spicslab.kr">Secure and Private Intelligence Computing Systems Lab</a>. As the name suggests, we work on topics about HW/SW/AI Security and Privavy, including :

* Diverse Privacy-Enhancing Techniques (FHE, MPC, ZKP, DP, FL) for diverse AI applications (RAG, LLM, MCP, On-device AI)
* Integrating Hardware and System Security measurements (such as TEEs) with PETs
* Accelerators and Side-channel attacks for/against Post-Quantum Cryptography
* Using AI for security purpose, such as automatic generation of flawless programs

I earned my Ph.D. degree from Seoul National University. More information can be found in my <a href="https://rallykevin.github.io/assets/files/kvnamcv.pdf">Curriculum Vitae (CV)</a>. You can also navigate pages of this webpage including <a href="https://rallykevin.github.io/publications/">Publications</a>. If you are interested or have questions about my research, please feel free to contact me.

{% include_relative _includes/news.md %}

{% include_relative _includes/contact.md %}
