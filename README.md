# Pascal Nague

Computer Science student at **RPTU Kaiserslautern-Landau**, working on **machine learning systems, data pipelines, model evaluation and performance engineering**.

I am particularly interested in the engineering around ML models: how data is loaded and validated, how model behaviour is measured, where performance bottlenecks appear, and how experimental ML components become usable software.

**Portfolio:** [pascal-cabrel-nague-portfolio.netlify.app](https://pascal-cabrel-nague-portfolio.netlify.app/)  
**LinkedIn:** [linkedin.com/in/pascal-nague](https://www.linkedin.com/in/pascal-nague/)

---

## ⚙️ Current work

- ML systems and performance engineering
- Data pipelines and data quality
- ASR / LLM evaluation
- Computer vision applications
- AI-assisted software and automation
- Benchmarking, profiling and reproducible experiments

I prefer projects where results can be **measured, reproduced and explained**, rather than treating the model as a black box.

---

## 🧪 Selected projects

### Minimal Dependency Dataset Library for PyTorch

A lightweight experimental data-loading library developed during my **completed Bachelor Project at DFKI**.

The project explores Parquet-backed image datasets and a custom concurrent loading architecture designed to integrate with standard PyTorch training code.

I built and benchmarked:

- a Parquet-backed dataset implementation
- a multi-threaded loading pipeline
- worker and batching orchestration
- throughput instrumentation
- scaling experiments from 1 to 32 workers
- comparisons against `torch.utils.data.DataLoader`

The original benchmarks reached a measured peak of approximately **3,245 samples/s at 16 workers**.

To test whether those results generalized beyond the original workload, I later built a separate validation benchmark using **Food-101**. That experiment showed an important limitation: the custom loader remained competitive at low worker counts, while PyTorch scaled better under the new workload.

**Stack:** `Python` · `PyTorch` · `PyArrow` · `Parquet` · `Concurrency` · `Benchmarking` · `SLURM`

[Repository](https://github.com/MrNague/minimal-dataset-pytorch) · [Food-101 validation](https://github.com/MrNague/food101-dataloader-benchmark)

---

### Speech & LLM Quality Lab

An **active engineering project** for evaluating speech-to-text systems and reviewing LLM outputs.

The project separates three different quality problems:

- **Data quality** — is the reference itself correct?
- **Model quality** — what errors does the model produce?
- **Software quality** — does the evaluation system measure and store results correctly?

The current implementation includes:

- Python package and CLI
- JSON schema validation
- audio manifest validation
- ASR pilot tooling
- WER / CER computation
- automated tests
- reporting utilities
- recording and reference-review workflows
- local model and hardware preparation tools

The revised peer beta is currently under development.

**Stack:** `Python` · `ASR` · `WER/CER` · `pytest` · `JSON Schema` · `Data Validation` · `Model Evaluation`

[Repository](https://github.com/MrNague/speech-llm-quality-lab)

---

### YOLO Webcam Detection

A modular real-time computer-vision application built with **YOLOv8 and OpenCV**.

Instead of stopping at model inference, the project wraps the detector inside an application with separate components for:

- webcam streaming
- YOLO inference
- person filtering
- configurable alarm logic
- automated screenshots
- FPS and runtime statistics

It was mainly an exercise in moving from **using a pretrained model** to integrating one into a structured software system.

**Stack:** `Python` · `YOLOv8` · `OpenCV` · `Computer Vision`

[Repository](https://github.com/MrNague/yolo-webcam-detection)

---

### Food-101 DataLoader Benchmark

An external validation experiment for the Minimal Dataset project using a reproducible **10,000-image subset of Food-101**.

The benchmark compares the custom loader with PyTorch across:

- multiple worker counts
- different image resolutions
- different batch sizes
- identical preprocessing pipelines

The results helped identify where the custom architecture scales well and where its current design reaches a throughput plateau.

**Stack:** `Python` · `PyTorch` · `Food-101` · `Parquet` · `Benchmarking` · `Performance Analysis`

[Repository](https://github.com/MrNague/food101-dataloader-benchmark)

---

## 🛠 Stack

**Machine Learning**

`Python` · `PyTorch` · `Scikit-learn` · `YOLO` · `OpenCV`

**Data & ML Systems**

`Pandas` · `PyArrow` · `Parquet` · `Data Pipelines` · `Model Evaluation` · `Benchmarking` · `Concurrency`

**Software Engineering**

`Git` · `GitHub` · `Docker` · `Linux` · `Windows` · `pytest` · `SLURM`

**Web**

`HTML` · `CSS` · `JavaScript`

---

## 🌐 Portfolio

My portfolio is built from scratch with vanilla HTML, CSS and JavaScript.

It serves as a central place for my technical projects, current engineering focus and professional profile.

[Visit portfolio](https://pascal-cabrel-nague-portfolio.netlify.app/) · [Source](https://github.com/MrNague/pascal-nague-portfolio)

---

## Current status

- **B.Sc. Computer Science** — RPTU Kaiserslautern-Landau
- **Bachelor Project at DFKI** — completed
- **Speech & LLM Quality Lab** — active development
- Building deeper experience in **ML systems, evaluation, data engineering and AI automation**
- Open to **Werkstudent roles and technical projects** in ML, Data and AI Engineering

---

> Build → measure → validate → improve.
