---
title: 'Discovering constraints for inductive process modeling'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ljupčo Todorovski
  - admin
  - Pat Langley

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2012-07-01'
doi: '10.1609/aaai.v26i1.8152'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the Twenty Sixth AAAI Conference on Artificial Intelligence*
publication_short: AAAI

abstract: "Scientists use two forms of knowledge in the construction of explanatory models: generalized entities and processes that relate them; and constraints that specify acceptable combinations of these components. Previous research on inductive process modeling, which constructs models from knowledge and time-series data, has relied on handcrafted constraints. In this paper, we report an approach to discovering such constraints from a set of models that have been ranked according to their error on observations. Our approach adapts inductive techniques for supervised learning to identify process combinations that characterize accurate models. We evaluate the method's ability to reconstruct known constraints and to generalize well to other modeling tasks in the same domain. Experiments with synthetic data indicate that the approach can successfully reconstruct known modeling constraints. Another study using natural data suggests that transferring constraints acquired from one modeling scenario to another within the same domain considerably reduces the amount of search for candidate model structures while retaining the most accurate ones."

# Summary. An optional shortened abstract.
summary: Previous research on inductive process modeling, which constructs models from knowledge and time-series data, has relied on handcrafted constraints. In this paper, we report an approach to discovering such constraints from a set of models that have been ranked according to their error on observations.


tags: [machine learning, ecology, constraints]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'http://www.aaai.org/ocs/index.php/AAAI/AAAI12/paper/view/4952'
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