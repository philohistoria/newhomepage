---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: How Using Machine Learning Classification as a Variable in Regression Leads
  to Attenuation Bias and What to Do About It
subtitle: ''
summary: ''
authors:
- Han Zhang
tags: []
categories: []
date: '2021-01-01'
lastmod: 2021-05-28T15:18:11+08:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-04-08T01:47:38.343468Z'
publication_types:
- '2'
abstract: ''
publication: '*SocArXiv*'
url_pdf: https://osf.io/preprints/socarxiv/453jk/
---

*Abstract*: Social scientists have increasingly been applying machine learning algorithms to "big data" to measure theoretical concepts they cannot easily measure before, and then been using these machine-predicted variables in a regression. This article first demonstrates that directly inserting binary predictions (i.e., classification) without regard for prediction error will generally lead to attenuation biases of either slope coefficients or marginal effect estimates.
We then propose several estimators to obtain consistent estimates of coefficients.
The estimators require the existence of validation data, of which researchers have both machine prediction and true values.This validation data is either automatically available during training algorithms or can be easily obtained.
Monte Carlo simulations demonstrate the effectiveness of the proposed estimators.
Finally, we summarize the usage pattern of machine learning predictions in 18 recent publications in top social science journals, apply our proposed estimators to two of them, and offer some practical recommendations.

