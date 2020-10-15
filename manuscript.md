---
author-meta:
- "Benjam\xEDn J. S\xE1nchez"
- Daniela C. Soto
bibliography:
- content/manual-references.json
date-meta: '2020-10-15'
header-includes: "<!--\nManubot generated metadata rendered from header-includes-template.html.\nSuggest improvements at https://github.com/manubot/manubot/blob/master/manubot/process/header-includes-template.html\n-->\n<meta name=\"dc.format\" content=\"text/html\" />\n<meta name=\"dc.title\" content=\"Manuscript Title\" />\n<meta name=\"citation_title\" content=\"Manuscript Title\" />\n<meta property=\"og:title\" content=\"Manuscript Title\" />\n<meta property=\"twitter:title\" content=\"Manuscript Title\" />\n<meta name=\"dc.date\" content=\"2020-10-15\" />\n<meta name=\"citation_publication_date\" content=\"2020-10-15\" />\n<meta name=\"dc.language\" content=\"en-US\" />\n<meta name=\"citation_language\" content=\"en-US\" />\n<meta name=\"dc.relation.ispartof\" content=\"Manubot\" />\n<meta name=\"dc.publisher\" content=\"Manubot\" />\n<meta name=\"citation_journal_title\" content=\"Manubot\" />\n<meta name=\"citation_technical_report_institution\" content=\"Manubot\" />\n<meta name=\"citation_author\" content=\"Benjam\xEDn J. S\xE1nchez\" />\n<meta name=\"citation_author_institution\" content=\"Department of Bioengineering, Technical University of Denmark, Kgs. Lyngby, 2800, Denmark\" />\n<meta name=\"citation_author_orcid\" content=\"0000-0001-6093-4110\" />\n<meta name=\"twitter:creator\" content=\"@BenjaSanchez\" />\n<meta name=\"citation_author\" content=\"Daniela C. Soto\" />\n<meta name=\"citation_author_institution\" content=\"Genome Center, MIND Institute, and Department of Biochemistry &amp; Molecular Medicine, Davis, CA 95616,USA\" />\n<meta name=\"citation_author_orcid\" content=\"0000-0002-6292-655X\" />\n<link rel=\"canonical\" href=\"https://computer-aided-biotech.github.io/better-cb/\" />\n<meta property=\"og:url\" content=\"https://computer-aided-biotech.github.io/better-cb/\" />\n<meta property=\"twitter:url\" content=\"https://computer-aided-biotech.github.io/better-cb/\" />\n<meta name=\"citation_fulltext_html_url\" content=\"https://computer-aided-biotech.github.io/better-cb/\" />\n<meta name=\"citation_pdf_url\" content=\"https://computer-aided-biotech.github.io/better-cb/manuscript.pdf\" />\n<link rel=\"alternate\" type=\"application/pdf\" href=\"https://computer-aided-biotech.github.io/better-cb/manuscript.pdf\" />\n<link rel=\"alternate\" type=\"text/html\" href=\"https://computer-aided-biotech.github.io/better-cb/v/88520516ba8fc6c44457ca9cd570bdfe8da7e459/\" />\n<meta name=\"manubot_html_url_versioned\" content=\"https://computer-aided-biotech.github.io/better-cb/v/88520516ba8fc6c44457ca9cd570bdfe8da7e459/\" />\n<meta name=\"manubot_pdf_url_versioned\" content=\"https://computer-aided-biotech.github.io/better-cb/v/88520516ba8fc6c44457ca9cd570bdfe8da7e459/manuscript.pdf\" />\n<meta property=\"og:type\" content=\"article\" />\n<meta property=\"twitter:card\" content=\"summary_large_image\" />\n<link rel=\"icon\" type=\"image/png\" sizes=\"192x192\" href=\"https://manubot.org/favicon-192x192.png\" />\n<link rel=\"mask-icon\" href=\"https://manubot.org/safari-pinned-tab.svg\" color=\"#ad1457\" />\n<meta name=\"theme-color\" content=\"#ad1457\" />\n<!-- end Manubot generated metadata -->"
keywords:
- markdown
- publishing
- manubot
lang: en-US
manubot-clear-requests-cache: false
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
title: Manuscript Title
...






<small><em>
This manuscript
([permalink](https://computer-aided-biotech.github.io/better-cb/v/88520516ba8fc6c44457ca9cd570bdfe8da7e459/))
was automatically generated
from [computer-aided-biotech/better-cb@8852051](https://github.com/computer-aided-biotech/better-cb/tree/88520516ba8fc6c44457ca9cd570bdfe8da7e459)
on October 15, 2020.
</em></small>

## Authors



+ **Benjamín J. Sánchez**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0001-6093-4110](https://orcid.org/0000-0001-6093-4110)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [BenjaSanchez](https://github.com/BenjaSanchez)
    · ![Twitter icon](images/twitter.svg){.inline_icon}
    [BenjaSanchez](https://twitter.com/BenjaSanchez)<br>
  <small>
     Department of Bioengineering, Technical University of Denmark, Kgs. Lyngby, 2800, Denmark
  </small>

+ **Daniela C. Soto**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0002-6292-655X](https://orcid.org/0000-0002-6292-655X)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [dcsoto](https://github.com/dcsoto)<br>
  <small>
     Genome Center, MIND Institute, and Department of Biochemistry & Molecular Medicine, Davis, CA 95616,USA
  </small>



## Abstract {.page_break_before}

This should be the abstract.


## Introduction

- Importance of computation in biological research and scope.
- Importance to reproducibility in computational biology.
- Mentioning previous literature and some of their major takeaways and topics not fully covered in here (what kind of languages to learn, advanced text editors/IDEs,
- The computational biology best-practices continuum: reproducibility at the personal level, sharing our research with others and over time.
- Addressing the audience: computational biologists researchers – data analysts, workflow designers, software developers, mathematical modelers, etc.
- Structure of this manuscript: mention Figure 1 and Figure 2.
  - **Figure 1:** Funnel structure for better computational biology.
  - **Figure 2:** Types of computational biology projects per level.


## Level 1: Personal Research

Goal: How should you manage your computational biology project?

Topics:
- Literate programming: R Markdown, Jupyter Notebooks
- Version control: Git / GitHub (commits)
- Software versioning and environment managers (Conda, python-env)
- Modularize, snippets
- Coding style: variable naming, linter, pep8, commenting
- Programming practices: paradigms (object-oriented, procedural), assertions, pair-programming


## Level 2: Collaboration

Goal: How to allow your collaborators to reproduce and interact with your research/software?

Topics:
- Sharing notebooks: R Markdowns and Jupyter Notebooks (Binder, Google CoLab)
- Sharing apps: Shiny apps, Dashboard.
- GitHub (branching, pull requests)
- Workflow automation: Snakemake (NextFlow, Make, Bash script)
- Sharing data and metadata


## Level 3: Community

Goal: How to develop and maintain a computational biology project with community feedback over time?

Topics:
- GitHub releases and semantic versioning
- Git Flow, GitHub Issues
- Continuous integration and unit tests
- Dependencies per user: pip-tools
- Sharing software as Python packages, Conda/Bioconda or containers (Docker, Singularity)
- Include license (MIT) and DOIs
- Documentation: read the docs.


## Case studies

- Example of computational biology project 1: RNA-seq analysis (workflow)
- Example of computational biology project 2: Genome-scale metabolic model (systems biology project)
- Example of computational biology project 3: Software development (computational tool)


## Conclusion

Pending


## Acknowledgments

Pending


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
