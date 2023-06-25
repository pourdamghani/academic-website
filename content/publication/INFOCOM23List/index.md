---
title: 'Self-Adjusting Partially Ordered Lists'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Vamsi Addanki
  - Maciej Pacut
  - admin
  - Gabor Retvari
  - Stefan Schmid
  - Juan Vanerio

# Author notes (optional)

date: '2023-05-16T00:00:00Z'
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

abstract:We introduce self-adjusting partially ordered lists, a generalization of self-adjusting lists where additionally there may be constraints for the relative order of some nodes in the list. The lists self-adjust to improve performance while serving input sequences exhibiting favorable properties, such as locality of reference, but the constraints must be respected.
We design a deterministic adjusting algorithm that operates without any assumptions about the input distribution and without maintaining frequency statistics or timestamps. Despite the more general model, we show that our deterministic algorithm performs closely to optimum (it is 4-competitive). In addition, we design a family of randomized algorithms with improved competitive ratios, handling also a more general rearrangement cost model, scaled by an arbitrary constant d ≥ 1. Moreover, we observe that different constraints influence the competitiveness of online algorithms, and we shed light on this aspect with a lower bound.
We investigate the applicability of our self-adjusting lists in the context of network packet classification. Our evaluations show that our classifier performs similarly to a static list for lowlocality traffic, but significantly outperforms Efficuts (by factor 7x), CutSplit (3.6x) and the static list (14x) for high locality and small rulesets.

# Summary. An optional shortened abstract.
summary: We solved online list access problem with constraints.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_slides: ''
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

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

# Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
