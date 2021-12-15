# 进一步优化

如果预优化模型和训练后工具无法满足您的用例，那么接下来请尝试使用不同的训练时工具。

训练时工具可以在训练数据上利用模型的损失函数，从而使模型可以“适应”优化技术带来的变化。

Keras 训练脚本是使用训练 API 的起点，您可以选择从预训练的 Keras 模型对该脚本进行初始化，以进一步微调。

可供您尝试的训练时工具包括：

- [权重剪枝](./pruning/)
- [量化](./quantization/training)
- [权重聚类](./clustering/)
- [协同优化](./combine/collaborative_optimization)