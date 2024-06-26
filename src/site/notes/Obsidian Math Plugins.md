---
{"dg-publish":true,"permalink":"/obsidian-math-plugins/"}
---

This is my current setup for taking math notes in Obsidian as well as some additional resources that may prove useful. 
- [[Math Note Format Explanation\|Math Note Format Explanation]]
# Plugins I'm Currently Using
- [[Latex Suite\|Latex Suite]]
- Mathlinks
- Latex-Style Theorems/References
- Quick Latex 
- Desmos Graph
- [Obsidian TikZJax](https://github.com/artisticat1/obsidian-tikzjax?tab=readme-ov-file#obsidian-tikzjax)
- Excalidraw

# CSS Snippets
- Bigger math font
```css
mjx-math {
  font-size: 120% !important;
}
```

- Center images
```css
img {
    display: block;
    margin-left: auto;
    margin-right: auto;
}

/* === Images size defaults === */
.image-embed.image-embed img:not([width]) {
    max-height: 450px;
    max-width: 500px;
}


```
- Center Desmos graphs
```css
/* Horizontally center the graph in the page content */
.desmos-graph {
    display: block;
    margin-left: auto;
    margin-right: auto;
}
```
# Interesting Plugins
I don't use these but they might be useful.
- [Mathlive](https://mathlive.danz.blog)
- LaTex OCR

# Resources
- [My experience With Obsidian For Mathematical Writing + Free Notes On Linear Programming](https://www.reddit.com/r/ObsidianMD/comments/1cv3shy/comment/l4vbvjs/)
- [One year of Math notes in Obsidian](https://www.reddit.com/r/ObsidianMD/comments/13lhyd7/one_year_of_math_notes_in_obsidian/)- [Zhaoshen Zhai](https://github.com/zhaoshenzhai)
- [How I'm able to take notes in mathematics lectures using LaTeX and Vim](https://castel.dev/post/lecture-notes-1/) - Gilles Castel (RIP)

