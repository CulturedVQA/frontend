---
title: "CVQA - A Culturally-diverse Multilingual Visual Question Answering Benchmark"
authors:
  - name: "David Romero"
    # link: "FIRST AUTHOR PERSONAL LINK"
  - name: "Chenyang Lyu"
    # link: "SECOND AUTHOR PERSONAL LINK"
    # link: "THIRD AUTHOR PERSONAL LINK"
  
authors_second:
  - name: "Haryo Akbarianto Wibowo"
  - name: "Teresa Lynn"
  - name: "Injy Hamed"
  - name: "Annotators (Soon to be announced)"
  - name: "Thamar Solorio"
  - name: "Alham Fikri Aji"

institution: "MBZUAI Core Team"
conference: "Submitted to a conference"
paperLink: "#"
arxivLink: "#"
huggingfaceLink: "https://huggingface.co/datasets/afaji/cvqa"
teaserVideo: "static/videos/banner_video.mp4"
teaserDescription: "Aliquam vitae elit ullamcorper tellus egestas pellentesque."

youtubeEmbed: "https://www.youtube.com/embed/JkaxUblCGz0"

sectionsOrder:
  - bibtex:
      bibtex: |
        tba
---

{{% abstract %}}
Visual Question Answering~(VQA) is an important task in multimodal AI, and it is often used to test the ability of vision-language models to understand and reason on knowledge present in both visual and textual data. However, most of the current VQA datasets and models are primarily focused on English and a few major world languages, with images that are typically Western-centric. While recent efforts have tried to increase the number of languages covered on VQA datasets, they still lack diversity in low-resource languages. More importantly, although these datasets often extend their linguistic range via translation or some other approaches, they usually keep images the same, resulting in narrow cultural representation. To address these limitations, we construct CVQA, a new Culturally-diverse multilingual Visual bf Question Answering benchmark, designed to cover a rich set of languages and cultures, where we engage native speakers and cultural experts in the data collection process. As a result, CVQA includes culturally-driven images and questions from across 28 countries on four continents, covering 26 languages with 11 scripts, providing a total of 9k questions. We then benchmark several Multimodal Large Language Models (MLLMs) on CVQA, and show that the dataset is challenging for the current state-of-the-art models. This benchmark can serve as a probing evaluation suite for assessing the cultural capability and bias of multimodal models and hopefully encourage more research efforts toward increasing cultural awareness and linguistic diversity in this field.{{% /abstract %}}

{{% text-section "./content/introduction.md" %}}
{{% text-section "./content/method.md" %}}
{{% text-section "./content/experiment-result.md" %}}
{{% text-section "./content/leaderboard.md" %}}


