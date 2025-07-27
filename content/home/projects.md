---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: projects

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Projects
subtitle: 'Descriptions & Datasets'

design:
  columns: '2'

# This is the first attempt at writing a project slide.

---

<style> 

.project-title {
   margin-bottom: 5px;
   margin-top: 20px;  /* Space above each section */
   font-size: 20px;
   font-weight: bold;
   color: violet;   /* violet appeared beautiful on the page */ 
}

.project-details {
   margin-bottom: 10px;
   margin-top: 10px;  /* Space above each section */
   font-size: 16px;
}
</style>


<h4 class="project-title">Distillation of Bio-species Infomation from LLMs</h4>

<div class='project-details'>
This project focuses on creating datasets for Named Entity Recognition (NER) and Relation Extraction (RE) in the domain of endangered species by distilling knowledge from GPT-4. We generated synthetic data about four classes of endangered species (amphibians, arthropods, birds, and fishes) using GPT-4, which was then verified by humans using external knowledge bases like IUCN and Wikipedia. The final dataset contains 3.6K sentences evenly split between NER and RE tasks, with annotations for species, habitat, feeding, and breeding entities, along with their relationships. We fine-tuned various BERT models (standard BERT, BioBERT, and PubMedBERT) on this dataset, with PubMedBERT achieving the best performance at 94.14% F1-score. Last, we demonstrated that GPT-4 performs better than UniversalNER-7B in zero-shot NER tasks on both easy and hard examples, confirming GPT-4's effectiveness as a teacher model for knowledge distillation in this domain. <br>
[<a href="https://arxiv.org/abs/2403.15430">PDF</a>] [<a href="https://github.com/jatuhurrra/DistillationBiospeciesLLM/">Code</a>]
[<a href="https://huggingface.co/datasets/atamiles/DistillationBiospeciesLLM">Data (HF)</a>] 
</div>

<h4 class="project-title">Large-scale NER Dataset Construction</h4>

<div class='project-details'>
We introduce RapidNER, a framework for efficiently creating named entity recognition (NER) datasets for new domains, with a focus on human-robot interaction. The framework operates through three key steps: 1) extracting domain-specific knowledge from Wikidata using instance-of and subclass-of relations, 2) collecting diverse texts from Wikipedia, Reddit, and Stack Exchange, and 3) implementing an efficient annotation scheme using Elasticsearch. We demonstrate the framework by creating NERsocial, a new dataset containing 153K tokens, 134K entities, and 99.4K sentences across six entity types relevant for social interactions: drinks, foods, hobbies, jobs, pets, and sports. When fine-tuned on NERsocial, transformer models like BERT, RoBERTa, and DeBERTa-v3 achieve F1-scores above 95%. The framework significantly reduces dataset creation time and effort while maintaining high quality, as evidenced by a 90.6% inter-annotator agreement.   <br>
[<a href="http://arxiv.org/abs/2412.09634">PDF</a>] [<a href="https://github.com/jatuhurrra/rapidner">Code</a>]  
[<a href="https://huggingface.co/datasets/atamiles/NERsocial">Data (HF)</a>] [<a href="https://jatuhurrra.github.io/Rapid/">Website</a>] 
</div>

<h4 class="project-title">J-ORA: A Robot Perception Framework for Japanese</h4>

<div class='project-details'>
J-ORA is a novel benchmark and dataset designed to advance research at the intersection of robotics, vision, and language understanding in non-English settings, specifically Japanese. Developed through a collaboration between NAIST and the RIKEN Guardian Robot Project, J-ORA addresses key challenges in robot perception, including ambiguity in object reference, dynamic scene understanding, and multimodal instruction grounding. The benchmark provides a richly annotated multimodal dataset consisting of 142 real-world image-dialogue pairs, captured from a robot’s egocentric viewpoint. Each instance includes detailed object-attribute annotations, dialogue utterances in Japanese, bounding boxes, and grounded references, enabling evaluation across three core tasks: Object Identification, Reference Resolution, and Next Action Prediction. J-ORA further integrates real-world dynamics such as object occlusions, overlapping visual features, and temporal context to evaluate fine-grained multimodal reasoning. The dataset supports training and evaluation of Vision-Language Models (VLMs) under zero-shot and fine-tuned settings, and includes comparisons across proprietary models (e.g., GPT-4o, Gemini) and open-source Japanese VLMs. By addressing gaps in multilingual and grounded robotics datasets, J-ORA lays the foundation for building more perceptive, culturally adaptive, and interactive domestic service robots.
[<a href="https://jatuhurrra.github.io/J-ORA/">Code</a>] 
[<a href="https://huggingface.co/datasets/atamiles/J-ORA/">Data (HF)</a>] [<a href="https://jatuhurrra.github.io/OpenPerception/">Website</a>] 
</div>

<h4 class="project-title">Visual-Language (VLURes) Benchmark</h4>

<div class='project-details'>
VLURes is a comprehensive multilingual benchmark designed to evaluate and advance the capabilities of Vision-Language Models (VLMs) across diverse linguistic and cultural contexts. It introduces eight vision-and-language tasks—ranging from Scene Understanding, Relation Understanding, Semantic Segmentation, Image Captioning, Image-Text Matching, Visual Question Answering, to novel tasks like Unrelatedness Detection and Multilingual Transfer—spanning both image-only and image-text modalities. Unlike existing benchmarks that focus primarily on English (or occasionally Chinese), VLURes includes four languages: English (En), Japanese (Jp), Swahili (Sw), and Urdu (Ur), with a special emphasis on low-resource languages that are often underrepresented in AI research. The benchmark contains 1,000 high-quality image-text pairs per language, each embedded in article-level long-form text, allowing rigorous testing of discourse-level grounding and cross-modal reasoning. VLURes also evaluates zero-shot and one-shot generalization, with and without rationales, and introduces fine-tuning experiments to assess language transfer. Through extensive evaluation of state-of-the-art proprietary and open-source VLMs (e.g., GPT-4o, Gemini, Llava, Qwen2VL), VLURes reveals persistent performance gaps, especially in Swahili and Urdu, underscoring the urgent need for equitable, globally aware multimodal AI.  <br>
[<a href="https://arxiv.org/abs/2406.15359">PDF</a>] [<a href="https://github.com/jatuhurrra/VLURes/">Code</a>] 
[<a href="https://huggingface.co/datasets/atamiles/VLURes/">Data (HF)</a>] [<a href="https://jatuhurrra.github.io/VLURes/">Website</a>] 
</div>

<h4 class="project-title">Zero-shot Intent Recognition</h4>

<div class='project-details'>
This research project investigates zero-shot user intent classification in human-robot interaction using large language models (LLMs). We created a new dataset containing 33,812 sentences across four languages (English, Japanese, Swahili, and Urdu) and six intent classes (pet, food, job, hobby, sport, and drink). We leveraged Wikidata knowledge graphs to extract sentences from Wikipedia articles and tested six different prompting methods with various LLMs including GPT-4, Claude 3, and Gemma. The experiments demonstrated that well-crafted prompts, utilizing adavanced prompting methods, enabled LLMs to achieve high accuracy in intent classification without requiring fine-tuning or example data, with GPT-4 and Claude 3 achieving nearly 95% accuracy across all languages. The study also showed that retrieval-augmented generation (RAG) improved classification performance, and simple zero-shot prompting was sufficient for achieving competitive results, especially with more capable LLMs like GPT-4 and Claude 3 Opus.  <br>
[<a href="https://www.researchgate.net/publication/381548253_Zero-shot_Retrieval_of_User_Intent_in_Human-Robot_Interaction_with_Large_Language_Models">PDF</a>] 
[<a href="https://github.com/jatuhurrra/LLM-for-Intent-Classification">Code</a>] 
[<a href="https://huggingface.co/datasets/atamiles/ZeroshotIntentClassification">Data (HF)</a>] 
</div>