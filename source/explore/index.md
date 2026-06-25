---
title: 探索
menu_id: explore
date: 2026-06-18 00:00:00
updated: 2026-06-18 00:00:00
rightbar:
comments: false
---

<div class="explore-box">
  <iframe src="/explore/panel.html"></iframe>
</div>

<style>
html, body, .l_body { overflow: hidden; }
.article.banner,
.l_body .l_right,
footer { display: none; }
.md-text.content {
  padding: 0; max-width: none;
  padding-bottom: 0;
}
.md-text > .explore-box { margin: 0; }
.md-text .explore-box iframe { margin: 0; }

.explore-box {
  overflow: clip;
  width: 100%;
  height: calc(100vh - 64px);
  border-radius: 24px;
  border: 1px solid var(--block-border);
  box-sizing: border-box;
}
.explore-box iframe {
  width: 100%;
  height: 100%;
  border: none;
  display: block;
}

@media screen and (min-width: 769px) {
  .l_body { --width-main: 100vw; }
  .md-text.content { grid-column: 2 / 4; }
  .float-panel { display: none; }
}
@media screen and (max-width: 768px) {
  .explore-box { height: calc(100vh - 56px); border-radius: 12px; }
}
</style>
