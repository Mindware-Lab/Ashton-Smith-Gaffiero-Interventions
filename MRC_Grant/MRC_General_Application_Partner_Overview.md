# Chronic Primary Pain Programme

## High-level partner overview

### The central proposition

The programme will develop and test a **mechanism-led digital cognitive-affective intervention for chronic primary pain**.

The pain intervention is the primary clinical product. It will be supported by the **HRP Transfer Lab**, a computational development environment designed to improve how intervention components, measures and early human studies are selected, calibrated and optimised.

A focused pathway and implementation strand will ensure that the resulting intervention is designed for a credible position within chronic-pain care rather than as a context-free cognitive-training product.

The overall architecture is:

```text
+ Pain-specific clinical intervention
+ enabling computational development technology
+ mechanism-sensitive measurement
+ pathway placement
+ prospective human validation
```

The immediate goal is a clinically credible intervention for chronic primary pain. The longer-term value is a reusable and auditable method for developing cognitive-affective interventions more efficiently across other health-related domains, with each new application requiring its own clinical and scientific validation.

---

## 1. The clinical problem

Chronic primary pain can have substantial effects on:

* daily functioning;
* valued activity;
* work and relationships;
* confidence in self-management;
* avoidance and persistence;
* emotional wellbeing and quality of life.

Pain intensity alone does not capture this burden adequately. People may continue to experience severe interference, uncertainty and loss of activity even after medical investigation or treatment.

The proposed intervention is therefore focused primarily on:

* pain-related functioning;
* activity engagement;
* adaptive interpretation;
* decision-making under uncertainty;
* self-management;
* updating expectations following safe or manageable experiences.

It is intended as a scalable digital adjunct to existing care—not as a replacement for multidisciplinary pain services and not as a claim that pain is unreal or merely the product of faulty thinking.

---

## 2. A connected cognitive-affective mechanism chain

The programme is based on the idea that several cognitive-affective processes form a connected adaptive chain:

```text
pain-related cue or ambiguity
→ attention and evidence selection
→ interpretation and threat/safety appraisal
→ uncertainty monitoring
→ activity, avoidance or self-management decision
→ experienced outcome
→ updating of predictions
→ reuse in daily functioning
```

Candidate intervention components may target:

* threat-sensitive attention;
* interpretation of ambiguous bodily and situational information;
* reliability-sensitive evidence accumulation;
* uncertainty monitoring;
* threat and safety prediction;
* avoidance and activity decisions;
* updating following tolerable or less adverse outcomes;
* implementation of adaptive decisions in daily life.

The programme will not assume that every participant has the same mechanism profile. Instead, it will compare a bounded, prespecified set of competing mechanism models and determine which intervention configuration is sufficiently measurable, plausible and modifiable to justify proof-of-concept testing.

Mechanism mapping is therefore not an independent exploratory exercise. It is the means by which the measurement system is calibrated and the clinical product is selected.

---

## 3. What makes the approach distinctive

Many behavioural and psychological interventions combine several components and test the complete package. If the package succeeds or fails, it may remain unclear:

* which component affected the intended mechanism;
* which component produced only task practice;
* which participants responded to which component;
* which elements added burden without benefit;
* whether any change generalised outside the training task.

This programme separates five different levels of evidence:

```text
≠ trained-task improvement
≠ mechanism change
≠ protected transfer
≠ functional transfer
≠ delayed retention
```

A participant becoming better at the training task is not sufficient evidence of a useful clinical effect.

The programme will therefore test a staged sequence:

```text
trained operation
→ changed parameters or wrapper
→ protected untrained task
→ patient-relevant functional outcome
→ delayed re-check
```

This makes the project an evidence-generating intervention-development programme rather than simply another digital cognitive exercise.

---

## 4. The role of the HRP Transfer Lab

The HRP Transfer Lab is the enabling computational environment through which the pain intervention will be developed.

Its central purpose is to reduce avoidable uncertainty before expensive human testing.

The computational workflow is:

```text
  evidence and dataset registration
→ transportability-weighted parameter priors
→ prespecified competing mechanism models
→ empirically constrained synthetic participants
→ synthetic experiments
→ parameter and model recovery
→ power and study-design optimisation
→ pain-specific human calibration
→ prospective candidate selection
→ active-controlled proof of concept
→ advance, revise or retire
```

The platform will help answer questions such as:

* Can the proposed mechanism actually be identified using the planned task?
* Can competing explanations be distinguished?
* Which task conditions provide the most information?
* Are there likely floor, ceiling, timing or model-confusion problems?
* How many participants and trials are needed?
* Which candidate intervention is most informative to test first?
* What predictions should be observed if the model is approximately correct?
* Which components should be advanced, revised or retired before a larger trial?

The aim is not to replace clinical research. It is to make early human studies better targeted, appropriately sized, denser in useful information and easier to interpret.

---

## 5. Evidence borrowing and transportability

The HRP Transfer Lab will draw on scientific literature, behavioural datasets, existing task data, pain-related evidence and local human calibration.

These sources will not be treated as equally informative.

Each source will be assessed for its match to the target question, including:

* construct match;
* task match;
* population match;
* delivery-format match;
* data quality;
* permitted use;
* uncertainty;
* risk of transportability failure.

Evidence from another task or population may inform a broad parameter range without being treated as direct evidence about chronic primary pain.

The platform will therefore use **transportability-weighted priors**:

```text
directly matched evidence
→ stronger influence

structurally similar evidence
→ moderate, discounted influence

broad or cross-domain evidence
→ weak constraints and sensitivity testing

pain-specific human calibration
→ primary source for novel clinical parameters
```

Alternative borrowing regimes will be compared. If intervention selection, power estimates or model identification change substantially across reasonable prior assumptions, the conclusion will be labelled **prior-sensitive**.

The appropriate response to prior sensitivity will be additional human calibration, not a stronger computational claim.

---

## 6. Synthetic experiments without synthetic clinical claims

Synthetic participants and synthetic experiments will be used to:

* test software and analysis code;
* assess parameter recovery;
* determine whether models are distinguishable;
* estimate power and precision;
* compare task and intervention schedules;
* stress-test missingness, adherence and device variation;
* generate prospective predictions.

Synthetic populations may represent realistic variation in:

* baseline cognitive performance;
* attention and lapse rates;
* threat and safety weighting;
* decision thresholds;
* context updating;
* learning rates;
* intervention response;
* transfer and retention;
* missingness and dropout.

These profiles are modelling hypotheses used to challenge the study design. They are not clinical labels.

Synthetic data will not be added to human observations to inflate the sample size or manufacture clinical certainty.

The governing principle is:

> **Databases constrain the plausible behavioural system; models formalise competing mechanisms; synthetic experiments optimise and challenge the design; prospective human studies determine what actually works.**

Human data remain the source of truth for:

* mechanism validity;
* task reliability;
* acceptability and burden;
* safety;
* intervention effects;
* transfer;
* functional benefit;
* clinical and pathway suitability.

---

## 7. Parameter recovery, model recovery and prospective prediction

A key technical contribution is testing whether the planned study can recover what it claims to measure.

### Parameter recovery

The system will generate data from known parameter values and test whether the planned analysis can recover them.

```text
→ known parameter values
→ synthetic study data
→ planned statistical model
→ recovered estimates
```

This will reveal whether parameters can be estimated with acceptable:

* bias;
* precision;
* interval coverage;
* robustness to lapses and missing data;
* ability to recover clinically meaningful contrasts.

A parameter that cannot be recovered reliably should not be treated as a strong outcome in the human study.

### Model recovery

The system will also generate data from each serious competing mechanism model and test whether the analysis can distinguish them.

Where different mechanisms produce indistinguishable results, the team will:

* redesign the task;
* add more informative conditions;
* collapse the models into a broader hypothesis class; or
* stop claiming that the mechanism can be identified.

### Prospective prediction

The platform will produce predictions before the human results are known.

Predictions may concern:

* baseline parameter distributions;
* learning trajectories;
* transfer costs;
* first-contact performance dips;
* recovery curves;
* adherence and missingness;
* intervention-effect scenarios;
* delayed retention;
* functional associations.

Predicted and observed outcomes will then be compared directly.

A failed prediction will be treated as evidence that the model, prior or transportability assumptions require revision—not hidden through post-hoc retuning.

---

## 8. Psychometric development alongside intervention development

The programme will engineer the measurement system alongside the intervention rather than treating assessment as an afterthought.

Potential measurement products include:

* mechanism-sensitive behavioural tasks;
* pain-appraisal measures;
* activity-prediction and decision measures;
* short questionnaires;
* patient-reported outcome modules;
* protected-transfer measures;
* intervention-fidelity indices;
* practitioner-facing summary scores.

The development sequence is:

```text
→ construct and intended-use definition
→ content and task blueprint
→ candidate item and task generation
→ expert and lived-experience review
→ synthetic psychometric testing
→ optimised human calibration
→ cognitive interviewing and usability testing
→ reliability and validity assessment
→ independent validation
```

AI may support the generation and criticism of candidate task materials or questionnaire items, but all content will be reviewed for:

* construct relevance;
* ambiguity;
* reading and cognitive burden;
* cultural assumptions;
* redundancy;
* fairness risks;
* harmful or blaming language;
* unintended shortcut solutions.

Synthetic psychometric performance cannot establish real validity, reliability, meaningful change or fairness. These require prospective human data.

This integrated psychometric function is important because the intervention cannot be evaluated convincingly unless the intended mechanism and transfer outcomes can first be measured reliably.

---

## 9. The role of AI

AI is primarily a constrained research and development tool within this programme.

Potential roles include:

* extracting structured information from scientific evidence;
* tracing parameter sources;
* proposing protocol variants under fixed constraints;
* identifying rival mechanisms;
* criticising claims and model assumptions;
* supporting psychometric item development;
* synthesising pathway documents;
* checking reproducibility artefacts.

AI will not:

* make autonomous clinical decisions;
* determine patient eligibility;
* allocate treatment;
* replace clinicians or statisticians;
* issue unreviewed clinical feedback;
* convert extracted evidence into an approved prior without human review.

All consequential scientific, clinical, pathway and progression decisions will remain human decisions.

The purpose of the AI layer is to increase the structure, traceability and scrutiny of the development process—not to bypass scientific or clinical responsibility.

---

## 10. Reproducibility, traceability and claims control

Every consequential dataset, prior, model, protocol, simulation and prediction will be versioned and traceable.

Computational outputs will record information such as:

* source datasets;
* evidence and prior-registry versions;
* model and protocol versions;
* analysis specifications;
* software environment;
* configuration settings;
* random seeds;
* output checksums;
* human review status.

This allows partners and reviewers to ask:

```text
What data informed this assumption?
Which prior version was used?
Which model produced this prediction?
What changed between analyses?
Who reviewed and approved the result?
Can the analysis be reproduced?
```

The platform is designed to produce **auditable evidence packets**, not isolated scores, rankings or recommendations.

Each evidence packet will also distinguish:

* what the data support;
* what remains hypothetical;
* what evidence level is justified;
* which assumptions materially affect the conclusion;
* what must not be inferred.

This claims-control function is central to preventing simulation results, task learning or AI-generated outputs from being overstated as clinical evidence.

---

## 11. Pain-specific human studies

The human programme has two principal stages.

### Stage 1: pain-specific mechanism mapping, measurement calibration and candidate selection

Adults with chronic primary pain will complete prespecified mechanism-sensitive tasks and relevant psychological and functional measures.

This stage will establish:

* measurement reliability;
* baseline parameter distributions;
* model and parameter recoverability;
* relationships between candidate mechanisms and functioning;
* acceptability and burden;
* device and timing quality;
* out-of-sample predictive validity;
* suitability of mechanism-targeted candidates.

The study will compare a small number of prespecified mechanism models and intervention candidates. It will not be an open-ended investigation of the mechanisms of chronic pain.

The output will be a prospectively locked:

* intervention configuration;
* mechanistic comparator;
* active control;
* measurement battery;
* proof-of-concept protocol.

### Stage 2: early proof of concept

The selected intervention will then be compared with the mechanistic comparator and active control.

The study will test:

* whether the intended mechanism changes;
* whether change transfers to a protected task;
* whether the result is distinguishable from practice or expectancy;
* whether functional outcomes move in the predicted direction;
* whether effects remain recoverable after delay;
* whether the intervention is feasible, acceptable and safe;
* whether computational predictions correspond with observed outcomes.

The endpoint is not automatically progression. It is a justified:

```text
advance
or
revise
or
retire
```

decision.

---

## 12. Intervention selection and progression

The platform will distinguish between two questions.

### Is the study design informative?

This concerns:

* mechanism identifiability;
* parameter and model recovery;
* measurement reliability;
* statistical precision;
* participant burden;
* technical quality;
* expected information value.

### Which intervention candidate should be tested?

This depends on explicit assumptions about:

* mechanistic plausibility;
* likely mechanism change;
* transfer probability;
* durability;
* adherence;
* functional relevance;
* safety;
* development cost.

Candidates will be compared across these separate dimensions rather than reduced automatically to a single opaque score.

The output may distinguish:

```text
primary candidate
mechanistic comparator
active control
conditional candidate
candidate to defer
candidate to retire
```

A candidate will advance only where its assumptions, evidence and trade-offs are explicit.

---

## 13. Pathway placement and implementation

The intervention will be designed for a defined point in the chronic-primary-pain pathway.

The programme will specify:

* intended users;
* clinical entry and access routes;
* exclusions and escalation procedures;
* practitioner oversight;
* safeguarding and onward care;
* information-governance requirements;
* implementation burden;
* patient and practitioner journeys;
* adoption risks;
* later health-economic requirements.

The pathway model will examine:

```text
→ patient need or referral cue
→ eligibility and clinical boundaries
→ access and onboarding
→ practitioner oversight
→ intervention use
→ monitoring and escalation
→ completion or non-response
→ onward care
→ patient and service outcomes
```

This strand is deliberately focused. It is not intended to redesign the entire NHS pain pathway or automate clinical allocation.

Its purpose is to ensure that the product has a credible route to patient benefit.

---

## 14. Patient and public involvement

People living with chronic primary pain will contribute before the intervention and study procedures are locked.

They will help assess:

* whether the mechanism narrative is credible and non-blaming;
* whether tasks reflect lived experience;
* cognitive and emotional burden;
* potentially distressing or invalidating content;
* meaningful functional outcomes;
* recruitment and retention;
* onboarding and feedback;
* acceptable support and escalation routes;
* interpretation of mixed or unexpected results.

PPI will be linked to identifiable changes in the intervention and development plan rather than treated as a general consultation exercise.

---

## 15. The role of the BPS enabling study

The proposed BPS mathematics-anxiety study is a separate methodological calibration case.

It may provide useful evidence about:

* remote digital delivery;
* adherence and retention;
* browser and device timing;
* trial-level instrumentation;
* learning curves;
* directional-transfer costs;
* lapse and response variability;
* delayed follow-up;
* parameter and model recovery.

It will not provide evidence for:

* pain-specific validity;
* chronic-pain parameter distributions;
* acceptability in people with chronic primary pain;
* pain-related efficacy;
* clinical pathway suitability.

The chronic-pain programme does not depend on the BPS study being funded or producing a positive effect.

Its value is as an early test of the transferable digital-delivery, measurement and computational-calibration methodology.

---

## 16. Why the architecture is coherent

The programme links every level of work to the same clinical-development decision.

```text
→ clinical problem
→ prespecified mechanism chain
→ mechanism-sensitive measurement
→ traceable evidence and priors
→ competing computational models
→ synthetic design validation
→ pain-specific human calibration
→ prospectively selected intervention
→ protected and delayed transfer
→ functional outcome
→ pathway fit
→ advance, revise or retire
```

The intervention, computational platform, measurement system and pathway work are therefore not separate projects.

They are connected parts of one translational architecture:

* the **clinical product** defines what must ultimately benefit patients;
* the **mechanism models** define what should change;
* the **measurement system** determines whether that change can be detected;
* the **evidence and prior system** makes assumptions explicit and traceable;
* the **synthetic experiments** test whether the study can answer its own questions;
* the **human studies** calibrate and challenge the models;
* the **transfer framework** prevents task learning from being mistaken for benefit;
* the **pathway strand** determines whether the product can be used credibly;
* the **governance layer** controls what may legitimately be claimed.

---

## 17. Value to collaborators and partners

### Clinical partners

Clinical collaborators provide:

* target-population definition;
* pathway placement;
* safety and escalation;
* recruitment feasibility;
* intervention co-design;
* interpretation of clinical relevance;
* future adoption routes.

The platform gives clinical partners a structured way to translate clinical hypotheses into measurable, testable and revisable intervention components.

### Quantitative and computational partners

These collaborators contribute:

* model specification;
* parameter and model recovery;
* longitudinal and hierarchical analysis;
* prospective prediction;
* study optimisation;
* uncertainty quantification;
* reproducibility and progression criteria.

The architecture provides a direct route from computational modelling to prospective human validation rather than leaving modelling as a post-hoc explanatory exercise.

### Psychometric partners

Psychometric collaborators contribute:

* construct definition;
* task and measure design;
* reliability and validity analysis;
* item-response and measurement modelling;
* short-form development;
* measurement invariance and fairness assessment.

The programme integrates psychometric development with intervention development from the outset.

### PPI and implementation partners

These partners ensure:

* acceptable language and burden;
* meaningful outcomes;
* credible patient journeys;
* practical delivery models;
* appropriate governance and support.

### Institutional and commercial partners

These partners support:

* IP and access agreements;
* regulatory development;
* implementation planning;
* commercialisation or licensing;
* later NHS pilots and larger evaluations.

The platform also creates structured, versioned assets that may support future licensing, collaboration and adaptation while maintaining clear evidence and claims boundaries.

---

## 18. Funding and progression strategy

The full MRC Proof of Concept programme is the primary route where the pain-specific prototype, clinical partnership, PPI, computational evidence and preliminary pain-relevant human evidence are sufficiently mature.

If one critical pain-specific uncertainty remains, the primary backup is an MRC Impact Acceleration Award focused on one bounded development step, such as:

* validating one pain-appraisal intervention module;
* calibrating one pain-specific computational model;
* conducting preliminary chronic-pain testing of the adaptive evidence task.

The strategic principle is:

> **Dual preparation, single submission.**

The team will prepare the full programme and primary backup only until the evidence supports a clear route decision.

A later full Proof of Concept submission will be preferred over submitting before the pain-specific readiness threshold has been reached.

---

## Partner-facing summary

The programme is designed to solve a recurring problem in behavioural intervention development: promising ideas are often taken into expensive human studies before the mechanism, measurement model, intervention component and transfer test have been adequately separated.

The proposed solution is a disciplined, mechanism-led development system in which:

* clinical need defines the target;
* evidence sources and assumptions are explicit;
* competing mechanisms are formalised;
* measurements are engineered alongside the intervention;
* synthetic experiments test whether the study can answer its own questions;
* prior sensitivity and transportability are evaluated;
* human studies calibrate and challenge the models;
* candidates are selected prospectively;
* transfer and functional outcomes are protected from simple practice effects;
* predictions are audited against observed data;
* every model, protocol and decision remains reproducible and traceable;
* every component can be advanced, revised or retired.

The immediate output is a clinically credible digital intervention for chronic primary pain.

The longer-term asset is a reusable, domain-adaptive and auditable method for developing future cognitive-affective interventions more efficiently—without assuming that evidence, validity or clinical benefit automatically transfer from one condition to another.
