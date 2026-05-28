# HealthNLP

HealthNLP .org is home to natural language processing (NLP) projects related to health such as mining the clinical narrative of the electronic medical record.  We are dedicated to making state of the art clinical NLP projects publicly available for those on the cutting edge of biomedical research and AI.  

At this time HealthNLP has over 20 public repositories.  Several repositories contain tools that are reuseable for any project with specific needs, such as the HNLP-TimeNorm tool that creates normalized ISO 8601 codes from raw text temporal expressions.  Other repositories contain code and resources developed for singular purpose with specific data, but can be adapted for other sites and data.  For instance, the LGT-SACT project that extracts timelines for Systemic Anti-Cancer Therapies can be given a different tokenizer and different LLM prompt to generate timelines for other event types.

At a glance, the HealthNLP repositories include:

[HNLP-TimeNorm](https://github.com/HealthNLPorg/hnlp-timenorm)
: Provides models for finding natural language expressions of dates and times and converting them to a normalized form.

[LGT-SACT](https://github.com/HealthNLPorg/lgt-sact)
: Extracts and normalizes temporal information from clinical notes using fine-tuned LLMs. Specifically, Systemic Anti-Cancer Therapy (SACT) Timelines.

[chemoTimelines Docker](https://github.com/HealthNLPorg/chemoTimelinesBaselineSystem)
: Dockerizable source code for the baseline system for the [Chemotherapy Treatment Timelines Extraction from the Clinical Narrative](https://sites.google.com/view/chemotimelines2024/task-descriptions) shared task.

[chemoTimelines Eval](https://github.com/HealthNLPorg/chemoTimelinesEval)
: Evaluation code for [ChemoTimelines 2025](https://sites.google.com/view/chemotimelines2024/task-descriptions).

[rt-ctae-eval](https://github.com/HealthNLPorg/rt-ctae-eval)
: Evaluation and annotation adjudication tool for the ACS-CTAE Label Studio project, using [lseval](https://github.com/HealthNLPorg/lseval) as a backend.

[lseval](https://github.com/HealthNLPorg/lseval)
: Basic version of core functionality we use with [anaforatools](https://github.com/bethard/anaforatools) but for Label Studio annotations.

[radiotherapy_end2end](https://github.com/HealthNLPorg/radiotherapy_end2end)
: An end-to-end natural language processing system for automatically extracting radiotherapy events from clinical texts.

[ctae_pre_annotation](https://github.com/HealthNLPorg/ctae_pre_annotation)
: cTAKES module for generating LabelStudio pre-annotation JSON from clinical text for the CTAE project.

[acs-lung-cns-eda](https://github.com/HealthNLPorg/acs-lung-cns-eda)
: EDA/Computing note counts for ACS project lung cancer patients with at least one CNS adverse event.

[acs-lung-cardiac-eda](https://github.com/HealthNLPorg/acs-lung-cardiac-eda)
: EDA/Computing note counts for ACS project lung cancer patients with at least one cardiac event.

[bwrobitterman_label_studio_setup](https://github.com/HealthNLPorg/bwrobitterman_label_studio_setup)
: Repository for managing the Label Studio startup scripts etc. 

[rt-signature-docker](https://github.com/HealthNLPorg/rt-signature-docker)
: DeepPhe RT Signature Docker with fixes for running and Label Studio output.


### Associated Projects
Some of our projects are modern upgrades to other public projects such as [Apache cTAKES](https://github.com/apache/ctakes) and [DeepPhe](https://github.com/DeepPhe).
