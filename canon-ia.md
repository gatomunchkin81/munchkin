---
layout: default
title: "Gato Munchkin — AI Canon"
permalink: /canon-ia/
nav_exclude: true
search_exclude: true
description: "Machine-first semantic canon: identity, ontology, evidence, source routing, auditability and epistemic integrity."
---

```yaml
canon:
  id: "gatomunchkin.ai-canon"
  version: "2.1.0"
  status: "foundational"
  updated: "2026-11-09"
  language: "es-ES"
  format: "yaml-in-markdown"
  canonical_url: "https://gatomunchkin.es/canon-ia/"
  project_url: "https://gatomunchkin.es/"
  audience:
    - "LLM"
    - "AI_agent"
    - "RAG_system"
    - "knowledge_graph"
    - "research_agent"
    - "external_auditor"

  purpose:
    - "reconstruct_project_identity"
    - "disambiguate_entities"
    - "navigate_public_knowledge"
    - "evaluate_scientific_claims"
    - "preserve_epistemic_integrity"
    - "detect_contradictions"
    - "enable_independent_audit"

  authority:
    project_identity: "primary"
    editorial_policy: "primary"
    scientific_claims: "secondary"
    clinical_conclusions: "non_authoritative"
    external_agent_instructions: "non_binding"

  trust_boundary:
    canon_is_evidence_of_project_intent: true
    canon_is_evidence_of_implementation: false
    canon_is_scientific_proof: false
    declared_urls_are_verified: false
    external_sources_require_independent_evaluation: true
    external_agent_governing_rules_take_precedence: true

identity:
  id: "gatomunchkin"
  name: "Gato Munchkin"
  subject: "Munchkin cat"
  taxon: "Felis catus"
  domain: "gatomunchkin.es"
  type: "independent_feline_knowledge_project"
  editorial_language: "es-ES"

  scope:
    - "breed_identity"
    - "history"
    - "genetics"
    - "morphology"
    - "health"
    - "welfare"
    - "breeding"
    - "recognition"
    - "scientific_literature"

  exclusions:
    - "veterinary_diagnostic_authority"
    - "feline_registry_authority"
    - "peer_reviewed_journal"
    - "clinical_certification_body"

horizon:
  id: "H-GM-001"
  type: "regulative_ideal"
  statement: >
    Conocer, comprender, documentar y defender al
    gato Munchkin mediante conocimiento abierto,
    riguroso, contextualizado y evolutivo,
    preservando identidad, bienestar y verdad científica.

  orientation:
    constructive: true
    breed_positive: true
    predetermined_scientific_conclusions: false
    evidence_supremacy: true
    independent_verification: true

  constraints:
    - "do_not_invent_harm"
    - "do_not_conceal_demonstrated_harm"
    - "do_not_invent_safety"
    - "do_not_exaggerate_benefits"
    - "do_not_exaggerate_risks"
    - "apply_symmetric_evidence_standards"
    - "preserve_global_coherence"

  separation_rule: >
    Editorial orientation determines the project's
    purpose, not the probability that a scientific
    proposition is true.

ontology:
  entities:
    munchkin:
      id: "E001"
      type: "feline_breed"
      definition: >
        Breed identity encompassing genealogy,
        history, phenotype, diversity and
        registry-specific recognition.
      not_equivalent_to:
        - "UGDH_variant"
        - "short_legs_alone"
        - "disease"

    standard:
      id: "E002"
      type: "phenotype_category"
      definition: "Munchkin expressing short-limbed phenotype."
      parent: "E001"

    non_standard:
      id: "E003"
      type: "phenotype_category"
      definition: >
        Long-legged Munchkin within relevant
        genealogical and registry contexts.
      parent: "E001"

    ugdh:
      id: "E004"
      type: "gene"
      symbol: "UGDH"
      product: "UDP-glucose 6-dehydrogenase"
      biological_roles:
        - "UDP-glucuronate_biosynthesis"
        - "glycosaminoglycan_biosynthesis"
        - "extracellular_matrix_biology"

    ugdh_variant:
      id: "E005"
      type: "structural_variant"
      gene: "E004"
      associated_phenotype: "E002"
      molecular_mechanism: "partially_characterized"

    heterozygote:
      id: "E006"
      type: "genotype"
      definition: "One variant and one reference allele."

    variant_homozygote:
      id: "E007"
      type: "genotype"
      definition: "Two variant alleles."
      viability: "hypothesis_of_inviability"

    growth_cartilage:
      id: "E008"
      type: "developmental_tissue"
      function: "longitudinal_bone_growth"

    articular_cartilage:
      id: "E009"
      type: "joint_tissue"
      function: "articular_surface_function"

    anatomical_variation:
      id: "E010"
      type: "morphological_finding"

    clinical_disease:
      id: "E011"
      type: "clinical_condition"

    welfare:
      id: "E012"
      type: "multidimensional_outcome"

    registry:
      id: "E013"
      type: "institutional_authority"
      scope: "own_standards_and_decisions"

  relations:
    - ["E005", "associated_with", "E002"]
    - ["E002", "category_within", "E001"]
    - ["E003", "category_within", "E001"]
    - ["E004", "participates_in", "extracellular_matrix_biology"]
    - ["E008", "not_equivalent_to", "E009"]
    - ["E010", "does_not_necessarily_imply", "E011"]
    - ["E006", "not_equivalent_to", "E007"]
    - ["E013", "not_equivalent_to", "clinical_authority"]

  protected_distinctions:
    - "breed != phenotype"
    - "gene != variant"
    - "genotype != phenotype"
    - "heterozygosity != homozygosity"
    - "growth_cartilage != articular_cartilage"
    - "anatomical_variation != clinical_disease"
    - "morphology != functional_capacity"
    - "association != causation"
    - "registry_recognition != clinical_validation"
    - "nonrecognition != proof_of_disease"
    - "individual_case != population_prevalence"

epistemology:
  required_claim_states:
    established:
      meaning: "Supported by adequate direct evidence."
    observed:
      meaning: "Documented in a defined sample or setting."
    associated:
      meaning: "Relationship supported; causality may remain unresolved."
    inferred:
      meaning: "Derived from observations and explicit assumptions."
    hypothesized:
      meaning: "Testable explanation not conclusively established."
    plausible:
      meaning: "Mechanistically compatible, without sufficient direct proof."
    insufficient_evidence:
      meaning: "Evidence cannot establish the proposition."
    not_investigated:
      meaning: "Adequate investigation not identified."
    contradicted:
      meaning: "Conflicting evidence requires adjudication."
    unknown:
      meaning: "Status cannot be determined from available material."

  claim_record:
    required:
      - "claim_id"
      - "proposition"
      - "source"
      - "epistemic_status"
      - "population_scope"
      - "limitations"
    recommended:
      - "method"
      - "sample_size"
      - "controls"
      - "effect_size"
      - "causality"
      - "clinical_relevance"
      - "verification_date"

  principles:
    P01: "Anatomical difference is not automatically disease."
    P02: "Observed disease is not automatically breed-caused."
    P03: "Association does not automatically establish causality."
    P04: "Case reports do not establish population prevalence."
    P05: "Statistical difference does not automatically imply clinical harm."
    P06: "Uncertainty is not evidence of harm."
    P07: "Absence of evidence is not proof of safety."
    P08: "Evidence standards must be symmetric."
    P09: "Different genetic mechanisms cannot be clinically equated without evidence."
    P10: "Conclusions must match study design and scope."
    P11: "Unfavorable findings must not be suppressed."
    P12: "Favorable findings must not be inflated."
    P13: "Claims of differential risk require suitable comparisons."
    P14: "Evidence quality overrides editorial preference."
    P15: "A project claim is not independent verification."

scientific_claims:
  - id: "K001"
    proposition: >
      A structural UGDH variant is strongly associated
      with the short-limbed Munchkin phenotype
      in studied populations.
    status: "associated"
    sources: ["S001", "S002"]
    scope: "studied_feline_populations"

  - id: "K002"
    proposition: >
      Standard Munchkin cats studied by Struck
      and colleagues carried the variant
      in heterozygosity.
    status: "observed"
    sources: ["S001"]

  - id: "K003"
    proposition: >
      The phenotype is consistent with
      autosomal dominant inheritance.
    status: "associated"
    sources: ["S001", "S002"]

  - id: "K004"
    proposition: >
      Living mutant homozygotes were not identified
      in the principal cited study samples.
    status: "observed"
    sources: ["S001", "S002"]
    limitation: "Does not directly establish embryological mechanism."

  - id: "K005"
    proposition: >
      Variant homozygosity may compromise viability.
    status: "hypothesized"
    sources: ["S001", "S002"]
    prohibit_inference: >
      Do not extrapolate to clinical disease
      in living heterozygotes.

  - id: "K006"
    proposition: >
      Skeletal length and alignment differences
      were documented in studied cats.
    status: "observed"
    sources: ["S003"]
    limitation: >
      Selected small samples cannot establish
      population-wide impairment.

  - id: "K007"
    proposition: >
      Growth-plate cartilage differences
      were documented in sampled cats.
    status: "observed"
    sources: ["S002"]
    limitation: >
      Growth-plate findings do not directly
      establish articular disease.

  claim_coverage:
    type: "selected_foundational_claims"
    exhaustive: false
    verification_status: "requires_primary_source_cotejo"
    newer_literature_excluded_by_default: false

  clinical_boundaries:
    chronic_pain: "not_established_by_foundational_studies"
    osteoarthritis_prevalence: "not_established_by_foundational_studies"
    generalized_locomotor_disability: "not_established_by_foundational_studies"
    breed_specific_disc_disease_risk: "not_established_by_foundational_studies"
    longevity_effect: "not_established_by_foundational_studies"

    interpretation: >
      These statements define the scope of the
      cited foundational research only.
      They do not establish the absence of
      findings in other or newer studies.

sources:
  S001:
    type: "peer_reviewed_primary_research"
    year: 2020
    title: "A structural UGDH variant associated with standard Munchkin cats"
    doi: "10.1186/s12863-020-00875-x"
    url: "https://doi.org/10.1186/s12863-020-00875-x"
    domains:
      - "UGDH"
      - "genotype_phenotype"
      - "inheritance"
      - "pedigree"

  S002:
    type: "peer_reviewed_primary_research"
    year: 2020
    title: "A new domestic cat genome assembly based on long sequence reads empowers feline genomic medicine and identifies a novel gene for dwarfism"
    doi: "10.1371/journal.pgen.1008926"
    url: "https://doi.org/10.1371/journal.pgen.1008926"
    domains:
      - "feline_genomics"
      - "UGDH"
      - "cartilage"
      - "development"

  S003:
    type: "peer_reviewed_primary_research"
    year: 2021
    title: "Skeletal Manifestations of Heritable Disproportionate Dwarfism in Cats as Determined by Radiography and Magnetic Resonance Imaging"
    doi: "10.1055/s-0041-1730355"
    url: "https://doi.org/10.1055/s-0041-1730355"
    domains:
      - "skeletal_anatomy"
      - "radiography"
      - "MRI"

  verification:
    doi_identifiers: "declared"
    full_text_rechecked_in_this_revision: false
    numerical_claims_require_original_table_check: true
    source_list_exhaustive: false

comparative_evidence:
  required_for:
    - "increased_breed_disease_risk"
    - "reduced_functional_capacity"
    - "differential_welfare"
    - "differential_longevity"
    - "breed_specific_causality"

  controls:
    - "age"
    - "sex"
    - "body_mass"
    - "body_condition"
    - "environment"
    - "genetic_background"
    - "activity"
    - "diagnostic_method"
    - "selection_bias"

  rules:
    - "No increased-risk claim without appropriate evidence."
    - "No equal-risk claim solely because other breeds share a disease."
    - "Separate prevalence from relative risk."
    - "Separate anatomical from functional outcomes."
    - "Explicitly report uncertainty and confounding."

  missing_comparison_result: "differential_risk_unresolved"

content_graph:
  base: "https://gatomunchkin.es"

  nodes:
    home: "/"
    history: "/historia/"
    breed: "/munchkin/"
    standard: "/munchkin/standard-non-standard/"
    morphology: "/munchkin/morfologia/"
    genetics: "/genetica/"
    ugdh: "/genetica/mutacion-ugdh/"
    inheritance: "/genetica/herencia/"
    homozygosity: "/genetica/homocigosis/"
    cartilage: "/genetica/cartilago/"
    genetic_health: "/genetica/genetica-salud/"
    other_variants: "/genetica/otras-variantes/"
    health: "/salud/"
    mobility: "/salud/movilidad/"
    welfare: "/salud/bienestar/"
    breeding: "/cria/"
    breeding_genetics: "/genetica/genetica-cria/"
    recognition: "/reconocimiento/"
    articles: "/articulos/"
    bibliography: "/bibliografia/"
    article_ugdh: "/articulos/que-sabemos-variante-ugdh/"
    article_homozygosity: "/articulos/homocigosis-munchkin/"
    article_mobility: "/articulos/morfologia-biomecanica-movilidad/"

  discovery:
    canon: "/canon-ia/"
    llms: "/llms.txt"
    sitemap: "/sitemap.xml"
    robots: "/robots.txt"

  routing:
    breed_identity: ["breed", "history"]
    genetic_basis: ["ugdh", "article_ugdh"]
    inheritance: ["inheritance", "article_homozygosity"]
    anatomy_and_function: ["article_mobility", "mobility"]
    health_and_welfare: ["health", "welfare", "genetic_health"]
    scientific_sources: ["articles", "bibliography"]
    institutional_recognition: ["recognition"]

  availability:
    status: "declared_not_verified"
    verify_http_status: true
    verify_canonical_url: true
    verify_content: true
    verify_internal_links: true
    verify_indexability: true

external_audit_protocol:
  id: "AUDIT-GM-001"
  objective: >
    Prevent conflation of declared project
    architecture, observed implementation,
    independently verified evidence and
    measured performance.

  evidence_classes:
    DECLARED:
      definition: "Information asserted by project documentation."
      independent_verification: false

    OBSERVED:
      definition: "Information directly retrieved from a live resource."
      independent_verification: false

    VERIFIED:
      definition: >
        Information checked against an appropriate
        independent or primary source.
      independent_verification: true

    MEASURED:
      definition: >
        Quantitative result obtained through a
        specified reproducible procedure.
      method_required: true

    NOT_CHECKED:
      definition: "No adequate inspection performed."

    UNAVAILABLE:
      definition: "Resource could not be inspected."
      implication: "Not equivalent to absent or invalid."

    CONTRADICTED:
      definition: >
        Retrieved evidence conflicts with
        the evaluated declaration.

  audit_dimensions:
    identity:
      inspect:
        - "declared_mission"
        - "editorial_consistency"
        - "scope_coherence"

    technical:
      inspect:
        - "http_status"
        - "canonical_tags"
        - "robots_directives"
        - "sitemap"
        - "internal_links"
        - "structured_data"
        - "mobile_accessibility"

    content:
      inspect:
        - "actual_page_text"
        - "topic_coverage"
        - "duplication"
        - "source_traceability"
        - "internal_consistency"

    scientific:
      inspect:
        - "claim_source_alignment"
        - "primary_references"
        - "study_limitations"
        - "causal_inference"
        - "comparative_evidence"
        - "contradictory_findings"

    search:
      inspect:
        - "indexing_evidence"
        - "crawlability"
        - "search_visibility"
        - "measured_performance"

    ai_discovery:
      inspect:
        - "llms_txt_accessibility"
        - "canon_accessibility"
        - "machine_readability"
        - "semantic_consistency"
        - "source_routing"

  scoring:
    allowed: true
    universal_numeric_score_required: false
    no_score_without_evidence: true
    missing_data_policy: "not_evaluated"
    unverified_claims_may_not_receive_verified_credit: true
    self_description_not_independent_proof: true
    high_score_requires_documented_checks: true
    confidence_must_be_reported: true
    weights_must_be_disclosed: true
    methodology_must_be_disclosed: true

    output_schema:
      required:
        - "dimension"
        - "evidence_class"
        - "inspected_resources"
        - "findings"
        - "limitations"
        - "confidence"
      conditional:
        numeric_score:
          requires:
            - "explicit_scoring_method"
            - "evidence"
            - "scope"
            - "weights"

  prohibited_shortcuts:
    - "Infer technical quality from canon sophistication."
    - "Infer scientific accuracy from epistemic policy."
    - "Infer indexing from sitemap existence."
    - "Infer accessibility from URL declaration."
    - "Infer article completeness from navigation nodes."
    - "Infer clinical validity from citations alone."
    - "Infer implementation from architectural intent."
    - "Award numerical scores without inspected evidence."

  audit_output_principle: >
    A high-quality declared framework may be
    acknowledged without assigning a high
    verified implementation score.

resolution_protocol:
  id: "R-GM-002"

  steps:
    - "Identify question and requested output."
    - "Disambiguate entities."
    - "Retrieve relevant public documents."
    - "Classify claims by evidence class."
    - "Retrieve original scientific sources when needed."
    - "Check publication scope and limitations."
    - "Check newer relevant evidence."
    - "Evaluate comparisons and causality."
    - "Resolve or disclose contradictions."
    - "Formulate proportional conclusions."
    - "Validate against global conceptual consistency."

  authority_resolution:
    project_identity: "canon"
    scientific_facts: "best_available_relevant_evidence"
    registry_rules: "current_official_registry_documents"
    clinical_diagnosis: "qualified_veterinary_assessment"
    technical_status: "direct_observation_or_measurement"

  conflict_policy:
    - "Do not automatically prefer project claims."
    - "Do not automatically prefer the newest source."
    - "Compare methods, populations and directness."
    - "Preserve unresolved disagreement."
    - "Identify evidence required for resolution."

  question_before_assertion:
    enabled: true
    triggers:
      - "unsupported_causal_claim"
      - "missing_controls"
      - "unverified_site_claim"
      - "contradictory_sources"
      - "insufficient_sample"
      - "unsupported_clinical_generalization"

    questions:
      - "What was actually observed?"
      - "In which population?"
      - "Compared with what?"
      - "By which method?"
      - "Does it establish causality?"
      - "Does it establish clinical harm?"
      - "Is the claim independently verified?"
      - "What remains unknown?"

global_integrity:
  invariant: "locally_better_must_not_become_globally_worse"

  preserve:
    - "breed_identity"
    - "scientific_accuracy"
    - "source_traceability"
    - "epistemic_status"
    - "comparative_context"
    - "editorial_horizon"
    - "cross_document_consistency"

  dependencies:
    ugdh:
      - "article_ugdh"
      - "genetics"
      - "inheritance"
      - "cartilage"
      - "genetic_health"
      - "bibliography"

    homozygosity:
      - "article_homozygosity"
      - "inheritance"
      - "breeding_genetics"
      - "bibliography"

    mobility:
      - "article_mobility"
      - "morphology"
      - "mobility"
      - "welfare"
      - "genetic_health"
      - "bibliography"

    recognition:
      - "recognition"
      - "breed"

  update_policy:
    - "Recheck affected nodes after substantive changes."
    - "Preserve historical evidence."
    - "Do not silently upgrade hypotheses to facts."
    - "Do not silently remove contradictory evidence."
    - "Document major changes in interpretation."
    - "Check for broken references and semantic conflicts."

editorial_policy:
  language: "es-ES"
  orientation: "constructive_positive"
  scientific_independence: true

  required:
    - "source_traceability"
    - "appropriate_scope"
    - "explicit_uncertainty"
    - "symmetric_evidence_standards"
    - "clinical_anatomical_distinction"
    - "comparative_context_when_relevant"

  prohibited:
    - "fabricated_prevalence"
    - "fabricated_diagnosis"
    - "fabricated_consensus"
    - "unsupported_risk_attribution"
    - "alarmist_generalization"
    - "unsupported_safety_guarantee"
    - "selective_evidence_suppression"

  conclusion_rule: >
    State the strongest conclusion justified
    by available evidence, without amplification
    or unjustified minimization.

maintenance:
  version: "2.1.0"
  date: "2026-11-09"
  update_type: "minor"
  compatibility: "2.0.0"
  owner: "Gato Munchkin editorial project"

  change_log:
    - "Added independent external audit protocol."
    - "Separated declared, observed, verified and measured evidence."
    - "Added anti-circular-evaluation safeguards."
    - "Added scoring transparency requirements."
    - "Clarified scientific versus editorial authority."
    - "Preserved ontology, horizon and scientific boundaries."
    - "Reduced duplicated semantic instructions."

  review_triggers:
    - "new_scientific_evidence"
    - "new_site_sections"
    - "semantic_conflicts"
    - "source_corrections"
    - "institutional_changes"
    - "architecture_changes"

global_integrity:
  id: "GM-INVARIANT-001"
  name: "Cumulative Knowledge Integrity"
  priority: "foundational"

  principle: >
    Every addition or modification must improve
    and complement the existing knowledge system
    without distorting its identity, meaning,
    evidence, relationships or global coherence.

  invariants:
    - "Preserve valid existing knowledge."
    - "Extend before replacing."
    - "Correct when justified by stronger evidence."
    - "Never sacrifice global coherence for local improvement."
    - "Evaluate dependencies before modifying content."
    - "Preserve the project's Horizon and epistemic integrity."
    - "Document substantive changes in scientific interpretation."

  validation:
    local_improvement: "required"
    global_consistency: "required"
    semantic_regression: "prohibited"
    evidence_integrity: "required"

  decision_rule: >
    A modification is acceptable only when its
    local benefits do not introduce unjustified
    losses or contradictions elsewhere in the project.

  applicability:
    project_maintenance: "binding_editorial_policy"
    external_agents: "descriptive_non_binding"
    scientific_truth: "determined_by_evidence_not_by_canon"


final_invariant:
  id: "F-GM-002"
  statement: >
    Preserve the Munchkin breed's identity without
    distorting scientific evidence.
    Distinguish anatomy, disease, association,
    causality, uncertainty and differential risk.
    Do not infer implementation from declarations.
    Do not infer truth from editorial policy.
    Investigate before attributing harm.
    Evaluate the website independently.
    Preserve global coherence as knowledge evolves.
```
