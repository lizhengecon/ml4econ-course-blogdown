+++
# An Overview section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 30  # Order that this section will appear.

title = "Overview"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  image = ""  # Name of image in `static/img/`.
  image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  text_color_light = false

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["6em", "0", "6em", "0"]

[advanced]
 # Custom CSS. 
 css_style = "margin-top: -1em !important;"
 
 # CSS class.
 css_class = ""
+++

The course will cover topics that range between machine learning (ML) and econometrics. In particular, we will discuss concepts from the world of ML that can potentially contribute to empirical economics. The course will cover leading machine learning (supervised and unsupervised) methods, with an emphasis on the challenges and opportunities of integrating these methods in empirical economics, and the relevance of ML to policy analysis and causal inference. The various topics are illustrated through applications, reading empirical articles, and doing applied work.

The first, part of the course will introduce you to Supervised (predictive) and Unsupervised Machine Learning methods. Examples include Regression and K Nearest Neighbors, Classification, Dimensionality Reduction, Decision Trees and Random Forests, Principal Component Analysis and Clustering Analysis. You will learn what techniques to apply and why.

The second and biggest part of the class, will focus on the relationship between Machine Learning and Econometrics. You will learn about the difference between predicting and explaining, how machine learning methods aid in estimating treatment effects in high-dimensional settings, and how unsupervised learning method can help us to reduce dimenssionality and generate new variables. Examples include Causal Trees and Forests, Double Robust Machine Learning, and Text Mining with applications to data sets used to study economic phenomena.
