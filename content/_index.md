---
title: ""
layout: landing
---

<div class="home-layout">
  <aside class="home-column home-column-left">
    <h2>目录</h2>
    {{< home-directory >}}
  </aside>

  <main class="home-column home-column-center">
    <h1>未保存但继续</h1>
    <p class="home-subtitle">unsavedyet · 记得 commit</p>

    <section>
      <h2>Book</h2>
      <div class="home-cover-card">
        <p>一本关于技术、记录和思考的小书。</p>
        <p><a href="/docs/">从目录开始阅读</a></p>
      </div>
    </section>

    <section>
      <h2>最近更新</h2>
      {{< recent-posts count="8" >}}
    </section>
  </main>

  <aside class="home-column home-column-right">
    <h2>标签</h2>
    {{< home-tags limit="24" >}}
  </aside>
</div>
