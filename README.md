# deHuBERT: Disentangling Noise in a Self-supervised Model for Robust Speech Recognition

Paper for this work: https://ieeexplore.ieee.org/document/10096603
Noise dataset used in this work can be downloaded [here](https://drive.google.com/drive/folders/1GT-drqG5vn9OfRrmNZXDjhBQC2p1sfoK?usp=share_link)
Note that we would like to credit the noise dataset from the work `An Investigation of End-to-End Models for Robust Speech Recognition`, but unfortunately, we found that it is currently inaccessible. For research purposes, we hope that the above link can help reproduce some of the results.
The test set for pre-mixed noisy speech is corrupted from the test-clean set of LibriSpeech, with text references matched to the utterances and file names respectively. You can obtain the labels by matching them yourself from the LibriSpeech corpus.

In addition, we would love to release the loss function used and online training noise augmentation implemented in this work to achieve the disentangling model as described in our paper soon.

If you find our work interesting, please help by citing it and feel free to approach us for any opportunities to collaborate
```
@INPROCEEDINGS{10096603,
  author={Ng, Dianwen and Zhang, Ruixi and Yip, Jia Qi and Yang, Zhao and Ni, Jinjie and Zhang, Chong and Ma, Yukun and Ni, Chongjia and Chng, Eng Siong and Ma, Bin},
  booktitle={ICASSP 2023 - 2023 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)}, 
  title={De’hubert: Disentangling Noise in a Self-Supervised Model for Robust Speech Recognition}, 
  year={2023},
  volume={},
  number={},
  pages={1-5},
  doi={10.1109/ICASSP49357.2023.10096603}}

```
