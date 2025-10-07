# Learning Chemistry through Dialogic Argumentation


## Introduction

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
    M(( ))
    
    %% Verbindungen
    A --> E
    A --> M
    M --> EN
    I --> M
    E --> U
    EN --> U
    A --> U
    
    %% Styling
    classDef default fill:#fff,stroke:#333,stroke-width:2px,color:#000
    classDef dot fill:#333,stroke:#333,stroke-width:1px
    class M dot
    
    %% Knoten M sehr klein machen
    style M width:1px,height:1px,fill:#333
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
