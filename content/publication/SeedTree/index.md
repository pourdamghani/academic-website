---
title: 'SeedTree: A Dynamically Optimal and Local Self-Adjusting Tree'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Chen Avin
  - Robert Sama
  - Stefan Schmid

# Author notes (optional)

date: '2023-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Conference on Computer Communications*
publication_short: In *INFOCOM'23*

abstract: We consider the fundamental problem of designing a self-adjusting tree, which efficiently and locally adapts itself towards the demand it serves (namely accesses to the items stored by the tree nodes), striking a balance between the benefits of such adjustments (enabling faster access) and their costs (reconfigurations). This problem finds applications, among others, in the context of emerging demand-aware and reconfigurable datacenter networks and features connections to self-adjusting data structures. Our main contribution is SeedTree, a dynamically optimal self-adjusting tree which supports local (i.e., greedy) routing, which is particularly attractive under highly dynamic demands. SeedTree relies on an innovative approach which defines a set of unique paths based on randomized item addresses, and uses a small constant number of items per node. We complement our analytical results by showing the benefits of SeedTree empirically, evaluating it on various synthetic and real-world communication traces.

# Summary. An optional shortened abstract.
summary: We introduce SeedTree, a dynamically optimal self-adjusting tree.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'INFOCOM23SeedTree.pdf'
url_code: 'https://github.com/inet-tub/SeedTree'
url_slides: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
