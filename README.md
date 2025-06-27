# 适用于英特尔 Arc GPU 的 YOLO

我很高兴地宣布，我成功修改了 YOLOv5 项目，使其可以在 **英特尔 Arc GPU** 上运行！这个整合包包含了为实现此兼容性所做的所有必要修改，并提供了方便的下载链接。

---

## 项目亮点

* **英特尔 Arc GPU 兼容性：** 针对在英特尔 Arc 显卡上运行 YOLO 模型进行了优化。
* **PyTorch 2.7：** 使用 PyTorch 2.7 版本进行开发和测试。
* **易于使用：** 提供整合包，简化了安装和配置过程。

---

## 我所做的修改

为了让 YOLO 在英特尔 Arc GPU 上顺利运行，我主要修改了以下文件：

* `utils/torch_utils.py`
* `utils/checks.py`
* `engine/trainer`

这些修改主要涉及对 PyTorch 后端和设备兼容性的调整，以充分利用英特尔 Arc GPU 的性能。

---

## 下载整合包

您可以从以下链接下载预配置的整合包，快速开始在您的英特尔 Arc GPU 上运行 YOLO：

* **直链下载 (ModelScope):** [https://www.modelscope.cn/models/Sakuya999/YOLO-For-Intel-Arc/resolve/master/yolo11.zip](https://www.modelscope.cn/models/Sakuya999/YOLO-For-Intel-Arc/resolve/master/yolo11.zip)
* **123 网盘:** [https://www.123865.com/s/0p0Mjv-FkKgh](https://www.123865.com/s/0p0Mjv-FkKgh)
* **百度网盘:** [https://pan.baidu.com/s/1EEwbSyr-jkUGYz2b1XgNLQ?pwd=1616](https://pan.baidu.com/s/1EEwbSyr-jkUGYz2b1XgNLQ?pwd=1616)
    * **提取码:** `1616`

---

## 如何使用

下载整合包后，请解压文件并按照 README 中的说明进行操作。您可能需要安装 OneAPI 相关驱动和库以确保最佳性能。

---

## 参考文档

* **Ultralytics YOLOv5 官方仓库:** [https://github.com/ultralytics/ultralytics](https://github.com/ultralytics/ultralytics)
* **英特尔 PyTorch 扩展:** [https://pytorch-extension.intel.com/?request=platform](https://pytorch-extension.intel.com/?request=platform)

---

## 贡献与反馈

如果您在使用过程中遇到任何问题或有任何改进建议，欢迎提交 Issue 或 Pull Request。您的反馈对我非常重要！

---

希望这个整合包能帮助到所有拥有英特尔 Arc GPU 的开发者和研究人员！
