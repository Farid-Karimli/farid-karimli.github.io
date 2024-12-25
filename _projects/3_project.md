---
layout: page
title: Herbaria LMM
description: Towards a foundational model for large-scale Herbarium specimen recognition.
img: /assets/img/herbaria.jpg
importance: 3
category: work
related_publications: false
---

This project aims to revolutionize the field of botany and biodiversity studies by developing a large-scale, multi-modal foundation model, to identify and analyze millions of Herbaria samples.

Right now, the research process on preserved plant samples is highly manual. It is also very prone to mistakes, as there is much suspicion of misnaming of samples.

The objective of our work is to enhance botanists' ability to investigate and draw insights with said samples. This is important since Herbaria samples are often the basis of the knowledge about climate change, evolution and biological lifecycles. Therefore, our work holds immense potential for transformative impact. By providing a deeper understanding of plant species and their ecosystems, we can better strategize on preserving biodiversity and even discover new species.

As part of my MS thesis work, I focused on recreating previous work on large-scale fine-grained visual classification (FGVC) in the herbarium domain [FGVC9](https://www.kaggle.com/competitions/herbarium-2022-fgvc9/overview), where SWIN Transformers were used to classify 15,501 species.
Zero-shot learning can help scale herbarium recognition to unseen species, reducing the need for extensive labeled data for less documents or newly discovered species. In an attempt to improve zero-shot prediction, I integrated SWIN as CLIP's vision backbone, which led to improved classification accuracy on images of previously unseen (untrained) species, on subsets of the 15,501 species. Results of preliminary experiments of this work can be found in my [Master's thesis](assets/pdf/thesis.pdf).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/herb1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/herb2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/herb3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Images of preserved herbaria samples.
</div>
