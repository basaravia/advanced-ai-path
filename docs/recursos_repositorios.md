# Recursos de los repositorios oficiales de los libros

Cada notebook de la carpeta [`notebooks/`](../notebooks/) incluye una sección **"📦 Recursos de los repositorios oficiales de los libros"** con los enlaces concretos por capítulo. Este documento consolida qué ofrece cada repositorio, cómo abrirlo y qué se aprovechó en la malla. Revisado en septiembre de 2026.

## Repositorios con código ejecutable

| Libro | Repositorio | Qué contiene | Cómo abrir | Se usa en |
|---|---|---|---|---|
| Géron, *Hands-On ML* 3.ª ed. | [ageron/handson-ml3](https://github.com/ageron/handson-ml3) | 19 notebooks de capítulo (`01_...` a `19_...`), `tools_numpy/pandas/matplotlib`, `math_linear_algebra`, `math_differential_calculus`, `extra_autodiff`, `extra_gradient_descent_comparison`, `extra_ann_architectures`; `environment.yml`, `requirements.txt` | Colab: `https://colab.research.google.com/github/ageron/handson-ml3/blob/main/<notebook>.ipynb` | M1 (tools/math), M2 (02-09), M3 (10-11, 14-15), M4 (17), M5 (16), M8 (18), M9 (13, 19) |
| James et al., *ISLP* | [intro-stat-learning/ISLP_labs](https://github.com/intro-stat-learning/ISLP_labs) (+ paquete [`ISLP`](https://github.com/intro-stat-learning/ISLP)) | Labs `Ch02-statlearn-lab` … `Ch13-multiple-lab`; datasets del libro vía `ISLP.load_data` | `uv pip install -r https://raw.githubusercontent.com/intro-stat-learning/ISLP_labs/v2.2.2/requirements.txt` | M2 |
| Bruce, Bruce & Gedeck | [gedeck/practical-statistics-for-data-scientists](https://github.com/gedeck/practical-statistics-for-data-scientists) | Notebooks Python por capítulo (`python/notebooks/Chapter 1 - … 7`), scripts (`python/code`), **19 datasets reales** (`data/`: `state.csv`, `loans_income.csv`, `web_page_data.csv`, `loan_data.csv.gz`, `lc_loans.csv`, `house_sales.csv`, `sp500_data.csv.gz`, `airline_stats.csv`, `kc_tax.csv.gz`…) | Clonar; los notebooks leen `../../data/` | M1 (Cap. 1-3), M2 (Cap. 4-7), M10 (Cap. 3, `loan_data`) |
| Cohen, *Practical Linear Algebra* | [mikexcohen/LinAlg4DataScience](https://github.com/mikexcohen/LinAlg4DataScience) | `LA4DS_ch02.ipynb` … `LA4DS_ch15.ipynb`, `pyFiles/`, `LA4DS_TOC.pdf`; [playlist de soluciones](https://www.youtube.com/watch?v=Vpei9S9mFyM&list=PLn0OLiymPak3REyB3XNqqqsRAhZ3LSEH8) | Clonar / abrir en Colab | M1 |
| Weidman, *Deep Learning from Scratch* | [SethHWeidman/DLFS_code](https://github.com/SethHWeidman/DLFS_code) | Carpetas `01_foundations` … `07_PyTorch`, cada una con notebook *Code* y *Math*; `05_convolutions/Numpy_Convolution_Demos.ipynb`; librería `lincoln/` (añadir a `PYTHONPATH`) | Clonar; `export PYTHONPATH=$PYTHONPATH:/ruta/DLFS_code/lincoln` | M3 |
| Zhang et al., *D2L* | [d2l-ai/d2l-en](https://github.com/d2l-ai/d2l-en) · web <https://d2l.ai> | Todo el libro como notebooks (PyTorch / JAX / TF / MXNet), un directorio por capítulo (`chapter_attention-mechanisms-and-transformers/…`), paquete `d2l` | `pip install d2l`; cada sección tiene botón Colab/SageMaker | M1, M3, M4, M5, M8, M9 |
| Tunstall, von Werra & Wolf | [nlp-with-transformers/notebooks](https://github.com/nlp-with-transformers/notebooks) | `01_introduction` … `11_future-directions`; `install.py`, `environment.yml`; Cap. 7 (QA) sin mantenimiento | Colab/Kaggle/Gradient/SageMaker Studio Lab: `https://colab.research.google.com/github/nlp-with-transformers/notebooks/blob/main/<notebook>.ipynb` | M5 (1-3, 8, 10), M6 (9) |
| Alammar & Grootendorst | [HandsOnLLM/Hands-On-Large-Language-Models](https://github.com/HandsOnLLM/Hands-On-Large-Language-Models) | `chapter01/` … `chapter12/` (un notebook por capítulo, pensados para Colab T4); **bonus**: *Visual Guide to Mamba*, *Quantization*, *Mixture of Experts*, *Reasoning LLMs*, *Illustrated DeepSeek-R1*, *Illustrated Stable Diffusion* | `https://colab.research.google.com/github/HandsOnLLM/Hands-On-Large-Language-Models/blob/main/chapterNN/<notebook>.ipynb` | M4 (bonus SD), M5 (1-3, bonus Mamba/MoE), M6 (6-8, 10-12) |
| Fregly, Barth & Eigenbrode | [generative-ai-on-aws/generative-ai-on-aws](https://github.com/generative-ai-on-aws/generative-ai-on-aws) | Carpetas `01_intro` … `12_bedrock` + `99_chatbot`; p. ej. `06_peft/01_peft_lora_fine_tune_dolly_llama2_adhoc.ipynb`, `06_peft/03_peft_qlora_…`, `06_peft/05_peft_prompt_tuning_bloom.ipynb`, `09_rag/05_langchain_llama2_opensearch_sagemaker.ipynb` | SageMaker Studio (cuenta AWS) | M4 (10-11, 4), M5 (3), M6 (2, 5-9, 12), M8 (7), M9 (4, 8) |
| Sutton & Barto | Oficial: <http://incompleteideas.net/book/code/code2nd.html> · réplica Python: [ShangtongZhang/reinforcement-learning-an-introduction](https://github.com/ShangtongZhang/reinforcement-learning-an-introduction) | Casi todas las figuras del libro por capítulo (`chapter03/grid_world.py`, `chapter06/cliff_walking.py`, `chapter06/windy_grid_world.py`, `chapter13/short_corridor.py`…) | `git clone` y ejecutar los scripts | M8 |

## Repositorios sin código (resúmenes y listas de recursos)

| Libro | Repositorio | Qué contiene | Se usa en |
|---|---|---|---|
| Huyen, *Designing ML Systems* | [chiphuyen/dmls-book](https://github.com/chiphuyen/dmls-book) | `ToC.pdf`, `summary.md`, `mlops-tools.md` (catálogo de herramientas por etapa), `resources.md`, `basic-ml-review.md`. El repo advierte: *"This is NOT a tutorial book"* | M9, M10 |
| Huyen, *AI Engineering* | [chiphuyen/aie-book](https://github.com/chiphuyen/aie-book) | `ToC.md`, `chapter-summaries.md`, `study-notes.md`, `resources.md` (13 secciones: evaluación, RAG/agentes, finetuning, inferencia…), `prompt-examples.md`, `case-studies.md`, `misalignment.md`, `scripts/ai-heatmap.ipynb` | M6, M9, M10 |
| Needham & Hodler, *Graph Algorithms* | Sin repo oficial; libro gratuito en <https://neo4j.com/graph-algorithms-book/>; ejemplos en <https://resources.oreilly.com/examples/0636920233145>; la librería `neo4j-graph-algorithms` está archivada → usar [Neo4j GDS](https://neo4j.com/docs/graph-data-science/current/) | M7 |
| Serra, *Deciphering Data Architectures* | Sin repo; capítulos de muestra y actualizaciones en <https://www.jamesserra.com/my-book/> | M9 |
| Stewart, Kolman & Hill, Zill | Sin repositorios; ejercicios resueltos en las notebooks de Cohen y Géron (`math_*`) | M1 |

## Qué se tomó de los repositorios para esta malla

1. **Índices verificados** (ver [`validacion_bibliografica.md`](validacion_bibliografica.md)): los nombres de notebooks/carpetas confirman la numeración de capítulos citada en cada módulo.
2. **Enlaces directos por capítulo** en la sección "📦 Recursos" de cada notebook, con la nota de *para qué* usarlos en relación con el contenido del módulo.
3. **Datasets reales** recomendados para repetir los ejercicios sintéticos con datos de verdad: Lending Club (`loan_data.csv.gz`) para crédito/equidad, `web_page_data.csv` para A/B, California housing (Géron), `Default`/`Hitters` (ISLP).
4. **Patrones de código** que se reflejan en los notebooks: *gradient check* y capas como clases (Weidman/`lincoln`), pipelines `ColumnTransformer` (Géron Cap. 2), atención desde cero (D2L 11 / Tunstall 3), RAG bi-encoder + re-ranker (Alammar 8), LoRA/QLoRA con `peft` (Fregly 6, Alammar 12), gridworld/cliff walking (Sutton & Barto).
5. **Lecturas primarias** curadas por Huyen (`aie-book/resources.md`) para RAG, agentes, evaluación y optimización de inferencia.

## Avisos de compatibilidad (2026)

- Los notebooks de Géron usan `gym` (M8) y TensorFlow/Keras 2; usa `gymnasium` y `KERAS_BACKEND=torch`/Keras 3.
- Alammar Cap. 7 y Fregly Cap. 9 usan LangChain 0.x (`AgentExecutor`, cadenas legacy); traduce a `create_agent` / LangGraph 1.0.
- Tunstall Cap. 7 (QA) está sin mantenimiento por dependencias obsoletas; el resto se actualiza.
- Needham & Hodler usan la librería `algo.*` de Neo4j 3.x; en Neo4j 5 es `gds.*`.
