---
title: "PUF-Based RFID Authentication Secure and Private under Memory Leakage"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Daisuke Moriyama
- admin
- Moti Yung

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2013-10-31T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2013-10-31T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "IACR Eprint archive"
publication_short:

abstract: "RFID tags are getting their presence noticeable and are expected to become an important tool for e-commerce, logistics, point-ofsale transactions, and so on, representing “things” and “human holding things” in transactions. Since a huge amount of tags are expected to be needed to be attached to various “objects,” a low-cost tag manufacturing is necessary. Thus, it is hard to imagine they will implement costly hardware protection mechanisms (like co-processor, TPMs). Therefore, in this context memory leakage (side-channel) attacks become a critical threat. Another well known threat to RFID devices is tag tracing implying violation of privacy. We consider physically unclonable functions (PUFs) as tamper resilient building blocks cheaper than protected hardware, and propose security against a memory leaking adversary, trying to violate security and privacy of tags (we emphasize that digitally-oriented PUFs are easy to implement and they are more likely than TPMs to be implemented in RFID chips, more so than TPMs). We then design the first provably secure and provably private RFID authentication protocol withstanding information leakage from the entire memory of the tag, and show its two properties: (1) security against man-in-the-middle attack, and (2) privacy protection against tag tracing."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://eprint.iacr.org/2013/712'
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
