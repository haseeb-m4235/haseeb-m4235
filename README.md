# Hi, I'm Haseeb

I'm an **AI Engineer** who is deeply passionate about **Machine Learning** and **Deep Learning**.
I enjoy turning research ideas into systems that solve real problems, and I care about building things that are simple, robust, and scalable.

## What I'm working on

I currently work as an **AI Engineer at BetaCodes**, where I'm building a project that aims to **revolutionize how compute clusters are deployed and acquired by users**.
The goal is to make provisioning and accessing clusters dramatically simpler, faster, and more accessible than it is today.

## Interests

- Machine Learning and Deep Learning
- Computer Vision and image segmentation
- LLM tooling, agents, and observability
- Building scalable, production-grade AI systems

## Tech Stack

<p align="left">
  <img src="https://cdn.simpleicons.org/python" alt="Python" height="50" />
  &nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/linux" alt="Linux" height="50" />
  &nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/tensorflow" alt="TensorFlow" height="50" />
  &nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/pytorch" alt="PyTorch" height="50" />
  &nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/fastapi" alt="FastAPI" height="50" />
  &nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/databricks" alt="Databricks" height="50" />
  &nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/snowflake" alt="Snowflake" height="50" />
  &nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/huggingface" alt="Hugging Face" height="50" />
  &nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/scikitlearn" alt="scikit-learn" height="50" />
</p>

## Open Source Contributions

**[Arize-ai/openinference #3308](https://github.com/Arize-ai/openinference/pull/3308)** - `fix(langchain): accept LangGraph interrupt and resume callbacks`

Fixed a bug in the OpenInference LangChain instrumentor where LangGraph's graph-level lifecycle callbacks (`on_interrupt` and `on_resume`) were dispatched to a tracer that didn't implement them.
This caused `langchain_core` to raise `AttributeError` and spam warning logs on every interrupt and resume event.
The fix adds no-op handlers for these lifecycle events, silencing the log noise while keeping tracing behavior and emitted spans completely unchanged.

## Publications

- **Segmentation of Wheat Rust Disease Using Co-Salient Feature Extraction**
  *AgriEngineering* (MDPI), 2025, 7(2), 23.
  [DOI: 10.3390/agriengineering7020023](https://www.mdpi.com/2624-7402/7/2/23)
  A two-stage pipeline that pairs a Vision Transformer classifier with a lightweight co-salient object detection model to segment wheat stripe rust, achieving higher F1, precision, and recall with roughly 5x less training time than prior state-of-the-art.

- **Cell Segmentation Beyond 2D - A Review of the State-of-the-Art**
  *Advanced Intelligent Discovery* (Wiley), 2026.
  [DOI: 10.1002/aidi.202500206](https://advanced.onlinelibrary.wiley.com/doi/10.1002/aidi.202500206)
  A review of deep learning approaches to cell segmentation that move beyond conventional 2D analysis, covering both pseudo-3D (2.5D) methods and fully 3D methods that exploit volumetric microscopy data.

## Connect

- GitHub: [@haseeb-m4235](https://github.com/haseeb-m4235)
- LinkedIn: [haseeb-muhammad](https://www.linkedin.com/in/haseeb-muhammad-1a8697274/)
- X: [@haseeb_md04](https://x.com/haseeb_md04)
- Email: [haseebmuhamamd4235@gmail.com](mailto:haseebmuhamamd4235@gmail.com)
