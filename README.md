_Life is like riding a bicycle._

_To keep your balance you must keep moving._ 

--Albert Einstein

## [Project 1: Image matting](https://peace-and-harmony.github.io/image-matting/)

**_Adapted the architecture of MODNet to the domain of clothing matting, aiming to extract the clothing foreground object from daily photos, and to feed in a recommendation system later._**

- Conducted image matting for the client. Trained deep learning model on 6.3G dataset to extract foreground objects.
- Improved accuracy and the new model reduced negative reviews from the app users and potentially increases the client's profit.
- Conducted inference benchmark tests on CPU via ONNX: 1.4X faster inference runtime. 
- TensorRT engine was generated based on simplified ONNX format which potentially speeds up inference on GPU.

## [Project 2: Topic modelling/evolution](https://peace-and-harmony.github.io/nature-articles-topic-modelling/)

**_Uncover the topic evolution since 1886_**

- Scraped ~20000 Nature research articles from 1886 to 2021.
- Performed EDA for the numerical data and found that the pandemic boosts the COVID-related research areas.
- Deployed Bertopic to investigate the evolution of Nature research article topics over 148 years.

