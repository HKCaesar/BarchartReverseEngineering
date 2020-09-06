# BarchartReverseEngineering
In this project we propose a new reverse-engineering method for bar charts. The main idea is to use neural networks for textual and numeric information extraction. For textual information, we use Faster-RCNN, which is a neural network-based object detection model, to simultaneously localize and classify textual information. This approach improves efficiency by simplifying the flow of prior work and reducing the low-level operations. For numeric information, we use an encoder–decoder framework that integrates convolutional neural network (CNN) and recurrent neural network (RNN). This framework can learn to directly transform chart images into numeric values without rules and thus achieves a good accuracy and robustness. This framework presents a potential generalization for other types of charts because it first understands chart images and then extracts numeric information by order without additional neural networks for matching the textual and numeric information. An attention mechanism, which is usually a shallow feed-forward neural network, is included to further increase accuracy. It helps the encoder–decoder framework produce highly accurate results by properly distributing “visual attention” over the chart image.


## Reference Paper
Fangfang Zhou, Yong Zhao, Wenjiang Chen, Yijing Tan, Yaqi Xu, Yi Chen, Chao Liu and Ying Zhao. Reverse-engineering Bar Charts Using Neural Networks[J]. Journal of Visualization, 2020 (ChinaVis 2020)
