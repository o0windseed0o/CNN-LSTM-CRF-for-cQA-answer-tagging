# CNN-LSTM-CRF-for-cQA-answer-tagging
Provide results for CNN+LSTM+CRF for cQA answer tagging by the paper:

http://www.aclweb.org/anthology/C/C16/C16-1117.pdf

It is published in COLING 2016.

The experiments are carried on SemEval 2015 task-3 cQA dataset.

  ----ARC-I: 58.96 on F1

  ----ARC-II: 58.29 on F1
  
The systems can be easily implemented with the help of https://github.com/glample/tagger and the parameter settings described in the coling paper.

Any work compared with this paper, please cite 

@inproceedings{Xiang2016Incorporating,
  title={Incorporating Label Dependency for Answer Quality Tagging in Community Question Answering via CNN-LSTM-CRF},
  author={Xiang, Yang and Zhou, Xiaoqiang and Chen, Qingcai and Zheng, Zhihui and Wang, Xiaolong and Qin, Yang},
  booktitle={COLING},
  year={2016},
}
