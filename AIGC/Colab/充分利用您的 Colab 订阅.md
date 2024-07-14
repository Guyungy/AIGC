## 更快的 GPU

已购买任一 Colab 付费方案的用户可使用付费 GPU。只需在菜单中依次选择`运行时 > 更改运行时类型`，升级笔记本的 GPU 设置，即可启用付费加速器。根据实际可用情况，选择付费 GPU 可能会授予您使用 V100 或 A100 Nvidia GPU 的权限。

免费版 Colab 会根据配额限制和实际可用情况，授予您使用 Nvidia T4 GPU 的权限。

只需执行以下单元格，即可随时查看分配给您的 GPU。如果以下代码单元格的运行结果是“Not connected to a GPU”（未连接到 GPU），您可以通过以下步骤更改运行时：在菜单中依次选择`运行时 > 更改运行时类型`，启用 GPU 加速器，然后重新执行该代码单元格。

---

[ ]

gpu_info = !nvidia-smi  
gpu_info = '\n'.join(gpu_info)  
if gpu_info.find('failed') >= 0:  
  print('Not connected to a GPU')  
else:  
  print(gpu_info)  

---

若要在笔记本上使用 GPU，请在菜单中依次选择`运行时 > 更改运行时类型`，然后从“硬件加速器”下拉菜单中选择 GPU。

---

## 更多内存

已购买任一 Colab 付费方案的用户可使用高内存虚拟机（如果可用）。 只需运行以下代码单元格，即可随时查看您的可用内存量。如果以下代码单元格的运行结果是“Not using a high-RAM runtime”（未使用高 RAM 运行时），您可以通过以下步骤启用高 RAM 运行时：在菜单中依次选择`运行时 > 更改运行时类型`，然后在“运行时规格”下拉菜单中选择“高 RAM”。完成选择后，重新执行该代码单元格。

---

[ ]

from psutil import virtual_memory  
ram_gb = virtual_memory().total / 1e9  
print('Your runtime has {:.1f} gigabytes of available RAM\n'.format(ram_gb))  
  
if ram_gb < 20:  
  print('Not using a high-RAM runtime')  
else:  
  print('You are using a high-RAM runtime!')  

---

## 更长的运行时

所有 Colab 运行时都会在一段时间后重置（如果运行时未执行代码，则会更早重置）。与免费版 Colab 相比，Colab Pro 和 Pro+ 用户可以享受更长的运行时。

## 后台执行

Colab Pro+ 用户可获得后台执行权限，即使是在关闭浏览器标签页后，笔记本仍会继续执行。只要有可用的计算单元，在 Pro+ 运行时中始终会启用此功能。

---

## 缓解 Colab Pro 中的资源限制

您在 Colab 中可以使用的资源量并非不受限制。若要充分利用 Colab，请避免在不需要时占用资源。例如，仅在需要时使用 GPU，并在使用完毕后关闭 Colab 标签页。

在遇到限制时，您可以通过随用随付的方式购买更多计算单元，以缓解此类限制。任何人都能通过[随用随付](https://colab.research.google.com/signup)方式购买计算单元，无需订阅。

---

## 向我们发送反馈！

如果您有任何反馈，欢迎告诉我们。发送反馈的最佳方式是使用“帮助”>“发送反馈…”菜单。如果您在 Colab Pro 中遇到用量限制，建议您订阅 Pro+。

如果您在使用 Colab Pro、Pro+ 或随用随付时遇到错误或其他结算（付款）相关问题，请发送电子邮件至 [colab-billing@google.com](mailto:colab-billing@google.com)。

---

## 更多资源

### 在 Colab 中使用笔记本

-   [Colaboratory 概览](https://colab.research.google.com/notebooks/basic_features_overview.ipynb)
-   [Markdown 指南](https://colab.research.google.com/notebooks/markdown_guide.ipynb)
-   [导入库和安装依赖项](https://colab.research.google.com/notebooks/snippets/importing_libraries.ipynb)
-   [在 GitHub 中保存和加载笔记本](https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb)
-   [互动表单](https://colab.research.google.com/notebooks/forms.ipynb)
-   [互动微件](https://colab.research.google.com/notebooks/widgets.ipynb)

### 处理数据

-   [加载数据：云端硬盘、表格和 Google Cloud Storage](https://colab.research.google.com/notebooks/io.ipynb)
-   [图表：可视化数据](https://colab.research.google.com/notebooks/charts.ipynb)
-   [BigQuery 使用入门](https://colab.research.google.com/notebooks/bigquery.ipynb)

### 机器学习速成课程

以下是 Google 在线机器学习课程中的部分笔记本。请查看[完整课程网站](https://developers.google.com/machine-learning/crash-course/)了解详情。

-   [Pandas DataFrame 简介](https://colab.research.google.com/github/google/eng-edu/blob/main/ml/cc/exercises/pandas_dataframe_ultraquick_tutorial.ipynb)
-   [通过 tf.keras 使用合成数据进行线性回归](https://colab.research.google.com/github/google/eng-edu/blob/main/ml/cc/exercises/linear_regression_with_synthetic_data.ipynb)

### 使用加速硬件

-   [将 TensorFlow 与 GPU 配合使用](https://colab.research.google.com/notebooks/gpu.ipynb)
-   [将 TensorFlow 与 TPU 配合使用](https://colab.research.google.com/notebooks/tpu.ipynb)

---

## 机器学习示例

如需查看 Colaboratory 能够实现的互动机器学习分析的端到端示例，请参阅这些使用 [TensorFlow Hub](https://tfhub.dev/) 中的模型的教程。

一些精选示例：

-   [重新训练图像分类器](https://tensorflow.org/hub/tutorials/tf2_image_retraining)：基于预训练的图像分类器，构建一个分辨花朵的 Keras 模型。
-   [文本分类](https://tensorflow.org/hub/tutorials/tf2_text_classification)：将 IMDB 影评分类为“褒义”或“贬义”。
-   [风格迁移](https://tensorflow.org/hub/tutorials/tf2_arbitrary_image_stylization)：使用深度学习在图像之间迁移风格。
-   [Multilingual Universal Sentence Encoder Q&A](https://tensorflow.org/hub/tutorials/retrieval_with_tf_hub_universal_encoder_qa)：使用机器学习模型回答来自 SQuAD 数据集中的问题。
-   [视频插帧](https://tensorflow.org/hub/tutorials/tweening_conv3d)：预测视频第一帧和最后一帧之间有些什么。