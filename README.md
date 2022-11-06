Description
=============
#### - GPT-2
  - Details of GPT-2: https://jalammar.github.io/illustrated-gpt2
  - Composed with Transformer decoder layers
  
  <img src="https://user-images.githubusercontent.com/52263269/200189225-d77cd65f-9081-4f03-bd29-49e56b84fbe1.png" width="90%"></img>  

  - Auto-regression model
    - Like traditional language models such as RNN
    - Outputs one token at a time
      - Step 1. after each token is produced, that token is added to the sequence of inputs
      - Step 2. And that new sequence becomes the input to the model in its next step.
    
  <img src="https://user-images.githubusercontent.com/52263269/200189769-3f7dbc22-9f38-44ae-9436-a378bbbeb952.png" width="90%"></img>      

#### - KOGPT2
  - GPT series of Korean version
  - Pretrained with Korean Wiki, news, corpus etc.

#### - Upload code as a Jupiter Notebook file (.ipynb) for immediate understanding

Contents
=============

#### - KoGPT2 zero-shot learning
  - [KoGPT2 implementation with zero-shot learning for text classification](https://github.com/qbxlvnf11/GPT-series/blob/main/KoGPT2-zero-shot-learning.ipynb)
  
Datasets
=============

#### - KR3: Korean Restaurant Reviews with Ratings

https://www.kaggle.com/datasets/ninetyninenewton/kr3-korean-restaurant-reviews-with-ratings

References
=============

#### - Papers

```
@article{GPT-2,
  title={Language Models are Unsupervised Multitask Learners},
  author={Alec Radford, Jeffrey Wu, Rewon Child, David Luan, Dario Amodei, Ilya Sutskever},
  year={2018}
}
```

#### - GPT-2

https://github.com/openai/gpt-2

#### - KoGPT2

https://github.com/SKT-AI/KoGPT2

https://www.kaggle.com/code/ninetyninenewton/zero-shot-sentiment-classification-using-gpt-2/notebook

Author
=============

#### - LinkedIn: https://www.linkedin.com/in/taeyong-kong-016bb2154

#### - Blog URL: https://blog.naver.com/qbxlvnf11

#### - Email: qbxlvnf11@google.com, qbxlvnf11@naver.com
