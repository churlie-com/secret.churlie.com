## secret.churlie.com

This is the homepage

<div>
  <div id="table-of-contents">
    {{ content | toc_only }}
  </div>
  <div id="markdown-content">
    {{ content | inject_anchors }}
  </div>
</div>

<div>
  <div id="table-of-contents">
    {% toc %}
  </div>
  <div id="markdown-content">
    {{ content }}
  </div>
</div>
