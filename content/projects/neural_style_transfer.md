---
title: "Neural Style Transfer"
summary: "Generates new image which has style and content of other images"
dateString: Jan 2021 - May 2021
draft: false
tags: ["Python", "PyTorch", "CNN", "DL", "AI"]
weight: 203
cover:
    image: "projects/neural_style_transfer/cover.png"
---

### 🔗[Github Repository](https://github.com/Acejoy/Neural-Style-Transfer)

## Idea

In this project, I implemented the paper **[A Neural Algorithm of Artistic Style
](https://arxiv.org/pdf/1508.06576.pdf)**. The eural network is used to extract the style/texture of the style image. and reduce the style loss and content loss of the generated image.

Furthermore, beam search is used during inference to enhance the prediction result. The network was trained in **PyTorch** on an **Nvidia GTX 1060** graphics card for over 80 epochs.