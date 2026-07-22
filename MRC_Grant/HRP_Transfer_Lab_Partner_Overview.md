# HRP Transfer Lab

## High-level technical and partner overview

### The central proposition

The HRP Transfer Lab is a **computational intervention-development environment** designed to improve how cognitive-affective interventions are conceived, measured, selected and tested.

Its first clinical application is the development of a mechanism-led digital intervention for chronic primary pain. The pain intervention remains the primary clinical product. The Transfer Lab is the enabling technology used to:

* organise and evaluate the relevant evidence;
* formalise competing mechanisms;
* develop mechanism-sensitive measures;
* test whether proposed studies can identify their intended targets;
* optimise early human experiments;
* compare intervention candidates prospectively;
* determine whether a candidate should advance, be revised or be retired.

Its purpose is not to replace human research. It is to reduce avoidable uncertainty before substantial time and resources are committed to clinical studies.

The core principle is:

> **Databases constrain the plausible behavioural system; models formalise competing mechanisms; synthetic experiments optimise and challenge candidate designs; prospective human studies determine what actually works.**

---

## 1. The problem the Transfer Lab addresses

Digital behavioural and psychological interventions are often developed through a relatively linear process:

```text
literature review
→ plausible intervention idea
→ fixed prototype
→ pilot study
→ post-hoc interpretation
```

This creates several risks:

* the proposed mechanism may not be measurable;
* different mechanisms may produce indistinguishable results;
* the task may have floor or ceiling problems;
* the study may use an inefficient balance of participants and trials;
* a candidate may reach human testing before weak assumptions have been identified;
* transfer outcomes may be added only after the intervention has been designed;
* positive task learning may be mistaken for clinically meaningful change.

The HRP Transfer Lab introduces a more disciplined development process:

```text
registered evidence
→ explicit priors
→ competing mechanism models
→ synthetic participants and experiments
→ recovery and power testing
→ pain-specific human calibration
→ prospective candidate selection
→ locked intervention comparison
→ protected and delayed transfer
→ functional outcomes
→ advance, revise or retire
```

The value lies in testing the **development logic itself** before asking whether the intervention works clinically.

---

## 2. One clinical product, supported by two enabling functions

The architecture supports one primary clinical product and two enabling development functions.

| Role                                         | Function                                                                                                   |
| -------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| **Pain intervention prototype**              | Attempts to modify specified cognitive-affective processes and improve functioning                         |
| **Mechanism-sensitive measurement function** | Measures attention, appraisal, uncertainty, decision policy, transfer and functional outcomes              |
| **Pathway-placement function**               | Defines intended users, access points, clinical boundaries, implementation requirements and adoption risks |

These functions are integrated but should not be confused.

The intervention is the product that may ultimately benefit patients.

The measurement system determines whether the relevant processes can be assessed reliably.

The pathway model determines whether the intervention can be placed credibly and safely within chronic-pain care.

---

## 3. A mechanism-led architecture

The Transfer Lab is organised around a connected cognitive-affective chain:

```text
pain-related cue or ambiguity
→ attention and evidence selection
→ threat and safety appraisal
→ uncertainty monitoring
→ activity, avoidance or self-management decision
→ experienced outcome
→ updating of predictions
→ reuse in daily functioning
```

Candidate mechanisms may include:

* threat-sensitive attention;
* pain-threat evidence weighting;
* safety-evidence discounting;
* interpretation priors;
* reliability learning;
* monitoring and commitment thresholds;
* context switching and hysteresis;
* avoidance cost;
* activity-value estimation;
* prediction-error sensitivity;
* wrapper recovery;
* delayed retention.

The project will not assume that all of these mechanisms are present, measurable or clinically important.

Instead, the platform will test a **small prespecified set of competing models** and ask:

* Can these mechanisms be identified using the proposed tasks?
* Can the models be distinguished from one another?
* Which parameters can be estimated with acceptable uncertainty?
* Which mechanism-targeted intervention candidate is sufficiently plausible and measurable to justify human testing?

Mechanism mapping is therefore product-directed. It is used to select and calibrate the intervention, not to create an open-ended theory of chronic pain.

---

## 4. Evidence and dataset architecture

Every external evidence source will be registered rather than imported informally.

The evidence registry records:

* source and ownership;
* licence and permitted use;
* population;
* task and measures;
* preprocessing;
* candidate parameters;
* construct match;
* task match;
* population match;
* delivery match;
* transportability risks;
* review status.

Evidence is weighted according to how closely it matches the target estimate.

```text
directly matched task evidence
→ stronger prior influence

structurally similar task evidence
→ moderate prior influence

construct-matched pain evidence
→ broad mechanism constraint

general behavioural datasets
→ heterogeneity and response-noise information only

local pain-specific calibration
→ primary source for novel parameters
```

This prevents the system from treating all published estimates as equally relevant.

It also creates a traceable answer to the question:

> Where did this parameter assumption come from, and how strongly should it influence the new study?

---

## 5. Transportability-weighted priors

The prior registry will store versioned parameter distributions together with:

* their source datasets;
* uncertainty;
* construct match;
* population match;
* task match;
* delivery match;
* discounting;
* sensitivity regimes;
* human approval.

At least three borrowing regimes will be tested:

```text
weak borrowing
moderate borrowing
stronger borrowing
```

This allows the team to determine whether a development decision depends excessively on assumptions borrowed from another task or population.

If the preferred intervention, predicted sample size or apparent model identifiability changes markedly across reasonable prior assumptions, the output will be labelled **prior-sensitive**.

The response to prior sensitivity is additional calibration—not stronger claims.

This is particularly important because the programme draws on several evidence sources that may be structurally informative without being directly pain-specific.

---

## 6. Synthetic participants and experiments

The Transfer Lab will generate empirically constrained synthetic participant populations.

These populations may represent:

* realistic baseline differences;
* correlated mechanism parameters;
* measurement error;
* lapses;
* missingness;
* practice and fatigue;
* different intervention responses;
* non-response;
* differences in transfer and retention.

Illustrative profiles may include:

* attention-limited performance;
* disproportionate pain-threat weighting;
* excessive evidence monitoring;
* premature avoidance;
* slow context updating;
* surface-specific learning;
* portable learning after an initial transfer dip.

These profiles are modelling hypotheses, not clinical classifications.

Synthetic experiments can then reproduce the planned study structure, including:

* task conditions;
* trial timing;
* evidence quality;
* masking;
* context shifts;
* intervention curricula;
* transfer probes;
* delayed re-checks;
* adherence and dropout;
* invalid or timing-contaminated data.

This allows the team to test a study before recruiting participants.

---

## 7. What synthetic experiments are used for

Synthetic work will be used to answer design questions such as:

* Can the proposed parameter be recovered?
* Can competing models be distinguished?
* Which conditions are most informative?
* How many trials are needed?
* How many participants are needed?
* Does increasing trial density improve precision, or are more independent participants required?
* Which intervention schedule provides the best mechanism discrimination?
* Which task conditions create floor or ceiling effects?
* How robust are results to dropout, lapses or device variability?
* What result should be observed if the model is correct?

Synthetic data will not be combined with human data to:

* inflate sample size;
* manufacture precision;
* imply efficacy;
* validate clinical measures;
* replace prospective participants.

Synthetic work is a design-validation instrument, not clinical evidence.

---

## 8. Parameter recovery and model recovery

Two validation processes are central.

### Parameter recovery

The system generates data from known parameter values and then fits the planned model.

```text
known generating parameters
→ synthetic observations
→ fitted model
→ recovered estimates
```

The team can then examine:

* bias;
* uncertainty;
* interval coverage;
* rank recovery;
* clinically meaningful contrasts;
* sensitivity to missing data and lapses.

If a parameter cannot be recovered reliably, it should not be treated as a strong human-study outcome.

### Model recovery

Data are generated from each serious competing model and then fitted using all candidate models.

This produces:

* model-confusion matrices;
* model-selection accuracy;
* held-out predictive performance;
* identification of indistinguishable explanations;
* information about which conditions improve model discrimination.

Where models remain indistinguishable, the options are to:

* combine them into a broader hypothesis class;
* redesign the experiment;
* stop claiming that the study can identify the mechanism.

This provides an explicit defence against overinterpreting ambiguous behavioural data.

---

## 9. Prospective prediction rather than post-hoc explanation

The Transfer Lab will generate predictions before the human studies are analysed.

Predictions may concern:

* parameter distributions;
* learning trajectories;
* transfer costs;
* first-contact performance dips;
* recovery curves;
* adherence;
* missingness;
* delayed retention;
* functional associations;
* intervention-effect scenarios.

Observed results will then be compared with those predictions.

Failure of prediction is treated as useful evidence:

```text
prediction succeeds
→ model gains support

prediction fails
→ model or transportability assumption must be revised
```

The system is therefore designed not only to fit data, but to be proven wrong in informative ways.

---

## 10. Intervention selection

The platform will separate two questions.

### Is the study design good?

This concerns:

* identifiability;
* model recovery;
* precision;
* task reliability;
* participant burden;
* timing quality;
* expected information;
* technical readiness.

### Which intervention candidate is most promising?

This depends on explicit assumptions about:

* mechanism change;
* transfer probability;
* durability;
* adherence;
* functional relevance.

Candidates will not be hidden inside a single opaque utility score.

They will be compared on separate dimensions, including:

* mechanistic plausibility;
* identifiability;
* transfer plausibility;
* information value;
* burden;
* safety;
* technical readiness;
* cost.

The output may classify candidates as:

```text
primary candidate
mechanistic comparator
active control
conditional candidate
defer
retire
```

A candidate advances only where its supporting assumptions and trade-offs are explicit.

---

## 11. Protected and delayed transfer

The Transfer Lab distinguishes several levels of evidence.

| Level                          | Meaning                                                               |
| ------------------------------ | --------------------------------------------------------------------- |
| **Trained-task learning**      | Improvement on the practised task                                     |
| **Near transfer**              | Improvement on new items or parameters within the same task grammar   |
| **Wrapper transfer**           | The same operation survives a changed format or carrier               |
| **Compositional transfer**     | Learned transformations are combined in a protected condition         |
| **Cross-task policy transfer** | The same adaptive operation appears in an independently designed task |
| **Delayed transfer**           | The transferred operation survives spacing                            |
| **Functional transfer**        | Change relates to activity, self-management or pain interference      |

The system will not infer a higher level of transfer automatically from a lower one.

For example:

```text
better performance on trained attention task
≠
improved pain-related functioning
```

This transfer hierarchy is one of the main scientific safeguards of the programme.

---

## 12. Psychometric development as part of intervention development

The Transfer Lab will develop measurements alongside the intervention rather than treating assessment as an afterthought.

Potential products include:

* mechanism-sensitive behavioural tasks;
* pain-appraisal measures;
* activity-prediction measures;
* short questionnaires;
* patient-reported outcome modules;
* protected transfer measures;
* fidelity indices;
* practitioner-facing summaries.

The psychometric workflow includes:

```text
construct definition
→ content blueprint
→ AI-assisted candidate generation
→ expert and lived-experience review
→ synthetic psychometric testing
→ optimised human calibration
→ cognitive interviewing
→ reliability and validity assessment
→ independent validation
→ short-form or adaptive version
```

AI may support candidate item and task generation, but generated content must undergo human review for:

* construct relevance;
* ambiguity;
* reading burden;
* cultural assumptions;
* redundancy;
* harmful or blaming language;
* unintended shortcut solutions.

Synthetic psychometric success does not establish real validity, fairness or meaningful change. Those require human data.

---

## 13. Pathway and implementation intelligence

The Transfer Lab includes a focused implementation strand because a technically effective intervention may still fail if it has no credible pathway position.

The pathway model will consider:

```text
patient need or referral cue
→ eligibility and clinical boundaries
→ access and onboarding
→ practitioner oversight
→ intervention use
→ monitoring and escalation
→ completion or non-response
→ onward care
→ patient and service outcomes
```

Outputs may include:

* intended-use statement;
* inclusion and exclusion criteria;
* escalation and safeguarding rules;
* practitioner roles;
* patient journey;
* data-flow requirements;
* implementation burden;
* adoption risks;
* future health-economic requirements.

AI may support structured synthesis of pathway documents, but it will not:

* allocate treatment;
* determine eligibility;
* make referral decisions;
* infer causal service bottlenecks from document frequency.

All pathway conclusions remain subject to clinical, service, PPI and implementation review.

---

## 14. Constrained AI roles

The AI layer is deliberately narrow and auditable.

Potential AI agents include:

| Agent                         | Role                                                       |
| ----------------------------- | ---------------------------------------------------------- |
| **Evidence extraction agent** | Converts studies into structured evidence records          |
| **Dataset and prior agent**   | Proposes parameter sources and transportability ratings    |
| **Protocol design agent**     | Generates variants under fixed scientific constraints      |
| **Model critic**              | Suggests rival explanations and identifies model confusion |
| **Psychometric critic**       | Flags ambiguity, redundancy and fairness risks             |
| **Pathway synthesis agent**   | Extracts pathway stages and implementation constraints     |
| **Claims critic**             | Identifies unsupported inferences and overclaiming         |
| **Reproducibility agent**     | Checks versions, seeds, manifests and missing artefacts    |

Safeguards include:

* source-grounded outputs;
* confidence and uncertainty fields;
* immutable audit logs;
* human approval;
* no silent changes to canonical registries;
* no autonomous clinical outputs;
* no unapproved access to identifiable data;
* versioned prompts and models where outputs affect decisions.

The system uses AI to increase scrutiny, not to bypass scientific responsibility.

---

## 15. Reproducibility and source traceability

Every computational output will record:

* Git commit;
* configuration hash;
* random seed;
* software environment;
* dataset versions;
* prior-registry version;
* model version;
* protocol version;
* analysis specification;
* output checksums;
* review status.

Raw evidence, assumptions, model versions and decisions will remain linked.

This supports questions such as:

```text
Which model produced this prediction?
Which prior version was used?
Which dataset informed the parameter?
Which assumptions changed?
Who approved the result?
Can the analysis be reproduced?
```

The infrastructure is therefore designed to produce **evidence packets**, not just charts or scores.

---

## 16. Evaluation of development efficiency

The Transfer Lab will not assume that its computational approach is more efficient.

It will be compared with a prospectively specified conventional workflow:

```text
manual evidence review
→ narrative candidate selection
→ fixed protocol design
→ conventional pilot
→ post-hoc mechanism and transfer assessment
```

The computational workflow is:

```text
structured evidence registry
→ weighted priors
→ competing mechanism models
→ synthetic recovery and power testing
→ informative human calibration
→ prospective candidate lock
→ protected transfer
```

Comparison metrics may include:

* time to a locked protocol;
* candidates retired before human testing;
* participants and participant-minutes per retained candidate;
* information gained per participant-minute;
* design failures detected early;
* prediction accuracy;
* number of revisions required;
* cost and time to an advance, revise or retire decision;
* reproducibility and traceability.

The comparison may use:

* parallel development exercises;
* prospectively documented benchmark processes;
* structured expert review;
* appropriately matched historical development cases.

The intended claim is modest but meaningful:

> The project will test whether computational screening and synthetic experimental design make early intervention and measurement development more informative, reproducible and resource-efficient.

---

## 17. Development phases

The technical programme is organised into four phases.

### Phase A — Foundation and identifiability

Build the registries, priors, models, simulation tools and recovery evidence required to justify the first human study.

### Phase B — Pain-specific mechanism mapping and product calibration

Calibrate mechanism-sensitive measures, update the models, assess acceptability and prospectively select the intervention, comparator and control.

### Phase C — Prospective proof of concept

Test mechanism change, protected transfer, delayed retention, functional outcomes and correspondence between predicted and observed results.

### Phase D — Consolidation and onward development

Harden the technical platform, prepare intervention and fidelity specifications, refine implementation requirements and support the next funding or clinical-evaluation stage.

Each phase has explicit deliverables and feeds a progression decision.

---

## 18. Minimum viable grant scope

The minimum viable technical programme is intentionally bounded.

It contains:

* one primary clinical product;
* one chronic-primary-pain pathway position;
* one primary cognitive-affective mechanism chain;
* a small set of rival models;
* one compact measurement battery;
* recovery and power testing;
* one pain-specific calibration study;
* one selected intervention configuration;
* one mechanistic comparator;
* one active control;
* protected and delayed outcomes;
* one advance, revise or retire decision.

It does not require the full future platform to be built in the first award.

Possible later extensions include:

* physiological measures;
* adaptive psychometrics;
* additional clinical indications;
* more extensive service-pathway analysis;
* richer affective-learning modules.

---

## 19. Generalisability without overclaiming

The architecture is designed to be reusable, but it is **domain-adaptive rather than domain-agnostic**.

What may be reusable:

* registry structures;
* prior and evidence workflows;
* model-recovery tools;
* simulation engines;
* psychometric-development methods;
* transfer-testing frameworks;
* reproducibility and governance systems.

What cannot be assumed to transfer:

* pain-specific mechanisms;
* parameter distributions;
* task validity;
* intervention effects;
* clinical conclusions;
* pathway position;
* safety and acceptability.

Every new indication would require its own:

* clinical problem definition;
* mechanism mapping;
* task and measurement adaptation;
* evidence and priors;
* recovery testing;
* intervention specification;
* pathway model;
* prospective human validation.

The chronic-primary-pain programme is therefore the first full demonstration of the architecture—not proof that one intervention applies across conditions.

---

## 20. Value to potential partners

### Clinical partners

The Transfer Lab gives clinical partners a structured method for:

* translating clinical hypotheses into measurable models;
* defining intended users and pathway position;
* testing safety and burden;
* selecting meaningful outcomes;
* avoiding overinterpretation of task effects;
* making explicit progression decisions.

### Statistical and computational partners

It provides a framework for:

* parameter and model recovery;
* hierarchical and longitudinal modelling;
* prospective prediction;
* power and information analysis;
* uncertainty quantification;
* reproducible decision support.

### Psychometric partners

It integrates:

* construct specification;
* task and item development;
* IRT and measurement modelling;
* short-form development;
* fairness and invariance assessment;
* human validation.

### NHS and implementation partners

It supports:

* pathway placement;
* practitioner-role definition;
* escalation and safeguarding;
* data-flow planning;
* implementation-risk assessment;
* preparation for health-economic and service evaluation.

### Technology and commercial partners

It creates:

* versioned protocol assets;
* auditable computational infrastructure;
* reusable registry and model schemas;
* structured IP;
* clear evidence and claims boundaries;
* a route from prototype to validated product.

---

## Why the architecture is coherent

Every part of the Transfer Lab serves the same translational decision.

```text
evidence
→ mechanism model
→ measurable parameter
→ validated study design
→ calibrated human task
→ selected intervention
→ transfer and functional test
→ pathway fit
→ advance, revise or retire
```

The components are therefore not separate technical projects.

* The evidence registry constrains the models.
* The models define what must be measured.
* The synthetic experiments test whether it can be measured.
* The psychometric engine builds the measures.
* The human study calibrates and challenges the models.
* The intervention comparison tests the selected candidate.
* The transfer framework prevents task learning from being mistaken for benefit.
* The pathway strand determines whether the product can be used.
* The governance layer controls what may legitimately be claimed.

---

## Partner-facing summary

The HRP Transfer Lab is designed to make behavioural and digital intervention development more rigorous before large human studies are launched.

Its distinctive contribution is the integration of:

```text
traceable evidence
+ explicit priors
+ competing mechanism models
+ synthetic design validation
+ mechanism-sensitive measurement
+ prospective prediction
+ protected transfer testing
+ human clinical calibration
+ pathway placement
+ advance / revise / retire governance
```

It does not assume that AI, modelling or synthetic data can establish clinical benefit.

Instead, it uses these tools to improve the questions, measurements and study designs that are taken into human research.

The immediate value is a better-developed digital intervention for chronic primary pain.

The longer-term value is a reusable, auditable and claims-controlled method for developing future cognitive-affective interventions more efficiently and transparently.
