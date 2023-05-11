---
title: "Building for tomorrow: Assessing the temporal persistence of text classifiers"
collection: publications
permalink: /publication/2022-11-20-Assessing-the-temporal-persistence-of-text-classifiers-6
excerpt: "Performance of text classification models tends to drop over time due to changes in data, which limits the lifetime of a pretrained model. Therefore an ability to predict a model's ability to persist over time can help design models that can be effectively used over a longer period of time. In this paper, we provide a thorough discussion into the problem, establish an evaluation setup for the task. We look at this problem from a practical perspective by assessing the ability of a wide range of language models and classification algorithms to persist over time, as well as how dataset characteristics can help predict the temporal stability of different models. We perform longitudinal classification experiments on three datasets spanning between 6 and 19 years, and involving diverse tasks and types of data. By splitting the longitudinal datasets into years, we perform a comprehensive set of experiments by training and testing across data that are different numbers of years apart from each other, both in the past and in the future. This enables a gradual investigation into the impact of the temporal gap between training and test sets on the classification performance, as well as measuring the extent of the persistence over time."
date: 2022-11-20
venue: "Information Processing & Management "
paperurl: "https://www.sciencedirect.com/science/article/pii/S0306457322003016"
citation: "Alkhalifa, R., Kochkina & Zubiaga, A. (2022). Building for tomorrow: Assessing the temporal persistence of text classifiers Information Processing & Management."
---
Performance of text classification models tends to drop over time due to changes in data, which limits the lifetime of a pretrained model. Therefore an ability to predict a model’s ability to persist over time can help design models that can be effectively used over a longer period of time. In this paper, we provide a thorough discussion into the problem, establish an evaluation setup for the task. We look at this problem from a practical perspective by assessing the ability of a wide range of language models and classification algorithms to persist over time, as well as how dataset characteristics can help predict the temporal stability of different models. We perform longitudinal classification experiments on three datasets spanning between 6 and 19 years, and involving diverse tasks and types of data. By splitting the longitudinal datasets into years, we perform a comprehensive set of experiments by training and testing across data that are different numbers of years apart from each other, both in the past and in the future. This enables a gradual investigation into the impact of the temporal gap between training and test sets on the classification performance, as well as measuring the extent of the persistence over time. Through experimenting with a range of language models and algorithms, we observe a consistent trend of performance drop over time, which however differs significantly across datasets; indeed, datasets whose domain is more closed and language is more stable, such as with book reviews, exhibit a less pronounced performance drop than open-domain social media datasets where language varies significantly more. We find that one can estimate how a model will retain its performance over time based on (i) how well the model performs over a restricted time period and its extrapolation to a longer time period, and (ii) the linguistic characteristics of the dataset, such as the familiarity score between subsets from different years. Findings from these experiments have important implications for the design of text classification models with the aim of preserving performance over time.

[Download paper here](https://www.sciencedirect.com/science/article/pii/S0306457322003016)