# HRP Transfer Lab
## Computational and AI Technical Appendix for Intervention, Psychometric and Pathway Development

**Grant-facing high-level specification — Version 1.0**  
**Primary demonstrator:** Chronic primary pain  
**Companion document:** *MRC Proof of Concept Stage One: General Application Plan*

---

## 1. Purpose

This appendix specifies the computational and AI-assisted methodology supporting the proposed development of a mechanism-led digital cognitive-affective intervention for chronic primary pain.

The HRP Transfer Lab is conceived as a **computational screening, design-validation and prospective-study optimisation environment**. It will combine external evidence, existing behavioural datasets, auditable parameter priors, generative cognitive models, empirically constrained synthetic populations, synthetic experiments, psychometric simulations and targeted AI agents.

Its purpose is to:

1. reduce uncertainty before expensive human experimentation;
2. identify intervention components and study designs that are informative enough to justify prospective testing;
3. retire poorly identifiable, low-information or implausible candidates early;
4. improve measurement quality and trial efficiency;
5. preserve explicit boundaries between computational plausibility, human mechanism evidence, transfer evidence and clinical benefit;
6. support a focused service-pathway and implementation-intelligence strand that places the intervention within a credible pain-care pathway.

The governing principle is:

> **Databases constrain the plausible behavioural system; models formalise competing mechanisms; synthetic experiments optimise and challenge candidate designs; prospective human studies determine what actually works.**

Synthetic data will not be added to human observations to inflate sample size, reduce uncertainty artificially or support efficacy claims. Synthetic experiments are instruments for design, model testing, power estimation, code validation and prospective prediction.

---

## 2. Relationship to the clinical programme

The computational system supports one primary clinical product and two enabling development functions.

| Role                                                      | Function                                                                                                       | Validation source                                            |
| --------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| **Primary clinical product: pain intervention prototype** | Modifies specified cognitive-affective processes and tests whether change transfers to independent functioning | Prospective human studies                                    |
| **Enabling measurement function**                         | Measures attention, appraisal, uncertainty, decision policy, transfer and functional outcomes                  | Human psychometric and experimental validation               |
| **Supporting pathway-placement function**                 | Defines intended users, entry points, clinical boundaries, implementation requirements and adoption risks      | Clinical, service, stakeholder and lived-experience evidence |


The computational platform is therefore an enabling technology, not the clinical product by itself.

The initial clinical development chain is:

```text
pain-related cue or ambiguity
→ attention and evidence selection
→ interpretation and threat/safety prediction
→ uncertainty monitoring
→ activity, avoidance or self-management decision
→ environmental feedback
→ model updating
→ reuse in a changed context and after delay
```

Candidate components will be considered only insofar as they contribute to this clinical chain.

---

## 3. Scope

### 3.1 In scope

The technical work will support:

- evidence and dataset registration;
- construction of transportability-weighted priors;
- modular computational cognitive modelling;
- simulation of heterogeneous participant populations;
- synthetic intervention and transfer experiments;
- model and parameter recovery;
- simulation-based power and precision analysis;
- prospective study-design optimisation;
- scenario-based intervention prioritisation;
- psychometric task and questionnaire development;
- planned-missing and adaptive-test design;
- AI-assisted evidence extraction and protocol criticism;
- focused pathway-document synthesis and implementation mapping;
- reproducible evidence packets and go/revise/retire decisions.

### 3.2 Out of scope for the initial project

The project will not attempt to provide:

- autonomous clinical decisions;
- automated eligibility, referral or treatment allocation;
- replacement of clinicians, statisticians, psychometricians or lived-experience contributors;
- clinical diagnosis;
- comprehensive NHS pain-system optimisation;
- ICB-wide resource allocation;
- unvalidated personalised treatment assignment;
- synthetic substitution for empirical participants;
- large-scale foundation-model training;
- definitive proof of far transfer from task improvement alone;
- strong physiological adaptation claims before separate biosignal feasibility work.

### 3.3 Generalisable architecture and domain-adaptation boundary

Although the initial product and validation programme focus exclusively on chronic primary pain, the HRP Transfer Lab is designed as a **generalisable intervention-development architecture**, rather than as a single-condition software tool.

The reusable value lies in the computational and translational infrastructure used to develop, calibrate and evaluate mechanism-led interventions. Reusable components include:

* evidence and dataset registries;
* source-traceability and transportability-weighted prior systems;
* modular cognitive, computational and psychometric models;
* synthetic-participant and synthetic-experiment engines;
* parameter-recovery and model-recovery tools;
* simulation-based power and study-design optimisation;
* psychometric task and measure-development workflows;
* protected and delayed transfer-testing methods;
* pathway-placement and implementation-intelligence methods;
* reproducibility, governance and claims-control systems.

The chronic-primary-pain programme will provide the **first full clinical instantiation and validation case** for this broader development architecture.

The generalisable element is not a fixed set of pain tasks, intervention components, measures or parameters. It is the underlying translational workflow:

```text
define the functional health problem
→ specify the intended clinical product and use case
→ identify the candidate cognitive-affective mechanism chain
→ formalise prespecified competing mechanisms
→ develop mechanism-sensitive tasks and measures
→ constrain models using relevant evidence and priors
→ simulate heterogeneous populations and intervention scenarios
→ test identifiability, recovery, power and transfer designs
→ conduct pain-specific mechanism mapping and product calibration
→ select intervention candidates prospectively
→ evaluate mechanism change, transfer, functioning and pathway fit
→ advance, revise or retire
```

This workflow is intended to remain structurally stable across applications. The clinical content, mechanism models, measures, parameters, intervention components and pathway specifications must nevertheless be adapted and validated separately for each target domain.

A general cognitive-affective mechanism scaffold is:

```text
domain-relevant cue, demand or ambiguity
→ attention and evidence selection
→ interpretation, valuation or prediction
→ uncertainty monitoring and confidence regulation
→ action selection, persistence or avoidance
→ environmental feedback and model updating
→ reconstruction in a changed context and after delay
→ functional outcome
```

For chronic primary pain, this scaffold is instantiated as:

```text
pain-related sensation or situational ambiguity
→ threat-sensitive attention and evidence selection
→ threat and safety appraisal
→ uncertainty about activity and consequences
→ activity, avoidance or self-management decision
→ experienced outcome
→ updating of pain and activity predictions
→ reuse in daily functioning
```

The platform is therefore **domain-adaptive rather than domain-agnostic**. Generalisability applies to the development architecture, not automatically to the clinical evidence.

A task, parameter, prior distribution, psychometric measure, intervention component or pathway model validated in chronic primary pain cannot be transferred directly to another indication without a separately justified adaptation and validation process. No pain-specific parameter or clinical conclusion will be reused silently in another domain.

Each new domain instantiation would require:

1. **Clinical and functional problem definition**
   Independent specification of the target population, health need, intended use, pathway position and meaningful functional outcomes.

2. **Prespecified mechanism mapping**
   A theoretically and empirically justified account of the candidate cognitive-affective processes linking the target problem to behaviour, functioning or treatment engagement.

3. **Task and measurement adaptation**
   Selection or development of mechanism-sensitive tasks and measures, followed by content-validity review, cognitive interviewing, calibration, reliability assessment, fairness testing and independent validation where appropriate.

4. **Domain-specific evidence and priors**
   Registration and assessment of relevant datasets for construct, task, population and delivery match. Cross-domain borrowing would require an explicit bridging model, uncertainty discounting and sensitivity analysis.

5. **Computational design validation**
   Fresh parameter recovery, model recovery, simulation-based calibration, power analysis and synthetic stress-testing of the adapted models and study designs.

6. **Intervention re-specification**
   Selection of intervention components linked to the newly defined mechanism chain rather than inherited automatically from the pain demonstrator.

7. **Transfer-framework adaptation**
   Independent definition of the relevant near, horizontal, compositional, cross-task, delayed and functional transfer outcomes.

8. **Pathway re-instantiation**
   Mapping of intended users, access routes, clinical boundaries, practitioner roles, safeguarding, escalation and implementation requirements within the relevant healthcare or service context.

9. **Prospective human calibration and validation**
   Human evidence to calibrate the models, validate the measures, test intervention effects, assess safety and determine whether change transfers to meaningful functioning.

This architecture creates two distinct forms of value.

#### Immediate translational value

The project will produce:

* a mechanism-led digital intervention for chronic primary pain;
* a pain-specific measurement system;
* a prospectively selected intervention configuration and comparator set;
* a focused pathway-placement and implementation model;
* an evidence-based advance, revise or retire decision.

#### Platform value

The project will also establish:

* a documented domain-adaptation framework;
* modular computational and technical infrastructure;
* reusable evidence, prior and model-registry schemas;
* general simulation and recovery components;
* a versioned intervention-development workflow;
* reusable psychometric-development methods;
* explicit rules governing cross-domain evidence borrowing, adaptation and claims.

The initial MRC project will not test multiple clinical indications. Any future application would constitute a separate mechanism-mapping, product-development and validation programme.

The domain-adaptation framework therefore strengthens the scientific, translational and commercial value of the computational investment while preserving the integrity of the single-indication application. It demonstrates that the development architecture may be reusable without implying that clinical efficacy, psychometric validity, parameter estimates or pathway fit can be transferred between populations without new evidence.

---

## 4. System architecture

```text
EVIDENCE AND DATA SOURCES
scientific literature
+ matched task datasets
+ pain and affective-learning datasets
+ clinical and service documents
+ local pilot telemetry
+ lived-experience and stakeholder evidence
        ↓
DATASET AND EVIDENCE REGISTRY
licence, source traceability, population, task, measures,
preprocessing, permitted use and transportability
        ↓
PRIOR REGISTRY
versioned parameter distributions
+ uncertainty
+ task, population and delivery match
+ discounting
+ sensitivity regimes
        ↓
MODULAR MECHANISM-MODEL LAYERS
observation and attention
+ content and affective modulation
+ frame and context
+ decision and evidence accumulation
+ learning and transfer
+ prespecified population variation
+ intervention-response scenarios
        ↓
SYNTHETIC EXPERIMENT ENGINE
synthetic participants
+ task generators
+ mechanism-targeted intervention curricula
+ protected transfer tests
+ delayed outcomes
+ missingness and data-quality models
        ↓
DESIGN AND MECHANISM VALIDATION
parameter recovery
+ model recovery
+ simulation-based calibration
+ predictive checks
+ model discrimination
+ power and precision
+ expected information value
        ↓
PAIN-SPECIFIC MECHANISM MAPPING
AND PRODUCT CALIBRATION
calibration of prespecified mechanism parameters
+ task and measure reliability
+ relationships with pain-related functioning
+ acceptability and burden
+ out-of-sample predictive validity
+ suitability of mechanism-targeted candidates
        ↓
PROSPECTIVE CANDIDATE SELECTION
AND LOCKED COMPARISON
selected intervention configuration
+ mechanistic comparator
+ active control
+ protected transfer
+ delayed assessment
+ patient-relevant functional outcomes
        ↓
EVIDENCE AND DECISION GATE
advance / revise / retire
```

Three supporting engines operate across this architecture:

1. **Intervention-development engine** — designs, simulates and compares prespecified mechanism-targeted protocols, and supports prospective selection of the intervention configuration, mechanistic comparator and active control.
2. **Psychometric-development engine** — develops reliable, efficient and interpretable mechanism-sensitive measures, protected-transfer outcomes and functional assessment tools.
3. **Pathway and implementation-intelligence engine** — places the intervention within a defined clinical pathway and identifies intended users, clinical boundaries, delivery requirements and practical adoption constraints.

The architecture is explicitly product-directed. Mechanism mapping is used to calibrate the measurement system, distinguish prespecified competing explanations and select the intervention configuration. It is not intended as an open-ended investigation of the mechanisms of chronic primary pain.

---

## 5. Evidence and dataset layer

### 5.1 Source hierarchy

External evidence will be weighted according to its match to the parameter being estimated.

| Evidence tier | Example | Intended use |
|---|---|---|
| **Directly matched** | Existing MFT-M, pain-appraisal or prototype task data using similar stimuli and delivery | Stronger priors for baseline performance and measurement noise |
| **Structurally matched** | Attention, evidence-accumulation, interpretation-bias or reversal tasks with comparable response structures | Moderate priors for process parameters |
| **Construct matched** | Chronic-pain, threat/safety, avoidance or activity-decision datasets using different tasks | Broad priors and mechanism constraints |
| **Broad behavioural** | Cross-experiment behavioural databases such as Psych-101 | Heterogeneity, sequential dependence and generic response stochasticity only |
| **Local calibration** | New mechanism-mapping and usability study | Primary source for novel task and transfer parameters |

### 5.2 Appropriate use of candidate sources

#### Local and published MFT-M data

These are expected to provide the strongest starting information for:

- majority-ratio effects;
- exposure-duration effects;
- masked perceptual performance;
- lapse and error rates;
- reaction-time distributions;
- practice and session effects;
- baseline individual heterogeneity;
- informativeness of candidate task conditions.

They will not determine novel pain, emotional-content or cross-task transfer parameters.

#### Psych-101

Psych-101 may support:

- broad behavioural heterogeneity;
- sequential dependence;
- generic learning-pattern classes;
- response stochasticity;
- benchmarking general behavioural models.

It will not be treated as a strong prior source for masked perceptual capacity, optic-flow cost, relative-frame cost, emotional-ensemble perception or chronic-pain intervention effects.

#### OpenCogData and related repositories

These will be treated as catalogues of specific datasets rather than homogeneous data sources. Every estimate must identify:

```text
specific dataset
specific task
specific population
specific preprocessing
specific fitted model
specific parameter estimate
```

#### Fearbase and related fear-conditioning resources

Where approved participant-level data are available, these may inform broad distributions for:

- threat acquisition;
- safety learning;
- extinction;
- reversal;
- return of fear;
- physiological measurement variability.

They will not be used as direct priors for happy/angry ensemble perception, pain interpretation or emotional MFT-M decision thresholds without a justified bridging model.

#### Pain and health-psychology data

Relevant datasets and publications may inform:

- interpretation-bias distributions;
- pain interference and functioning;
- activity avoidance;
- uncertainty and intolerance-of-uncertainty measures;
- treatment engagement;
- relationships between cognitive-affective mechanisms and functional outcomes.

Novel relationships between the new intervention tasks and pain outcomes will remain weakly informed until calibrated prospectively.

---

## 6. Dataset and evidence registry

Every source will be represented by a structured manifest.

```yaml
dataset_id: pain_attention_dataset_v1
title: Example task dataset
version: 1.0
source_owner: named organisation
access_type: public | governed | internal
licence_or_agreement: recorded
population: chronic primary pain
sample_size: 000
tasks:
  - task_name
measures:
  - measure_name
candidate_parameters:
  - parameter_name
construct_match: high | moderate | low
task_match: high | moderate | low
population_match: high | moderate | low
delivery_match: high | moderate | low
permitted_uses:
  - prior estimation
  - model validation
prohibited_uses:
  - public redistribution
checksum: recorded
review_status: proposed | approved | retired
```

The registry will store:

- data lineage;
- licensing and permitted uses;
- preprocessing decisions;
- missing-data handling;
- version history;
- inclusion and exclusion decisions;
- source citations;
- task and population similarity;
- risks of transportability failure.

No AI agent may silently convert an extracted estimate into an approved prior.

---

## 7. Prior registry and transportability

### 7.1 Prior record

Every model parameter will have an auditable prior record.

```yaml
prior_id: attention_lapse_rate_v1
parameter: lapse_rate
distribution: beta
hyperparameters:
  alpha: value
  beta: value
source_datasets:
  - dataset_id
source_analysis: analysis_manifest_id
construct_match: high
task_match: moderate
population_match: moderate
delivery_match: low
discount_factor: 0.50
status: proposed
human_reviewer: named role
sensitivity_regimes:
  - weak
  - moderate
  - stronger
```

### 7.2 Borrowing regimes

At least three regimes will be evaluated:

| Regime | Purpose |
|---|---|
| **Weak borrowing** | Tests whether conclusions survive broad priors and limited transportability |
| **Moderate borrowing** | Default analysis using discounted matched evidence |
| **Stronger borrowing** | Best-case analysis restricted to directly comparable sources |

A fourth **robust mixture prior** may be used where there is substantial risk that the new study differs from external sources.

### 7.3 Stability rule

If model identification, power estimates or candidate prioritisation change materially across plausible prior regimes, the output will be labelled **prior-sensitive**. The recommended response will be additional calibration, not a stronger synthetic claim.

---

## 8. Intervention-development engine

### 8.1 Candidate pain-intervention components

The initial candidate space may include:

| Component | Intended process |
|---|---|
| **Neutral attention control** | Extract relevant information under noise while resisting lapses and distractors |
| **Affective perturbation** | Preserve the control policy when information carries emotional salience |
| **Adaptive evidence accumulation** | Adjust evidence gathering and commitment to reliability and uncertainty |
| **Interpretation/appraisal updating** | Separate sensation, prediction, meaning and alternative explanations |
| **Activity prediction and action selection** | Test expectations about activity, symptoms and future functioning |
| **Wrapper/context variation** | Determine whether a policy survives new surfaces and contexts |
| **Implementation intentions and missions** | Bind the policy to real-world cues and obtain feedback |
| **Delayed re-checks** | Test retention and recovery after spacing |

The hard-deadline MFT-M variant will be retained as a candidate extension. It should enter the core pain intervention only if the mechanism-mapping evidence identifies late commitment, omission or deadline-sensitive switching as a clinically relevant bottleneck.

### 8.2 Modular model architecture

The system will not rely on a flat list of unrelated models. Candidate explanations will be assembled from layers.

| Layer | Candidate mechanisms |
|---|---|
| **Observation layer** | Sensory sensitivity, exposure effect, majority-ratio effect, perceptual noise, lapses |
| **Content layer** | Neutral cost, affective salience, pain-related threat weighting, positive/safety evidence discounting |
| **Frame/context layer** | Absolute versus relative representation, context inference, context switching, hysteresis |
| **Decision layer** | Fixed threshold, reliability-sensitive stopping, evidence cost, history dependence |
| **Deadline layer** | Urgency, switch initiation, action-completion latency, omission risk |
| **Learning layer** | Surface learning, additive factor learning, compositional learning, invariant-policy learning |
| **Population layer** | Continuous heterogeneity, correlated traits, optional mixture/profile structure |
| **Intervention layer** | Hypothesised changes to one or more parameters following a protocol |

### 8.3 Pain-specific latent parameters

Candidate parameters may include:

```text
attention sensitivity
lapse probability
pain-threat evidence weighting
safety-evidence weighting
interpretation prior
reliability-learning rate
context-switch hazard
context hysteresis
monitoring/commitment threshold
avoidance cost
activity-value estimate
prediction-error sensitivity
wrapper-recovery rate
prompt dependence
delayed retention
```

Parameters will be included only when the proposed task can plausibly identify them.

### 8.4 Synthetic participant populations

Synthetic participants will be sampled from correlated population distributions. The simulator will represent:

- realistic baseline heterogeneity;
- measurement error;
- missingness and lapses;
- practice and fatigue;
- different mechanism profiles;
- different intervention responses;
- plausible non-response;
- differing transfer and retention probabilities.

Illustrative profiles may include:

| Profile | Example signature |
|---|---|
| **Attention limited** | Low signal extraction and high lapse rate across content |
| **Threat weighted** | Disproportionate weighting of pain or negative evidence |
| **Excessive monitor** | High evidence threshold and delayed commitment |
| **Premature avoider** | Low evidence at commitment and rapid avoidance choice |
| **Context rigid** | Slow updating after reliability or contextual change |
| **Surface learner** | Strong trained-task gain but weak wrapper recovery |
| **Portable learner** | Initial transfer dip followed by rapid recovery and delayed retention |

These profiles are hypotheses used to stress-test the experiment. They are not clinical labels.

### 8.5 Intervention-response scenarios

Intervention effects will be specified separately from empirical priors.

```yaml
intervention_id: adaptive_pain_evidence_v1
target_parameters:
  reliability_sensitivity:
    change_distribution: specified
    evidence_level: hypothesis
  monitoring_threshold:
    change_distribution: specified
    evidence_level: hypothesis
transfer_scenarios:
  protected_task:
    conservative: value
    moderate: value
    optimistic: value
  pain_function:
    conservative: value
    moderate: value
    optimistic: value
```

The system will answer:

> Under which assumptions would candidate A be more informative or promising than candidate B?

It will not present assumed intervention effects as observed efficacy.

---

## 9. Synthetic experiments and curriculum simulation

### 9.1 Synthetic trial generation

The simulator will reproduce the planned task structure, including:

- stimulus class;
- reference frame;
- majority ratio or evidence quality;
- exposure duration;
- masking;
- context reliability;
- sample cost;
- deadline where applicable;
- response accuracy;
- response time;
- confidence;
- lapse and invalid-trial processes;
- learning across trials and sessions;
- wrapper probes, return-to-base tests and delayed re-checks.

### 9.2 Curriculum comparison

The system may compare:

| Curriculum | Structure |
|---|---|
| **Repeated surface practice** | One trained task and wrapper |
| **Equal-block variation** | Predetermined equal exposure to wrappers |
| **Fixed phase progression** | Advance after a fixed criterion |
| **Breakpoint-driven horizontal protocol** | Stabilise, probe, measure dip, recover, return, mix and delay |
| **Adaptive evidence protocol** | Reliability-sensitive sampling across wrappers |
| **Affective or pain-specific augmentation** | Neutral stabilisation followed by salient or domain-specific transfer |

Candidate learning models will predict different outcomes on protected conditions. This allows the planned study to test whether observed performance is consistent with surface learning, additive learning, compositional generalisation or a more portable control policy.

### 9.3 Protected transfer design

Where the neutral MFT-M family is used, a factorial structure may include:

```text
stimulus carrier: arrows versus optic flow
reference frame: absolute versus relative
```

A composition such as `flow_relative` may be protected from training to test recombination of previously experienced transformations.

This is classified as **horizontal/compositional transfer**, not as proof of real-world far transfer.

---

## 10. Transfer evidence classification

Every outcome will be assigned an evidence level.

| Level | Description | Example |
|---|---|---|
| **L0 — Trained-task learning** | Improvement on the trained format | Better trained MFT-M performance |
| **L1 — Near transfer** | New items or parameter values within the same grammar | New majority ratio or exposure duration |
| **L2 — Horizontal wrapper transfer** | Same operation under a changed carrier or frame | Arrows to optic flow |
| **L3 — Compositional/context transfer** | Previously learned transformations combined or context changed | Protected flow-relative condition |
| **L4 — Policy/cross-task transfer** | Same adaptive policy reconstructed in an independently designed task | Reliability-sensitive decision task |
| **L5 — Delayed transfer** | L1–L4 effect survives spacing | Follow-up after days or weeks |
| **L6 — Functional/niche transfer** | Policy activates under real cues and relates to meaningful functioning | Activity engagement or pain interference |

No higher-level claim will be inferred automatically from a lower-level result.

---

## 11. Design validation and model criticism

### 11.1 Parameter recovery

For each estimand, the system will:

```text
select known parameter values
→ generate complete synthetic datasets
→ fit the planned model
→ compare recovered and generating values
```

Evaluation will include:

- bias;
- root mean squared error;
- interval coverage;
- rank recovery;
- posterior uncertainty;
- recovery of clinically meaningful contrasts;
- robustness to missing data and lapses.

Criteria will be parameter-specific rather than based on one universal numerical threshold.

### 11.2 Model recovery

Data will be generated from each candidate model or model combination and fitted using all serious alternatives.

Outputs will include:

- confusion matrices;
- model-selection accuracy;
- predictive accuracy on held-out trials;
- identification of empirically indistinguishable explanations;
- conditions that maximise model discrimination.

Models that remain indistinguishable will be collapsed into a broader hypothesis class or targeted by a redesigned experiment.

### 11.3 Simulation-based calibration

Where Bayesian models are used, simulation-based calibration will assess whether posterior inference is calibrated under the assumed generative process.

### 11.4 Posterior predictive and out-of-sample checks

Models will be evaluated against:

- complete accuracy distributions;
- response-time quantiles;
- conditional accuracy;
- trial-history effects;
- context shifts;
- first-contact transfer dips;
- recovery curves;
- return-to-base effects;
- delayed observations.

Predictive success on held-out human participants, conditions or sessions will be prioritised over in-sample fit.

### 11.5 Adversarial model criticism

An independent analysis or AI-supported critic will attempt to reproduce the same signature using simpler explanations such as:

- practice;
- fatigue;
- stimulus difficulty;
- response-key learning;
- regression to the mean;
- recent-trial history;
- generic engagement;
- differential attrition.

---

## 12. Statistical design and power

### 12.1 Simulation-based power

Power will be estimated by generating complete studies containing the proposed:

- participant number;
- trials per condition;
- trial sequence;
- random effects;
- learning trajectories;
- missing and invalid trials;
- intervention adherence;
- analysis model.

The design grid will vary participants and trials per participant. This will reveal when additional trials improve precision and when additional independent participants are required.

### 12.2 Primary estimands

Every human study will specify:

```text
population
intervention
comparator
outcome
time point
causal estimand
```

For example:

> The mean difference between the selected adaptive pain protocol and active control in change in an untrained pain-appraisal decision measure at post-intervention, with pain interference at delayed follow-up as a secondary functional outcome.

### 12.3 Beyond nominal power

The design report will also assess:

- type I error;
- sign error;
- magnitude inflation;
- interval coverage;
- convergence failure;
- sensitivity to random-slope variance;
- sensitivity to dropout;
- expected information per participant-minute.

---

## 13. Intervention prioritisation

### 13.1 Separate design quality from treatment assumptions

The platform will generate two distinct outputs.

#### Output A — Model-independent design quality

This evaluates:

- identifiability;
- model recovery;
- statistical precision;
- expected information gain;
- measurement reliability;
- participant burden;
- technical readiness;
- data-quality robustness.

#### Output B — Scenario-based intervention prioritisation

This evaluates which candidate is preferred under conservative, moderate and optimistic assumptions about:

- mechanism change;
- transfer probability;
- durability;
- adherence;
- functional relevance.

### 13.2 Pareto shortlist

Rather than hiding assumptions inside one utility score, candidates will be compared on separate dimensions.

| Dimension | Question |
|---|---|
| Mechanistic plausibility | Does the component target the proposed bottleneck? |
| Identifiability | Can the target change be measured? |
| Transfer plausibility | Is there a credible bridge to the protected outcome? |
| Information value | Will the human study discriminate meaningful theories? |
| Burden | Are trials, sessions and cognitive demands acceptable? |
| Safety and acceptability | Could the task aggravate distress or avoidance? |
| Technical readiness | Can the protocol be implemented and monitored reliably? |
| Cost | What development and recruitment resources are required? |

The output will identify:

- primary candidate;
- mechanistic comparator;
- active control;
- conditional candidate;
- candidate to defer;
- candidate to retire.

A candidate is promoted only if it is not clearly dominated across the important dimensions and the assumptions supporting its position are explicit.

---

## 14. Psychometric-development engine

The same infrastructure will support efficient development of task-based and questionnaire measures required by the pain programme and later applications.

### 14.1 Intended measurement products

Potential outputs include:

- mechanism-sensitive behavioural tasks;
- short questionnaires;
- patient-reported outcome modules;
- pain-appraisal and activity-prediction measures;
- intervention-fidelity indices;
- adaptive task batteries;
- confidence and evidence-status labels;
- protected transfer measures;
- practitioner-facing summary scores.

### 14.2 Development sequence

```text
construct and intended-use definition
→ content and task blueprint
→ AI-assisted candidate generation
→ expert and lived-experience review
→ synthetic response generation
→ factor/IRT/model recovery
→ optimised human calibration design
→ cognitive interviews and usability testing
→ human item/task calibration
→ independent validation
→ short form or adaptive version
→ longitudinal and criterion validation
```

### 14.3 Construct blueprint

Every measure will define:

- target construct;
- construct boundaries;
- intended population;
- intended interpretation;
- intended decision use;
- facets and content coverage;
- plausible method factors;
- competing structural models;
- prohibited interpretations.

### 14.4 AI-assisted item and task generation

AI may generate candidate:

- questionnaire items;
- ambiguous pain scenarios;
- task trials;
- distractors and near-miss foils;
- difficulty variants;
- parallel forms;
- accessible-language alternatives.

Generated material will be screened for:

- construct relevance;
- ambiguity;
- double-barrelled wording;
- reading demand;
- social desirability;
- cultural assumptions;
- redundancy;
- local dependence;
- potentially harmful or blaming language;
- shortcut solutions.

No AI-generated item or clinical feedback text will be used without human review.

### 14.5 Synthetic psychometric populations

Questionnaire simulations may include:

```text
target trait
+ correlated subtraits
+ general factor
+ wording/keying effects
+ acquiescence
+ extreme response
+ social desirability
+ careless responding
+ subgroup-specific item functioning
+ missingness
```

Ability/task simulations may include:

```text
latent capacity
+ component-process parameters
+ item-feature demands
+ speed
+ persistence
+ guessing
+ lapses
+ practice and fatigue
```

### 14.6 Structural recovery

Competing structures may include:

- unidimensional;
- correlated factors;
- bifactor;
- general trait plus wording factor;
- longitudinal state-trait;
- formative or network alternatives where justified.

The system will assess whether the planned item pool and sample can recover the intended structure and distinguish it from plausible method effects.

### 14.7 IRT and adaptive testing

Where appropriate, the platform will support:

- item difficulty and discrimination estimation;
- category-threshold modelling;
- test-information analysis;
- item-bank calibration;
- planned-missing or matrix-sampling designs;
- linked forms using anchors;
- short-form assembly;
- computer-adaptive item selection;
- stopping rules based on precision.

Adaptive testing will be implemented only after sufficient real-response calibration and independent validation.

### 14.8 Fairness and measurement invariance

Synthetic studies will establish whether the planned analyses can detect differential item functioning of meaningful size. Human validation will examine:

- measurement invariance;
- subgroup comparability;
- accessibility;
- literacy and language effects;
- device effects for digital tasks;
- consequential risks of score interpretation.

Semantic AI screening does not establish fairness by itself.

### 14.9 Human validation requirements

Synthetic methods cannot establish:

- how participants interpret items;
- actual factor structure;
- reliability and test–retest stability;
- convergent and discriminant validity;
- criterion and predictive validity;
- meaningful change;
- clinical cut-offs;
- real subgroup fairness;
- acceptability and burden.

These require cognitive interviews, calibration samples, independent validation, longitudinal data and criterion-linked studies.

---

## 15. Service-pathway and implementation-intelligence engine

This strand will support clinical placement and later adoption without expanding into comprehensive system redesign.

### 15.1 Inputs

- NICE and professional guidance;
- local pain-service specifications;
- referral and eligibility documents;
- patient information;
- practitioner workflow descriptions;
- stakeholder interviews and workshops;
- lived-experience evidence;
- recruitment and retention data;
- prototype usability and safety findings;
- later, administrative or process data where access is approved.

### 15.2 AI-supported functions

AI may assist with:

- document classification and structured extraction;
- comparison of referral, eligibility and discharge criteria;
- identification of recurring workflow or access constraints;
- traceable synthesis of patient and practitioner evidence;
- mapping candidate intervention entry points;
- comparing a small number of delivery scenarios;
- maintaining an implementation-risk register.

All pathway interpretations will be reviewed by clinical, service, PPI and implementation contributors.

### 15.3 Pathway representation

The pathway model will represent:

```text
patient need or referral cue
→ eligibility and clinical boundaries
→ entry or self-access route
→ onboarding and consent
→ practitioner oversight
→ intervention use
→ monitoring and escalation
→ completion or non-response
→ onward care
→ patient and service outcomes
```

### 15.4 Candidate pathway outputs

- current-state pathway map;
- unmet-support point;
- intended-use statement;
- inclusion and exclusion specification;
- escalation and safeguarding rules;
- practitioner role map;
- patient journey;
- data-flow and information-governance requirements;
- implementation burden assessment;
- adoption and integration risks;
- future health-economic data requirements.

### 15.5 Boundary

The system will not make automated treatment or referral decisions. It will not claim causal pathway bottlenecks from document frequency alone. Any process-mining or administrative-data work will require separate approvals, data-quality analysis and human interpretation.

---

## 16. AI-agent specification

AI agents will have constrained, reviewable roles.

| Agent | Primary function | Required review |
|---|---|---|
| **Evidence extraction agent** | Extract study, sample, task and parameter information into structured records | Human evidence reviewer |
| **Dataset/prior agent** | Propose parameter sources and transportability ratings | Statistician or modeller |
| **Protocol design agent** | Generate task and intervention variants under fixed constraints | Scientific and clinical team |
| **Model critic** | Propose rival mechanisms and identify model confusion | Computational lead and statistician |
| **Psychometric item critic** | Flag ambiguity, redundancy, method effects and fairness risks | Psychometrician and PPI contributors |
| **Pathway synthesis agent** | Extract pathway stages, eligibility and workflow constraints | Clinical and implementation leads |
| **Adversarial claims agent** | Identify unsupported inferences, circular ranking and overclaiming | Claims/governance reviewer |
| **Reproducibility agent** | Check manifests, seeds, versions and missing artefacts | Research engineer |

### 16.1 Agent safeguards

- source-grounded extraction;
- no silent writes to canonical registries;
- confidence and uncertainty fields;
- human approval before use;
- immutable audit logs;
- separation of proposal and approved truth;
- no access to identifiable data unless explicitly authorised;
- no autonomous clinical output;
- versioned prompt and model records where outputs affect research decisions.

---

## 17. Human calibration and prospective validation

### 17.1 Initial pain-specific mechanism-mapping and candidate-selection study

The first human study will primarily calibrate the platform. It may include:

- neutral attention-control task;
- arrow/optic-flow and absolute/relative transfer conditions;
- affective perturbation;
- Adaptive Evidence task;
- pain-appraisal and activity-decision tasks;
- relevant patient-reported measures;
- acceptability and burden assessments;
- pain interference and activity/function outcomes.

Its purposes are to estimate:

- baseline parameter distributions;
- task correlations;
- measurement reliability;
- prespecified variation in mechanism parameters and candidate response profiles;
- relationship to pain functioning;
- device and timing quality;
- plausible intervention targets.

### 17.2 Prospective intervention comparison

After model updating, a small number of candidates will be locked prospectively. The study will include:

- an intervention candidate;
- a mechanistic comparator;
- an active control;
- protected transfer outcomes;
- delayed reassessment;
- patient-relevant functional outcomes;
- intervention-fidelity telemetry;
- prespecified estimands and analysis.

### 17.3 Prediction audit

The project will compare predicted and observed:

- parameter distributions;
- intervention effects;
- transfer costs;
- adherence;
- missingness;
- functional associations.

Discrepancies will be documented as model failures or transportability failures rather than hidden by post-hoc retuning.

---

## 18. Intervention fidelity and data quality

The platform will log:

- protocol version;
- actual exposure and dose;
- task conditions received;
- difficulty trajectory;
- wrapper-swap timing;
- probe performance;
- dip and recovery estimates;
- return-to-base performance;
- adherence and session completion;
- deviations from the adaptive controller;
- invalid trials and device warnings;
- delayed-probe completion.

### 18.1 Browser and device policy

The study specification will define:

- supported browsers and devices;
- minimum display and refresh requirements;
- timing checks;
- tab visibility and interruption detection;
- invalid-trial rules;
- latency and frame-drop handling;
- exclusion criteria;
- sensitivity analyses excluding timing-limited participants.

Where perceptual timing cannot be standardised sufficiently, analyses will prioritise robust behavioural contrasts or supervised/laboratory administration.

---

## 19. Efficiency evaluation

The project will evaluate efficiency rather than assume a fixed multiplier.

### 19.1 Reference workflow

The HRP Transfer Lab will be evaluated against a predefined conventional intervention-development workflow.

The conventional reference workflow will be specified prospectively and may be represented as:

```text
manual evidence review
→ narrative mechanism and candidate selection
→ fixed task and protocol design
→ conventional pilot study
→ post-hoc assessment of mechanism and transfer
```

The computational workflow is:

```text
structured evidence and dataset registry
→ explicit transportability-weighted priors
→ prespecified competing mechanism models
→ synthetic parameter recovery, model recovery and power analysis
→ informative pain-specific mechanism mapping and product calibration
→ prospective candidate selection and locked comparison
→ protected and delayed transfer assessment
```

Before the efficiency evaluation begins, the team will specify how each indicator will be compared. Depending on the metric, this may involve:

* a parallel development comparison;
* a prospectively documented benchmark process;
* structured expert review; or
* an appropriately matched historical development case.

The comparison method, assumptions and limitations will be prespecified before outcome evaluation.

The reference workflow is intended to provide a credible benchmark rather than a deliberately weak comparator. Both workflows will be evaluated against the same product-development endpoint and, where possible, the same standards for:

* protocol readiness;
* mechanism identifiability;
* measurement quality;
* participant burden;
* prediction accuracy;
* transfer sensitivity;
* reproducibility;
* cost and time to an advance, revise or retire decision.


### 19.2 Metrics

| Metric | Definition |
|---|---|
| **Time to locked protocol** | Time from evidence-map freeze to preregistered candidate specification |
| **Candidate retirement before human testing** | Number and proportion rejected for non-identifiability, low information or poor feasibility |
| **Human participant efficiency** | Participants and participant-minutes used per retained candidate |
| **Trial information efficiency** | Expected information or precision per participant-minute |
| **Design failure avoided** | Floor, ceiling, convergence and model-confusion problems detected before the human study |
| **Prediction accuracy** | Agreement between prospectively predicted and observed distributions or effects |
| **Psychometric efficiency** | Items/trials and respondents required to achieve specified measurement precision |
| **Pathway uncertainty resolved** | Pre-adoption uncertainties clarified before later clinical evaluation |
| **Decision cost** | Cost and time required to reach advance/revise/retire |

### 19.3 Efficiency claim boundary

The initial claim will be:

> The project will test whether computational screening and synthetic experimental design improve the efficiency and informativeness of early intervention and measurement development relative to a predefined reference workflow.

No numerical efficiency multiplier will be asserted before empirical comparison across development cycles.

---

## 20. Reproducibility, source traceability and technical infrastructure

### 20.1 Environment allocation

```text
VS Code / Codex / GitHub workstation
→ code, schemas, tests, public-safe documentation and synthetic fixtures

Local encrypted research node
→ authorised datasets, private registries, model fitting,
simulations, participant exports and evidence packets

Cloud or external compute
→ large synthetic or redacted simulation sweeps where required
```

### 20.2 Core registries

The platform will maintain:

- protocol registry;
- dataset registry;
- evidence registry;
- prior registry;
- model registry;
- psychometric item/task registry;
- simulation-run registry;
- human-study registry;
- pathway/implementation evidence registry;
- claims and review registry.

### 20.3 Run manifest

Every computational output will record:

```text
Git commit
configuration hash
random seed
software environment
source dataset versions
prior registry version
model version
protocol version
analysis specification
output artefact checksums
review status
```

### 20.4 Git and data boundaries

GitHub may contain:

- source code;
- configuration files;
- schemas;
- synthetic fixtures;
- unit tests;
- redacted aggregate reports;
- public-safe method documentation.

GitHub will not contain:

- identifiable participant data;
- governed third-party datasets;
- secrets or credentials;
- unredacted clinical exports;
- restricted stimuli;
- private embeddings of controlled content.

---

## 21. Governance, ethics and claims

### 21.1 Human authority

Consequential scientific, clinical, psychometric, pathway and commercial decisions remain human decisions.

### 21.2 Permitted computational conclusions

The system may conclude:

- a proposed experiment is or is not capable of identifying a mechanism under stated assumptions;
- a task design is vulnerable to floor, ceiling or model confusion;
- a candidate is more informative to test first under explicit scenarios;
- a psychometric design can recover a specified structure synthetically;
- a pathway placement scenario is supported by reviewed evidence;
- a ranking or conclusion is robust or sensitive to prior assumptions.

### 21.3 Prohibited conclusions from synthetic work alone

The system may not conclude:

- that an intervention reduces chronic pain or pain interference;
- that one protocol is clinically superior;
- that a participant should receive a particular intervention;
- that a psychometric score is valid, fair or diagnostic;
- that a pathway allocation decision should be automated;
- that transfer to a wrapper establishes real-world far transfer.

### 21.4 Audit and correction

All evidence packets will contain:

```text
What protocol version produced this?
What data, source or assumption supports it?
What evidence level is justified?
What review gate approved it?
What must not be inferred?
```

Corrections will be versioned and dated.

---

## 22. Technical phases and deliverables

### Phase A — Foundation and identifiability

**Indicative period:** Months 0–6

Activities:

- registry schemas and governance;
- initial matched datasets;
- prior registry;
- task generators;
- modular generative model;
- initial psychometric blueprints;
- parameter and model recovery;
- simulation-based power;
- focused pathway-document map.

Deliverables:

- D1: approved dataset and evidence manifests;
- D2: prior registry version 1;
- D3: model and task simulator version 1;
- D4: recovery and calibration report;
- D5: pathway-placement evidence map;
- D6: pain-specific product-calibration and candidate-selection protocol.

### Phase B — Pain-specific mechanism mapping, measurement calibration and candidate selection

**Indicative period:** Months 6–15

Activities:

* conduct the prespecified pain-specific mechanism-mapping and product-calibration study;
* complete usability, acceptability and data-quality analysis;
* calibrate the mechanism-sensitive psychometric tasks and measures;
* update and compare the prespecified computational models;
* test parameter recovery, model recovery and out-of-sample predictions;
* conduct initial pathway and patient-journey validation;
* prospectively lock the intervention configuration, mechanistic comparator and active control.

Deliverables:

- D7: human-calibrated parameter distributions;
- D8: validated or revised measures for proof-of-concept use;
- D9: candidate Pareto shortlist;
- D10: preregistered intervention-comparison protocol;
- D11: updated implementation-risk register.

### Phase C — Prospective proof of concept

**Indicative period:** Months 15–30

Activities:

- prototype refinement;
- active-controlled study;
- protected transfer;
- delayed follow-up;
- functional outcomes;
- prediction audit;
- pathway-integration and health-economic requirements.

Deliverables:

- D12: proof-of-mechanism report;
- D13: transfer evidence packet;
- D14: prediction-calibration report;
- D15: advance/revise/retire decision;
- D16: next-stage clinical and implementation study design.

### Phase D — Consolidation and onward development

**Indicative period:** Months 30–36, if included in final scope

Activities:

- final technical hardening;
- psychometric short forms or adaptive specifications where justified;
- implementation and commercial requirements;
- publication and knowledge mobilisation;
- next funding or trial application.

Deliverables:

- D17: technical platform specification;
- D18: intervention manual and fidelity model;
- D19: psychometric validation plan;
- D20: pathway-integration and commercialisation dossier.

---

## 23. Minimum viable grant scope

To prevent over-engineering, the minimum viable technical scope should include:

1. one primary clinical product for chronic primary pain;
2. one defined intended-use and pathway position;
3. one primary cognitive-affective mechanism chain;
4. a small number of prespecified rival models;
5. one compact mechanism-sensitive measurement battery;
6. synthetic parameter recovery, model recovery and power analysis;
7. one pain-specific product-calibration study;
8. one prospectively selected intervention configuration;
9. one mechanistic comparator and one active control;
10. protected and delayed transfer outcomes;
11. one explicit advance, revise or retire decision;
12. the minimum reusable computational infrastructure required to support these activities.

Possible later extensions include:

- deadline-sensitive commitment training;
- richer emotional or fear-conditioning modules;
- physiological covariates;
- computer-adaptive psychometrics;
- additional clinical indications;
- larger pathway and service-system analyses.

---

## 24. Success criteria

The technical programme will be considered successful if it can demonstrate that:

- the target mechanisms and critical contrasts are measurable with acceptable uncertainty;
- the experiment can distinguish at least two clinically meaningful competing explanations;
- the synthetic and statistical pipeline is calibrated and reproducible;
- a compact human study can update the model and narrow the candidate space;
- psychometric measures are sufficiently reliable and interpretable for the proof-of-concept study;
- protected transfer and delayed outcomes are specified prospectively;
- the selected pathway position, clinical boundaries and implementation requirements are credible;
- predictions are audited against observed human data;
- the project reaches an explicit advance, revise or retire decision;
- efficiency is measured against a predefined reference workflow rather than asserted.

---

## 25. Summary

The HRP Transfer Lab will provide an auditable development environment connecting:

```text
external evidence and databases
→ transportability-weighted priors
→ modular cognitive and psychometric models
→ empirically constrained synthetic populations
→ synthetic recovery, power and design experiments
→ smaller, more informative human calibration studies
→ protected and delayed transfer tests
→ patient-relevant functional outcomes
→ pathway placement and implementation planning
```

The distinctive contribution is not the use of AI or synthetic data in isolation. It is the disciplined integration of these tools within a staged translational process in which:

- assumptions are explicit;
- rival mechanisms are implemented;
- designs are tested before recruitment;
- measures are engineered alongside interventions;
- pathway placement is considered before adoption;
- human evidence remains the source of truth;
- and every candidate can be advanced, revised or retired according to prespecified evidence gates.

---

