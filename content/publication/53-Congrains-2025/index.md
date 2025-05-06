---
title: "CCS‐Consensuser: A Haplotype‐Aware Consensus Generator for PacBio Amplicon Sequences"
authors:
- Carlos Congrains
- Forest Bremer
- Julian Dupuis
- Norman Barr
- Ivonne Garzón-Orduña
- Daniel Rubinoff
- admin
- Michael San Jose
- Kimberley Morris
- Angela Kauwe
- Scott Geib
author_notes: ""
date: "2025-01-01T00:00:00Z"
doi: "https://doi.org/10.1111/1755-0998.14113"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Molecular Ecology Resources"
publication_short: ""

abstract: "DNA sequencing technology has undergone substantial improvements in recent years, to the extent that Third Generation Sequencing platforms are capable of massively generating long-reads. Amplicon sequencing has been among the most popular techniques due to its wide application in diverse fields of biological sciences. However, there is a lack of software specifically designed to analyse intra-individual genetic variation using amplicon long-read data. Here, we present CCSconsensuser, an end-to-end pipeline that generates consensus sequences from amplicon sequencing using high-fidelity reads produced by PacBio circular consensus sequencing (CCS). We evaluated the concordance of the results produced using CCS + CCS-consensuser and other sequencing platforms (Illumina and Sanger), as well as accuracy using a simulated dataset. This assessment showed that CCS amplicon data coupled with CCS-consensuser can produce high-quality sequences (PHRED > 30). The pipeline resulted in high proportions of identical sequence bins for real data, achieving up to 94.94% concordance with COI Sanger sequences and 92.61% with nuclear loci Illumina sequences (considering heterozygous loci), and 95.55% with a fully phased nuclear simulated dataset. Furthermore, our pipeline can be used to detect heteroplasmy in mtDNA, cross-contamination, resolve the phase of nuclear genes in diploid organisms, and conceivably for multi-copy gene systems such as rDNA. These results not only support its potential for application in studies using haploid data such as DNA barcoding, but also demonstrate its unique capacity to explore within individual haplotype variation. Therefore, our strategy shows promise for a broad range of applications in biology and medicine that have been challenging to assess using traditional techniques.
"

# Summary. An optional shortened abstract.
summary: "We present CCSconsensuser, an end-to-end pipeline that generates consensus sequences from amplicon sequencing using high-fidelity reads produced by PacBio circular consensus sequencing (CCS)."

tags:
- Source Themes
featured: true

# links:
# - name: ""
#   url: ""
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
image:
  caption: 'Image credit: [C. Congrains](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
