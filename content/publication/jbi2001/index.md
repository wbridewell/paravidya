---
title: 'A Simple Algorithm for Identifying Negated Findings and Diseases in Discharge Summaries'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Wendy W. Chapman
  - admin 
  - Paul Hanbury
  - Gregory F. Cooper
  - Bruce G. Buchanan

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2001-10-01'
doi: '10.1006/jbin.2001.1029'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Journal of Biomedical Informatics
publication_short: JBI

abstract: "Narrative reports in medical records contain a wealth of information that may augment structured data for managing patient information and predicting trends in diseases. Pertinent negatives are evident in text but are not usually indexed in structured databases. The objective of the study reported here was to test a simple algorithm for determining whether a finding or disease mentioned within narrative medical reports is present or absent. We developed a simple regular expression algorithm called NegEx that implements several phrases indicating negation, filters out sentences containing phrases that falsely appear to be negation phrases, and limits the scope of the negation phrases. We compared NegEx against a baseline algorithm that has a limited set of negation phrases and a simpler notion of scope. In a test of 1235 findings and diseases in 1000 sentences taken from discharge summaries indexed by physicians, NegEx had a specificity of 94.5% (versus 85.3% for the baseline), a positive predictive value of 84.5% (versus 68.4% for the baseline) while maintaining a reasonable sensitivity of 77.8% (versus 88.3% for the baseline). We conclude that with little implementation effort a simple regular expression algorithm for determining whether a finding or disease is absent can identify a large portion of the pertinent negatives from discharge summaries."


# Summary. An optional shortened abstract.
summary: "We developed a simple regular expression algorithm called NegEx that implements several phrases indicating negation, filters out sentences containing phrases that falsely appear to be negation phrases, and limits the scope of the negation phrases."


tags: [negation, natural language processing, informatics]

# Display this page in the Featured widget?
featured: true

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
  - negex
  - biomedical-informatics

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---