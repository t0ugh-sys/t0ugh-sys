<div align="center">

# t0ugh

视觉算法工程师 | Computer Vision Engineer

专注目标检测、分割、跟踪、OCR 与边缘部署

面向工业视觉与边缘 AI 场景，关注推理优化、跨平台部署与可落地的视频分析链路

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-27338E?style=for-the-badge&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-111827?style=for-the-badge&logo=ultralytics&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![RKNN](https://img.shields.io/badge/RKNN-6C47FF?style=for-the-badge)

</div>

Focus:
- 视觉算法研发与工程落地（Detection, Segmentation, Tracking, OCR）
- 模型训练、推理优化与部署（PyTorch, YOLO, ONNX, TensorRT, RKNN）
- 视觉应用服务化与多模态检索（FastAPI, Milvus, LangChain）

Featured Projects:
- [vision-inference-pipeline](https://github.com/t0ugh-sys/vision-inference-pipeline) — 面向 Rockchip RK3588/RK3568 与 NVIDIA GPU 的视频推理部署骨架，覆盖硬解码、预处理、后端适配与 RKNN / TensorRT 部署。
- [camera-calibration-lab](https://github.com/t0ugh-sys/camera-calibration-lab) — 相机标定工具链，支持单目标定、双目标定、角点可视化与去畸变结果验证。
- [DeepRAG](https://github.com/t0ugh-sys/DeepRAG) — 企业级 RAG 知识库系统，支持混合检索、重排、多租户隔离与服务化部署。

Architecture Preview:

```mermaid
flowchart LR
    A["FFmpeg Demux"] --> B["Decoder<br/>MPP / NVDEC"]
    B --> C["Preprocess<br/>RGA / CUDA"]
    C --> D["Inference<br/>RKNN / TensorRT"]
    D --> E["Postprocess<br/>YOLO Decode / NMS"]
    E --> F["Industrial Vision Applications"]
```

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/t0ugh-sys/t0ugh-sys/output/github-contribution-grid-snake-dark.svg?palette=github-dark" />
    <img alt="GitHub contribution snake" src="https://raw.githubusercontent.com/t0ugh-sys/t0ugh-sys/output/github-contribution-grid-snake.svg" />
  </picture>
</div>
