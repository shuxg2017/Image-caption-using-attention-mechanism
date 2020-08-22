# Image Caption With Attention
**In this project, I built a neural network model which can describe an image. (more details below)**

- I trained with 50k images and 250k captions. (5 captions/image)
- Data source: http://cocodataset.org/#download
- Due to the size of the model, it is not able to be uploaded on this site :(. However, you can download my [code](https://github.com/shuxg2017/Image-caption-using-attention-mechanism/tree/master/imgcap_model).
- Model structure
  - InceptionV3 pre-trained model
  - Feature map encoder
  - Attention
  - Decoder

### Model Prediction
- **The title on the image below is the caption generated by the model.**

![describe an image](https://github.com/shuxg2017/Image-caption-using-attention-mechanism/blob/master/results/image.png)

- **Attention maps: the dark and bright areas correspond how much they contribute when a specific word is generated.**

![attention maps](https://github.com/shuxg2017/Image-caption-using-attention-mechanism/blob/master/results/attention_maps.png)
