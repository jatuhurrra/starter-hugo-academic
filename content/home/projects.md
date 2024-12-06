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
</div>

<h4 class="project-title">Large-scale NER Dataset Construction</h4>

<div class='project-details'>
We introduce RapidNER, a framework for efficiently creating named entity recognition (NER) datasets for new domains, with a focus on human-robot interaction. The framework operates through three key steps: 1) extracting domain-specific knowledge from Wikidata using instance-of and subclass-of relations, 2) collecting diverse texts from Wikipedia, Reddit, and Stack Exchange, and 3) implementing an efficient annotation scheme using Elasticsearch. We demonstrate the framework by creating NERsocial, a new dataset containing 153K tokens, 134K entities, and 99.4K sentences across six entity types relevant for social interactions: drinks, foods, hobbies, jobs, pets, and sports. When fine-tuned on NERsocial, transformer models like BERT, RoBERTa, and DeBERTa-v3 achieve F1-scores above 95%. The framework significantly reduces dataset creation time and effort while maintaining high quality, as evidenced by a 90.6% inter-annotator agreement.
</div>

<h4 class="project-title">Open-world Object Recognition</h4>

<div class='project-details'>
One of the hardest tasks for robots is to recognize unseen objects, relevant to inform the execution of tasks in the robot's vicinity. In this project we leverage state-of-the-art foundaiton models to enhance the robot's ability to perceive the world around it, and then perfom complex reasoning tasks. 
</div>

<h4 class="project-title">Visual Semantic Understanding</h4>

<div class='project-details'>
We introduce nine vision-and-language (VL) tasks and constructs multilingual datasets in English, Japanese, Swahili, and Urdu to evaluate vision language models (VLMs), with a particular focus on GPT-4V. The tasks include object recognition, scene understanding, relationship understanding, semantic segmentation, image captioning, image-text matching, unrelatedness (a newly introduced task), entity extraction, and visual question answering. We collected 1,000 image-text pairs from Wikinews and Wikipedia across 10 categories, selected 200 pairs for detailed analysis, and used GPT-4V to generate answers and rationales for each task in all four languages. Native speakers evaluated the quality of translations and model outputs using a 5-point Likert scale. The results showed that GPT-4V performed best in English (94.81% accuracy), followed by Urdu (90.56%), Japanese (88.09%), and Swahili (83.57%), with better performance on image-only tasks compared to tasks requiring both image and text understanding. This project contributes to the new frontier of omprehensive VL analysis in Swahili and Urdu languages.
</div>

<h4 class="project-title">On-the-fly Intent Recognition</h4>

<div class='project-details'>
This research project investigates zero-shot user intent classification in human-robot interaction using large language models (LLMs). We created a new dataset containing 33,812 sentences across four languages (English, Japanese, Swahili, and Urdu) and six intent classes (pet, food, job, hobby, sport, and drink). We leveraged Wikidata knowledge graphs to extract sentences from Wikipedia articles and tested six different prompting methods with various LLMs including GPT-4, Claude 3, and Gemma. The experiments demonstrated that well-crafted prompts, utilizing adavanced prompting methods, enabled LLMs to achieve high accuracy in intent classification without requiring fine-tuning or example data, with GPT-4 and Claude 3 achieving nearly 95% accuracy across all languages. The study also showed that retrieval-augmented generation (RAG) improved classification performance, and simple zero-shot prompting was sufficient for achieving competitive results, especially with more capable LLMs like GPT-4 and Claude 3 Opus.
</div>