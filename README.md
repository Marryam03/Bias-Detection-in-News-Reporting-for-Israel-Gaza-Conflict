# Bias Detection in News Reporting: NLP Framework for Israel-Gaza Conflict
This project presents an NLP-based framework for detecting bias in news reporting, focusing on the politically sensitive and polarized context of the Israel-Gaza conflict. The framework leverages Nakba narratives as linguistic resources and uses advanced preprocessing, class imbalance mitigation, and state-of-the-art machine learning models to improve bias detection accuracy.

# Dataset
The dataset consists of multilingual news articles annotated for bias and propaganda, focusing strongly on Arabic texts. The dataset includes:
- **Nakba Narratives**: Linguistic resources for bias analysis.
- **Annotations**: Bias and propaganda labels curated for training and evaluation.

# Methodology
The project explores various approaches, including:
- **Traditional ML Models**: Random Forest, XGBoost, Logistic Regression.
- **Deep Learning Models**: LSTM, Bi-LSTM, Bi-GRU with Attention.
- **Transformer-based Architectures**: AraBERT, T5-small.
- **Generative Models**: Leveraging large-scale pre-trained models for contextual understanding.

Key techniques include:
- **Preprocessing**: Tokenization, stemming, and noise removal.
- **Class Imbalance Handling**: Using Borderline-SMOTE and other augmentation methods.

# Results:
- The proposed framework achieved notable performance in bias detection, particularly with ensemble machine learning methods. Random Forest and XGBoost demonstrated the highest accuracy (93% and 92%, respectively), showcasing their effectiveness in handling the nuanced and imbalanced dataset. Deep learning models, such as LSTM, achieved moderate success (84% accuracy), while Transformer-based models like AraBERT exhibited reasonable performance (58% accuracy) but were limited by the dataset size and domain complexity. Generative models, including T5-small and Silma, struggled in this context, highlighting the challenges of applying generative approaches to bias detection tasks.

#Publication Link:
https://aclanthology.org/2025.nakbanlp-1.12/#

# Cite:
@inproceedings{mohammed-etal-2025-bias,
    title = "Bias Detection in Media: Traditional Models vs. Transformers in Analyzing Social Media Coverage of the Israeli-{G}aza Conflict",
    author = "Mohammed, Marryam Yahya  and
      Mohamed, Esraa Ismail  and
      Esmat, Mariam Nabil  and
      Nagib, Yomna Ashraf  and
      Radwan, Nada Ahmed  and
      Elshaer, Ziad Mohamed  and
      Mohamed, Ensaf Hussein",
    editor = "Jarrar, Mustafa  and
      Habash, Habash  and
      El-Haj, Mo",
    booktitle = "Proceedings of the first International Workshop on Nakba Narratives as Language Resources",
    month = jan,
    year = "2025",
    address = "Abu Dhabi",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.nakbanlp-1.12/",
    pages = "114--121",
    abstract = "Bias in news reporting significantly influences public perception, particularly in sensitive and polarized contexts like the Israel-Gaza conflict. Detecting bias in such cases presents unique challenges due to political, cultural, and ideological complexities, often amplifying disparities in reporting. While prior research has addressed media bias and dataset fairness, these approaches inadequately capture the nuanced dynamics of the Israel-Gaza conflict. To address this gap, we propose an NLP-based framework that leverages Nakba narratives as linguistic resources for bias detection in news coverage. Using a multilingual corpus focusing on Arabic texts, we apply rigorous data cleaning, pre-processing, and methods to mitigate imbalanced class distributions that could skew classification outcomes. Our study explores various approaches, including Machine Learning (ML), Deep Learning (DL), Transformer-based architectures, and generative models. The findings demonstrate promising advancements in automating bias detection, and enhancing fairness and accuracy in politically sensitive reporting."
}
