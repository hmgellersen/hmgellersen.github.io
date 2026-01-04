---
title: 'Systematic evaluation of fMRI data-processing pipelines for consistent functional connectomics'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Andrea I. Luppi
  - admin 
  - Zhen-Qi Liu  
  - Alexander R. D. Peattie  
  - Anne E. Manktelow  
  - David K. Menon  
  - Stavros I. Dimitriadis  
  - Emmanuel A. Stamatakis  

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-06-04'
doi: 'https://doi.org/10.1038/s41467-024-48781-5'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ['journal-article']

# Publication name and optional abbreviated publication name.
publication: _Nature Communications_
publication_short: ''

abstract: Functional interactions between brain regions can be viewed as a network, enabling neuroscientists to investigate brain function through network science. Here, we systematically evaluate 768 data-processing pipelines for network reconstruction from resting-state functional MRI, evaluating the effect of brain parcellation, connectivity definition, and global signal regression. Our criteria seek pipelines that minimise motion confounds and spurious test-retest discrepancies of network topology, while being sensitive to both inter-subject differences and experimental effects of interest. We reveal vast and systematic variability across pipelines’ suitability for functional connectomics. Inappropriate choice of data-processing pipeline can produce results that are not only misleading, but systematically so, with the majority of pipelines failing at least one criterion. However, a set of optimal pipelines consistently satisfy all criteria across different datasets, spanning minutes, weeks, and months. We provide a full breakdown of each pipeline’s performance across criteria and datasets, to inform future best practices in functional connectomics.


# Summary. An optional shortened abstract.
summary: We benchmarked >750 data-processing pipelines to construct a functional connectivity network from fMRI data.

tags:
  - benchmarking
  - fMRI
  - network science

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://hmgellersen.github.io/publication/luppi2024b_natcomm.pdf'
url_cite: 'https://hmgellersen.github.io/publication/luppi2024b_natcomm/cite.bib'
url_code: 'https://github.com/andrealuppi/Trustworthy-Functional-Connectomics'
url_dataset: '' # 'https://github.com/HugoBlox/hugo-blox-builder'
url_poster: ''
url_project: ''
url_slides: ''
url_source: '' #'https://github.com/HugoBlox/hugo-blox-builder'
url_video: '' #'https://youtube.com'

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
projects: []
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: '' #example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
