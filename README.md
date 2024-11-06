# News Article Title Generation

This project aims to generate accurate and concise titles for news articles. By fine-tuning transformer-based models, we strive to improve title generation that captures the core content of each article. The dataset comprises news articles from various sources, allowing us to train models that produce titles across diverse topics and styles.

## Project Overview

### Objective
Generate high-quality titles for news articles that accurately reflect the article's content, using NLP techniques and transformer models.

### Dataset
- **Filename**: New_articles_combined.csv (~3GB)
- **Source**: Combined news dataset from various providers, including CNN/DailyMail, BBC, and The New York Times. This dataset includes article content, which is used to train models to generate relevant and concise titles.

Additional News Datasets:
- [Inshorts News Data](https://www.kaggle.com/datasets/shashichander009/inshorts-news-data)
- [BBC Articles Dataset](https://www.kaggle.com/datasets/jacopoferretti/bbc-articles-dataset)
- [NYTimes Article Dataset](https://www.kaggle.com/datasets/parsonsandrew1/nytimes-article-lead-paragraphs-18512017)

## Models and Methods

The project utilizes transformer models, particularly:
- **BART (Bidirectional and Auto-Regressive Transformers)**: Fine-tuned for generating concise and informative titles.
- **T5 (Text-To-Text Transfer Transformer)**: Adapted for title generation tasks, trained on diverse article content.
  
### Process
1. **Data Preprocessing**: 
   - Clean and preprocess article text data.
   - Tokenize text for model input.
2. **Model Training**: 
   - Fine-tune BART and T5 on the news dataset to generate titles based on article content.
3. **Evaluation**:
   - Assess the quality of generated titles using metrics like ROUGE, BLEU, and human evaluation for relevance and accuracy.

### Additional Resources
- [Generating Text with BART](https://huggingface.co/docs/transformers/model_doc/bart)
- [Training T5 on Text Generation](https://huggingface.co/docs/transformers/model_doc/t5)

## References and Resources
- [Text Generation Project](https://github.com/umd-fire-coml/2020-Text-Generation) – Example project generating next sentences based on input text.
- [Automated Headline Generation from News Descriptions](https://github.com/vishal1797/Automated-Headline-Generation-from-News-Descriptions/tree/main)
