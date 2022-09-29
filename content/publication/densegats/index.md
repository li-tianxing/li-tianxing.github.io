---
title: "DenseGATs: A Graph-Attention-Based Network for Nonlinear Character Deformation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- rui-shi
- Takashi Kanai

# Author notes (optional)
author_notes:
- ""
- ""
- ""

date: "2020-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-05-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *ACM SIGGRAPH Symposium on Interactive 3D Graphics and Games*, Article No.5, May 2020.
publication_short: In *I3D'20* 

abstract: In animation production, animators always spend significant time and efforts to develop quality deformation systems for characters with complex appearances and details. In order to decrease the time spent repetitively skinning and fine-tuning work, we propose an end-to-end approach to automatically compute deformations for new characters based on existing graph information of high-quality skinned character meshes. We adopt the idea of regarding mesh deformations as a combination of linear and nonlinear parts and propose a novel architecture for approximating complex nonlinear deformations. Linear deformations on the other hand are simple and therefore can be directly computed, although not precisely. To enable our network handle complicated graph data and inductively predict nonlinear deformations, we design the graph-attention-based (GAT) block to consist of an aggregation stream and a self-reinforced stream in order to aggregate the features of the neighboring nodes and strengthen the features of a single graph node. To reduce the difficulty of learning huge amount of mesh features, we introduce a dense connection pattern between a set of GAT blocks called "dense module" to ensure the propagation of features in our deep frameworks. These strategies allow the sharing of deformation features of existing well-skinned character models with new ones, which we call densely connected graph attention network (DenseGATs). We tested our DenseGATs and compared it with classical deformation methods and other graph-learning-based strategies. Experiments confirm that our network can predict highly plausible deformations for unseen characters.

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
# To use, place an image named `featured.jpg/png` in your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
# Set `preview_only` to `true` to just use the image for thumbnails.
image:
  placement: 1
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


