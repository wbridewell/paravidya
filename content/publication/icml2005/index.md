---
title: 'Reducing Overfitting in Process Model Induction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Narges Bani Asadi
  - Pat Langley
  - Ljupčo Todorovski

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2005-08-07'
doi: '10.1145/1102351.1102362'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 22nd International Conference on Machine Learning*
publication_short: In *ICML 2005*

abstract: "In this paper, we review the paradigm of inductive process modeling, which uses background knowledge about possible component processes to construct quantitative models of dynamical systems. We note that previous methods for this task tend to overfit the training data, which suggests ensemble learning as a likely response. However, such techniques combine models in ways that reduce comprehensibility, making their output much less accessible to domain scientists. As an alternative, we introduce a new approach that induces a set of process models from different samples of the training data and uses them to guide a final search through the space of model structures. Experiments with synthetic and natural data suggest this method reduces error and decreases the chance of including unnecessary processes in the model. We conclude by discussing related work and suggesting directions for additional research."

# Summary. An optional shortened abstract.
summary: "We note that previous methods for inductive process modeling tend to overfit the training data, which suggests ensemble learning as a likely response. We introduce a new approach that induces a set of process models from different samples of the training data and uses them to guide a final search through the space of model structures."

tags: [machine learning, ensemble learning]

# Display this page in the Featured widget?
featured: false

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
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - inductive-process-modeling

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---