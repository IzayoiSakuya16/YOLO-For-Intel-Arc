# 适用于英特尔 Arc GPU 的 YOLO

这是一个基于ultralytics的yolo11修改的整合包。

---

## 简介

* **Intel Arc GPU 兼容性：** 针对在英特尔 Arc 显卡上运行 YOLO 模型进行了适配。
* **PyTorch 2.7：** 使用 PyTorch 2.7 版本。
* **使用方法：** 提供整合包，按照视频教程即可使用。
* **视频链接：** [红魔馆的主人](https://www.bilibili.com/video/BV1HvKyzfEit/?spm_id_from=333.1007.top_right_bar_window_dynamic.content.click&vd_source=633b982861136e43023b3172db0f77ab)
---

## 主要修改

为了让 YOLO 在Intel Arc GPU 上顺利运行，主要修改了以下文件：

* `utils/torch_utils.py`
* `utils/checks.py`
* `engine/trainer`

这些修改主要是将cuda改成xpu，最重要的是在运行脚本禁用了混合精度以兼容arc显卡。

---

## 下载整合包

你可以从以下链接下载整合包，并在你的Intel Arc GPU 上运行 YOLO：

* [直链下载（限速4-6Mb/s，下载约7分钟）](https://www.modelscope.cn/models/Sakuya999/YOLO-For-Intel-Arc/resolve/master/YOLO-For-Intel-Arc.zip)
* [123 网盘](https://www.123865.com/s/0p0Mjv-FkKgh)
* [百度网盘](https://pan.baidu.com/s/1EEwbSyr-jkUGYz2b1XgNLQ?pwd=1616)
---

## 如何使用

下载整合包后，请解压文件并按照视频中的说明进行操作。

---

## 参考文档

* **Ultralytics YOLOv5 官方仓库:** [https://github.com/ultralytics/ultralytics](https://github.com/ultralytics/ultralytics)
* **英特尔 PyTorch 扩展:** [https://pytorch-extension.intel.com/?request=platform](https://pytorch-extension.intel.com/?request=platform)

---

