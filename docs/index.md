---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "Fucking Leetcode"
  text: "前端也该刷点算法题！"
  # tagline: My great project tagline
  actions:
    - theme: brand
      text: 快速开始
      link: /leetcode/bfs/0102
    - theme: alt
      text: GitHub
      link: https://github.com/lxj0501/leetcode-book

# features:
#   - title: Feature A
#     details: Lorem ipsum dolor sit amet, consectetur adipiscing elit
#   - title: Feature B
#     details: Lorem ipsum dolor sit amet, consectetur adipiscing elit
#   - title: Feature C
#     details: Lorem ipsum dolor sit amet, consectetur adipiscing elit
---
<style>
:root {
  --vp-home-hero-name-color: transparent;
  --vp-home-hero-name-background: -webkit-linear-gradient(120deg, #bd34fe 30%, #41d1ff);

  --vp-home-hero-image-background-image: linear-gradient(-45deg, #bd34fe 50%, #47caff 50%);
  --vp-home-hero-image-filter: blur(40px);
}

@media (min-width: 640px) {
  :root {
    --vp-home-hero-image-filter: blur(56px);
  }
}

@media (min-width: 960px) {
  :root {
    --vp-home-hero-image-filter: blur(72px);
  }
}
</style>
