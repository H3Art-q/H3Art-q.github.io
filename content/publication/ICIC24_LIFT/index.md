---
title: 'LIFT: Discriminant Classification Approach of Malware Family on Time Consistent Open Set'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here,
# and it will be replaced with their full name and linked to their profile.
authors:
    - Yuxia Sun
    - Siyi Pan
    - Yang Yang
    - Ziying Huo
    - admin

# Author notes (optional)
author_notes:
  - 'Corresponding Author'

date: '2024-08-01T00:00:00Z'
doi: 'https://doi.org/10.1007/978-981-97-5663-6_4'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-08-23T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: International Conference on Intelligent Computing
publication_short: ICIC (CCF-C)

abstract: In recent years, the rapid evolution of malware, including the emergence of new variants and families, has posed a significant challenge to antivirus defenses. To address this, some approaches to Malware Open Set Recognition (MOSR) have been introduced, aiming to categorize known malware families and detect new ones. Nevertheless, current MOSR research tends to neglect the effect of time inconsistency within datasets, which can result in an overly optimistic evaluation of MOSR effectiveness. To mitigate this issue, a new MOSR method named LIFT has been developed, focusing on a time-consistent division of malware datasets. LIFT employs the self-attention mechanism to understand the correlations among known malware families. It also integrates a linear probe and a unique regularization term to enhance the separability of deep representations. In the recognition phase, LIFT implements a feature truncation tactic to adjust the dimensional values in the samples' deep representation vectors, thereby enhancing their distinctiveness. Tests on time-consistent open datasets demonstrate that LIFT significantly outperforms existing techniques in open set recognition efficiency.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Malware classification
  - Time-consistent dataset
  - Open set recognition
  - Discriminative model

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://link.springer.com/content/pdf/10.1007/978-981-97-5663-6_4.pdf?pdf=inline%20link'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---