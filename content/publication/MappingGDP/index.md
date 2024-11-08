---
title: "Machine learning-based economic development mapping from multi-source open geospatial data"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Cao, Rui
- Tu, Wei
- Cai, Jixuan
- Zhao, Tianhong
- Xiao, Jie
- Cao, Jinzhou
- admin
- Su, Hanjing


# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-05-01T00:00:00Z"
doi: "10.1016/j.compenvurbsys.2018.02.006"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *ISPRS Journal of Photogrammetry and Remote Sensing*
publication_short: In *ISPRS Ann. Photogramm. Remote Sens*

abstract: Timely and accurate socioeconomic indicators are the prerequisite for smart social governance. For example, the level of economic development and the structure of population are important statistics for regional or national policy-making. However, the collection of these characteristics usually depends on demographic and social surveys, which are time- and labor-intensive. To address these issues, we propose a machine learning-based approach to estimate and map the economic development from multi-source open available geospatial data, including remote sensing imagery and OpenStreetMap road networks. Specifically, we first extract knowledge-based features from different data sources; then the multi-view graphs are constructed through different perspectives of spatial adjacency and feature similarity; and a multi-view graph neural network (MVGNN) model is built on them and trained in a self-supervised learning manner. Then, the handcrafted features and the learned graph representations are combined to estimate the regional economic development indicators via random forest models. Taking China’s county-level gross domestic product (GDP) as an example, extensive experiments have been conducted and the results demonstrate the effectiveness of the proposed method, and the combination of the knowledge-based and learning-based features can significantly outperform baseline methods. Our proposed approach can advance the goal of acquiring timely and accurate socioeconomic variables through widely accessible geospatial data, which has the potential to extend to more social indicators and other geographic regions to support smart governance and policy-making in the future.
# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: False

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
