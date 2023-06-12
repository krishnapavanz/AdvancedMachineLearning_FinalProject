## Text summarisation models for summarising news articles

News articles are an essential source of information, but the increasing volume of news content poses challenges for readers to keep up with the vast amount of available information. To address this issue, we embarked on a research project focused on text summarization for news articles. This project aims to develop a text summarization system that can generate concise and informative headlines from news articles. The system was trained on Kaggle Inshorts News Data. In this report, we present our exploration of four powerful models that employ different approaches to summarize news articles efficiently and accurately.

### 1. Sequence to Sequence model and Attention - Encoder-Decoder Architecture:
Our research began with the implementation of a sequence-to-sequence network with attention, utilizing an encoder-decoder architecture. This model leverages the power of recurrent neural networks (RNNs) to capture contextual information from the input news articles. By employing attention mechanisms, the model learns to focus on relevant parts of the text and generate concise summaries. We achieved promising results with this initial approach.

### 2. Transformer Model:
Building upon our initial model, we sought to explore the potential of transformer models for text summarization. Transformers have revolutionized natural language processing tasks, and their attention mechanisms excel at capturing long-range dependencies. By adapting the transformer architecture to our text summarization task, we aimed to improve the quality and coherence of the generated summaries. 

### 3. BART Model: 
Inspired by the success of pretrained models in various natural language processing tasks, we turned our attention to BART (Bidirectional and AutoRegressive Transformers). BART combines the power of denoising autoencoding and sequence-to-sequence models, enabling it to generate high-quality abstractive summaries. By fine-tuning the BART model on our news dataset, we aimed to leverage its pretraining to enhance the summarization process. 

### 4. T5, PyTorch, and PyTorch Lightning: 
In our pursuit of exploring diverse models, we incorporated the T5 model, leveraging the capabilities of PyTorch and PyTorch Lightning frameworks. T5 is a versatile model that can be fine-tuned for various text generation tasks, including summarization. By employing T5, we sought to compare its performance with the previously implemented models. PyTorch and PyTorch Lightning frameworks streamlined our experimentation process, allowing us to focus on the model's architecture and hyperparameters. The T5 model demonstrated competitive results, further expanding the range of models available for text summarization.


### Methodology:  
Each model was trained, fine-tuned, and assessed for its summarization capabilities. The Sequence to Sequence Network and Attention served as the initial approach, leveraging recurrent neural networks and attention mechanisms. The Transformer model explored the power of self-attention and positional encoding, while the BART model capitalized on pretrained architectures for enhanced abstractive summarization. Lastly, the T5 model, integrated with PyTorch and PyTorch Lightning, provided a versatile and conditional generation framework.

The comparative analysis using the BLEU metric provided valuable insights into the models' summarization capabilities. It revealed the importance of architectural choices, fine-tuning techniques, and the utilization of pretraining for enhancing summarization quality. The findings contribute to the field of text summarization and shed light on the effectiveness of different models for news article summarization.
