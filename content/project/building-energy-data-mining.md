+++
# Date this page was created.
date = 2018-09-26T00:00:00

# Project title.
title = "Building Energy Data Mining"

# Project summary to display on homepage.
summary = "Understanding the underlying dynamics of building energy consumption through data mining"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "building_energy_data_mining1.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Machine learning", "Energy System", "Modeling"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "building_energy.png"
caption = "Interaction between building energy consumption, building physics, weather parameters and behavior"

+++

Understanding the underlying dynamics of building energy consumption is the very firrst step towards energy saving in building sector; as a powerful tool for knowledge discovery, data mining is being applied to this domain more and more frequently. However, most previous researchers focus on model development during the pipeline of data mining, with feature engineering simply being overlooked. To fill this gap, three different feature engineering approaches, namely Exploratory Data Analysis (EDA) as a feature visualization method, Random Forest (RF) as a feature selection method and Principal Component Analysis (PCA) as a feature extraction method, are investigated in the paper. These feature engineering methods are tested with a building energy consumption dataset with 124 features, which describe the building physics, weather condition, and occupant behavior. The 124 features are analyzed and ranked in this paper. It is found that although feature importance depends on specific machine learning model, yet certain features will always dominate the feature space. The outcome of this study favors the usage of effective yet computationally cheap feature engineering methods such as EDA; for other building energy data mining problems, the method proposed by this study has important implications as well because it provides a starting point where effecient feature engineering and machine learning models could be further developed.