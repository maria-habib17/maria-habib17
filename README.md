<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&height=220&color=0:0f172a,50:4f46e5,100:06b6d4&text=Maria%20Habib&fontColor=ffffff&fontSize=62&fontAlignY=42&desc=Software%20Engineer%20%C2%B7%20AI4SE%20%C2%B7%20Program%20Analysis&descSize=18&descAlignY=64&animation=fadeIn" width="100%" alt="Maria Habib"/>

<img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=20&duration=3000&pause=1000&color=6366F1&center=true&vCenter=true&width=700&lines=I+study+what+code+similarity+actually+preserves;Building+experiments%2C+not+just+applications;Robustness+vs.+discrimination+in+source-code+similarity" alt="Typing SVG"/>

<br/>

<a href="https://github.com/maria-habib17"><img src="https://img.shields.io/badge/GitHub-maria--habib17-0f172a?style=flat-square&logo=github&logoColor=white"/></a>
<a href="mailto:mariahabib1059@gmail.com"><img src="https://img.shields.io/badge/Email-get_in_touch-4f46e5?style=flat-square&logo=gmail&logoColor=white"/></a>
<a href="https://blog.ptidej.net/codespectra-the-illusion-of-easy-coding-why-ai-still-demands-effort/"><img src="https://img.shields.io/badge/Article-CodeSpectra-06b6d4?style=flat-square&logo=readme&logoColor=white"/></a>

</div>

<br/>

<div align="center">

### Code similarity has a trade-off nobody mentions

*Make a comparison robust to refactoring, and unrelated programs start looking identical too.*
*I build controlled experiments to measure exactly where that line is.*

</div>

<br/>

---

## Projects

<table>
<tr>
<td width="33%" valign="top">

### SimProbe
`experimental research`

Controlled experiments on the **robustness vs. discrimination** trade-off of similarity representations.

Identifier renaming · method reordering · class splitting · control similarity

[**View repositories →**](https://github.com/maria-habib17?tab=repositories)

</td>
<td width="33%" valign="top">

### BehavClone
`research prototype`

Whole-submission code comparison that keeps **structural, cohort-relative and behavioural evidence separate** instead of one plagiarism score.

JPlag 6.3.0 baseline · open negative results

[**View on GitHub →**](https://github.com/maria-habib17/behavclone)

</td>
<td width="33%" valign="top">

### CodeSpectra
`final-year project`

Academic clone detection across lexical, structural and semantic similarity of student programs (Type-1 to Type-4).

[**Read the article →**](https://blog.ptidej.net/codespectra-the-illusion-of-easy-coding-why-ai-still-demands-effort/)

</td>
</tr>
</table>

<br/>

> [!NOTE]
> **Latest finding (BehavClone, synthetic cohort of 16 submissions, 120 pairs):**
> 24/24 related pairs reached normalized similarity 1.0, but so did 48/96 unrelated control pairs.
> Normalization recovered similarity across transformations, and on this fixture it also removed information needed to tell independent programs apart.
> I'm publishing the failure and designing the next experiment around it.

---

## How the work connects

```mermaid
flowchart LR
    A["CodeSpectra<br/><sub>clone detection</sub>"] --> B{"What does<br/>similarity mean?"}
    B --> C["SimProbe<br/><sub>robustness vs. discrimination</sub>"]
    B --> D["BehavClone<br/><sub>structure + behaviour</sub>"]
    C --> E(["Evidence for<br/>human review"])
    D --> E
```

---

## Current lab status

<table>
<tr>
<td width="50%" valign="top">

**SimProbe / experiment-003**

| Stage | Status |
|---|---|
| Protocol | 🔒 frozen |
| Fixture specification | 🔒 frozen |
| 12 base programs | ✅ pass |
| Behaviour tests | ✅ 36 / 36 |
| Transformations | ⏭️ next |

</td>
<td width="50%" valign="top">

**What I care about**

The goal isn't another similarity score.

It's understanding **what information a score actually preserves**, from how code looks, to how it's structured, to how it behaves.

</td>
</tr>
</table>

---

## Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=java,python,js,mysql,git,github,vscode&theme=dark" alt="tech stack"/>

<br/><br/>

`AI4SE` · `Program Analysis` · `Code Similarity` · `Clone Detection` · `Empirical SE` · `Reproducibility`

</div>

---

## GitHub activity

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=maria-habib17&show_icons=true&hide_border=true&bg_color=0f172a&title_color=818cf8&icon_color=06b6d4&text_color=e2e8f0&rank_icon=github" alt="stats"/>
<img width="37%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=maria-habib17&layout=compact&hide_border=true&bg_color=0f172a&title_color=818cf8&text_color=e2e8f0" alt="top languages"/>

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=maria-habib17&hide_border=true&area=true&bg_color=0f172a&color=818cf8&line=4f46e5&point=06b6d4&area_color=4f46e5" width="88%" alt="activity graph"/>

</div>

---

<div align="center">

### Let's talk about code similarity, program analysis or evaluation design

<a href="mailto:mariahabib1059@gmail.com"><img src="https://img.shields.io/badge/Email-mariahabib1059@gmail.com-4f46e5?style=for-the-badge&logo=gmail&logoColor=white"/></a>

<sub><i>From how code looks, to how it is structured, to how it behaves.</i></sub>

<img src="https://capsule-render.vercel.app/api?type=waving&height=100&section=footer&color=0:0f172a,50:4f46e5,100:06b6d4" width="100%" alt=""/>

</div>
