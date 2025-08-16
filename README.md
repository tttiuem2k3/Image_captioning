# Image Captioning (CNN + RNN Models)

This project implements image captioning models that generate natural language descriptions from images using **CNN feature extractors** combined with **RNN-based decoders**.  
Currently supported architectures:
- **CNN + LSTM**
- **CNN + GRU**
- **CNN + BiGRU**

## 📌 Features
- Extract image features using pre-trained CNNs (e.g., ResNet, InceptionV3).
- Generate captions using RNNs with word embeddings (GloVe).
- Support for attention mechanisms to improve caption quality.
- Evaluation using BLEU and METEOR metrics.

## 🗂 Dataset
- **Flickr30k**: 31,783 images with 5 captions each.
- Train / Validation / Test split:
  - Train: 25,110 images  
  - Validation: 6,356 images  
  - Test: 317 images

## 📊 Example Results
| Metric  | CNN+LSTM | CNN+GRU | CNN+BiGRU |
|--------:|:--------:|:-------:|:---------:|
| BLEU-1  | 0.6054   | 0.5880  | 0.5873    |
| BLEU-2  | 0.3697   | **0.4053** | 0.3697    |
| BLEU-3  | 0.2586   | 0.3247  | 0.2415    |
| BLEU-4  | 0.1704   | 0.2761  | 0.1614    |
| METEOR  | 0.3565   | 0.4010  | 0.4004    |

##  📞 Contact
- 📧 Email: tttiuem2k3@gmail.com
- 👥 Linkedin: [Thịnh Trần](https://www.linkedin.com/in/thinh-tran-04122k3/)
- 💬 Zalo / Phone: +84 329966939 | +84 336639775
