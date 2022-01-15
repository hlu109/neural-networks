# neural-networks

Image classification of bird species. Exploration of convolutional neural networks using the PyTorch library. 

Model performance: 

| model                         | # classes| # epochs trained |augmented data?| validation accuracy | test accuracy |
| -----------                   | -------- | -----------      | --------      | --------            | -----------   |
| BirdNet (trained from scratch)|    20    |20                |yes, x10       |86%                  |83%            |
| AlexNet (transfer learning)   |      20  |3                 |no             |98%                  |97%            |
