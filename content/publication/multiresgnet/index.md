---
title: "MultiResGNet: Approximating nonlinear deformation via multi-resolution graphs"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Rui Shi
- Takashi Kanai

# Author notes (optional)
author_notes:
- ""
- ""
- ""

date: "2021-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-05-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Computer Graphics Forum*, 40(2) (Eurographics 2021 Conference Issue), pp.537-548, 2021.
publication_short: In *Computer Graphics Forum (Eurographics 2021 Conference Issue)* 

abstract: This paper presents a graph-learning-based, powerfully generalized method for automatically generating nonlinear deformation for characters with an arbitrary number of vertices. Large-scale character datasets with a significant number of poses are normally required for training to learn such automatic generalization tasks. There are two key contributions that enable us to address this challenge while making our network generalized to achieve realistic deformation approximation. First, after the automatic linear-based deformation step, we encode the roughly deformed meshes by constructing graphs where we propose a novel graph feature representation method with three descriptors to represent meshes of arbitrary characters in varying poses. Second, we design a multi-resolution graph network (MultiResGNet) that takes the constructed graphs as input, and end-to-end outputs the offset adjustments of each vertex. By processing multi-resolution graphs, general features can be better extracted, and the network training no longer heavily relies on large amounts of training data. Experimental results show that the proposed method achieves better performance than prior studies in deformation approximation for unseen characters and poses.

# Summary. An optional shortened abstract.
summary: A graph-learning-based deformation method
tags: []

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
image:
  caption: 'TeaserFig'
  focal_point: "Smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---


