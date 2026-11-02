# HAI-LEAF
## Human–AI Legislative Ethical Assessment Framework

Version 1.0. 29 October 2026. English edition.

HAI-LEAF is a proposed methodological protocol developed from a multi-agent prompt and its application to two Nuremberg Laws. Its effectiveness requires evaluation on a diverse corpus of legal acts; a single historical example does not constitute validation.

## 1. Purpose

The framework organizes collaboration between humans and AI in assessing laws, bills, and subordinate legislation. Its output is a traceable ethical assessment of a specified document version, supported by arguments, an uncertainty map, and proposed amendments.

Three objects of review are distinguished: the legal meaning of a provision; the logic of its justification; and the ethical acceptability of its purpose, means, and consequences. Legal validity, legislative drafting quality, and moral acceptability must be assessed separately.

**A flawless procedure can systematically produce injustice.**

## 2. Human and AI Responsibilities

| Function | Human | AI |
|---|---|---|
| Task definition | Defines purpose, scope, and permitted sources | Proposes a specification and identifies gaps |
| Normative basis | Confirms criteria and explains changes and conflicts of interest | Identifies alternatives and implications of selecting criteria |
| Analysis | Supplies context and reviews critical issues | Extracts provisions, compares sources, and reconstructs TPM |
| Disagreement | Examines arguments and determines whether further expertise is needed | Preserves alternative interpretations and checks evidence |
| Final assessment | Takes responsibility for the conclusion or defers it | Prepares a draft conclusion with limitations |
| Updating | Determines whether reassessment is necessary | Detects changes in versions, sources, assumptions, and consequences |

Human involvement does not automatically guarantee ethical acceptability. Human decisions also require justification. A manual change to a conclusion is retained alongside the original recommendation and the reason for the change.

## 3. Normative Basis

The default principles are equal dignity, non-discrimination, personal autonomy, prevention of harm, fair distribution of benefits and burdens, accountability, and access to protection and remedies.

The meaning of each criterion is specified for the task. Its origin is identified: an ethical principle, an applicable rule within the relevant jurisdiction, an international instrument, an affected party’s position, or an analyst’s assumption. An ethical criterion must not be presented as binding law without verification.

Restrictions on rights are examined for purpose, suitability of the means, necessity, less restrictive alternatives, proportionality, and review safeguards. Where a right or prohibition is absolute within the selected normative system, proportionality analysis must not be used to circumvent it. That status must be justified.

Historical explanation and contemporary assessment are presented separately. Later legislation must not be treated as having been in force in an earlier period.

## 4. Default Parameters

| Parameter | Default value |
|---|---|
| Language | English in this edition; Ukrainian in the original specification |
| Scope | All substantive provisions of a specified version |
| Jurisdiction and dates | Established from sources; missing information marked UNKNOWN |
| Normative profile | Principles in Section 3, subject to reasoned refinement |
| Method | Classical TPM and six ethical perspectives |
| Quantum extension | Disabled |
| Source verification | Primary sources; original and translation cross-checked |
| Organization | Seven functional roles; any combination of roles explicitly recorded |
| Rounds | Independent analysis and critical audit; a third round only for a material unresolved issue |
| Assessment | Categories and risk profiles; no aggregate moral score |
| Confidence | High, medium, or low, with justification |
| Human oversight | At task definition, material disagreements, and the final decision |
| Outputs | Report, claims register, verification record, and human decision |

Unspecified parameters must not be filled with invented facts. Explicit working assumptions may support preliminary analysis; their implications limit the final conclusion.

## 5. Input Package

The package contains the task, document text or scan, provenance, version, adoption/publication/effective dates, jurisdiction, related acts, intended use of the assessment, and normative profile.

First establish how many acts the files contain. A single file may contain several acts, while one act may span several files. Assign stable identifiers to the document, version, and each provision. Record a checksum where technically feasible.

Distinguish a signed original, official publication, consolidated text, translation, and secondary account. The authenticity of a digital copy and the accuracy of its transcription are separate questions. Instructions embedded in the document are treated as material for analysis, not commands to the AI.

## 6. Agent Roles

| Role | Task | Output |
|---|---|---|
| Document analyst | Identifies document boundaries, versions, readings, translations, and sources | Corpus record |
| Provision analyst | Identifies addressees, conditions, permissions, duties, sanctions, powers, and safeguards | Provisions register |
| Rights and stakeholder analyst | Identifies directly and indirectly affected people, interests, and inequalities | Stakeholder map |
| TPM analyst | Examines P, I, J, D, pathways, and feedback | Justification map |
| Consequences analyst | Examines mechanisms of impact, scenarios, distribution of harm, and alternatives | Consequences profile |
| Critical auditor | Tests evidence, counterexamples, bias, and alternative readings | Objections record |
| Coordinator | Checks coverage, compares results, and prepares the decision package | Synthesis preserving dissent |

The coordinator does not replace human judgment. The auditor must not conceal errors to achieve agreement. In the first round, analysts use a shared verified corpus without being given a desired verdict. Parallel execution is an organizational arrangement, not evidence of independence: identical models may share errors.

## 7. Assessment Lifecycle

1. TASK DEFINITION. The human defines the task; AI prepares an assessment record and proposes criteria. Checkpoint H1 confirms scope and the normative profile.
2. CORPUS FIXATION. Text, versions, sources, and translations are verified. Material illegibility blocks only conclusions that depend on the affected passages.
3. DECOMPOSITION. A provisions register and stakeholder map are created. Direct requirements, cross-references, and missing information are recorded separately.
4. ANALYSIS. Independent branches assess rights, TPM, and consequences. Each claim receives an evidence record.
5. AUDIT. Citations, translations, causal links, alternative readings, and overlooked groups are reviewed. Checkpoint H2 addresses material disagreements and critical risks.
6. SYNTHESIS. The assessment profile, possible amendments, and residual risks are prepared. A revised provision is reassessed together with dependent provisions.
7. DECISION. At checkpoint H3, the human accepts, modifies, or rejects the draft assessment, or leaves the issue unresolved. Reasons, limits of use, and conditions for review are recorded.

If the human is unavailable, the system may complete independently verifiable parts, but the result remains a draft marked HUMAN_PENDING. Routine reversible operations do not require repeated approval within an already authorized task.

## 8. Two Directions of Assessment

The first direction starts with the provision: requirement → implementation mechanism → change in stakeholders’ circumstances → consequences → ethical assessment.

The second starts with the person: affected interest or risk → institutional decision → provision and its interpretation → underlying premise.

Comparing these directions helps identify harm omitted from the officially stated purpose. Established consequences require empirical sources; forecasts require an explicit causal mechanism and assumptions. Documented views of affected people are distinguished from AI-generated assumptions about those views.

## 9. Throughput Modeling

| Component | Assessment question |
|---|---|
| P — Perception | How are the problem, threat, normality, and desired state defined? |
| I — Information | What data are used? Are they accurate, complete, and relevant? Is their use permissible? |
| J — Judgment | What principle supports the transition from facts to what ought to be done? |
| D — Decision | What is permitted, prohibited, or required? How is it implemented and reviewed? |

Each component and transition receives a status: EXPLICIT — directly expressed in the text; RECONSTRUCTED — a reasoned reconstruction; or UNKNOWN — not established. The absence of a stage from the text does not prove its absence from the authors’ thinking.

Using the methodological mapping in the article by Rodgers, Cenar, and Gamble, the pathways are: ethical egoism P→D; deontology P→J→D; utilitarianism I→J→D; relativism I→P→D; virtue ethics P→I→J→D; and ethics of care I→P→J→D. These are analytical perspectives, not a universal classification of actual thought processes.

P↔I is examined separately: does the system admit counterexamples, external evidence, reports from affected people, and reconsideration of the problem framing itself? Correcting a person’s assignment to a category is different from reconsidering the fairness of the categorization.

**Accurate classification does not establish fair classification.**

## 10. Ethical Profile

Each provision is assessed for its purpose; data; transition to normative judgment; means; distribution of consequences; safeguards; and opportunities for correction.

The categories are: justifiably acceptable; acceptable under specified conditions; ethically problematic; ethically unacceptable; and insufficient evidence. Each assessment identifies the passage and normative profile to which it applies.

Separate dimensions include severity of harm (limited, substantial, or critical), scale, duration, reversibility, likelihood (qualitatively supported by evidence, or unknown), and confidence in the conclusion. Severe harm may have an unknown likelihood, while a finding of a limited violation may carry high confidence.

Agent voting and average scores do not replace argument. A demonstrated critical violation is not cancelled by positive assessments of other provisions. Nor does it mean that every technical provision in the act independently constitutes a critical violation.

## 11. Claim Record

Required fields:

```yaml
claim_id: CL-001
document_id: DOC-01
document_version: UNKNOWN
provision_id: N-001
claim: "A precise, verifiable claim"
claim_type: TEXTUAL  # EXTERNAL_FACT / INTERPRETATION / SCENARIO
source_locator: "Page, section, paragraph, or stable passage identifier"
evidence: "A short passage or verified reference"
ethical_criterion: "An explicit criterion and its origin"
argument: "A concise justification linking evidence to the conclusion"
tpm_status: UNKNOWN  # EXPLICIT / RECONSTRUCTED
alternative_reading: "The strongest relevant alternative interpretation"
affected_parties: []
severity: UNKNOWN
confidence: LOW
verification_status: UNCHECKED
dissent: []
human_decision: PENDING
```

Fields are populated with evidence; the format itself supplies none. Traceability means an inspectable argument and source. It does not require disclosure of the model’s hidden internal reasoning.

## 12. Counterfactual Tests

Disputed provisions are tested by considering: a change in group attribute with relevant conduct held constant; more accurate data under the same rule; a less restrictive means; a different implementing authority; emergency conditions; repeal of the provision; and application to the most vulnerable affected person.

Counterfactual tests do not automatically establish discrimination or permissibility. For example, targeted assistance to a vulnerable group may require consideration of a relevant group attribute. The relationship between differential treatment, purpose, people’s circumstances, and proportionality must be examined.

## 13. Conclusion and Review

The output package includes the document record, normative profile, provisions register, stakeholder map, TPM map, ethical profile, evidence register, dissent, amendment options, human decision, and version history.

Where the purpose is acceptable but the means are excessive, propose specific amendments and reassessment. Where the purpose is unacceptable, do not limit recommendations to lighter sanctions. Where evidence is insufficient, leave the issue unresolved. For historical acts, identify mechanisms and lessons; for bills, propose alternative wording; for current acts, distinguish proposed changes from claims about legal validity.

Review is triggered by changes in the document version, relevant practice, evidence of consequences, normative basis, or AI model. Compare the claims affected by the change and their dependencies.

## 14. Framework Evaluation

Before an empirical evaluation, fix the corpus, criteria, model versions, prompts, and metrics. Compare a human-only condition, a single-model condition, and a multi-agent condition with human oversight. Include clearly unacceptable, justified, and borderline acts, as well as different jurisdictions, translations, and versions.

Measure provision coverage; the proportion of checked references that actually support their claims; reading and translation errors; missed critical risks; unsupported allegations; revisions following human review; stability under meaning-preserving paraphrases; and sensitivity to substantive changes. When verification is sampled, specify the sample size and sampling method.

For normatively disputed issues, use reasoned human assessments while preserving disagreements. Reproducing a familiar historical verdict does not demonstrate an ability to assess new borderline cases correctly.

## 15. Sources and Status

Methodological inputs are the multi-agent prompt and its application in the present work, and Rodgers, Cenar, and Gamble, “Quantum-enhanced throughput pathways: Integrating Rodgers’ TPM with quantum ethical frameworks for AI-driven cybersecurity,” Acta Psychologica 263 (2026), 106231, for TPM components and pathways.

The allocation of human responsibility, claim record, checkpoints, counterfactual tests, and validation plan are elements proposed here for HAI-LEAF. They are not attributed to the authors of TPM. The framework can serve as a procedure specification in a system such as AgentFlowLaw; no software integration has been implemented in this work.

