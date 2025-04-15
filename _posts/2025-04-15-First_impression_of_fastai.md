---
title: "First Impressions of fastai"
description: "Diving into the world of deep learning with fastai"
date: 2025-04-15
categories: [fastai, deep-learning]
---

Today I began my fastai journey!   
After setting up my environment with `conda` and launching the Jupyter notebooks, I dove into Lesson 1 of the [fastai course](https://course.fast.ai/).

---

## What I Learned

- How to fine-tune a pretrained model using just **two lines of code**
- The power of **transfer learning**
- How `vision_learner` simplifies PyTorch models

Here’s the training code:

```python
learn = vision_learner(dls, resnet34, metrics=error_rate)
learn.fine_tune(1)
```

And that’s it! I had a working image classifier.

---

## Tips

- Use `learn.show_results()` to visualize predictions after training.
- Use small datasets at first to iterate faster.
- Don’t worry about understanding everything immediately — try running the code and tweak parameters to explore.

---

## Output Preview

You can also save training results as images and embed them in your post:

![Sample Training Output](images/training-image.png)

---

## Final Thoughts

fastai makes deep learning feel intuitive. Instead of wrestling with low-level code, I got to *focus on learning*. It’s clear why this course is so highly recommended.

