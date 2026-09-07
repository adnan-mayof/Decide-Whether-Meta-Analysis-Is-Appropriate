# Step 12 — Decide Whether Meta-Analysis Is Appropriate
[← Previous Step: Risk-of-Bias Assessment](https://github.com/adnan-mayof/Risk-of-Bias-Assessment/blob/main/README.md)

Maya has completed data extraction.

After the risk-of-bias assessment and the protocol-defined handling of studies, **111 studies** are available for the systematic review.

Now Maya needs to determine whether she should conduct a meta-analysis.

> **Maya:** “I have finished extracting the data. Since this is a systematic review, should I automatically conduct a meta-analysis?”

> **Mentor:** “Not automatically. First, you need to examine what information the studies actually provide and determine whether quantitative synthesis is appropriate.”

> **Maya:** “So some studies might contribute to the systematic review but not to the meta-analysis?”

> **Mentor:** “Exactly.”

Maya reviews her extraction dataset.

She discovers that most studies report their findings without enough statistical information for her planned quantitative synthesis.

However, about **20% of the studies report suitable statistical outcomes** that can be used to calculate or obtain effect sizes.

---

# 1. Systematic Review vs. Meta-Analysis

Maya's mentor explains the difference.

A **systematic review** is the broader process of systematically identifying, evaluating, and synthesizing evidence.

A **meta-analysis** is a statistical method for quantitatively combining results from multiple studies.

Therefore, a systematic review can include studies that do not contribute to the meta-analysis.

```text
Systematic Review
       ↓
   111 studies
       ↓
 ┌─────┴──────────┐
 ↓                ↓
Studies with      Studies without
suitable          suitable
quantitative      quantitative
information       information
 ↓                ↓
≈22 studies       ≈89 studies
 ↓                ↓
Meta-analysis     Systematic /
                  narrative synthesis
```

The systematic review considers the broader evidence.

The meta-analysis quantitatively synthesizes the subset of studies for which quantitative synthesis is appropriate.

---

# 2. Maya Examines the Extracted Results

Maya reviews the results reported by all 111 studies.

She finds:

| Type of Evidence                  | Number of Studies | Approx. Percentage | Contribution                      |
| --------------------------------- | ----------------: | -----------------: | --------------------------------- |
| Suitable quantitative outcomes    |                22 |              19.8% | Systematic review + meta-analysis |
| No suitable quantitative outcomes |                89 |              80.2% | Systematic review                 |
| **Total**                         |           **111** |           **100%** |                                   |

Maya summarizes this as:

> **Approximately 20% of the studies provide suitable statistical outcomes for quantitative synthesis.**

---

# 3. Why Can't Maya Meta-Analyze All 111 Studies?

> **Maya:** “But all 111 studies are eligible for the review. Why can't I include all of them in the meta-analysis?”

> **Mentor:** “Because eligibility for the systematic review and eligibility for a particular quantitative synthesis are not necessarily the same.”

A study may meet all of Maya's review eligibility criteria but still lack the statistical information needed for the planned meta-analysis.

For example, a study might report:

> “Students who received the AI intervention showed greater improvement in learning than students in the comparison group.”

That finding is relevant to Maya's systematic review.

However, if the study does not provide sufficient information to calculate an appropriate effect size, it may not contribute to the meta-analysis.

Therefore:

```text
Eligible for systematic review
              ↓
Relevant evidence
              ↓
Insufficient quantitative information
              ↓
Not included in meta-analysis
              ↓
May still contribute to systematic synthesis
```

---

# 4. What Does "Suitable Statistical Information" Mean?

Maya asks:

> **Maya:** “What kind of information would allow a study to contribute to the meta-analysis?”

> **Mentor:** “It depends on the effect-size measure you plan to use.”

For example, statistical information may include:

* Means
* Standard deviations
* Sample sizes
* Standard errors
* Confidence intervals
* Test statistics
* Correlations
* Other statistics that can be converted into an appropriate effect size

The important question is:

> **Can the reported results be converted into a suitable quantitative effect size for the planned meta-analysis?**

Having a statistical result does not automatically mean that it can be included.

---

# 5. Example: A Study That Can Contribute to the Meta-Analysis

Study 001 reports:

| Group           |  n | Mean |  SD |
| --------------- | -: | ---: | --: |
| AI intervention | 60 | 82.4 | 8.6 |
| Control         | 60 | 76.8 | 9.1 |

Maya has:

* Intervention sample size
* Control sample size
* Intervention mean
* Control mean
* Intervention standard deviation
* Control standard deviation

This information can potentially be used to calculate a standardized effect size.

Therefore:

```text
Study 001
    ↓
Suitable statistical information
    ↓
Appropriate effect size can be calculated
    ↓
Eligible for meta-analysis
```

---

# 6. Example: A Study That Cannot Contribute to the Meta-Analysis

Study 045 reports:

> “Students receiving the AI intervention demonstrated greater improvement than students in the comparison group.”

However, the study does not provide enough statistical information for Maya's planned effect-size calculation.

Maya checks:

* Full text
* Tables
* Figures
* Supplementary materials
* Other available reports

She still cannot obtain the necessary information.

Therefore:

```text
Study 045
    ↓
Eligible for systematic review
    ↓
Relevant finding reported
    ↓
Insufficient quantitative information
    ↓
Not included in meta-analysis
```

The study remains part of the systematic review.

---

# 7. Maya Makes an Important Distinction

Maya writes two separate questions in her extraction dataset.

### Question 1

> **Is the study eligible for the systematic review?**

### Question 2

> **Does the study provide appropriate quantitative information for a particular meta-analysis?**

These are different questions.

```text
Systematic-review eligibility
            ↓
         111 studies

Meta-analysis eligibility
            ↓
         ≈22 studies
```

---

# 8. A Study Can Be Included in the Review Without Being in the Meta-Analysis

Maya now understands:

> **Maya:** “So a study can be included in my systematic review but not contribute to my meta-analysis.”

> **Mentor:** “Exactly.”

For example:

| Study     | Systematic Review | Meta-Analysis | Reason                                     |
| --------- | ----------------- | ------------- | ------------------------------------------ |
| Study 001 | Yes               | Yes           | Suitable quantitative information          |
| Study 002 | Yes               | Yes           | Suitable quantitative information          |
| Study 003 | Yes               | No            | Insufficient quantitative information      |
| Study 004 | Yes               | Yes           | Suitable quantitative information          |
| Study 005 | Yes               | No            | Insufficient quantitative information      |
| Study 006 | Yes               | No            | Outcome not suitable for planned synthesis |

---

# 9. Does Maya Need a Minimum Number of Studies?

Maya now has another question.

> **Maya:** “Is there a minimum number of studies I need before I can conduct a meta-analysis?”

> **Mentor:** “There is no universally accepted minimum number of studies required for a meta-analysis.”

Methodological guidance indicates that **two studies can be quantitatively combined** when quantitative synthesis is otherwise appropriate and the studies provide suitable, sufficiently comparable information.

Therefore, Maya should not use an arbitrary rule such as:

> “I need at least 10 studies.”

The number of studies required for the **basic meta-analysis** is different from the number that may be useful for additional analyses.

---

# 10. Two Studies Can Be Enough for a Basic Meta-Analysis

For example:

```text
Study 001 → Effect size
Study 002 → Effect size
             ↓
        Pooled estimate
```

A basic meta-analysis can be conducted with two studies.

However, having only two studies provides limited information for examining:

* Between-study heterogeneity
* Sources of heterogeneity
* Moderators
* Small-study effects
* Publication bias

Therefore:

> **Being able to conduct a meta-analysis is not the same as having enough studies for every additional analysis.**

---

# 11. What About 10 Studies?

Maya has heard researchers mention a threshold of 10 studies.

> **Maya:** “What does 10 studies mean, then?”

> **Mentor:** “Ten studies is sometimes used as a practical threshold for certain additional statistical assessments. It is not a universal minimum for conducting a meta-analysis.”

For example, assessments of small-study effects or publication bias may have limited usefulness when very few studies are available.

Therefore:

```text
2 studies
   ↓
Basic meta-analysis may be possible

More studies
   ↓
More information for additional analyses

≈10+ studies
   ↓
Some additional assessments may become
more reasonable, depending on the method
```

The specific statistical analysis determines what amount of evidence is needed.

---

# 12. What About Meta-Regression?

Maya remembers that her research question also asks which characteristics explain differences between study effects.

> **Maya:** “What about meta-regression?”

> **Mentor:** “Meta-regression requires a separate consideration.”

A commonly used rule of thumb is approximately **10 studies per study-level predictor**, although this is not an absolute requirement.

Maya has approximately 22 studies.

Therefore, she should be cautious about fitting a model with many moderators.

For example:

```text
22 studies
   ↓
Basic meta-analysis
   ✓ Potentially appropriate

22 studies
   ↓
Meta-regression with many predictors
   ⚠ Requires careful consideration
```

Maya must consider:

* Number of studies
* Number of predictors
* Distribution of moderator categories
* Statistical power
* Scientific rationale
* Planned analysis

She should not simply add many moderators because the dataset contains many variables.

---

# 13. Statistical Information Alone Is Not Enough

Maya discovers another important issue.

Some studies provide statistical information, but their outcomes are substantially different from the outcomes in her primary synthesis.

> **Maya:** “If a study gives me means and standard deviations, can I automatically include it?”

> **Mentor:** “No. Statistical information is necessary, but it is not sufficient.”

The study also needs to provide an outcome that is appropriate for the planned synthesis.

Therefore:

```text
Suitable statistical information
              +
Relevant outcome
              +
Compatible effect-size approach
              +
Conceptually appropriate synthesis
              ↓
      Meta-analysis
```

---

# 14. Example: Statistical Information but an Incompatible Outcome

Suppose Maya's primary meta-analysis focuses on **student learning outcomes**.

Study 078 reports:

* Mean
* Standard deviation
* Sample size

But its outcome measures **students' attitudes toward AI**, rather than learning.

Maya cannot automatically include it in the primary learning-outcome meta-analysis.

The study may still contribute to the systematic review.

```text
Study 078
    ↓
Statistical information available
    ↓
Outcome = Attitude toward AI
    ↓
Different construct from primary outcome
    ↓
Not included in primary learning-outcome meta-analysis
```

---

# 15. Maya Examines the 111 Studies

Maya now classifies her studies.

| Category                                       | Number | Percentage |
| ---------------------------------------------- | -----: | ---------: |
| Eligible studies for systematic review         |    111 |       100% |
| Studies with suitable quantitative outcomes    |     22 |      19.8% |
| Studies without suitable quantitative outcomes |     89 |      80.2% |

She realizes that the **89 studies are not excluded from the systematic review**.

They simply do not contribute to the quantitative meta-analysis.

---

# 16. Maya Decides to Conduct Both a Systematic Review and Meta-Analysis

Maya discusses her findings with her mentor.

> **Maya:** “I have 111 eligible studies. Most don't provide suitable statistical outcomes, but about 20% do.”

> **Mentor:** “Then what does that tell you?”

> **Maya:** “I can conduct a systematic review of all 111 studies and a meta-analysis of the approximately 22 studies with suitable quantitative information.”

> **Mentor:** “Exactly.”

Maya's project will therefore include:

### Systematic Review

**111 studies**

### Meta-Analysis

**22 studies**

### Systematic/Narrative Synthesis of Non-Quantitative Evidence

**89 studies**

---

# 17. Maya's Overall Synthesis Structure

```text
                     111 Eligible Studies
                              ↓
                     Systematic Review
                              ↓
                 ┌────────────┴────────────┐
                 ↓                         ↓
          22 studies                  89 studies
            ≈20%                        ≈80%
                 ↓                         ↓
         Meta-analysis              Systematic /
         quantitative               narrative
         synthesis                  synthesis
                 └────────────┬────────────┘
                              ↓
                    Overall Evidence Review
```

The systematic review provides the broader picture.

The meta-analysis provides the quantitative estimate from the subset of studies with suitable data.

---

# 18. Example Results

Maya records the decision in her review documentation.

> **Example result:**
>
> “A total of 111 studies met the eligibility criteria for the systematic review. Of these, 22 studies (19.8%) reported suitable quantitative outcomes and sufficient statistical information for inclusion in the meta-analysis. The remaining 89 studies (80.2%) contributed to the systematic review but were not included in the quantitative synthesis because they did not provide suitable quantitative information for the planned meta-analysis.”

Maya can now clearly explain why the number of studies in the systematic review is different from the number of studies in the meta-analysis.

---

# 19. What If Some Studies Have Only Partially Usable Data?

Maya finds another situation.

Study 090 reports:

* Achievement → sufficient statistical information
* Motivation → insufficient statistical information

> **Maya:** “What should I do with this study?”

> **Mentor:** “You don't necessarily exclude the entire study from the meta-analysis. Look at the particular outcome and synthesis.”

The same study may contribute one outcome to the meta-analysis while another outcome contributes only to the broader systematic review.

For example:

```text
Study 090
   │
   ├── Achievement
   │       ↓
   │   Suitable data
   │       ↓
   │   Meta-analysis
   │
   └── Motivation
           ↓
     Insufficient data
           ↓
      Systematic review
```

This is another reason why Maya needs to distinguish **study-level inclusion** from **outcome-level quantitative eligibility**.

---

# 20. Maya Documents Her Decision

Maya creates a decision record.

```text
Meta-analysis decision:

Systematic review:
111 eligible studies

Studies with suitable quantitative outcomes:
22 (19.8%)

Studies without suitable quantitative outcomes:
89 (80.2%)

Decision:
Conduct a systematic review and meta-analysis.

Systematic review:
All 111 eligible studies contribute to the
broader evidence synthesis.

Meta-analysis:
Quantitatively synthesize the 22 studies with
suitable quantitative outcomes and sufficient
statistical information.

Minimum-study principle:
There is no universal minimum number of studies
required for a meta-analysis. Two appropriately
comparable studies may be sufficient for a basic
quantitative synthesis.

Additional analyses:
Consider the number of available studies
separately for heterogeneity assessment,
subgroup analysis, meta-regression, and
small-study/publication-bias assessments.
```

---

# 21. Maya's Decision Workflow

Maya summarizes the entire decision process.

```text
Extracted Data
       ↓
Identify Available Outcomes
       ↓
Check Statistical Information
       ↓
Are Outcomes Appropriate?
       ↓
Can an Appropriate Effect Size
Be Calculated or Obtained?
       ↓
 ┌─────┴──────────────┐
 ↓                    ↓
Yes                   No
 ↓                    ↓
Meta-analysis         Systematic /
                      narrative synthesis
       └──────┬───────┘
              ↓
       Document Decision
```

---

# 22. Maya's Final Decision

Maya writes in her research notebook:

> **Systematic review:** 111 eligible studies.
>
> **Meta-analysis:** 22 studies (19.8%) with suitable quantitative outcomes and sufficient statistical information.
>
> **Systematic/narrative synthesis:** 89 studies (80.2%) that contribute to the systematic review but do not contribute to the quantitative meta-analysis.

She now understands why her review contains two related but different forms of synthesis.

---

# ⭐ Important Principle

> **A systematic review and meta-analysis does not require every eligible study to contribute to the meta-analysis. All eligible studies can contribute to the systematic review, while the meta-analysis can synthesize only the subset of studies that report suitable and sufficiently comparable quantitative outcomes. There is no universal minimum number of studies required for a basic meta-analysis; two appropriately comparable studies can be sufficient. However, additional analyses such as heterogeneity assessment, subgroup analysis, meta-regression, and assessments of small-study effects may require more studies and should be considered separately.**

---

# 🚀 Maya's Journey Continues

Maya now understands the difference between the two parts of her evidence synthesis.

> **Maya:** “Now I understand. The systematic review gives me the broader picture from all 111 studies, while the meta-analysis quantitatively combines the studies with suitable data.”

> **Mentor:** “Exactly.”

> **Maya:** “And I don't need an arbitrary number like 10 studies just to conduct a meta-analysis.”

> **Mentor:** “Correct. What matters is whether the quantitative synthesis is appropriate. The number of studies becomes especially important when you consider additional analyses.”

Maya opens the dataset containing the **22 studies selected for the meta-analysis**.

> **Next step: Prepare the Data for Analysis.**

---

# Assessment

## Multiple-Choice Questions

### 1. How many studies are included in Maya's systematic review?

A. 22
B. 89
C. 111
D. 10

### 2. Approximately what percentage of the eligible studies provide suitable quantitative outcomes?

A. 10%
B. 20%
C. 50%
D. 80%

### 3. How many studies are available for Maya's meta-analysis in this example?

A. 22
B. 89
C. 111
D. 126

### 4. What happens to the 89 studies that do not provide suitable quantitative information?

A. They are automatically excluded from the systematic review
B. They can contribute to the systematic or narrative synthesis
C. They are counted as duplicates
D. They must be assigned an estimated effect size

### 5. Does every eligible study have to contribute to the meta-analysis?

A. Yes
B. No
C. Only if it is randomized
D. Only if it has a large sample

### 6. Is there a universally accepted minimum number of studies required to conduct a basic meta-analysis?

A. Yes, 5
B. Yes, 10
C. Yes, 20
D. No

### 7. Can two appropriately comparable studies be quantitatively combined?

A. Yes
B. No
C. Only when both have identical sample sizes
D. Only when both are published in the same year

### 8. Why can a small number of studies limit additional analyses?

A. There may be limited information for examining heterogeneity, moderators, or small-study effects
B. Effect sizes cannot be calculated with fewer than 10 studies
C. Systematic reviews require exactly 10 studies
D. Small studies cannot report statistics

### 9. Maya has 22 studies for her meta-analysis. What should she consider before conducting a meta-regression with many predictors?

A. Only the publication year
B. The number of studies, number of predictors, moderator distribution, and scientific rationale
C. Only the study titles
D. Only the sample size of the largest study

### 10. Is suitable statistical information alone enough to include a study in the meta-analysis?

A. Yes
B. No
C. Only when the result is statistically significant
D. Only for randomized trials

### 11. Study 090 provides suitable statistical information for achievement but not motivation. What can Maya potentially do?

A. Exclude the entire study from the systematic review
B. Include the achievement outcome in the relevant meta-analysis while retaining the motivation finding for the broader synthesis
C. Invent the missing motivation statistics
D. Count Study 090 as two independent studies

### 12. What is the best description of Maya's final synthesis?

A. 111 studies in the meta-analysis and 0 in the systematic review
B. 22 studies in both the systematic review and meta-analysis, with 89 excluded from the review
C. 111 studies in the systematic review, with 22 contributing to the quantitative meta-analysis
D. 89 studies in the meta-analysis and 22 in the systematic review

---

# Answer Key

| Question | Answer |
| -------: | :----: |
|        1 |    C   |
|        2 |    B   |
|        3 |    A   |
|        4 |    B   |
|        5 |    B   |
|        6 |    D   |
|        7 |    A   |
|        8 |    A   |
|        9 |    B   |
|       10 |    B   |
|       11 |    B   |
|       12 |    C   |

---

# Repository Structure

```text
step-12-decide-whether-meta-analysis-is-appropriate/
│
├── README.md
│
├── decision/
│   ├── meta-analysis-decision.md
│   ├── quantitative-eligibility.md
│   └── synthesis-plan.md
│
├── data/
│   ├── synthesis-eligibility.xlsx
│   └── meta-analysis-studies.xlsx
│
└── assessment/
    └── assessment.md
```
