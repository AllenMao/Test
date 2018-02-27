# test
| pretrained\evaluation | main_acc | main_voting_acc | evaluate_new | time (ms) |
|:---------------------:|:--------:|:---------------:|:------------:|:---------:|
| init model            | 0.9687   | 0.9736          | -            | -         |
| googlenet_init_model  | 0.9662   | 0.9734          | 0.9746       | 19.3      |
| googlenet_imagenet    | 0.9691   | 0.9772          | 0.9792       | 19.3      |
| resnet50_imagenet     | 0.9814   | 0.9827          | 0.9852       | 55.2      |

# source
| model    | top-1   | top-5   |
|:--------:|:-------:|:-------:|
| VGG-16   | 28.5%   | 9.9%    |
| ResNet-50| 24.7%   | 7.8%    |
| ResNet-101| 23.6%  | 7.1%    |
| ResNet-152| 23.0%  | 6.7%    |

# 复现
| Model              | Top 5 Error | Top 1 Error |
|:-------------------|-------------|------------:|
| ResNet18           |     10.50%  |      29.66% |
| ResNet34					 |     8.56%   |      26.17% |
| ResNet50           |     6.85%   |      23.61% |
| ResNet50-SE				 |     6.24%   |      22.64% |
| ResNet101      		 |     6.04%   |      21.95% |
| ResNet152      		 |     5.78%   |      21.51% |
