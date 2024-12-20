# imGPT

**Base Description**: Generate easy-to-read captions for complex images. Helpful for those with visual disabilities or streamlining image description related workflows.


**Further Description**: Was trained on the MSCOCO dataset and then trained on the GPT-2 model. COCO dataset was used due its wide array of detailed and specially pre-labeled images. This made it much easier to train the model for accurate object detection and eventual caption generation.

**Images**: Images were normalized and graident shifted to maximize feature detection and improve the overall model accuracy. 

**Model Architecture**: The pipeline combines a CNN-based encoder for image feature extraction with the GPT-2 transformer model as a decoder, leveraging the encoder-decoder framework for efficient caption generation. This allows the model to create contextually rich and semantically accurate captions for even the most intricate images.

**Applications**: imGPT is ideal for accessibility tools, content moderation, automated image tagging for social media, and enhancing workflows in fields such as digital marketing and e-commerce.

## Usage
To run the project, use the following command:

```bash
streamlit run main.py
```

Model should be pretrained and open to running


