---
layout: post
title:  "StoryDALL-E: Adapting Pretrained Text-to-Image Transformers for Story Continuation"
date:   2022-10-22 22:21:59 +00:00
image: /images/storydalle.png
categories: multimodal
author: "Adyasha Maharana"
authors: "<em>Adyasha Maharana</em>, Darryl Hannan, Mohit Bansal"
venue: "European Conference on Computer Vision (ECCV)"
arxiv: https://arxiv.org/pdf/2209.06192
code: https://github.com/adymaharana/storydalle
demo: https://replicate.com/adymaharana/story-dalle
---
We retro-fit open-source implementation of DALL-E to perform parallelized generation of a sequence of visual frames based on a given story. The generated images are conditioned on a source frame to improve generalization to unseen characters in the story. 