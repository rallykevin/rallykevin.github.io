<h2 id="publications" style="margin: 2px 0px -15px;">Publications</h2>
<br>

You can also refer to my <a href="https://scholar.google.com/citations?user=CsJKBq4AAAAJ&hl=ko">Google Scholar profile</a> or my <a href="https://rallykevin.github.io/assets/files/kvnamcv.pdf">curriculum vitae</a>.

Next to the names, a single star (*) denotes authors who equally contributed, and two stars (**) denotes corresponding authors.

<h3 style="margin: 2px 0px -5px;">International Conference Papers</h3>

<details>
  <summary>Open/Close</summary>
<br>

<div class="publications">
<ol class="bibliography">

{% for link in site.data.publications.main %}
<li>
<div class="pub-row">
  <div class="col-sm-3 abbr" style="position: relative;padding-right: 15px;padding-left: 15px;">
    {% if link.image %} 
    <img src="{{ link.image }}" class="teaser img-fluid z-depth-1" style="width=100;height=40%">
    {% if link.conference_short %} 
    <abbr class="badge">{{ link.conference_short }}</abbr>
    {% endif %}
    {% endif %}
  </div>
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><strong style="color:#2d92f0">{{ link.title }}</strong></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em>{{ link.conference }}</em>
      </div>
    <div class="links">
      {% if link.pdf %} 
      <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Github</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
      {% endif %}
      {% if link.notes %} 
      <strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>
<br>

{% endfor %}

</ol>
</div>
</details>

<h3 style="margin: 2px 0px -5px;">International Journal Publications</h3>

<details>
  <summary>Open/Close</summary>
<br>

<div class="publications">
<ol class="bibliography">

{% for link in site.data.intjournal.main %}

<li>
<div class="pub-row">
  <div class="col-sm-3 abbr" style="position: relative;padding-right: 15px;padding-left: 15px;">
    {% if link.image %} 
    <img src="{{ link.image }}" class="teaser img-fluid z-depth-1" style="width=100;height=40%">
    {% if link.conference_short %} 
    <abbr class="badge">{{ link.conference_short }}</abbr>
    {% endif %}
    {% endif %}
  </div>
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><strong style="color:#2d92f0">{{ link.title }}</strong></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em>{{ link.conference }}</em>
      </div>
    <div class="links">
      {% if link.pdf %} 
      <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
      {% endif %}
      {% if link.notes %} 
      <strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>
<br>

{% endfor %}

</ol>
</div>
</details>

<h3 style="margin: 2px 0px -5px;">International Poster Presentations</h3>

<details>
  <summary>Open/Close</summary>
<br>

<ul style="margin:0 0 5px;">
  <li><strong>Affinity-based Optimizations of Homomorphic Encryption Operations on Processing-in-DRAM</strong>. <strong style="color:#1fcc05">Kevin Nam</strong>, Heonhui Jung, Hyunyoung Oh**, Yunheung Paek**. The 61st ACM/IEEE Design Automation Conference Work-in-Progress (DAC`24 WiP), 2024.</li>
  <li><strong>Implementing Efficient, Precise N-bit Operations of TFHE on Commodity CPU-FPGA</strong>. <strong style="color:#1fcc05">Kevin Nam</strong>, Hyunyoung Oh, Hyungon Moon**, Yunheung Paek**. The 59th ACM/IEEE Design Automation Conference Work-in-Progress (DAC`22 WiP), 2022.</li>
</ul>
</details>

<h3 style="margin: 2px 0px -5px;">Patents</h3>

<details>
  <summary>Open/Close</summary>
<br>

<ul style="margin:0 0 5px;">
  <li><strong>다종 동형암호 체계를 활용한 암호화 데이터 연산 방법 및 장치</strong>. 백윤흥, <strong style="color:#1fcc05">남기빈</strong>, 주유연. Oct 2026. KR Patent No. 10-3037535, <strong><u>Registered (등록)</u></strong> (Applied Nov 2024, No. 10-2024-0153707)</li>
  <li><strong>다중 신뢰실행환경 기반 온디바이스 AI 상호 프라이버시 보호 추론 서비스 방법 및 시스템</strong>. 백윤흥, <strong style="color:#1fcc05">남기빈</strong>, 유준승. Jan 2026. KR Patent No. 10-2026-0007142, Applied (출원)</li>
  <li><strong>인공 신경망을 위한 비산술 함수를 처리하는 방법 및 그 방법을 이용한 암호화 장치</strong>. 백윤흥, 주유연, <strong style="color:#1fcc05">남기빈</strong>. Oct 2025. KR Patent No. 10-2025-0147837, Applied (출원)</li>
  <li><strong>METHOD FOR PROCESSING HOMOMORPHIC CIPHERTEXT AND ELECTRONIC APPARATUS</strong>. Yunheung Paek, Heonhui Jung, <strong style="color:#1fcc05">Kevin Nam</strong>, Seungjin Ha, Junbum Shin, Inkwan Yu, Sunchul Jung, Jungjoo Seo. Feb 2025. US Patent No. 19/052442, Applied</li>
  <li><strong>동형 암호문 처리 방법 및 전자 장치</strong>. 백윤흥, 정헌희, <strong style="color:#1fcc05">남기빈</strong>, 하승진, 신준범, 유인관, 정선철, 서정주. Jan 2025. KR Patent No. 10-2025-0008424, Applied (출원)</li>
  <li><strong>신뢰 기관을 이용한 동형암호 공통키 배포</strong>. 백윤흥, 오현영, <strong style="color:#1fcc05">남기빈</strong>, 조영필. Jan 2021. KR Patent No. 10-2021-0006281, Applied (출원)</li>
</ul>
</details>

<h3 style="margin: 2px 0px -5px;">Domestic Papers</h3>

<details>
  <summary>Open/Close</summary>
<br>

<ul style="margin:0 0 5px;">
  <li><strong>정확한 동형암호 기반 나눗셈(역수) 연산을 위한 효과적인 근사식 설계 방식에 대한 연구</strong>. 김우현, 박준서, <strong style="color:#1fcc05">남기빈</strong>**, 최현민**. 한국정보보호학회 동계학술대회 (CISC-W 2026), Nov 2026.</li>
  <li><strong><a href="https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE12882095" target="_blank">On-device AI를 위한 프라이버시 보호 기술 활용 동향 (Privacy Protection Technology Trends for On-device AI)</a></strong>. <strong style="color:#1fcc05">남기빈</strong>. 정보과학회지 (Communications of KIISE), Vol. 44, No. 6, Jun 2026.</li>
  <li><strong><a href="https://www.koreascience.kr/article/CFKO202520957603637.view" target="_blank">모델 프라이버시 보호를 위한 TEE 기반 On-device 추론에 대한 연구 (A Study on the TEE-based On-device Inference for Protecting Model Privacy)</a></strong>. 하승진, <strong style="color:#1fcc05">남기빈</strong>, 백윤흥. 한국정보처리학회 춘계학술발표대회 (ASK 2025), May 2025.</li>
  <li><strong><a href="https://koreascience.kr/article/CFKO202433161915282.page" target="_blank">TFHE 가속화를 위한 CUDA 최적화 기법 비교 연구 (A Comparative Study of CUDA Optimisation Techniques for Accelerating TFHE)</a></strong>. 하승진, <strong style="color:#1fcc05">남기빈</strong>, 백윤흥. 한국정보처리학회 추계학술발표대회 (ACK 2024), Oct 2024.</li>
  <li><strong><a href="https://doi.org/10.3745/PKIPS.y2024m10a.338" target="_blank">빠르고 정확한 암호화된 신경망 연산을 위한 중간 데이터를 활용한 근사식 생성 기술 (Intermediate Data Guided Approximation for Fast and Accurate Encrypted Neural Networks)</a></strong>. <strong style="color:#1fcc05">남기빈</strong>, 주유연, 하승진, 백윤흥. 한국정보처리학회 추계학술발표대회 (ACK 2024), Oct 2024.</li>
  <li><strong><a href="https://koreascience.kr/article/CFKO202433161904137.page" target="_blank">신뢰실행환경 기반 프록시 암호화를 활용한 동형암호 기반 클라우드 서비스의 성능 개선 연구 (Proxy Encryption with Trusted Execution Environments to Reduce the Communication Overhead of Cloud Services over Encrypted Data)</a></strong>. 주유연, <strong style="color:#1fcc05">남기빈</strong>, 하승진, 백윤흥. 한국정보처리학회 추계학술발표대회 (ACK 2024), Oct 2024.</li>
  <li><strong><a href="https://koreascience.kr/article/CFKO202422572273826.page" target="_blank">TFHE 기반 CNN 연산 최적화를 위한 비산술연산의 양자화 기술 연구 (Quantization of Non-Arithmetics to Optimize CNNs over TFHE)</a></strong>. <strong style="color:#1fcc05">남기빈</strong>, 정헌희, 이동주, 백윤흥. 한국정보처리학회 춘계학술발표대회 (ASK 2024), May 2024.</li>
  <li><strong><a href="https://koreascience.kr/article/CFKO202319360810903.page" target="_blank">동형암호에 대한 부채널 공격과 대응에 관한 연구 (Side-Channel Attacks on Homomorphic Encryption and Their Mitigation Methods)</a></strong>. <strong style="color:#1fcc05">남기빈</strong>, 주유연, 하승진, 백윤흥. 한국정보처리학회 춘계학술발표대회 (ASK 2023), May 2023. <strong><i style="color:#e74d3c">(NIPA Director Award)</i></strong></li>
  <li><strong><a href="https://koreascience.kr/article/CFKO202125036370346.page" target="_blank">동형암호를 활용한 딥러닝 모델 학습에 대한 연구 (Realization of Homomorphic Encrypted Deep Learning Models)</a></strong>. <strong style="color:#1fcc05">남기빈</strong>, 조명현, 김현준, 백윤흥. 한국정보처리학회 춘계학술발표대회 (ASK 2021), May 2021. <strong><i style="color:#e74d3c">(Undang Academic Award)</i></strong></li>
</ul>
</details>
