# Validación bibliográfica y registro de cambios (edición 2026)

Este documento registra **cómo se verificó cada cita de capítulo** de la malla y qué se corrigió. Los sitios de las editoriales (O'Reilly, d2l.ai, statlearning.com) no eran accesibles desde el entorno de trabajo, así que se usaron los **repositorios oficiales de código de cada libro** (que replican el índice en los nombres de carpetas/notebooks) y páginas de referencia. Fecha de verificación: septiembre de 2026.

## 1. Índices verificados

| Libro | Fuente de verificación | Índice confirmado (capítulos relevantes) |
|---|---|---|
| Zhang et al., *Dive into Deep Learning* | `d2l-ai/d2l-en` (`index.md`, toctree) | 1 Introduction · 2 Preliminaries · 3 Linear Regression · 4 Linear Classification · 5 MLP · 6 Builders' Guide · 7 CNN · 8 Modern CNN · 9 RNN · 10 Modern RNN · **11 Attention & Transformers** · 12 Optimization · 13 Computational Performance · 14 Computer Vision · 15 NLP Pretraining · 16 NLP Applications · **17 Reinforcement Learning** · 18 Gaussian Processes · 19 Hyperparameter Optimization · **20 GANs** · 21 Recommender Systems · Apéndices (Math, Tools). **No existe capítulo de autoencoders.** |
| Géron, *Hands-On ML* 3.ª ed. (2022) | `ageron/handson-ml3` (nombres de notebooks) | 1 Landscape · **2 End-to-End Project** · **3 Classification** · 4 Linear Models · 5 SVM · 6 Trees · 7 Ensembles · 8 Dim. Reduction · 9 Unsupervised · 10 ANNs with Keras · 11 Training DNNs · 12 Custom TF · 13 Data · 14 CNN · 15 Sequences · 16 NLP with RNNs and Attention · **17 Autoencoders, GANs and Diffusion Models** · **18 Reinforcement Learning** · 19 Training & Deploying at Scale |
| James et al., *ISLP* (2023) | `intro-stat-learning/ISLP_labs` | 2 Statistical Learning · 3 Linear Regression · 4 Classification · 5 Resampling · 6 Model Selection & Regularization · 7 Nonlinear · 8 Trees · 9 SVM · 10 Deep Learning · 11 Survival · 12 Unsupervised · 13 Multiple Testing |
| Bruce, Bruce & Gedeck, *Practical Statistics* 2.ª ed. | `gedeck/practical-statistics-for-data-scientists` (notebooks por capítulo) | 1 EDA · 2 Data & Sampling Distributions · 3 Statistical Experiments & Significance Testing · 4 Regression & Prediction · 5 Classification · 6 Statistical ML · 7 Unsupervised Learning |
| Cohen, *Practical Linear Algebra for Data Science* | `mikexcohen/LinAlg4DataScience` + búsqueda | 2-3 Vectors · 4 Vector Applications · 5-6 Matrices · 7 Matrix Applications · 8 Inverse · 9 Orthogonal/QR · 10 Row reduction/LU · **11 General Linear Models & Least Squares** · 12 LS Applications · **13 Eigendecomposition** · **14 SVD** · 15 Eigen/SVD Applications |
| Weidman, *Deep Learning from Scratch* | `SethHWeidman/DLFS_code` (carpetas) | 1 Foundations · 2 Fundamentals · 3 Deep Learning from Scratch · 4 Extensions · 5 Convolutions · 6 RNNs · 7 PyTorch |
| Tunstall, von Werra & Wolf, *NLP with Transformers* | `nlp-with-transformers/notebooks` | 1 Hello Transformers · 2 Text Classification · 3 Transformer Anatomy · 4 Multilingual NER · 5 Text Generation · 6 Summarization · 7 QA · 8 Efficient in Production · 9 Few/No Labels · 10 Training from Scratch · 11 Future Directions |
| Alammar & Grootendorst, *Hands-On LLMs* | `HandsOnLLM/Hands-On-Large-Language-Models` | **1 Introduction to Language Models** · **2 Tokens and Embeddings** · 3 Looking Inside Transformer LLMs · 4 Text Classification · 5 Clustering/Topic Modeling · 6 Prompt Engineering · 7 Advanced Text Generation · 8 Semantic Search & RAG · 9 Multimodal · 10 Creating Embedding Models · 11 Fine-tuning Representation Models · 12 Fine-tuning Generation Models |
| Fregly, Barth & Eigenbrode, *Generative AI on AWS* | `generative-ai-on-aws/generative-ai-on-aws` | 1 Use Cases · 2 Prompt Engineering & ICL · 3 LLM Foundation Models · 4 Quantization & Distributed · 5 Fine-Tuning & Evaluation · 6 PEFT · 7 RLHF · 8 Optimize & Deploy · 9 RAG & Agents · 10 Multimodal · 11 Stable Diffusion · 12 Bedrock |
| Huyen, *Designing ML Systems* (2022) | búsqueda web (capítulos citados en O'Reilly/resúmenes) | 1 Overview · 2 Intro to ML Systems Design · 3 Data Engineering · 4 Training Data · 5 Feature Engineering · **6 Model Development & Offline Evaluation** · **7 Model Deployment & Prediction Service** · 8 Data Distribution Shifts & Monitoring · 9 Continual Learning & Test in Production · 10 Infrastructure & Tooling for MLOps · **11 The Human Side of ML** |
| Huyen, *AI Engineering* (2025) | `chiphuyen/aie-book/chapter-summaries.md` | 1 Intro · 2 Understanding Foundation Models · 3 Evaluation Methodology · 4 Evaluate AI Systems · 5 Prompt Engineering · 6 RAG and Agents · 7 Finetuning · 8 Dataset Engineering · 9 Inference Optimization · 10 AI Engineering Architecture & User Feedback |
| Needham & Hodler, *Graph Algorithms* (2019) | búsqueda web (O'Reilly, PDF de cortesía Neo4j) | 1 Introduction · 2 Graph Theory & Concepts · **3 Graph Platforms & Processing** · 4 Pathfinding & Search · 5 Centrality · 6 Community Detection · 7 In Practice · 8 Graph Algorithms to Enhance ML |
| Serra, *Deciphering Data Architectures* (2024) | búsqueda web (TOC en jamesserra.com / blog del autor) | Parte I: 1 Big Data · 2 Types of Data Architectures · 3 Architecture Design Session · Parte II: conceptos (4-9) · Parte III: **10 Modern Data Warehouse · 11 Data Fabric · 12 Data Lakehouse · 13-14 Data Mesh** · Parte IV: personas/procesos y tecnologías |
| Sutton & Barto, *RL: An Introduction* 2.ª ed. | búsqueda web (índice del libro) | 3 Finite MDPs · 4 Dynamic Programming · 5 Monte Carlo · 6 Temporal-Difference Learning · 13 Policy Gradient Methods |
| Stewart, *Cálculo de varias variables. Trascendentes tempranas* | búsqueda web (índice Cengage) | 10 Paramétricas/polares · 11 Series · 12 Vectores · 13 Funciones vectoriales · **14 Derivadas parciales** · 15 Integrales múltiples · 16 Cálculo vectorial · 17 EDO 2.º orden |
| Kolman & Hill, *Álgebra Lineal* 8.ª ed. | búsqueda web (índice) | 1 Ecuaciones lineales y matrices · 2 Sistemas · 3 Determinantes · 4 Espacios vectoriales reales · 5 Producto interno · 6 Transformaciones lineales · 8 Valores y vectores propios · 9 Aplicaciones de eigen |
| Zill, *Ecuaciones diferenciales con aplicaciones de modelado* 9.ª ed. | búsqueda web (índice Cengage) | 1 Introducción · 2 EDO de primer orden · 3 Modelado 1.er orden · 4 Orden superior · 5 Modelado orden superior · 6 Series · 7 Laplace · 8 Sistemas lineales · 9 Soluciones numéricas |

## 2. Correcciones respecto a la malla anterior

| Módulo | Cita anterior | Problema | Cita corregida |
|---|---|---|---|
| 1 | Stewart Cap. 4-5 | Corresponden a cálculo de una variable | Stewart **Cap. 14** (derivadas parciales, gradiente, Lagrange) |
| 1 | Kolman Cap. 1-2; Cohen Cap. 1 | Insuficiente para IA (faltan eigen/SVD/mínimos cuadrados) | Kolman **1, 4, 5, 8**; Cohen **2-3, 5-6, 11, 13, 14** |
| 1 | Zill sin capítulo | — | Zill **1-2, 9** (métodos numéricos ↔ Neural ODEs / difusión) |
| 2 | James et al. (2020) ed. R | El curso es en Python | **ISLP (2023)** Cap. 2-6, 8, 12 |
| 3 | Zhang et al. Cap. 2 "redes neuronales" | El Cap. 2 de D2L son *Preliminaries* | D2L **Cap. 3-6** (+7-10, 12) |
| 4 | Zhang et al. Cap. 7 Autoencoders / Cap. 8 GANs | Cap. 7-8 son CNN; GAN es Cap. 20; no hay cap. de autoencoders | D2L **Cap. 20**; autoencoders en Géron **Cap. 17** |
| 5 | Alammar Cap. 2 "Introducción a LLMs" | El Cap. 2 es *Tokens and Embeddings* | Alammar **Cap. 1** (intro), **2** (tokens), **3** (interior) |
| 7 | Needham & Hodler Cap. 3 | Es el capítulo de plataformas | Needham **Cap. 2, 4, 5, 6, 8** |
| 7 | Sutton & Barto "capítulos iniciales" | Vago | **Cap. 3, 4, 5, 6, 13** |
| 8 (ahora 9) | Huyen Cap. 6 "sistemas en producción"; Serra Cap. 4 | Cap. 6 es *Model Development*; las arquitecturas de Serra están en 10-14 | Huyen DMLS **7-10** (+3-6); Serra **1-3, 10-14** |
| 9 (ahora 10) | Huyen Cap. 7 "ética y gobernanza" | Cap. 7 es *Model Deployment* | Huyen DMLS **Cap. 11** |

## 3. Actualizaciones de práctica (verificadas en septiembre de 2026)

| Tema | Evidencia consultada | Decisión |
|---|---|---|
| Versiones | PyTorch 2.13+ (jul-2026), scikit-learn 1.9 (jun-2026), Keras 3 multi-backend (JAX/TF/PyTorch) | PyTorch como framework principal; Keras 3 como vía para el código TF |
| Entrenamiento distribuido | Horovod deprecado en Databricks (tras 15.4 LTS); recomendaciones: FSDP, DeepSpeed, Ray Train, Accelerate | Se elimina Horovod del temario; se enseña DDP/FSDP2 |
| LLM frameworks | LangChain 1.0 y LangGraph 1.0 (oct-2025); `AgentExecutor` deprecado; `create_agent` | Módulo 6 nuevo; ejemplos con `create_agent`/StateGraph |
| Protocolos de agentes | MCP (nov-2024) donado a la Linux Foundation / Agentic AI Foundation (ene-2026); adoptado por OpenAI, Google, Microsoft, AWS | MCP como estándar de herramientas en el Módulo 6 |
| Generativo | Flow matching / rectified flow como objetivo de SD3, FLUX; comparativas 2025-26 | DDPM + Flow Matching implementados desde cero en el Módulo 4 |
| Secuencias | Mamba-3 (Princeton PLI, 2026); híbridos SSM+atención (Zamba2, Hymba, Jamba…) | SSM selectivo implementado; híbridos como estado del arte |
| Regulación | Calendario AI Act: prohibiciones 2-feb-2025; GPAI 2-ago-2025; aplicación general/Art. 50 2-ago-2026; alto riesgo Anexo III **2-dic-2027** y Anexo I **2-ago-2028** (aplazados por el Digital Omnibus) | Tabla de calendario en el Módulo 10 con aviso de verificar la fecha vigente |

## 4. Fuentes consultadas

- https://github.com/d2l-ai/d2l-en · https://github.com/ageron/handson-ml3 · https://github.com/intro-stat-learning/ISLP_labs · https://github.com/gedeck/practical-statistics-for-data-scientists · https://github.com/mikexcohen/LinAlg4DataScience · https://github.com/SethHWeidman/DLFS_code · https://github.com/nlp-with-transformers/notebooks · https://github.com/HandsOnLLM/Hands-On-Large-Language-Models · https://github.com/generative-ai-on-aws/generative-ai-on-aws · https://github.com/chiphuyen/aie-book · https://github.com/chiphuyen/dmls-book
- https://www.oreilly.com/library/view/graph-algorithms/9781492047674/ · https://www.jamesserra.com/my-book/ · http://incompleteideas.net/book/the-book-2nd.html
- https://artificialintelligenceact.eu/implementation-timeline/ · https://www.euaiact.com/implementation-timeline
- https://www.langchain.com/blog/langchain-langgraph-1dot0 · https://en.wikipedia.org/wiki/Model_Context_Protocol · https://pli.princeton.edu/blog/2026/mamba-3-improved-sequence-modeling-using-state-space-principles · https://docs.databricks.com/aws/en/archive/machine-learning/train-model/horovod · https://github.com/pytorch/pytorch/releases · https://scikit-learn.org/stable/whats_new.html · https://keras.io/keras_3/
