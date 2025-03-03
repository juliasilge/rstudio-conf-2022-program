---
# Do not edit
talk_id: 22119
talk_slug: tidysynthesis-r-package
talk_type: regular
talk_tags: [modeling, tool]
session_slug: machine-learning
# ---- Edit information below this line ----
# The title of your talk
talk_title: "The tidysynthesis R package"
# A short version of the title, suitable for small displays
talk_title_short: The tidysynthesis R package
# A link to your talk's materials, when ready
talk_materials_url: ~
speakers:
- name: Aaron R. Williams
  affiliation: Urban Institute
  url:
    webpage: https://aaronrwilliams.com/home/
    twitter: https://twitter.com/awunderground
    github: https://github.com/awunderground
    linkedin: https://www.linkedin.com/in/aaronrwilliams100
    affiliation: https://www.urban.org/
  username: aaron_r_williams
  photo: /assets/img/2022Conf/_talks/22119_aaron-r-williams.jpeg
  bio: |+
    Aaron R. Williams is a senior data scientist at the Urban Institute
    where he works on microsimulation models, data imputation methods,
    and expanding access to administrative data with formal privacy and
    synthetic data. Williams leads Urban’s R Users Group and teaches Intro
    to Data Science in the McCourt School of Public Policy at Georgetown
    University.


---

<!-- ABSTRACT ----
Please write abstract below. You may use simple markdown (links, code style, bold, italics)
-->

Society benefits when leaders make more evidence-based decisions, but growing
privacy concerns hamper researchers’ ability to understand and improve the
world. Fully synthetic data, pseudo data generated by models, can protect
confidentiality and produce statistically valid analysis. This talk shares how
the Urban Institute collaborates with the IRS to create fully synthetic tax data
for tax policy research. We built an R package called tidysynthesis to create
machine learning models for each variable in the data. tidysynthesis leverages
the power of tidymodels and allows users to run a sequences of machine learning
models with different recipes, engines, and samplers while adding additional
noise and enforcing logical constraints.
