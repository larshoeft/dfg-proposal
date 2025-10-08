# Learning Chemistry through Dialogic Argumentation


## Introduction

### Refutation Texts

- “findings show a consistent and statistically significant advantage of
  refutation texts over non-refutation texts in controlled experiments
  confronting scientific misconceptions. We also found that moderators
  neither enhanced nor diminished the impact of the refutation texts.”
  (Danielson et al., 2025)
- “refutation text is associated with a positive, moderate effect
  (*g* = 0.41, *p* \< .001) compared to other learning conditions. This
  effect was consistent and robust across a wide variety of contexts”
  (Schroeder & Kucera, 2022)
- “Methodological issues we identified centered on problems of using a
  single topic (or very few) within a study, the role of testing in
  conceptual change, and the durability of change beyond an immediate
  posttest.” (Zengilowski et al., 2021)

### Argumentation

- “Furthermore, the deeper integration of computer technology and
  argumentation needs to be strengthened in the future.” (Fu & Zhan,
  2025)
- “It is proved that online argumentation activities have an
  upper-middle positive effect on students’ “Learn to Argue” (Hedges’
  g = 0.603, P = 0.000) and “Argue to Learn” (Hedges’ g = 0.596,
  P = 0.000) abilities. Finally, the results of moderator analysis
  showed that the natural science issues have the greatest effect.
  Compared with higher education, online scientific argumentation is of
  greater value in K-12 classroom.” (Zhou, 2024)
- “Those who read congruent texts showed greater knowledge gains and
  were more likely to think causally than those in the incongruent
  group.” (Danielson et al., 2023)

### Epistemic Emotions

- “epistemic emotions are triggered by cognitive states involving
  discrepancy, or conflict, between active schemas and incoming
  information, or gap in one’s knowledge” (Nerantzaki et al., 2021)
- confusion -\> frustration -\> no learning gains (Muis et al., 2025)

### Research Questions

1.  Does engaging in dialogic argumentation enhance conceptual
    understanding from refutation texts on the concept of chemical
    reactions?
2.  Does the conceptual stance of discussion partners in dialogic
    argumentation (e.g., both accurate vs. one accurate and one
    misconceived) influence conceptual understanding?
3.  Do epistemic emotions mediate the relationship between the
    conceptual stance of discussion partners in dialogic argumentation
    and conceptual understanding?
4.  Does a brief argumentation training intervention enhance conceptual
    understanding during dialogic argumentation, and is this effect
    mediated by reductions in confusion and frustration?

### Proposed Model

``` mermaid
flowchart LR
    %% Knoten definieren
    A[Type of<br/>Argumentation]
    I[Intervention]
    E[Epistemic<br/>Emotion]
    EN[Engagement]
    U[Conceptual<br/>Knowledge]
    M1(( ))
    M2(( ))
    
    %% Verbindungen
    A --> M1
    A --> M2
    M1 --> EN
    M2 --> E
    I --> M1
    I --> M2
    E --> U
    EN --> U
    A --> U
    
    %% Styling
    classDef default fill:#fff,stroke:#333,stroke-width:2px,color:#000
    %% classDef dot fill:#333,stroke:#333,stroke-width:2px
    %% class M1 dot
    
    %% Knoten M sehr klein machen
    style M1 width:1px,height:1px,fill:#333
    style M2 width:1px,height:1px,fill:#333
```

## Study 1

### Research Questions

1.  Does engaging in dialogic argumentation enhance conceptual
    understanding from refutation texts on the concept of chemical
    reactions?
2.  Do epistemic emotions mediate the relationship between the
    conceptual stance of discussion partners in dialogic argumentation
    and conceptual understanding?

### Procedure

<table style="width:99%;">
<caption>Overview of Study Procedure for Control (CG) and Experimental
Groups (EG)</caption>
<colgroup>
<col style="width: 5%" />
<col style="width: 36%" />
<col style="width: 25%" />
<col style="width: 30%" />
</colgroup>
<thead>
<tr>
<th>Phase</th>
<th>Shared Procedure</th>
<th>CG Description</th>
<th>EG Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>Pre-test</td>
<td>Assess students’ conceptual understanding of <strong>chemical
reactions</strong>.</td>
<td>—</td>
<td>—</td>
</tr>
<tr>
<td>Manipulation</td>
<td><ul>
<li>Students complete multiple tasks on chemical reactions in randomized
order</li>
<li>Correct answers are provided</li>
<li>Students explain to an LLM agent <em>why</em> the provided answer is
correct</li>
</ul></td>
<td>LLM provides corrective feedback on the student’s explanations</td>
<td>LLM formulates counterarguments and requests clarification from the
student</td>
</tr>
<tr>
<td>Post-test</td>
<td>Assess students’ conceptual understanding of <strong>chemical
reactions</strong> after the intervention</td>
<td>—</td>
<td>—</td>
</tr>
</tbody>
</table>

**Note.** CG = Control Group; EG = Experimental Group. Shared Procedure
describes steps common to both groups.

### Material

- omc (4 - 6 options?)
- open answer

## Study 2

### Research Questions

1.  Does engaging in dialogic argumentation enhance conceptual
    understanding from refutation texts on the concept of chemical
    reactions?
2.  Does the conceptual stance of discussion partners in dialogic
    argumentation (e.g., both accurate vs. one accurate and one
    misconceived) influence conceptual understanding?
3.  Do epistemic emotions mediate the relationship between the
    conceptual stance of discussion partners in dialogic argumentation
    and conceptual understanding?

### Procedure:

<table style="width:99%;">
<caption>Overview of Study Procedure for Control (CG) and Experimental
Groups (EG)</caption>
<colgroup>
<col style="width: 3%" />
<col style="width: 19%" />
<col style="width: 17%" />
<col style="width: 28%" />
<col style="width: 30%" />
</colgroup>
<thead>
<tr>
<th>Phase</th>
<th>Shared Procedure</th>
<th>Control Group</th>
<th>Experimental Group 1</th>
<th>Experimental Group 2</th>
</tr>
</thead>
<tbody>
<tr>
<td>Pre-Test</td>
<td>Assess students’ conceptual understanding of <strong>chemical
reactions</strong>.</td>
<td>—</td>
<td>—</td>
<td>—</td>
</tr>
<tr>
<td>Manipulation</td>
<td>Students complete multiple tasks on chemical reactions in randomized
order</td>
<td><ul>
<li>Receive correct answers</li>
<li>Explain to an LLM agent <em>why</em> the provided answer is
correct</li>
<li>Engage in dialogic argumentation with a typical/default LLM (see
Study 1)</li>
</ul></td>
<td><ul>
<li>Receive correct answers</li>
<li>Explain to an LLM agent <em>why</em> the provided answer is
correct</li>
<li>Engage in dialogic argumentation with two LLM agents: both
exhibiting accurate understanding of the scientific concept and
task</li>
</ul></td>
<td><ul>
<li>Receive correct answers</li>
<li>Explain to an LLM agent <em>why</em> the provided answer is
correct</li>
<li>Engage in dialogic argumentation with two LLM agents: one accurate,
one exhibiting misconceptions and inappropriate task interpretation</li>
</ul></td>
</tr>
<tr>
<td>Post-Test</td>
<td>Assess students’ conceptual understanding of <strong>chemical
reactions</strong> after the intervention</td>
<td>—</td>
<td>—</td>
<td>—</td>
</tr>
</tbody>
</table>

**Note.** CG = Control Group; EG = Experimental Group. Shared Procedure
describes steps common to both groups.

## Study 3

### Research question

4.  Does a brief argumentation training intervention enhance conceptual
    understanding during dialogic argumentation, and is this effect
    mediated by reductions in confusion and frustration?

<table style="width:99%;">
<caption>Overview of Study Procedure for Control (CG) and Experimental
Groups (EG)</caption>
<colgroup>
<col style="width: 3%" />
<col style="width: 22%" />
<col style="width: 36%" />
<col style="width: 36%" />
</colgroup>
<thead>
<tr>
<th>Phase</th>
<th>Shared Procedure</th>
<th>Control Group</th>
<th>Experimental Group</th>
</tr>
</thead>
<tbody>
<tr>
<td>Pre-Test</td>
<td>Assess students’ conceptual understanding of <strong>chemical
reactions</strong>.</td>
<td>—</td>
<td>—</td>
</tr>
<tr>
<td>Intervention</td>
<td></td>
<td></td>
<td>Students receive instruction on argument formulation and the
objectives of argumentation.</td>
</tr>
<tr>
<td></td>
<td>Students complete multiple tasks on chemical reactions in randomized
order</td>
<td><ul>
<li><p>Receive correct answers</p></li>
<li><p>Explain to an LLM agent <em>why</em> the provided answer is
correct</p></li>
<li><p>Engage in dialogic argumentation with two LLM agents: one
accurate, one exhibiting misconceptions and inappropriate task
interpretation</p></li>
</ul></td>
<td><ul>
<li><p>Receive correct answers</p></li>
<li><p>Explain to an LLM agent <em>why</em> the provided answer is
correct</p></li>
<li><p>Engage in dialogic argumentation with two LLM agents: one
accurate, one exhibiting misconceptions and inappropriate task
interpretation</p></li>
</ul></td>
</tr>
<tr>
<td>Post-Test</td>
<td>Assess students’ conceptual understanding of chemical reactions
after the intervention</td>
<td>—</td>
<td>—</td>
</tr>
</tbody>
</table>

**Note.** CG = Control Group; EG = Experimental Group. Shared Procedure
describes steps common to both groups.

## References

<div id="refs" class="references csl-bib-body hanging-indent"
entry-spacing="0" line-spacing="2">

<div id="ref-danielson2025_effectiveness" class="csl-entry">

Danielson, R. W., Jacobson, N. G., Patall, E. A., Sinatra, G. M.,
Adesope, O. O., Kennedy, A. A. U., H. Bhat, B., Ramazan, O., Akinrotimi,
B., Nketah, G., Jin, G., & Sunday, O. J. (2025). The effectiveness of
refutation text in confronting scientific misconceptions: A
meta-analysis. *Educational Psychologist*, *60*(1), 23–47.
<https://doi.org/10.1080/00461520.2024.2365628>

</div>

<div id="ref-danielson2023_can" class="csl-entry">

Danielson, R. W., Sinatra, G. M., Trevors, G., Muis, K. R., Pekrun, R.,
& Heddy, B. C. (2023). Can Multiple Texts Prompt Causal Thinking? The
Role of Epistemic Emotions. *The Journal of Experimental Education*,
*91*(4), 621–635. <https://doi.org/10.1080/00220973.2022.2107604>

</div>

<div id="ref-fu2025_effectiveness" class="csl-entry">

Fu, X., & Zhan, Q. (2025). Effectiveness of argument in science
education: a meta-analysis based on the results of 17 experiments.
*Research in Science & Technological Education*, 1–21.
<https://doi.org/10.1080/02635143.2025.2527603>

</div>

<div id="ref-muis2025_confusion" class="csl-entry">

Muis, K. R., Kohatsu, M., Pekrun, R., & Li, S. (2025). Confusion and
confusion regulation: An empirical investigation of the emotion
regulation in achievement situations model. *Contemporary Educational
Psychology*, *80*, 102350.
<https://doi.org/10.1016/j.cedpsych.2025.102350>

</div>

<div id="ref-nerantzaki2021_epistemic" class="csl-entry">

Nerantzaki, K., Efklides, A., & Metallidou, P. (2021). Epistemic
emotions: Cognitive underpinnings and relations with metacognitive
feelings. *New Ideas in Psychology*, *63*, 100904.
<https://doi.org/10.1016/j.newideapsych.2021.100904>

</div>

<div id="ref-schroeder2022_refutation" class="csl-entry">

Schroeder, N. L., & Kucera, A. C. (2022). Refutation Text Facilitates
Learning: a Meta-Analysis of Between-Subjects Experiments. *Educational
Psychology Review*, *34*(2), 957–987.
<https://doi.org/10.1007/s10648-021-09656-z>

</div>

<div id="ref-zengilowski2021_critical" class="csl-entry">

Zengilowski, A., Schuetze, B. A., Nash, B. L., & Schallert, D. L.
(2021). A critical review of the refutation text literature:
Methodological confounds, theoretical problems, and possible solutions.
*Educational Psychologist*, *56*(3), 175–195.
<https://doi.org/10.1080/00461520.2020.1861948>

</div>

<div id="ref-zhou2024_learn" class="csl-entry">

Zhou, D. (2024). “Learn to Argue” and “Argue to Learn”: meta-analysis of
effective instructional design for online scientific argumentation
activities. *Interactive Learning Environments*, *32*(9), 4857–4880.
<https://doi.org/10.1080/10494820.2023.2205904>

</div>

</div>
