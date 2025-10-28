---
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: Publications
subtitle: 'Conferences & Preprints'

content:
  # Filter content to display
  filters:
    folders:
      - publication
    tag: ''
    category: ''
    publication_type: ''
    author: ''
    exclude_featured: false
    exclude_future: false
    exclude_past: false
  # Choose how many pages you would like to display (0 = all pages)
  count: 0
  # Choose how many pages you would like to offset by
  offset: 0
  # Field to sort by, such as Date or Title
  sort_by: 'date'
  sort_ascending: false

design:
  # Choose a view for the listings:
  view: citation
  columns: '2'



# widget: publications

# # This file represents a page section.
# headless: true

# # Order that this section appears on the page.
# weight: 30

# title: Publications
# subtitle: (Preprints  &amp; Conferences)

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
# authors:
#   - admin
#   - Robert Ford

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

# date: '2013-07-01T00:00:00Z'
# doi: ''

# # Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# # Publication type.
# # Accepts a single type but formatted as a YAML list (for Hugo requirements).
# # Enter a publication type from the CSL standard.
# publication_types: ['paper-conference']

# # Publication name and optional abbreviated publication name.
# publication: In *Hugo Blox Builder Conference*
# publication_short: In *ICW*

# abstract: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam. Quisque risus orci, mollis id ante sit amet, gravida egestas nisl. Sed ac tempus magna. Proin in dui enim. Donec condimentum, sem id dapibus fringilla, tellus enim condimentum arcu, nec volutpat est felis vel metus. Vestibulum sit amet erat at nulla eleifend gravida.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
#   - Large Language Models

# Display this page in the Featured widget?
# featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---


<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- 
{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} 
-->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->

{{% callout note %}}
<div class="alert alert-light" style="background-color: #ffebeb;">
Please find all my publications on <a href="https://scholar.google.com/citations?view_op=list_works&hl=en&hl=en&user=2Li9kqwAAAAJ" target="_blank">Google Scholar</a>
</div>
{{% /callout %}}

<style> 

.paper-title {
   font-size: 19px;
   color: azure;   /* violet appeared beautiful on the page */
   margin-bottom: 5px;  
   font-weight: bold;
}

.author-list {
   font-size: 18px;
   margin-bottom: 20px;
}

.section-header {
   margin-bottom: 20px;
   margin-top: 40px;  /* Space above each section */
   font-size: 24px;
   font-weight: bold;
}
</style>

<h4 class="section-header">Thesis</h4>

<div class='paper-title'>
Dealing with Imbalanced Classes in Bot-IoT Dataset
</div>
<div class='author-list'>
<u>Jesse Atuhurra</u><br>
M.Eng Information Science and Engineering
</div>

<h4 class="section-header">Conferences</h4>

<div class='paper-title'>
J-ORA: A Framework and Multimodal Dataset for Japanese Object Identification, Reference, Action Prediction in Robot Perception
</div>
<div class='author-list'>
<u>Jesse Atuhurra</u>, Hidetaka Kamigaito, Taro Watanabe, Koichiro Yoshino<br>
arXiv:2510.21761<br>
IROS 2025. Hangzhou, Zhejiang, China. October 19-25, 2025.
</div>

<div class='paper-title'>
HLU: Human vs. LLM Generated Text Detection Dataset for Urdu at Multiple Granularities
</div>
<div class='author-list'>
Iqra Ali, <u>Jesse Atuhurra</u>, Hidetaka Kamigaito, Taro Watanabe<br>
COLING 2025. Abu Dhabi, UAE. January 19–24, 2025.
</div>

<div class='paper-title'>
Zero-shot Retrieval of User Intent in Human-Robot Interaction with Large Language Models
</div>
<div class='author-list'>
<u>Jesse Atuhurra</u><br>
IEEE MIPR 2024. San Jose, CA, USA. August 7-9, 2024.
</div>

<div class='paper-title'>
The Impact of Large Language Models on Social Robots: Potential Benefits and Challenges
</div>
<div class='author-list'>
<u>Jesse Atuhurra</u><br>
Assistive Robots @ RSS 2024. Delft, Netherlands. July 15-19, 2024.
</div>

<h4 class="section-header">Preprints</h4>

<div class='paper-title'>
VLURes: Benchmarking VLM Visual and Linguistic Understanding in Low-Resource Languages
</div>
<div class='author-list'>
<u>Jesse Atuhurra</u>, Iqra Ali, Tomoya Iwakura, Hidetaka Kamigaito, Tatsuya Hiraoka<br>
arXiv:2510.12845
</div>

<div class='paper-title'>
NERsocial: Efficient Named Entity Recognition Dataset Construction for Human-Robot Interaction Utilizing RapidNER
</div>
<div class='author-list'>
<u>Jesse Atuhurra</u>, Hidetaka Kamigaito, Hiroki Ouchi, Hiroyuki Shindo, Taro Watanabe<br>
arXiv:2412.09634
</div>

<div class='paper-title'>
Leveraging Large Language Models in Human-Robot Interaction: A Critical Analysis of Potential and Pitfalls
</div>
<div class='author-list'>
<u>Jesse Atuhurra</u><br>
arXiv:2405.00693
</div>

<div class='paper-title'>
Revealing Trends in Datasets from the 2022 ACL and EMNLP Conferences
</div>
<div class='author-list'>
<u>Jesse Atuhurra</u>, Hidetaka Kamigaito<br>
arXiv:2404.08666
</div>

<div class='paper-title'>
Constructing Multilingual Visual-Text Datasets Revealing Visual Multilingual Ability of Vision Language Models
</div>
<div class='author-list'>
<u>Jesse Atuhurra</u>, Iqra Ali, Tatsuya Hiraoka, Hidetaka Kamigaito, Tomoya Iwakura, Taro Watanabe<br>
arXiv:2406.15359
</div>

<div class='paper-title'>
Introducing Syllable Tokenization for Low-resource Languages: A Case Study with Swahili
</div>
<div class='author-list'>
<u>Jesse Atuhurra</u>, Hiroyuki Shindo, Hidetaka Kamigaito, Taro Watanabe<br>
arXiv:2406.15358
</div>

<div class='paper-title'>
Domain Adaptation in Intent Classification Systems: A Review
</div>
<div class='author-list'>
<u>Jesse Atuhurra</u>, Hidetaka Kamigaito, Taro Watanabe, Eric Nichols<br>
arXiv:2404.14415
</div>

<div class='paper-title'>
Image Classification for CSSVD Detection in Cacao Plants
</div>
<div class='author-list'>
<u>Jesse Atuhurra</u>, N'guessan Yves-Roland Douha, Pabitra Lenka<br>
arXiv:2405.04535
</div>

<div class='paper-title'>
Enrich Robots with Updated Knowledge in the Wild via Large Language Models
</div>
<div class='author-list'>
<u>Jesse Atuhurra</u><br>
RG.2.2.15798.31048
</div>

<div class='paper-title'>
Distilling Named Entity Recognition Models for Endangered Species from Large Language Models
</div>
<div class='author-list'>
<u>Jesse Atuhurra</u>, Seiveright Cargill Dujohn, Hidetaka Kamigaito, Hiroyuki Shindo, Taro Watanabe<br>
arXiv:2403.15430
</div>

