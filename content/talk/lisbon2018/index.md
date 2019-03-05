+++
title = "Development of two linguistic resources to improve the extraction of causal relations in medical language"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date = 2018-10-03T15:35:45+01:00
#date_end = 2019-03-05T15:35:45+01:00
all_day = false

# Schedule page publish date (NOT talk date).
#publishDate = 2019-03-05T15:35:45+01:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["admin"]

# Location of event.
location = "Lisbon, Portugal"

# Name of event and optional event URL.
event = "3rd TechLing"
event_url = "http://cehum.ilch.uminho.pt/techling2018"

# Abstract. What's your talk about?
abstract = "The objective of this research is to analyse and to automatically extract causal expressions from a medical corpus, built from patient records written by doctors. This research is based on the idea that causal relations can be expressed either directly (causal connectives, causal verbs, causal expressions [rendre x + adj.]) or indirectly by words that potentially have a causal meaning, even if this causal interpretation is not the first and intuitive meaning of these words (connectives [en cas de, et], syntactic constructions [relative clauses, participles and gerundives]). Based on this premise, we simultaneously form two linguistic resources by means of an exploratory study of the corpus. This anonymised corpus is made of 226 000 medical texts (around 93 million words) that were collected in six services of Brussels hospitals. First, we design a causal lexicon which is constituted by lexicon and causal adverbials both from standard language and from medical language (such as post in 1)._(1)a. amaigrissement de 40 kg post pose d'un anneau gastrique en [DATE] b.weight loss of 40 kg post-putting on a gastric band in [DATE]_Secondly, we develop a program of disambiguation (coded in Perl) which rests upon the method of the automated text categorisation. We propose here to focus on six French connectives that correspond with this causal ambiguity (et, si, après, quand, lorsque, dès que). We adhere to a 4-steps methodology:(i) Automatic extraction of these connectives (Unitex); (ii) Manual annotation of causal and non causal meanings by a linguist and by a specialist physician;(iii) Identification of causal contexts;(iv) Lexical formalisation of these contexts. We finally implement these two resources in a program of extraction of causal relations in order to appreciate the value added by these linguistic resources compared to the existing programs in the medical field."

# Summary. An optional shortened abstract.
summary = "Automated text categorisation, medical language, causality, corpus linguistics, information extraction"

# Is this a featured talk? (true/false)
featured = true

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Markdown Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Optional filename of your slides within your talk folder or a URL.
url_slides = ""

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Links (optional).
url_pdf = ""
url_video = ""
url_code = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
