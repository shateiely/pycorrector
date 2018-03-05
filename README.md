# corrector
中文错别字纠正工具。音似、形似错字（或变体字）纠正，可用于中文拼音、笔画输入法的错误纠正。python开发。

**corrector** 依据语言模型检测错别字位置，通过拼音音似特征、笔画五笔编辑距离特征及语言模型困惑度特征纠正错别字。

### 语言模型
* Kenlm（统计语言模型工具）
* RNN（TensorFlow、PaddlePaddle均有实现栈式双向LSTM的语言模型）