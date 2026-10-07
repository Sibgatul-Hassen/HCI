# Privacy Policy Comprehension Among Bilingual Users in Bangladesh

## Research description

This document describes the research foundation for the bKash privacy-notice
HCI prototype in this repository. The study investigates how the design and
presentation of a privacy policy affect whether bilingual users in Bangladesh
can understand what personal information is collected, why it is collected,
how it may be used or shared, how long it may be retained, and what choices are
available to them.

The central premise is that **translation is necessary but not sufficient**.
A policy can be available in Bangla and still be difficult to understand when
it uses legal language, long paragraphs, weak visual hierarchy, unexplained
terms, or unclear consent actions. This research therefore treats privacy
policy comprehension as both a language problem and an interaction-design
problem.

> **Evidence status:** This repository contains a Figma research prototype and
> a proposed study framework. No participant dataset, statistical analysis,
> interview transcript, or independently verified empirical result is included
> here. The findings section distinguishes prototype-derived design findings
> from results that require user testing.

## Study title

**Privacy Policy Comprehension Along the English–Bangla Language Continuum:
Measuring and Redesigning Interactive Privacy Notices for Bilingual Users in
Bangladesh**

The shorter working title is **Privacy Policy Comprehension**.

## Abstract

Digital financial services ask users to make consequential decisions about
personal information through privacy notices. In Bangladesh, users may read
English, Bangla, or both, but language availability alone does not guarantee
comprehension. This research proposes a user-centred redesign of a privacy
notice that combines bilingual content, section-based navigation,
plain-language explanations, visual highlighting, an AI-summary concept, and a
data-journey view.

The study compares comprehension-oriented interaction patterns with a
conventional long-form notice. It focuses on whether users can accurately
identify data categories, purposes, legal basis, retention, sharing, and
available choices. It also examines trust, perceived control, reading effort,
and the risk that summaries or visual emphasis could oversimplify or distort
the source policy.

The expected contribution is a practical framework for designing and
evaluating bilingual privacy notices in a Bangladeshi context. The prototype is
an artefact for research and education, not an official bKash policy or
production financial-service interface.

## Background and motivation

Privacy notices are often written to be legally complete rather than easy to
use. Users may accept them without knowing:

- which categories of information are collected;
- why each category is needed;
- whether information is shared with other parties;
- how long information is retained;
- what rights or controls are available; and
- what accepting or declining means in practice.

The difficulty is amplified when a notice is read across languages. Direct
translation can preserve words while failing to preserve plain meaning,
context, tone, or the distinctions needed for an informed decision. Users may
also switch between English and Bangla depending on the subject, their
education, their familiarity with financial terminology, and the quality of
the translation.

The prototype responds to these concerns with layered disclosure. The full
notice remains available, while navigation, definitions, highlighting,
summaries, and a data-journey explanation provide additional ways to inspect
the same information.

## Problem statement

Many privacy notices provide formal disclosure without enabling reliable user
understanding. There is insufficient evidence about which combinations of
bilingual content, information architecture, plain-language support, and
visual emphasis help Bangladeshi users answer privacy questions accurately
without hiding important qualifications.

The research problem is therefore:

> How can a bilingual privacy notice be redesigned so that users in Bangladesh
> can understand and act on key data-practice information while retaining
> access to the complete and accurate policy?

## Research aim

To design and evaluate an interactive bilingual privacy notice that improves
users’ ability to locate, explain, and make decisions about personal-data
practices.

## Objectives

1. Identify the information users need in order to make an informed privacy
   decision.
2. Characterize comprehension barriers caused by legal language, translation,
   document length, terminology, and information structure.
3. Design an interactive notice that supports English and Bangla reading
   without treating either language as a secondary mode.
4. Measure comprehension of collection, purpose, retention, sharing, and
   choice information.
5. Compare the redesigned experience with a conventional long-form notice.
6. Assess whether summaries and explanations improve understanding without
   introducing inaccurate or overconfident interpretations.
7. Document design principles for future bilingual privacy-notice research in
   Bangladesh.

## Research questions

### Primary question

**RQ1.** How does an interactive bilingual privacy-notice design affect users’
ability to understand key data practices compared with a conventional
long-form notice?

### Secondary questions

- **RQ2.** Which privacy concepts remain difficult after users switch between
  English and Bangla?
- **RQ3.** Do section navigation and visual hierarchy reduce the time needed
  to locate an answer?
- **RQ4.** Do contextual term explanations improve accuracy for legal or
  technical vocabulary?
- **RQ5.** Does highlighting help users identify important information, or does
  it cause them to overlook unhighlighted qualifications?
- **RQ6.** Does an AI-summary concept improve orientation while preserving
  trust in the original policy?
- **RQ7.** Do users perceive “Not now” and “I agree” as equally visible and
  meaningful choices?
- **RQ8.** How do reading preference, language proficiency, age, education,
  digital-finance experience, and privacy experience influence outcomes?

## Hypotheses

These are testable hypotheses, not confirmed findings:

- **H1:** Users who read the redesigned notice will score higher on
  comprehension questions than users who read a conventional long-form
  notice.
- **H2:** Users will locate requested privacy information faster with section
  navigation than with linear scrolling alone.
- **H3:** Contextual plain-language definitions will improve understanding of
  unfamiliar privacy terms.
- **H4:** Bilingual access will reduce language-related difficulty for users
  who are more comfortable switching between English and Bangla.
- **H5:** A summary will improve initial orientation, but users will still need
  access to the full policy to answer qualification and exception questions.
- **H6:** Equal visibility of “Not now” and “I agree” will improve perceived
  choice and reduce pressure to consent.

## Conceptual model

The proposed model connects the notice design to user outcomes:

```text
Notice structure + language support + explanation layers
                         |
                         v
       Findability + readability + perceived control
                         |
                         v
       Accurate comprehension + informed privacy choice
```

The model also includes a risk pathway:

```text
Highlighting or summarization
            |
            v
Selective attention or oversimplification
            |
            v
Misinterpretation of qualifications and exceptions
```

The second pathway is important because a more approachable interface is not
successful if it makes the policy sound simpler or safer than it actually is.

## Prototype intervention

The Figma prototype operationalizes the research concepts through four
connected areas:

1. **Notice:** The complete policy is divided into navigable sections such as
   collected information, legal basis, and retention.
2. **AI summary:** A shorter explanation helps users orient themselves before
   returning to the source text. It is a support layer, not a replacement.
3. **Data journey:** A conceptual view shows how information moves through
   collection, use, storage, and related stages.
4. **Ask:** A question-oriented view provides a place to clarify unfamiliar
   content.

The reading state also includes:

- an English/Bangla language toggle;
- tappable or marked terms for plain-language explanations;
- an optional highlight mode;
- persistent “Not now” and “I agree” actions; and
- a clear label that the screen is a research prototype.

### Design principles

- **Completeness before compression:** Keep the source policy available.
- **Progressive disclosure:** Reveal help when users need it, without forcing
  every user through the same explanation.
- **Language parity:** Do not make Bangla a hidden or degraded alternative.
- **Traceable interpretation:** Let users return from a summary or definition
  to the relevant source passage.
- **Choice symmetry:** Do not visually or interactionally punish declining.
- **Uncertainty honesty:** Mark generated or simplified content as explanatory.
- **Mobile-first scanning:** Use hierarchy and grouping that work on narrow
  screens and under limited attention.

## Proposed methodology

### Study design

A mixed-method, between-groups usability study is recommended:

1. **Baseline condition:** A conventional long-form privacy notice with
   equivalent policy content.
2. **Interactive condition:** The bilingual, layered prototype described above.
3. **Comprehension tasks:** Participants answer questions about the notice
   after reading and locating information.
4. **Qualitative follow-up:** Think-aloud observations and semi-structured
   interviews identify confusion, trust concerns, and language preferences.

If resources permit, a within-participant pilot can follow the initial study,
with counterbalanced order and alternative but equivalent policy questions to
reduce learning effects.

### Participants

Recruit adult users of digital financial services in Bangladesh who report
reading English, Bangla, or both. Sampling should intentionally include
different levels of:

- Bangla and English reading proficiency;
- age and educational background;
- urban and non-urban experience;
- familiarity with mobile financial services; and
- prior exposure to privacy notices.

The final sample size should be determined by the study design, statistical
power requirements, recruitment feasibility, and ethics review. It should not
be inferred from this prototype repository.

### Procedure

1. Obtain informed consent for the research session.
2. Collect only necessary demographic and language-background information.
3. Introduce the task without teaching participants the correct answers.
4. Present the assigned notice condition.
5. Ask realistic information-location and comprehension questions.
6. Record task accuracy, completion time, navigation path, and requests for
   clarification.
7. Conduct a short post-task survey covering ease, trust, clarity, control,
   cognitive effort, and language preference.
8. Conduct a semi-structured interview or retrospective walkthrough.
9. Debrief participants and explain the prototype’s research status.

### Example comprehension tasks

Participants may be asked to:

- identify the categories of information collected;
- explain why a selected category is needed;
- identify the stated legal basis or purpose;
- determine how long information is retained;
- identify whether and with whom information may be shared;
- locate an available user choice or withdrawal mechanism;
- explain a highlighted or dotted term in their own words; and
- compare the summary with the relevant source passage.

Questions should test both direct retrieval and interpretation. At least some
questions should require participants to notice a qualification, exception, or
condition rather than relying on the most prominent sentence.

## Measures and analysis plan

### Primary outcome: comprehension

Create a preregistered scoring rubric for each question:

- **2 points:** accurate and complete answer;
- **1 point:** partially accurate answer with a meaningful omission;
- **0 points:** incorrect, contradicted, or unsupported answer.

Report total and topic-level scores for collection, purpose, retention,
sharing, rights, and consent choice. Score answers against the source policy,
not against the summary alone.

### Secondary quantitative measures

- task completion time;
- information-location success rate;
- number of navigation errors or backtracks;
- help requests and explanation opens;
- perceived cognitive effort;
- perceived control and voluntariness;
- trust and credibility ratings;
- preference for English, Bangla, or switching; and
- willingness to recommend or use the notice format.

Use descriptive statistics first. For a sufficiently powered study, compare
conditions using an appropriate model for the outcome type and participant
design. Report effect sizes and uncertainty, not only statistical
significance. Account for language proficiency and prior digital-finance
experience where the design supports it.

### Qualitative analysis

Transcribe interviews and think-aloud sessions with participant identifiers
removed. Code for:

- legal or financial vocabulary confusion;
- translation mismatch or awkward Bangla phrasing;
- difficulty finding information;
- summary reliance and source verification;
- perceived pressure to agree;
- trust, scepticism, and credibility;
- accessibility and visual overload; and
- moments where users changed language or interaction mode.

Use a documented codebook and retain examples of both confirming and
contradicting evidence. A second reviewer or participant-validation step can
improve confidence in the themes.

## Results and findings

### What is currently supported by the prototype

The following are **design findings from inspection of the prototype**, not
empirical participant results:

1. **The design supports layered disclosure.** Users can move from the full
   notice to section navigation, term explanations, highlighting, summaries,
   and data-journey views.
2. **The primary reading state makes key concepts visible.** Collection,
   legal basis, and retention are represented as separate navigation targets.
3. **Language choice is treated as a first-class control.** English and Bangla
   are presented together rather than placing language selection in a distant
   settings screen.
4. **Consent actions are persistently visible.** “Not now” and “I agree” are
   presented together, which creates a basis for testing choice symmetry.
5. **The prototype exposes a potential accuracy risk.** Summaries,
   highlighting, and plain-language explanations may guide attention but could
   omit conditions. This must be tested against the source policy.
6. **The prototype communicates its non-production status.** The preview
   labels itself as a research prototype and should not be mistaken for an
   official bKash screen.

### What cannot be claimed yet

This repository does **not** provide evidence to claim that the design:

- improves comprehension;
- is preferred by Bangla-speaking or bilingual users;
- reduces reading time;
- increases trust;
- improves consent quality;
- produces accurate AI summaries; or
- is accessible to users with disabilities.

Those claims require participant research, a defined comparison condition,
recorded measures, and analysis. Until that evidence exists, the hypotheses
above remain open.

### Reporting template for future results

When the study is conducted, replace this section with:

| Outcome | Baseline notice | Interactive notice | Difference/effect | Evidence |
| --- | ---: | ---: | ---: | --- |
| Overall comprehension score | To be measured | To be measured | To be calculated | Participant data |
| Collection and purpose accuracy | To be measured | To be measured | To be calculated | Participant data |
| Retention and sharing accuracy | To be measured | To be measured | To be calculated | Participant data |
| Median information-location time | To be measured | To be measured | To be calculated | Interaction logs |
| Perceived control | To be measured | To be measured | To be calculated | Post-task survey |

The completed report should include the sample, exclusions, missing data,
question wording, scoring rubric, uncertainty estimates, qualitative themes,
negative cases, and any deviations from the preregistered plan.

## Ethical and privacy considerations

Privacy research about financial services can itself expose sensitive
information. The study should:

- receive institutional ethics approval or a documented exemption before
  recruitment;
- obtain informed consent in language participants understand;
- avoid collecting real account numbers, identity documents, transaction data,
  or unnecessary personal information;
- use synthetic policy content or a controlled research scenario;
- explain that the prototype is not an official bKash policy;
- avoid implying that participation changes a participant’s financial-service
  access;
- store recordings and responses with access controls and retention limits;
- allow participants to withdraw without penalty; and
- report findings in aggregate with identifying details removed.

If an AI summarizer is added for testing, participant text should not be sent
to an external model without explicit approval, appropriate safeguards, and a
clear explanation of processing.

## Validity, reliability, and bias

The study should address the following threats:

- **Language confounding:** English and Bangla versions may differ in wording,
  not only language. Use equivalent, reviewed content.
- **Literacy confounding:** Comprehension scores may reflect general reading
  ability rather than policy design alone.
- **Novelty effect:** Participants may favour the interactive prototype because
  it is visually newer.
- **Familiarity effect:** Prior use of mobile financial services may change
  trust and task speed.
- **Question leakage:** Teaching users during the session can inflate scores.
- **Summary anchoring:** Users may accept the summary without checking the
  source.
- **Researcher interpretation:** Qualitative coding should preserve negative
  and unexpected evidence.
- **Device effects:** Screen size, browser performance, and connectivity can
  affect the experience.

Pilot the tasks, check translated equivalence with qualified bilingual
reviewers, counterbalance condition order where appropriate, and preserve the
exact materials used in the study.

## Expected contributions

If validated through future testing, this work could contribute:

1. A measurable definition of privacy-policy comprehension for bilingual users.
2. Evidence about the value and limits of layered privacy-notice interaction.
3. Design guidance for language parity, term explanations, summaries, and
   consent choice architecture.
4. A method for checking simplified explanations against a complete policy.
5. A research agenda for privacy UX in Bangladeshi digital-finance contexts.

The contribution is not a claim that one interface solves privacy
comprehension. It is a testable approach for making privacy information easier
to inspect while preserving accuracy and user control.

## Reproducibility and project artefacts

The current artefacts are:

- [the embedded prototype](./index.html);
- [the static preview](./preview.png);
- [the interactive Figma prototype](https://www.figma.com/proto/gV3XI8qkRSyHQSLaQJfhPp/Untitled?node-id=1-3549&m=draw&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1);
- [the main Figma design file](https://www.figma.com/design/gV3XI8qkRSyHQSLaQJfhPp/Untitled?node-id=2-5149&m=draw); and
- [the project README](./README.md).

Future study releases should include the anonymized task materials, translated
policy versions, scoring rubric, analysis code, preregistration or protocol,
and a data dictionary. Raw participant data should not be published if doing
so could identify participants or expose sensitive information.

## Conclusion

Privacy-policy comprehension should be evaluated by what people can accurately
understand and use, not only by whether a translated document exists. This
prototype proposes a bilingual, layered, and choice-aware reading experience
for users in Bangladesh. Its current value is as a research artefact and
testable design hypothesis. Empirical findings must be collected and reported
before claims about effectiveness are made.

## Credit and copyright

Research concept, prototype presentation, and documentation by **Sibgatul
Hassen**.

Copyright © 2026 Sibgatul Hassen. The repository is provided under the terms
in [`LICENSE`](./LICENSE). The bKash name and marks belong to their respective
owners and are used only to identify the research scenario.
