---
title: "Recall This Gesture? Investigating Gesture Memorability in Augmented Reality"
collection: publications
category: journal
permalink: /publication/2026-recall-gesture
excerpt: "A study of gesture memorability in AR; evaluates which gestures are easier to recall and design implications for gesture-based interfaces."
date: 2026-01-01
venue: "IEEE Transactions on Visualization and Computer Graphics (TVCG)"
paperurl: "https://ieeexplore.ieee.org/document/11457803"
slidesurl: "/files/publications/2026-recall-gesture-slides.pdf"
videourl: "/files/publications/2026-recall-gesture-video.mp4"
citation: "Borhani, Z., Holen, E., Williams, A., Barrera‑Machua, M., Batmaz, A., Kelley, B., Zhou, X., Rhodes, M., & Ortega, F.R. (2026). Recall This Gesture? Investigating Gesture Memorability in Augmented Reality. IEEE Transactions on Visualization and Computer Graphics (TVCG)."
tags: [TVCG, AR, gestural-interaction, memorability]
---

<!-- single-image carousel: shows one image at a time with high-contrast arrows -->
<style>
.pub-carousel { position: relative; max-width: 960px; margin: 0 auto 1rem; overflow: hidden; border-radius: 8px; }
.pub-slides { display: flex; transition: transform .36s ease; will-change: transform; }
.pub-slide { min-width: 100%; box-sizing: border-box; }
.pub-slide img { width: 100%; height: auto; display: block; }
.pub-carousel .btn {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background: rgba(0,0,0,0.65);
  color: #fff;
  border: none;
  width:48px;
  height:48px;
  border-radius:50%;
  display:flex;
  align-items:center;
  justify-content:center;
  cursor:pointer;
  z-index:30;
  box-shadow: 0 8px 24px rgba(0,0,0,0.25);
  transition: transform .12s ease, background .12s ease;
}
.pub-carousel .btn:hover,
.pub-carousel .btn:focus { background: rgba(0,0,0,0.85); transform: translateY(-50%) scale(1.06); outline: none; }
.pub-carousel .prev { left: 12px; }
.pub-carousel .next { right: 12px; }
.pub-dots { text-align:center; margin-top:0.6rem; }
.pub-dot { display:inline-block; width:12px; height:12px; background:#ddd; margin:0 6px; border-radius:50%; cursor:pointer; }
.pub-dot.active { background:#333; }
</style>

<div class="pub-carousel" aria-label="Publication image gallery" tabindex="0">
  <div class="pub-slides">
    <div class="pub-slide">
      <a href="{{ site.baseurl }}/assets/images/publications/2026-recall-gesture-fig1.jpg" target="_blank" rel="noopener">
        <img src="{{ site.baseurl }}/assets/images/publications/2026-recall-gesture-fig1.jpg" alt="Overview figure: gesture examples and setup">
      </a>
    </div>
    <div class="pub-slide">
      <a href="{{ site.baseurl }}/assets/images/publications/2026-recall-gesture-fig2.jpg" target="_blank" rel="noopener">
        <img src="{{ site.baseurl }}/assets/images/publications/2026-recall-gesture-fig2.jpg" alt="Results: memorability by gesture type">
      </a>
    </div>
    <div class="pub-slide">
      <a href="{{ site.baseurl }}/assets/images/publications/2026-recall-gesture-fig3.jpg" target="_blank" rel="noopener">
        <img src="{{ site.baseurl }}/assets/images/publications/2026-recall-gesture-fig3.jpg" alt="Study setup and participant flow">
      </a>
    </div>
  </div>

  <button class="btn prev" aria-label="Previous image" title="Previous">&larr;</button>
  <button class="btn next" aria-label="Next image" title="Next">&rarr;</button>
</div>

<div class="pub-dots" role="tablist" aria-label="Gallery navigation">
  <span class="pub-dot" data-index="0" role="tab" aria-selected="true"></span>
  <span class="pub-dot" data-index="1" role="tab" aria-selected="false"></span>
  <span class="pub-dot" data-index="2" role="tab" aria-selected="false"></span>
</div>

<script>
(function(){
  const carousel = document.querySelector('.pub-carousel');
  if (!carousel) return;
  const track = carousel.querySelector('.pub-slides');
  const slides = carousel.querySelectorAll('.pub-slide');
  const prev = carousel.querySelector('.prev');
  const next = carousel.querySelector('.next');
  const dots = document.querySelectorAll('.pub-dot');
  let index = 0;
  function update() {
    track.style.transform = 'translateX(' + (-index * 100) + '%)';
    dots.forEach((d,i)=>{ d.classList.toggle('active', i===index); d.setAttribute('aria-selected', i===index); });
  }
  prev.addEventListener('click', ()=>{ index = (index -1 + slides.length) % slides.length; update(); });
  next.addEventListener('click', ()=>{ index = (index +1) % slides.length; update(); });
  dots.forEach(d => d.addEventListener('click', e => { index = Number(e.currentTarget.dataset.index); update(); }));
  carousel.addEventListener('keydown', e => { if (e.key==='ArrowLeft') prev.click(); if (e.key==='ArrowRight') next.click(); });
  update();
})();
</script>

Abstract
--------
This paper studies gesture memorability in augmented reality systems. We run controlled experiments comparing multiple gesture sets, analyze recall rates and error patterns, and identify design recommendations for selecting and presenting gestures to users. Results show that gestures with clear semantic mappings and moderate motor complexity are most memorable, informing guidelines for gesture-based AR interfaces.

Recommended citation
--------------------
Borhani, Z., Holen, E., Williams, A., Barrera‑Machua, M., Batmaz, A., Kelley, B., Zhou, X., Rhodes, M., & Ortega, F.R. (2026). Recall This Gesture? Investigating Gesture Memorability in Augmented Reality. IEEE Transactions on Visualization and Computer Graphics (TVCG). [https://ieeexplore.ieee.org/document/11457803]({{ page.paperurl }})

Media & links
-------------
- Paper: [TVCG article]({{ page.paperurl }})
- Slides: [Slides PDF]({{ page.slidesurl }})
- Video: [Presentation / demo]({{ page.videourl }})
- Figures (full resolution): /assets/images/publications/

Notes
-----
- Add the three figure files to assets/images/publications/ with the exact names used above and commit.  
- If your _config.yml sets site.baseurl use the {{ site.baseurl }} placeholders as included.  
- For a site-wide style, move the CSS block into assets/css/main.css and remove the <style> here.
```// filepath: /home/fali/website/faezehborhani.github.io/_publications/2026-01-01-recall-gesture.md
---
title: "Recall This Gesture? Investigating Gesture Memorability in Augmented Reality"
collection: publications
category: journal
permalink: /publication/2026-recall-gesture
excerpt: "A study of gesture memorability in AR; evaluates which gestures are easier to recall and design implications for gesture-based interfaces."
date: 2026-01-01
venue: "IEEE Transactions on Visualization and Computer Graphics (TVCG)"
paperurl: "https://ieeexplore.ieee.org/document/11457803"
slidesurl: "/files/publications/2026-recall-gesture-slides.pdf"
videourl: "/files/publications/2026-recall-gesture-video.mp4"
citation: "Borhani, Z., Holen, E., Williams, A., Barrera‑Machua, M., Batmaz, A., Kelley, B., Zhou, X., Rhodes, M., & Ortega, F.R. (2026). Recall This Gesture? Investigating Gesture Memorability in Augmented Reality. IEEE Transactions on Visualization and Computer Graphics (TVCG)."
tags: [TVCG, AR, gestural-interaction, memorability]
---

<!-- single-image carousel: shows one image at a time with high-contrast arrows -->
<style>
.pub-carousel { position: relative; max-width: 960px; margin: 0 auto 1rem; overflow: hidden; border-radius: 8px; }
.pub-slides { display: flex; transition: transform .36s ease; will-change: transform; }
.pub-slide { min-width: 100%; box-sizing: border-box; }
.pub-slide img { width: 100%; height: auto; display: block; }
.pub-carousel .btn {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background: rgba(0,0,0,0.65);
  color: #fff;
  border: none;
  width:48px;
  height:48px;
  border-radius:50%;
  display:flex;
  align-items:center;
  justify-content:center;
  cursor:pointer;
  z-index:30;
  box-shadow: 0 8px 24px rgba(0,0,0,0.25);
  transition: transform .12s ease, background .12s ease;
}
.pub-carousel .btn:hover,
.pub-carousel .btn:focus { background: rgba(0,0,0,0.85); transform: translateY(-50%) scale(1.06); outline: none; }
.pub-carousel .prev { left: 12px; }
.pub-carousel .next { right: 12px; }
.pub-dots { text-align:center; margin-top:0.6rem; }
.pub-dot { display:inline-block; width:12px; height:12px; background:#ddd; margin:0 6px; border-radius:50%; cursor:pointer; }
.pub-dot.active { background:#333; }
</style>

<div class="pub-carousel" aria-label="Publication image gallery" tabindex="0">
  <div class="pub-slides">
    <div class="pub-slide">
      <a href="{{ site.baseurl }}/assets/images/publications/2026-recall-gesture-fig1.jpg" target="_blank" rel="noopener">
        <img src="{{ site.baseurl }}/assets/images/publications/2026-recall-gesture-fig1.jpg" alt="Overview figure: gesture examples and setup">
      </a>
    </div>
    <div class="pub-slide">
      <a href="{{ site.baseurl }}/assets/images/publications/2026-recall-gesture-fig2.jpg" target="_blank" rel="noopener">
        <img src="{{ site.baseurl }}/assets/images/publications/2026-recall-gesture-fig2.jpg" alt="Results: memorability by gesture type">
      </a>
    </div>
    <div class="pub-slide">
      <a href="{{ site.baseurl }}/assets/images/publications/2026-recall-gesture-fig3.jpg" target="_blank" rel="noopener">
        <img src="{{ site.baseurl }}/assets/images/publications/2026-recall-gesture-fig3.jpg" alt="Study setup and participant flow">
      </a>
    </div>
  </div>

  <button class="btn prev" aria-label="Previous image" title="Previous">&larr;</button>
  <button class="btn next" aria-label="Next image" title="Next">&rarr;</button>
</div>

<div class="pub-dots" role="tablist" aria-label="Gallery navigation">
  <span class="pub-dot" data-index="0" role="tab" aria-selected="true"></span>
  <span class="pub-dot" data-index="1" role="tab" aria-selected="false"></span>
  <span class="pub-dot" data-index="2" role="tab" aria-selected="false"></span>
</div>

<script>
(function(){
  const carousel = document.querySelector('.pub-carousel');
  if (!carousel) return;
  const track = carousel.querySelector('.pub-slides');
  const slides = carousel.querySelectorAll('.pub-slide');
  const prev = carousel.querySelector('.prev');
  const next = carousel.querySelector('.next');
  const dots = document.querySelectorAll('.pub-dot');
  let index = 0;
  function update() {
    track.style.transform = 'translateX(' + (-index * 100) + '%)';
    dots.forEach((d,i)=>{ d.classList.toggle('active', i===index); d.setAttribute('aria-selected', i===index); });
  }
  prev.addEventListener('click', ()=>{ index = (index -1 + slides.length) % slides.length; update(); });
  next.addEventListener('click', ()=>{ index = (index +1) % slides.length; update(); });
  dots.forEach(d => d.addEventListener('click', e => { index = Number(e.currentTarget.dataset.index); update(); }));
  carousel.addEventListener('keydown', e => { if (e.key==='ArrowLeft') prev.click(); if (e.key==='ArrowRight') next.click(); });
  update();
})();
</script>

Abstract
--------
This paper studies gesture memorability in augmented reality systems. We run controlled experiments comparing multiple gesture sets, analyze recall rates and error patterns, and identify design recommendations for selecting and presenting gestures to users. Results show that gestures with clear semantic mappings and moderate motor complexity are most memorable, informing guidelines for gesture-based AR interfaces.

Recommended citation
--------------------
Borhani, Z., Holen, E., Williams, A., Barrera‑Machua, M., Batmaz, A., Kelley, B., Zhou, X., Rhodes, M., & Ortega, F.R. (2026). Recall This Gesture? Investigating Gesture Memorability in Augmented Reality. IEEE Transactions on Visualization and Computer Graphics (TVCG). [https://ieeexplore.ieee.org/document/11457803]({{ page.paperurl }})

Media & links
-------------
- Paper: [TVCG article]({{ page.paperurl }})
- Slides: [Slides PDF]({{ page.slidesurl }})
- Video: [Presentation / demo]({{ page.videourl }})
- Figures (full resolution): /assets/images/publications/

Notes
-----
- Add the three figure files to assets/images/publications/ with the exact names used above and commit.  
- If your _config.yml sets site.baseurl use the {{ site.baseurl }} placeholders as included.  
- For a site-wide style, move the CSS block into assets/css/main.css and remove the <style> here.