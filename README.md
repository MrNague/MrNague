# Pascal Nague

**Computer Science Student @ RPTU Kaiserslautern-Landau**  
**AI Engineering · Machine Learning Systems · Software Engineering**

I build and evaluate software systems around machine learning models — from **data pipelines and model integration to APIs, automated testing, performance analysis, and usable applications**.

My interests lie at the intersection of **AI Engineering, Data Engineering, and Software Development**. I enjoy turning experimental ideas into structured, reproducible, and maintainable software.

I believe that successful AI engineering goes beyond model accuracy. It also requires reliable data, well-designed software, meaningful evaluation, and an understanding of how systems behave under real-world constraints.

**[Portfolio](https://portfolio.naguepc.de/)** · **[LinkedIn](https://www.linkedin.com/in/pascal-nague/)** · **[GitHub Projects](https://github.com/MrNague?tab=repositories)**

---

## Engineering Focus

- **AI & ML Applications:** integrating models into complete software workflows
- **ML Systems:** data loading, preprocessing, inference, and evaluation pipelines
- **Software Engineering:** modular Python development, APIs, automation, and testing
- **Data Engineering:** validation, processing, reproducibility, and data quality
- **Model Evaluation:** quantitative metrics, error analysis, and reporting
- **Performance Engineering:** benchmarking, profiling, concurrency, and scalability

My guiding principle is simple:

**Build → Measure → Validate → Improve.**

---

## Featured Projects

### ImmoLens — Real Estate Price Prediction Application

**Full-stack ML application | Active development**

ImmoLens explores how a machine learning model can be integrated into an end-to-end software application for estimating residential property prices.

The project includes:

- Data preparation and feature engineering
- Random Forest regression and evaluation
- Model artifact management and prediction workflows
- REST API development using FastAPI
- React-based frontend development
- Input validation and automated testing
- Prediction history and model methodology features under development

The project currently uses synthetic training data, so its results are intended for engineering validation rather than reliable real-world property valuation.

**Technologies:** `Python` · `Scikit-learn` · `FastAPI` · `React` · `Pandas` · `pytest`

[Project repository](https://github.com/MrNague/Immobilien-Vorhersage-projekt)

---

### Minimal Dependency Dataset Library for PyTorch

**ML Systems & Performance Engineering | Completed Bachelor Project at DFKI**

An experimental lightweight data-loading library designed to explore efficient integration of Parquet-backed image datasets into PyTorch training workflows.

My work included:

- Designing a Parquet-backed dataset implementation
- Developing concurrent loading and batching components
- Implementing throughput measurements and performance instrumentation
- Running scalability experiments with 1–32 workers
- Benchmarking against the standard PyTorch DataLoader
- Investigating performance bottlenecks and architectural trade-offs

The original benchmark reached approximately **3,245 samples/second using 16 workers** under the tested configuration.

I subsequently performed an independent validation experiment using a 10,000-image subset of Food-101. The results revealed that the custom loader could remain competitive at low worker counts, but that PyTorch scaled more effectively under the new workload.

This comparison reinforced an important engineering lesson: **a performance improvement must be evaluated across workloads before it can be generalized.**

**Technologies:** `Python` · `PyTorch` · `PyArrow` · `Parquet` · `Concurrency` · `Benchmarking` · `SLURM`

[Main repository](https://github.com/MrNague/minimal-dataset-pytorch) · [Food-101 validation benchmark](https://github.com/MrNague/food101-dataloader-benchmark)

---

### Speech & LLM Quality Lab

**AI Evaluation Infrastructure | Active development**

An engineering project focused on evaluating speech recognition systems and improving the reliability of AI evaluation workflows.

The project is organized around three independent dimensions:

**Data quality:** Are the audio samples, references, and metadata trustworthy?

**Model quality:** What errors does a speech recognition system produce, and how should they be measured?

**Software quality:** Can the evaluation pipeline validate inputs, reproduce measurements, and report results correctly?

Implemented components include:

- Modular Python package and command-line interface
- Audio manifest and JSON Schema validation
- ASR pilot tooling
- Word Error Rate (WER) and Character Error Rate (CER) computation
- Automated tests and validation workflows
- Reporting utilities
- Reference-review and provenance workflows
- Local model preparation and hardware checks

A revised peer beta and additional evaluation features are under development.

**Technologies:** `Python` · `ASR` · `pytest` · `JSON Schema` · `WER/CER` · `Data Validation` · `Model Evaluation`

[Project repository](https://github.com/MrNague/speech-llm-quality-lab)

---

### YOLO Webcam Detection

**Computer Vision & Real-Time Software Integration**

A modular real-time object detection application using a pretrained YOLOv8 model and OpenCV.

Rather than treating object detection as a standalone inference script, this project explores how to integrate computer vision into a structured application.

Implemented functionality includes:

- Webcam capture and real-time processing
- YOLO inference integration
- Person detection and filtering
- Configurable alert conditions
- Automated screenshot capture
- FPS and runtime statistics
- Modular application components

**Technologies:** `Python` · `YOLOv8` · `OpenCV` · `Computer Vision`

[Project repository](https://github.com/MrNague/yolo-webcam-detection)

---

## Technical Toolkit

| Area | Technologies & Practices |
|---|---|
| **Programming** | Python, JavaScript, SQL |
| **Machine Learning** | PyTorch, Scikit-learn, YOLOv8 |
| **Data Engineering** | Pandas, PyArrow, Parquet, Data Validation |
| **Backend & APIs** | FastAPI, REST APIs, Pydantic |
| **Frontend** | React, HTML, CSS, JavaScript |
| **Testing & Quality** | pytest, Automated Testing, JSON Schema, Benchmarking |
| **Development Tools** | Git, GitHub, Docker, Linux, Windows |
| **Performance & Research** | Concurrency, Profiling, SLURM, Reproducible Experiments |

---

## Academic & Community Involvement

**B.Sc. Computer Science — RPTU Kaiserslautern-Landau**

My academic work includes algorithms, software engineering, machine learning, distributed programming, and research-oriented projects.

**Bachelor Project — DFKI**

Completed an experimental PyTorch data-loading project involving concurrency, benchmarks, and performance evaluation.

**Bachelor Seminar — Document Retrieval with LLMs**

Currently studying methods for retrieving evidence from long, multi-page documents, including document representation, segmentation, retrieval strategies, and evaluation.

**Technical Mentoring — JustCode-KL**

Supporting student project development, collaborative engineering practices, and foundational programming skills.

---

## What I'm Looking For

I am interested in **Werkstudent opportunities and collaborative engineering projects** involving:

- AI Engineering and ML-enabled applications
- Python and backend software development
- Data Engineering and automation
- ML Systems, MLOps, and model evaluation
- Software quality, prototyping, and security-related engineering

My goal is to gain hands-on industry experience building reliable software while continuing to deepen my expertise in applied AI and machine learning systems.

---

### Engineering Mindset

> Build systems that work. Measure what matters. Validate assumptions. Improve continuously.

**[Explore my portfolio](https://portfolio.naguepc.de/)**
