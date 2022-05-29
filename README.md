# jekyll-journey
Repo for learning how to make websites with jekyll pages

## Table of Content
**README.md** 
- first to be displayed on Git repo
- Markdown file
- header syntax is similar to iPython Shell

**Terminology**
- Markdown: simpler HTML 
- Commit: Git edits


**Markdown (md) Syntax**
- markdown syntax is Discord code syntax
- *italics*: `*text here*`
- **bold**: `**text**`
- paragraph break: double space
- bullet points: `- then text`
- > Quoted blocks: `> text`
- lists: 
    - ordered
        1. ordered: place `1. ` before text
        2. like this
    - unordered: `-` or `*`
    - nested: double identations
    - checklists 
        > `+ [ ] text` *for nested list*  
        > `- [ ] text`
- Links: `[text](url.com)`
- Image upload: `![text](url.com) `
- Tables: uses `|` seperator to indicate divisions and `--` under first cells
- Summary dropdown
    ```
    <details>
      <summary>Title</summary>

        Content here
    </details>  
    ```
  
<details>
  <summary> like this </summary>
    This is a dropdown.
</details>
    
</details>  

*For multiple source citation:*  
  `[Title][reference]`
  `[reference]: url.com`


  
**Github Pages**
- free website hosting?
- Note: repo must be set to *public* to enable Github Pages
- Settings -> Pages -> Select branch `main`
- Other files here must be referenced accordingly from `file.md` as `https://YOURUSERNAME.github.io/REPONAME/other-files.html` to access the page

**index.md**
- default landing site in `main` branch
- Jekyll converts `index.md` to `index.html`

## References
1. [Building Websites With Jekyll and GitHub](https://carpentries-incubator.github.io/jekyll-pages-novice/)
2. [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
