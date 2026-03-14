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
  <summary style="padding-bottom: 0px; margin-bottom: -10px;">Open/Close</summary>
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
  <li>Kevin Nam, Heonhui Jung, Hyunyoung Oh**, Yunheung Paek**, "Affinity-based Optimizations of Homomorphic Encryption Operations on Processing-in-DRAM" in the 61th ACM/IEEE Design Automation Conference Work-in-Progress (DAC`24 WiP), 2024</li>
    <li>Kevin Nam, Hyunyoung Oh, Hyungon Moon**, Yunheung Paek**, "Implementing Efficient, Precise N-bit Operations of TFHE on Commodity CPU-FPGA" in the 59th ACM/IEEE Design Automation Conference Work-in-Progress (DAC`22 WiP), 2022</li>
</ul>
</details>

