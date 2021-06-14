---
title: "Leakage Resilient Strong Key-Insulated Signatures in Public Channel"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Le Trieu Phong
- admin
- Moti Yung


# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2010-12-13T00:00:00Z"
doi: "https://doi.org/10.1007/978-3-642-25283-9_11"

# Schedule page publish date (NOT publication's date).
publishDate: "2010-12-13T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "INTRUST 2010: Lecture Notes in Computer Science 6802, pp. 160-172. Springer Verlag, 2010"
publication_short:

abstract: "Key-insulation aims at minimizing (i.e., compartmentalizing) the damage of users from key exposures, and traditionally requires a private channel of communication between a user and a semi-trusted party called a helper to refresh the private keys. The configuration is highly suitable to architectures where the signer is a user application and the helper resides in the safer trusted module, yet the user wants to remain in control of the sensitive crypto operation. The private channel employed in the model, while acceptable in some settings, certainly limits the usage of key insulation schemes (in case the user sits across the network from the trusted environment). In 2009, Bellare, Duan, and Palacio (CT-RSA 2009) refined the model of key-insulation by consid- ering public channels (namely, ones controlled by the adversary), and showed how to convert a key-insulated signature scheme from the private channel into the public one, using extra primitives such as key exchange protocols and symmetric encryption. In this paper, we show that the primitives may be redundant in specific cases. In particular, we revisit the original key-insulated signature scheme in the private channel given by Dodis, Katz, Xu, and Yung (PKC 2003), and show that, with a tweak, the scheme can be naturally proved secure in the public channel without any additional primitives. Next we consider the area of leakage resilient cryptographic schemes which has gained much interest recently. In particular, we consider the continual key leakage scenario of our design (which is more general than the model of key exposure), and argue that our proposal, while requiring an added helper component, nevertheless enjoys several advantages over the recent signature scheme of Faust et al. (TCC 2010) with the same purpose of allowing continual leakage. Our design demonstrates how when given a more complex architecture with some parts that are safer than others, a trade-off can be applied, exploiting the safer modules but keeping users in control; further we show how to do it while mitigating the effect of exposures and leakages."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://link.springer.com/chapter/10.1007/978-3-642-25283-9_11'
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
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#-

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
