# Responsible AI governance concerns in Health AI

Stakeholder questions and needs organised by approaches in the literature. Each example describes a possible governance episode or concern in a Health AI project. The first-person formulations are illustrative, not quotations from participants. Where a study concerns AI outside healthcare, the examples are adapted to Health AI.

## 1. Ethics integrated into AI development

**Approach:** Address ethical concerns through requirements, design, development, evaluation and deployment. Amugongo et al. [1].

- **Clinical lead, requirements:** I need to know which patients the risk-prediction model is intended to serve, so that its use and evaluation reflect our clinical population.
- **Data protection lead, requirements:** Do participants' permissions cover using wearable and symptom data to train a prediction model?
- **Project manager, design:** Can we train the model without transferring identifiable patient records between partner hospitals?
- **Clinician, design:** I need to review and, where necessary, disregard model-generated recommendations before they influence treatment.
- **Developer, implementation:** Which patient information and model outputs may each clinical or technical role access?
- **Clinical evaluator, testing:** Is performance acceptable across patient subgroups, including those poorly represented in the training data?
- **Patient representative, testing:** Can patients understand what the prediction means, its uncertainty and how it may affect their care?
- **Product owner, deployment:** Do changes to the model or clinical workflow require renewed safety or ethics review?

## 2. Decision points in healthcare AI adoption

**Approach:** Examine organisational decisions from selecting an AI application to continued use or withdrawal. Kim et al. [2].

- **Clinical director:** Is AI appropriate for this clinical problem, or would an existing non-AI process better serve patients?
- **Health service manager:** I need to decide whether to develop a prediction model internally or procure one, taking account of available clinical and technical support.
- **Clinical lead:** What minimum sensitivity, specificity and clinical benefit would justify using this model in our service?
- **Ward manager:** Who should receive an AI-generated deterioration alert, and who is responsible for acting on it?
- **Clinical safety officer:** Is the evidence sufficient to approve a pilot, or should deployment be restricted or postponed?
- **Training lead:** I need clinicians to understand when they can rely on the system and when they must use independent judgement.
- **Hospital AI lead:** Who will monitor the model after deployment, and who can authorise changes or suspend its use?
- **Medical director:** Should we withdraw the system if its clinical benefit is no longer supported by current evidence?

## 3. Clinical fairness and social justice

**Approach:** Assess fairness in relation to clinical outcomes, affected groups and social context, rather than treating it as a statistical measure alone. McCradden et al. [3].

- **Clinical researcher:** Are patients with rare conditions or from under-represented groups missing from the training data?
- **Health equity lead:** Which differences in errors between patient groups are clinically consequential, rather than merely numerically different?
- **Clinical lead:** I need to understand whether improving overall accuracy would increase the risk of missed diagnoses for a particular group.
- **Model evaluator:** Can we justify the decision threshold for each subgroup in relation to clinical benefit and potential harm?
- **Patient representative:** Would the proposed risk score reinforce stigma or unequal access to care for the people it classifies?
- **Service lead:** Are differences in patient outcomes emerging after the model is introduced into routine care?

## 4. Clinical governance and assurance

**Approach:** Establish oversight, clinical evaluation, accountability and conditions for responsible healthcare AI use. Reddy et al. [4].

- **Clinical governance lead:** Who needs to review the AI application before it is used to support clinical decisions?
- **Clinical investigator:** I need evidence that the model is safe and effective for the patients and clinical setting in which we intend to use it.
- **Patient representative:** Will patients know when AI contributes to their care and what its limitations are?
- **Data controller:** Under what conditions may the hospital share patient records with an external model developer?
- **Medical director:** Who accepts clinical responsibility for acting on a prediction when the model provider operates the technical system?
- **Quality lead:** When a model changes or an unexpected outcome occurs, what evidence is needed before continuing its use?

## 5. Stakeholder participation and concept selection

**Approach:** Involve affected stakeholders and examine whether an AI concept should be developed before substantial investment. Kallina et al. [5]; Jung et al. [6]. These Health AI situations are illustrative applications of the approaches.

- **Patient representative:** Whose experiences are missing from the proposal for an automated triage service, especially among patients who have difficulty accessing care?
- **Nurse:** I need the team to consider whether the proposed triage model would delay urgent assessment or add work to clinical staff.
- **Carer:** Can I challenge an incorrect monitoring alert, and will my concern affect the design?
- **Project lead:** How will we know whether patient and clinician feedback changed the model's requirements, rather than merely confirmed the original plan?
- **Founder:** Should we focus on administrative support instead of clinical triage if we cannot obtain adequate evidence for the higher-risk application?
- **Clinical partner:** I need agreement on which patient groups and clinical uses we should exclude until they can be evaluated properly.

## 6. Governance in interdisciplinary work

**Approach:** Understand how clinical, technical and other specialists raise and resolve ethical concerns during ordinary project work. Hine and Barnaghi [7]; Deng et al. [8]. The smart-care concerns draw on reported interdisciplinary work; fairness-coordination scenarios are illustrative Health AI adaptations.

- **Research coordinator:** Do we need an ethics amendment before adding new sensing or AI analysis to the dementia-monitoring study?
- **Data scientist:** I need enough clinical context to develop the model, but the care provider cannot share all identifiable patient information. What can be made available?
- **Care worker:** How can I explain that a monitoring alert may misrepresent a resident's behaviour or condition?
- **Clinical lead:** I need engineers to understand which prediction errors would change clinical decisions and which would not.
- **ML engineer:** Who can decide how subgroup performance should be assessed when the clinical and product teams prioritise different outcomes?
- **Project manager:** Who is responsible for resolving disagreements between clinical requirements, fairness testing and delivery commitments?

## 7. Accountability across organisations

**Approach:** Examine responsibility, access to information and control across developers, suppliers, integrators and AI users. Cobbe et al. [9]. These Health AI examples are adaptations of supply-chain accountability analysis.

- **Hospital digital lead:** Which organisation controls the prediction model, its updates, the hosting infrastructure and the clinical interface?
- **Clinical service manager:** Who can correct the system if its outputs become unsafe, and who can authorise the correction?
- **Procurement lead:** I need to know whether the model provider can supply the information required for our clinical assurance review.
- **Data protection officer:** Who is responsible when a supplier processes patient data on behalf of several healthcare organisations?
- **Clinical investigator:** If a prediction appears incorrect, can we obtain sufficient information from each provider to investigate it?
- **Project founder:** We are responsible for the final health application, but we do not control the underlying model. What evidence and contractual access do we need?

## 8. Regulatory and data-quality governance

**Approach:** Interpret applicable requirements and connect them to data, roles and evidence in AI development. Batool et al. [10]; Wang et al. [11]. Data-quality examples are adapted to Health AI where the cited study addresses broader machine-learning settings.

- **Founder:** Does the intended clinical use of our AI system create obligations that would not apply if we offered the same functionality as a consumer-health application?
- **Regulatory lead:** Which obligations apply to this model, and which organisation must demonstrate compliance?
- **Project coordinator:** I need to understand which AI-specific evidence the funder expects before approving the next project milestone.
- **Data manager:** Can we trace the origin, permissions and processing history of each dataset used for training and validation?
- **ML engineer:** Are missing labels, inconsistent clinical coding or uneven sampling likely to invalidate the model's evaluation?
- **Quality manager:** Who can confirm that dataset completeness and representativeness meet the required standard?
- **Consortium lead:** We need a regulatory or ethics deliverable, but the evidence is held by a partner. Who can provide and approve it?

## 9. Monitoring, correction and non-adoption

**Approach:** Examine continuing governance responsibilities and decisions to defer, narrow or discontinue AI. Owens et al. [12]; Chappidi and Singh [13]. Monitoring concerns are grounded in healthcare research; non-adoption scenarios are illustrative Health AI adaptations.

- **Hospital AI lead:** Who is responsible for monitoring model performance when IT, clinicians and an external supplier all contribute to the system?
- **Clinical safety officer:** How will we know if prediction accuracy has deteriorated after changes in the patient population or clinical pathway?
- **Patient safety lead:** I need a way to investigate harmful model outputs even when no formal incident report has been made.
- **Developer:** Who can authorise retraining or a model update, and what revalidation will be required?
- **Founder:** Should we defer a patient-facing migraine prediction feature until we have adequate clinical evidence and regulatory clearance?
- **Product lead:** We cannot support the proposed clinical use within the current budget. Could a narrower intended use reduce the evidence and operational requirements?
- **Medical director:** Should we suspend or retire the AI system because its risks, maintenance demands or uncertain clinical benefit are no longer acceptable?

## References

1. Amugongo, L. M., Kriebitz, A., Boch, A. and Lütge, C. (2025). *Operationalising AI Ethics through the Agile Software Development Lifecycle: A Case Study of AI-Enabled Mobile Health Applications*. *AI and Ethics*, 5, 227–244. https://doi.org/10.1007/s43681-023-00331-3
2. Kim, J. Y. et al. (2023). *Organizational Governance of Emerging Technologies: AI Adoption in Healthcare*. *ACM FAccT*, 1396–1417. https://doi.org/10.1145/3593013.3594089
3. McCradden, M. et al. (2023). *What's fair is... fair? Presenting JustEFAB, an ethical framework for operationalizing medical ethics and social justice in the integration of clinical machine learning*. *ACM FAccT*, 1505–1519. https://doi.org/10.1145/3593013.3594096
4. Reddy, S., Allan, S., Coghlan, S. and Cooper, P. (2020). *A governance model for the application of AI in health care*. *Journal of the American Medical Informatics Association*, 27(3), 491–497. https://doi.org/10.1093/jamia/ocz192
5. Kallina, E., Bohné, T. and Singh, J. (2025). *Stakeholder Participation for Responsible AI Development: Disconnects Between Guidance and Current Practice*. *ACM FAccT*. https://doi.org/10.1145/3715275.3732069
6. Jung, J. Y. et al. (2025). *Making the Right Thing: Bridging HCI and Responsible AI in Early-Stage AI Concept Selection*. *ACM DIS*. https://doi.org/10.1145/3715336.3735745
7. Hine, C. and Barnaghi, P. (2024). *Ethics and Artificial Intelligence in the Interdisciplinary Collaborations of Smart Care*. *Science, Technology, & Human Values*. https://doi.org/10.1177/01622439241302519
8. Deng, W. H. et al. (2023). *Investigating Practices and Opportunities for Cross-functional Collaboration around AI Fairness in Industry Practice*. *ACM FAccT*. https://doi.org/10.1145/3593013.3594037
9. Cobbe, J., Veale, M. and Singh, J. (2023). *Understanding accountability in algorithmic supply chains*. *ACM FAccT*, 1186–1197. https://doi.org/10.1145/3593013.3594073
10. Batool, A., Zowghi, D. and Bano, M. (2025). *AI governance: a systematic literature review*. *AI and Ethics*, 5, 3265–3279. https://doi.org/10.1007/s43681-024-00653-w
11. Wang, Y., Irion, K., Groth, P. and Harmouch, H. (2026). *“Detective Work We Shouldn't Have to Do”: Practitioner Challenges in Regulatory-Aligned Data Quality in Machine Learning Systems*. *ACM FAccT*, 3217–3241. https://doi.org/10.1145/3805689.3812313
12. Owens, K., Griffen, Z. and Damaraju, L. (2025). *Managing a “responsibility vacuum” in AI monitoring and governance in healthcare: a qualitative study*. *BMC Health Services Research*, 25, 1217. https://doi.org/10.1186/s12913-025-13388-z
13. Chappidi, S. and Singh, J. (2026). *To Build or Not to Build? Factors that Lead to Non-Development or Abandonment of AI Systems*. *ACM FAccT*. https://doi.org/10.1145/3805689.3806736
