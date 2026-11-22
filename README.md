# Awesome Python Ecosystem

A curated map of essential, popular, emerging, and specialized Python libraries for real-world development.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: CC0-1.0](https://img.shields.io/badge/license-CC0--1.0-lightgrey.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/MertGedik35/awesome-python-ecosystem?style=social)](https://github.com/MertGedik35/awesome-python-ecosystem)
[![Last commit](https://img.shields.io/github/last-commit/MertGedik35/awesome-python-ecosystem)](https://github.com/MertGedik35/awesome-python-ecosystem/commits/main)

## Introduction

Awesome Python Ecosystem is a curated guide to Python libraries, frameworks, tools, and packages organized by what developers want to build. It is for beginners choosing a first library, experienced engineers comparing alternatives, researchers looking for domain tools, and maintainers evaluating ecosystem options.

Projects are selected for clear purpose, official documentation, source availability, practical usefulness, ecosystem relevance, maintenance signals, adoption, and licensing clarity. Official documentation, canonical source repositories, and PyPI pages are prioritized because they are more reliable than tutorials or mirrors. Inclusion is informational, not an endorsement, certification, or guarantee of safety, quality, compatibility, or future maintenance.

## How to Use This Guide

- Start with [Essential Python Libraries](#essential-python-libraries) for widely useful projects.
- Use [Most Popular by Category](#most-popular-by-category) for recognized starting points without treating the list as a strict ranking.
- Use [Choose by What You Want to Build](#choose-by-what-you-want-to-build) when you have a practical goal.
- Browse [Core Development Categories](#core-development-categories) for technical areas and [Specialized and Niche Domains](#specialized-and-niche-domains) for industries or research fields.
- Check [Library Comparison Guides](#library-comparison-guides) when several projects solve similar problems.
- Follow official documentation and PyPI package names before installing anything.

## Quick Navigation

- [Introduction](#introduction)
- [How to Use This Guide](#how-to-use-this-guide)
- [Quick Navigation](#quick-navigation)
- [Essential Python Libraries](#essential-python-libraries)
- [Most Popular by Category](#most-popular-by-category)
- [Choose by What You Want to Build](#choose-by-what-you-want-to-build)
- [Python Standard Library Highlights](#python-standard-library-highlights)
- [Core Development Categories](#core-development-categories)
- [Specialized and Niche Domains](#specialized-and-niche-domains)
- [Library Comparison Guides](#library-comparison-guides)
- [Emerging Projects](#emerging-projects)
- [Selection Criteria](#selection-criteria)
- [Status Labels](#status-labels)
- [Contributing](#contributing)
- [Disclaimer](#disclaimer)

## Essential Python Libraries

These are widely relevant projects that many Python developers evaluate early. They are not ranked, and they are not the only good options.

| Project | Primary use | Install | Links |
| ------- | ----------- | ------- | ----- |
| [NumPy](https://numpy.org/) | Foundational arrays and numerical computing for scientific Python. | `pip install numpy` | [Docs](https://numpy.org/doc/) · [Source](https://github.com/numpy/numpy) · [PyPI](https://pypi.org/project/numpy/) |
| [pandas](https://pandas.pydata.org/) | Widely adopted DataFrame library for data cleaning, analysis, and tabular workflows. | `pip install pandas` | [Docs](https://pandas.pydata.org/docs/) · [Source](https://github.com/pandas-dev/pandas) · [PyPI](https://pypi.org/project/pandas/) |
| [Polars](https://pola.rs/) | Performance-focused DataFrame engine with eager and lazy APIs. | `pip install polars` | [Docs](https://docs.pola.rs/) · [Source](https://github.com/pola-rs/polars) · [PyPI](https://pypi.org/project/polars/) |
| [SciPy](https://scipy.org/) | Core algorithms for optimization, statistics, integration, signal processing, and scientific computing. | `pip install scipy` | [Docs](https://docs.scipy.org/doc/scipy/) · [Source](https://github.com/scipy/scipy) · [PyPI](https://pypi.org/project/scipy/) |
| [Matplotlib](https://matplotlib.org/) | General-purpose plotting library used throughout the scientific Python ecosystem. | `pip install matplotlib` | [Docs](https://matplotlib.org/stable/) · [Source](https://github.com/matplotlib/matplotlib) · [PyPI](https://pypi.org/project/matplotlib/) |
| [Plotly](https://plotly.com/python/) | Interactive charting library for notebooks, dashboards, and web applications. | `pip install plotly` | [Source](https://github.com/plotly/plotly.py) · [PyPI](https://pypi.org/project/plotly/) |
| [Requests](https://requests.readthedocs.io/) | Synchronous HTTP client with a simple API for everyday web requests. | `pip install requests` | [Source](https://github.com/psf/requests) · [PyPI](https://pypi.org/project/requests/) |
| [HTTPX](https://www.python-httpx.org/) | Modern HTTP client with sync, async, HTTP/2, and transport customization support. | `pip install httpx` | [Source](https://github.com/encode/httpx) · [PyPI](https://pypi.org/project/httpx/) |
| [aiohttp](https://docs.aiohttp.org/en/stable/) | Asynchronous HTTP client and server framework built on asyncio. | `pip install aiohttp` | [Source](https://github.com/aio-libs/aiohttp) · [PyPI](https://pypi.org/project/aiohttp/) |
| [Pydantic](https://docs.pydantic.dev/) | Data validation and settings management using Python type hints. | `pip install pydantic` | [Source](https://github.com/pydantic/pydantic) · [PyPI](https://pypi.org/project/pydantic/) |
| [FastAPI](https://fastapi.tiangolo.com/) | API framework built around type hints, OpenAPI, and ASGI. | `pip install fastapi` | [Source](https://github.com/fastapi/fastapi) · [PyPI](https://pypi.org/project/fastapi/) |
| [Django](https://www.djangoproject.com/) | Batteries-included web framework for full web applications. | `pip install Django` | [Docs](https://docs.djangoproject.com/) · [Source](https://github.com/django/django) · [PyPI](https://pypi.org/project/Django/) |
| [Flask](https://flask.palletsprojects.com/) | Minimal web framework with a large extension ecosystem. | `pip install Flask` | [Source](https://github.com/pallets/flask) · [PyPI](https://pypi.org/project/Flask/) |
| [SQLAlchemy](https://www.sqlalchemy.org/) | SQL toolkit and ORM for relational database applications. | `pip install SQLAlchemy` | [Docs](https://docs.sqlalchemy.org/) · [Source](https://github.com/sqlalchemy/sqlalchemy) · [PyPI](https://pypi.org/project/SQLAlchemy/) |
| [Alembic](https://alembic.sqlalchemy.org/) | Database migration tool commonly used with SQLAlchemy. | `pip install alembic` | [Source](https://github.com/sqlalchemy/alembic) · [PyPI](https://pypi.org/project/alembic/) |
| [pytest](https://docs.pytest.org/) | Flexible testing framework for unit, integration, and functional tests. | `pip install pytest` | [Source](https://github.com/pytest-dev/pytest) · [PyPI](https://pypi.org/project/pytest/) |
| [Ruff](https://docs.astral.sh/ruff/) | Fast Python linter and formatter from Astral. | `pip install ruff` | [Source](https://github.com/astral-sh/ruff) · [PyPI](https://pypi.org/project/ruff/) |
| [mypy](https://mypy-lang.org/) | Static type checker for Python codebases that use type annotations. | `pip install mypy` | [Docs](https://mypy.readthedocs.io/) · [Source](https://github.com/python/mypy) · [PyPI](https://pypi.org/project/mypy/) |
| [Black](https://black.readthedocs.io/) | Opinionated code formatter that reduces style debates. | `pip install black` | [Source](https://github.com/psf/black) · [PyPI](https://pypi.org/project/black/) |
| [Poetry](https://python-poetry.org/) | Project packaging and dependency management tool. | `pip install poetry` | [Docs](https://python-poetry.org/docs/) · [Source](https://github.com/python-poetry/poetry) · [PyPI](https://pypi.org/project/poetry/) |
| [uv](https://docs.astral.sh/uv/) | Fast Python package and project manager from Astral. | `pip install uv` | [Source](https://github.com/astral-sh/uv) · [PyPI](https://pypi.org/project/uv/) |
| [Pillow](https://pillow.readthedocs.io/) | Imaging library for opening, editing, and saving common image formats. | `pip install Pillow` | [Source](https://github.com/python-pillow/Pillow) · [PyPI](https://pypi.org/project/Pillow/) |
| [OpenCV](https://opencv.org/) | Computer vision library with Python bindings for image and video processing. | `pip install opencv-python` | [Docs](https://docs.opencv.org/) · [Source](https://github.com/opencv/opencv-python) · [PyPI](https://pypi.org/project/opencv-python/) |
| [scikit-image](https://scikit-image.org/) | Image-processing algorithms designed for scientific Python workflows. | `pip install scikit-image` | [Docs](https://scikit-image.org/docs/stable/) · [Source](https://github.com/scikit-image/scikit-image) · [PyPI](https://pypi.org/project/scikit-image/) |
| [scikit-learn](https://scikit-learn.org/stable/) | Standard machine-learning toolkit for classical models and preprocessing. | `pip install scikit-learn` | [Source](https://github.com/scikit-learn/scikit-learn) · [PyPI](https://pypi.org/project/scikit-learn/) |
| [PyTorch](https://pytorch.org/) | Deep-learning framework with strong research and production adoption. | `pip install torch` | [Docs](https://docs.pytorch.org/) · [Source](https://github.com/pytorch/pytorch) · [PyPI](https://pypi.org/project/torch/) |
| [TensorFlow](https://www.tensorflow.org/) | Machine-learning platform for model training, deployment, and production pipelines. | `pip install tensorflow` | [Source](https://github.com/tensorflow/tensorflow) · [PyPI](https://pypi.org/project/tensorflow/) |
| [JAX](https://jax.readthedocs.io/) | Array computing and automatic differentiation system for high-performance ML research. | `pip install jax` | [Source](https://github.com/jax-ml/jax) · [PyPI](https://pypi.org/project/jax/) |
| [Transformers](https://huggingface.co/docs/transformers/) | Model library for transformer-based NLP, vision, audio, and multimodal tasks. | `pip install transformers` | [Source](https://github.com/huggingface/transformers) · [PyPI](https://pypi.org/project/transformers/) |
| [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) | HTML and XML parsing library useful for small scraping and extraction tasks. | `pip install beautifulsoup4` | [Source](https://code.launchpad.net/beautifulsoup) · [PyPI](https://pypi.org/project/beautifulsoup4/) |
| [Scrapy](https://scrapy.org/) | Web crawling framework for structured scraping projects. | `pip install Scrapy` | [Docs](https://docs.scrapy.org/en/latest/) · [Source](https://github.com/scrapy/scrapy) · [PyPI](https://pypi.org/project/Scrapy/) |
| [Selenium](https://www.selenium.dev/) | Browser automation framework for end-to-end tests and web interaction. | `pip install selenium` | [Docs](https://www.selenium.dev/documentation/) · [Source](https://github.com/SeleniumHQ/selenium) · [PyPI](https://pypi.org/project/selenium/) |
| [Playwright](https://playwright.dev/python/) | Modern browser automation library with reliable cross-browser testing support. | `pip install playwright` | [Source](https://github.com/microsoft/playwright-python) · [PyPI](https://pypi.org/project/playwright/) |
| [Typer](https://typer.tiangolo.com/) | CLI framework built on Click and Python type hints. | `pip install typer` | [Source](https://github.com/fastapi/typer) · [PyPI](https://pypi.org/project/typer/) |
| [Click](https://click.palletsprojects.com/) | Composable command-line interface toolkit. | `pip install click` | [Source](https://github.com/pallets/click) · [PyPI](https://pypi.org/project/click/) |
| [Rich](https://rich.readthedocs.io/) | Terminal formatting library for tables, progress bars, tracebacks, and styled text. | `pip install rich` | [Source](https://github.com/Textualize/rich) · [PyPI](https://pypi.org/project/rich/) |
| [Celery](https://docs.celeryq.dev/) | Distributed task queue for background jobs and asynchronous work. | `pip install celery` | [Source](https://github.com/celery/celery) · [PyPI](https://pypi.org/project/celery/) |
| [Dask](https://www.dask.org/) | Parallel and distributed computing library that scales Python analytics workloads. | `pip install dask` | [Docs](https://docs.dask.org/) · [Source](https://github.com/dask/dask) · [PyPI](https://pypi.org/project/dask/) |
| [JupyterLab](https://jupyterlab.readthedocs.io/) | Interactive notebook and computational environment for data, research, and teaching. | `pip install jupyterlab` | [Source](https://github.com/jupyterlab/jupyterlab) · [PyPI](https://pypi.org/project/jupyterlab/) |
| [Streamlit](https://streamlit.io/) | Application framework for data apps and internal tools. | `pip install streamlit` | [Docs](https://docs.streamlit.io/) · [Source](https://github.com/streamlit/streamlit) · [PyPI](https://pypi.org/project/streamlit/) |
| [Gradio](https://www.gradio.app/) | UI framework for demos and machine-learning interfaces. | `pip install gradio` | [Docs](https://www.gradio.app/docs) · [Source](https://github.com/gradio-app/gradio) · [PyPI](https://pypi.org/project/gradio/) |
| [Sphinx](https://www.sphinx-doc.org/) | Documentation generator widely used by Python projects. | `pip install Sphinx` | [Source](https://github.com/sphinx-doc/sphinx) · [PyPI](https://pypi.org/project/Sphinx/) |
| [MkDocs](https://www.mkdocs.org/) | Markdown-oriented documentation site generator. | `pip install mkdocs` | [Source](https://github.com/mkdocs/mkdocs) · [PyPI](https://pypi.org/project/mkdocs/) |
| [pypdf](https://pypdf.readthedocs.io/) | Pure-Python toolkit for splitting, merging, and inspecting PDF files. | `pip install pypdf` | [Source](https://github.com/py-pdf/pypdf) · [PyPI](https://pypi.org/project/pypdf/) |

## Most Popular by Category

This section is an editorial overview of recognized starting points. Labels such as common default, widely adopted, modern, and performance-focused describe common usage patterns, not objective rankings.

| Category | Projects to evaluate first | Selection note |
| --- | --- | --- |
| Data analysis | pandas | Common default for tabular analysis; consider Polars for performance-sensitive workflows. |
| Data visualization | Matplotlib, seaborn, Plotly, Altair | Choose static, statistical, interactive, or declarative plotting based on output needs. |
| Scientific computing | NumPy, SciPy, SymPy, Xarray | Start with NumPy/SciPy; use SymPy for symbolic math and Xarray for labeled multidimensional data. |
| Machine learning | scikit-learn, XGBoost, LightGBM, CatBoost | scikit-learn is the general baseline; gradient boosting libraries are strong for tabular prediction. |
| Deep learning | PyTorch, TensorFlow, JAX, Keras | PyTorch is common in research; TensorFlow remains important for production ecosystems; JAX is strong for differentiable systems. |
| Generative AI and LLMs | Transformers, vLLM, LangChain, LlamaIndex | Separate model access, inference, orchestration, retrieval, and evaluation decisions. |
| Web development | Django, Flask, FastAPI, Litestar | Django favors full applications; Flask and FastAPI fit smaller services; Litestar is a modern ASGI option. |
| API development | FastAPI, Django REST Framework, Starlette | FastAPI is a strong default for typed APIs; DRF is the natural choice inside Django. |
| HTTP clients | Requests, HTTPX, aiohttp | Requests is simple and synchronous; HTTPX covers sync and async; aiohttp is asyncio-oriented. |
| Web scraping | Beautiful Soup, lxml, Scrapy, Playwright | Use parsers for HTML extraction, Scrapy for crawlers, and browser automation for JavaScript-heavy pages. |
| Browser automation | Playwright, Selenium | Playwright has modern test ergonomics; Selenium remains widely supported across browser infrastructure. |
| Databases and ORMs | SQLAlchemy, Django ORM, SQLModel, asyncpg | Pick ORM, query builder, or driver based on how much abstraction the application needs. |
| Testing | pytest, Hypothesis, coverage.py, tox | pytest is the common default; add property tests, coverage, and environment automation as risk increases. |
| Code quality | Ruff, Black, mypy, Pyright | Ruff and Black cover style quickly; type checkers catch interface and data-shape mistakes. |
| Command-line applications | Click, Typer, argparse, Rich | Click is mature, Typer is annotation-friendly, argparse has no dependency, and Rich improves terminal output. |
| Desktop applications | PySide6, PyQt6, Tkinter, Kivy, Flet | Licensing and target platform matter more than generic popularity. |
| Task queues | Celery, RQ, Dramatiq, Huey | Celery is feature-rich; RQ and Huey are simpler; Dramatiq is a focused modern worker option. |
| Workflow orchestration | Airflow, Prefect, Dagster, Luigi | Airflow is scheduler-centric; Prefect and Dagster emphasize Python-native workflows and observability. |
| Parallel and distributed computing | Dask, Ray, PySpark | Dask fits Python analytics; Ray fits distributed applications and ML systems; PySpark fits Spark clusters. |
| Configuration | Pydantic Settings, Dynaconf, Hydra, OmegaConf | Use simple environment loading for apps and structured configuration for complex experiments. |
| Logging and observability | logging, structlog, Loguru, OpenTelemetry, Sentry | Start with the standard library, then add structured events, traces, metrics, and error monitoring. |

## Choose by What You Want to Build

| Goal | Evaluate first | How to choose |
| --- | --- | --- |
| I want to build a REST API | FastAPI, Litestar, Django REST Framework | FastAPI is a practical typed default; DRF fits Django projects; Litestar is worth evaluating for modern ASGI services. |
| I want to build a full web application | Django, Flask, FastAPI plus templates | Django gives the most built-in structure; Flask is smaller; FastAPI works well when the app is API-first. |
| I want to analyze tabular data | pandas, Polars, DuckDB | Use pandas for broad compatibility, Polars for speed, and DuckDB for SQL over local analytical data. |
| I want maximum DataFrame performance | Polars, DuckDB, PyArrow, Dask | Benchmark on real data; columnar formats and lazy execution often matter more than API preference. |
| I want to automate a browser | Playwright, Selenium | Playwright is often easier for modern web apps; Selenium remains useful where existing grid infrastructure matters. |
| I want to scrape websites | Beautiful Soup, lxml, Scrapy, trafilatura | Use parsers for small jobs, Scrapy for crawlers, and extraction libraries for article-like text. |
| I want to train a machine-learning model | scikit-learn, XGBoost, LightGBM, CatBoost | Start with scikit-learn baselines and compare gradient boosting for structured prediction. |
| I want to work with LLMs | Transformers, vLLM, LiteLLM, LangChain, LlamaIndex | Separate local inference, provider routing, orchestration, and retrieval before choosing a stack. |
| I want to build an AI agent | LangGraph, CrewAI, AutoGen, Pydantic AI | Prefer explicit state, tool boundaries, and testable behavior over vague agent abstractions. |
| I want to create a CLI | argparse, Click, Typer, Rich | argparse is dependency-free; Click is mature; Typer is concise for typed commands; Rich improves output. |
| I want to build a desktop application | PySide6, PyQt6, Tkinter, wxPython, Kivy | Check licensing, native look, packaging, and mobile requirements before choosing. |
| I want to process images | Pillow, OpenCV, scikit-image, Kornia | Pillow is simple, OpenCV is broad, scikit-image is scientific, and Kornia fits differentiable PyTorch image workflows. |
| I want to process video | OpenCV, PyAV, MoviePy, ffmpeg-python | Use OpenCV for frame operations, PyAV/FFmpeg wrappers for codec control, and MoviePy for editing workflows. |
| I want to work with PDFs | pypdf, PyMuPDF, pdfplumber, ReportLab, WeasyPrint | Extraction, editing, generation, and HTML-to-PDF rendering are different problems. |
| I want to create dashboards | Streamlit, Dash, Panel, Gradio | Streamlit is fast for data apps, Dash is web-app oriented, Panel fits HoloViz, and Gradio is strong for ML demos. |
| I want to run background jobs | Celery, RQ, Dramatiq, Huey | Choose based on broker, scheduling, retries, monitoring, and operational complexity. |
| I want to create data pipelines | Airflow, Prefect, Dagster, Luigi, DVC | Use orchestration for scheduled workflows and DVC for data/model versioning. |
| I want to perform optimization | SciPy, CVXPY, PuLP, OR-Tools, Pyomo | Match the solver and modeling layer to convex, linear, routing, or algebraic optimization needs. |
| I want to work with geospatial data | GeoPandas, Shapely, Rasterio, pyproj, Cartopy | Vector, raster, coordinate transformation, and mapping tasks usually require different libraries. |
| I want to automate Excel or Office documents | openpyxl, XlsxWriter, xlwings, python-docx, python-pptx | File generation and live desktop automation are different workflows. |
| I want to monitor a production Python service | OpenTelemetry, prometheus_client, sentry-sdk, structlog | Combine logs, metrics, traces, and error reporting rather than relying on one signal. |
| I want to build network automation | Netmiko, NAPALM, Nornir, Scrapli | Pick a direct device library for scripts and an orchestration framework for fleet operations. |

## Python Standard Library Highlights

The Python standard library does not require `pip install`. Start with the official [Python Standard Library documentation](https://docs.python.org/3/library/) when a built-in module solves the problem well.

| Module | Use |
| --- | --- |
| `pathlib` | Object-oriented filesystem paths. |
| `os` | Operating-system interfaces. |
| `sys` | Interpreter and runtime information. |
| `json` | JSON parsing and writing. |
| `csv` | CSV reading and writing. |
| `datetime` | Dates, times, and time zones. |
| `time` | Time access and simple timing. |
| `math` | Mathematical functions. |
| `statistics` | Basic statistical calculations. |
| `random` | Pseudo-random numbers for non-security use. |
| `collections` | Specialized containers such as `Counter` and `defaultdict`. |
| `itertools` | Iterator building blocks. |
| `functools` | Higher-order functions and caching helpers. |
| `re` | Regular expressions. |
| `logging` | Application logging. |
| `sqlite3` | Built-in SQLite database access. |
| `subprocess` | Process creation and command execution. |
| `threading` | Thread-based concurrency. |
| `multiprocessing` | Process-based concurrency. |
| `asyncio` | Asynchronous I/O framework. |
| `unittest` | Standard-library testing framework. |
| `argparse` | Command-line argument parsing. |
| `typing` | Type-hint support. |
| `dataclasses` | Boilerplate reduction for data containers. |
| `concurrent.futures` | Thread and process executors. |
| `http` | HTTP protocol utilities. |
| `urllib` | URL handling and basic HTTP requests. |
| `secrets` | Cryptographically strong random values. |
| `hashlib` | Secure hash and message digest algorithms. |

## Core Development Categories

The entries below focus on Python packages and tools beyond the essential list. If a common default appears above, this section usually adds alternatives or adjacent tools rather than repeating the same entry.

#### Arrays and numerical computing

- **[Xarray](https://docs.xarray.dev/)** - Labeled arrays for multidimensional scientific data.  
  `pip install xarray` · [Source](https://github.com/pydata/xarray) · [PyPI](https://pypi.org/project/xarray/)
- **[CuPy](https://docs.cupy.dev/)** - NumPy-compatible GPU arrays for NVIDIA CUDA workloads.  
  `pip install cupy` · [Source](https://github.com/cupy/cupy) · [PyPI](https://pypi.org/project/cupy/)
- **[Numba](https://numba.pydata.org/)** - JIT compiler for accelerating numerical Python functions.  
  `pip install numba` · [Source](https://github.com/numba/numba) · [PyPI](https://pypi.org/project/numba/)
- **[numexpr](https://numexpr.readthedocs.io/)** - Fast numerical expression evaluator for array-heavy calculations.  
  `pip install numexpr` · [Source](https://github.com/pydata/numexpr) · [PyPI](https://pypi.org/project/numexpr/)
#### DataFrames and tabular data

- **[PyArrow](https://arrow.apache.org/docs/python/)** - Python bindings for Apache Arrow columnar memory and data interchange.  
  `pip install pyarrow` · [Source](https://github.com/apache/arrow) · [PyPI](https://pypi.org/project/pyarrow/)
- **[DuckDB](https://duckdb.org/docs/api/python/overview)** - Embedded analytical database with a strong Python API.  
  `pip install duckdb` · [Source](https://github.com/duckdb/duckdb) · [PyPI](https://pypi.org/project/duckdb/)
- **[Ibis](https://ibis-project.org/)** - Portable dataframe expression system that targets multiple SQL and dataframe backends.  
  `pip install ibis-framework` · [Source](https://github.com/ibis-project/ibis) · [PyPI](https://pypi.org/project/ibis-framework/)
- **[Modin](https://modin.readthedocs.io/)** - Distributed DataFrame engine designed to speed up pandas-like workloads.  
  `pip install modin` · [Source](https://github.com/modin-project/modin) · [PyPI](https://pypi.org/project/modin/)
#### Distributed data processing

- **[Ray](https://docs.ray.io/)** - Distributed computing framework for Python applications and ML systems.  
  `pip install ray` · [Source](https://github.com/ray-project/ray) · [PyPI](https://pypi.org/project/ray/)
- **[PySpark](https://spark.apache.org/docs/latest/api/python/)** - Python API for Apache Spark distributed data processing.  
  `pip install pyspark` · [Source](https://github.com/apache/spark) · [PyPI](https://pypi.org/project/pyspark/)
#### Data validation

- **[Pandera](https://pandera.readthedocs.io/)** - Schema validation for pandas, Polars, and related dataframe workflows.  
  `pip install pandera` · [Source](https://github.com/unionai-oss/pandera) · [PyPI](https://pypi.org/project/pandera/)
- **[Cerberus](https://docs.python-cerberus.org/)** - Lightweight validation library for dictionaries and document-like data.  
  `pip install Cerberus` · [Source](https://github.com/pyeve/cerberus) · [PyPI](https://pypi.org/project/Cerberus/)
- **[marshmallow](https://marshmallow.readthedocs.io/)** - Object serialization and validation library for Python data structures.  
  `pip install marshmallow` · [Source](https://github.com/marshmallow-code/marshmallow) · [PyPI](https://pypi.org/project/marshmallow/)
#### Data profiling and quality

- **[Great Expectations](https://docs.greatexpectations.io/)** - Data quality framework for expectations, validation, and documentation.  
  `pip install great_expectations` · [Source](https://github.com/great-expectations/great_expectations) · [PyPI](https://pypi.org/project/great_expectations/)
- **[Soda Core](https://docs.soda.io/)** - Open-source data quality checks and monitoring for data pipelines.  
  `pip install soda-core` · [Source](https://github.com/sodadata/soda-core) · [PyPI](https://pypi.org/project/soda-core/)
- **[ydata-profiling](https://docs.profiling.ydata.ai/)** - Exploratory data profiling reports for tabular datasets.  
  `pip install ydata-profiling` · [Source](https://github.com/ydataai/ydata-profiling) · [PyPI](https://pypi.org/project/ydata-profiling/)
#### Data versioning and serialization

- **[DVC](https://dvc.org/doc)** - Data and model versioning tool for ML and data workflows.  
  `pip install dvc` · [Source](https://github.com/iterative/dvc) · [PyPI](https://pypi.org/project/dvc/)
- **[orjson](https://github.com/ijl/orjson)** - Fast JSON library with dataclass, datetime, and NumPy support.  
  `pip install orjson` · [PyPI](https://pypi.org/project/orjson/)
- **[PyYAML](https://pyyaml.org/wiki/PyYAMLDocumentation)** - YAML parser and emitter for configuration and data files.  
  `pip install PyYAML` · [Source](https://github.com/yaml/pyyaml) · [PyPI](https://pypi.org/project/PyYAML/)
- **[msgpack](https://msgpack-python.readthedocs.io/)** - MessagePack serialization library for compact binary data exchange.  
  `pip install msgpack` · [Source](https://github.com/msgpack/msgpack-python) · [PyPI](https://pypi.org/project/msgpack/)
#### Data visualization

- **[seaborn](https://seaborn.pydata.org/)** - Statistical data visualization library built on Matplotlib.  
  `pip install seaborn` · [Source](https://github.com/mwaskom/seaborn) · [PyPI](https://pypi.org/project/seaborn/)
- **[Altair](https://altair-viz.github.io/)** - Declarative statistical visualization library based on Vega-Lite.  
  `pip install altair` · [Source](https://github.com/vega/altair) · [PyPI](https://pypi.org/project/altair/)
- **[Bokeh](https://docs.bokeh.org/)** - Interactive visualization library for browsers and dashboards.  
  `pip install bokeh` · [Source](https://github.com/bokeh/bokeh) · [PyPI](https://pypi.org/project/bokeh/)
- **[HoloViews](https://holoviews.org/)** - High-level data visualization library for concise exploratory plots.  
  `pip install holoviews` · [Source](https://github.com/holoviz/holoviews) · [PyPI](https://pypi.org/project/holoviews/)
#### Interactive apps and notebooks

- **[Panel](https://panel.holoviz.org/)** - Dashboard and app framework from the HoloViz ecosystem.  
  `pip install panel` · [Source](https://github.com/holoviz/panel) · [PyPI](https://pypi.org/project/panel/)
- **[Dash](https://dash.plotly.com/)** - Framework for analytical web apps and interactive dashboards.  
  `pip install dash` · [Source](https://github.com/plotly/dash) · [PyPI](https://pypi.org/project/dash/)
- **[IPython](https://ipython.readthedocs.io/)** - Interactive Python shell and kernel used by many notebook workflows.  
  `pip install ipython` · [Source](https://github.com/ipython/ipython) · [PyPI](https://pypi.org/project/ipython/)
- **[Papermill](https://papermill.readthedocs.io/)** - Parameterization and execution tool for Jupyter notebooks.  
  `pip install papermill` · [Source](https://github.com/nteract/papermill) · [PyPI](https://pypi.org/project/papermill/)
#### Classical machine learning

- **[XGBoost](https://xgboost.readthedocs.io/)** - Gradient boosting library used for structured-data machine learning.  
  `pip install xgboost` · [Source](https://github.com/dmlc/xgboost) · [PyPI](https://pypi.org/project/xgboost/)
- **[LightGBM](https://lightgbm.readthedocs.io/)** - Gradient boosting framework designed for speed and large tabular datasets.  
  `pip install lightgbm` · [Source](https://github.com/microsoft/LightGBM) · [PyPI](https://pypi.org/project/lightgbm/)
- **[CatBoost](https://catboost.ai/)** - Gradient boosting library with strong categorical-feature support.  
  `pip install catboost` · [Source](https://github.com/catboost/catboost) · [PyPI](https://pypi.org/project/catboost/)
- **[imbalanced-learn](https://imbalanced-learn.org/)** - Sampling and model-selection tools for imbalanced classification problems.  
  `pip install imbalanced-learn` · [Source](https://github.com/scikit-learn-contrib/imbalanced-learn) · [PyPI](https://pypi.org/project/imbalanced-learn/)
- **[Optuna](https://optuna.org/)** - Hyperparameter optimization framework for machine-learning experiments.  
  `pip install optuna` · [Docs](https://optuna.readthedocs.io/) · [Source](https://github.com/optuna/optuna) · [PyPI](https://pypi.org/project/optuna/)
#### Deep learning and computer vision

- **[Keras](https://keras.io/)** - High-level neural-network API with multi-backend support.  
  `pip install keras` · [Source](https://github.com/keras-team/keras) · [PyPI](https://pypi.org/project/keras/)
- **[Flax](https://flax.readthedocs.io/)** - Neural-network library for JAX-based research and production models.  
  `pip install flax` · [Source](https://github.com/google/flax) · [PyPI](https://pypi.org/project/flax/)
- **[Lightning](https://lightning.ai/docs/pytorch/stable/)** - Training framework and tooling for PyTorch projects.  
  `pip install lightning` · [Source](https://github.com/Lightning-AI/pytorch-lightning) · [PyPI](https://pypi.org/project/lightning/)
- **[Kornia](https://kornia.readthedocs.io/)** - Differentiable computer-vision library for PyTorch.  
  `pip install kornia` · [Source](https://github.com/kornia/kornia) · [PyPI](https://pypi.org/project/kornia/)
- **[Ultralytics](https://docs.ultralytics.com/)** - Computer-vision framework known for YOLO model training and inference workflows.  
  `pip install ultralytics` · [Source](https://github.com/ultralytics/ultralytics) · [PyPI](https://pypi.org/project/ultralytics/)
#### Natural language, speech, and text-to-speech

- **[spaCy](https://spacy.io/)** - Industrial-strength NLP library for pipelines, tokenization, and information extraction.  
  `pip install spacy` · [Source](https://github.com/explosion/spaCy) · [PyPI](https://pypi.org/project/spacy/)
- **[NLTK](https://www.nltk.org/)** - Long-running NLP and text-processing toolkit useful for teaching and research.  
  `pip install nltk` · [Source](https://github.com/nltk/nltk) · [PyPI](https://pypi.org/project/nltk/)
- **[Gensim](https://radimrehurek.com/gensim/)** - Topic modeling and vector-space NLP toolkit.  
  `pip install gensim` · [Source](https://github.com/piskvorky/gensim) · [PyPI](https://pypi.org/project/gensim/)
- **[Stanza](https://stanfordnlp.github.io/stanza/)** - Stanford NLP toolkit for linguistic analysis across many languages.  
  `pip install stanza` · [Source](https://github.com/stanfordnlp/stanza) · [PyPI](https://pypi.org/project/stanza/)
- **[Sentence Transformers](https://www.sbert.net/)** - Sentence, text, and image embedding models built around transformer encoders.  
  `pip install sentence-transformers` · [Source](https://github.com/UKPLab/sentence-transformers) · [PyPI](https://pypi.org/project/sentence-transformers/)
- **[faster-whisper](https://github.com/SYSTRAN/faster-whisper)** - Fast Whisper inference implementation based on CTranslate2.  
  `pip install faster-whisper` · [PyPI](https://pypi.org/project/faster-whisper/)
- **[Vosk](https://alphacephei.com/vosk/)** - Offline speech recognition toolkit with Python bindings.  
  `pip install vosk` · [Source](https://github.com/alphacep/vosk-api) · [PyPI](https://pypi.org/project/vosk/)
#### Generative AI and LLM systems

- **[Diffusers](https://huggingface.co/docs/diffusers/)** - Hugging Face library for diffusion models in image, audio, and generative workflows.  
  `pip install diffusers` · [Source](https://github.com/huggingface/diffusers) · [PyPI](https://pypi.org/project/diffusers/)
- **[PEFT](https://huggingface.co/docs/peft/)** - Parameter-efficient fine-tuning methods for large models.  
  `pip install peft` · [Source](https://github.com/huggingface/peft) · [PyPI](https://pypi.org/project/peft/)
- **[vLLM](https://docs.vllm.ai/)** - High-throughput inference and serving engine for large language models.  
  `pip install vllm` · [Source](https://github.com/vllm-project/vllm) · [PyPI](https://pypi.org/project/vllm/)
- **[llama-cpp-python](https://llama-cpp-python.readthedocs.io/)** - Python bindings for llama.cpp local LLM inference.  
  `pip install llama-cpp-python` · [Source](https://github.com/abetlen/llama-cpp-python) · [PyPI](https://pypi.org/project/llama-cpp-python/)
- **[LiteLLM](https://docs.litellm.ai/)** - Unified API layer for calling many LLM providers from Python.  
  `pip install litellm` · [Source](https://github.com/BerriAI/litellm) · [PyPI](https://pypi.org/project/litellm/)
- **[LangChain](https://python.langchain.com/docs/)** - Framework for LLM applications, chains, integrations, and agent workflows.  
  `pip install langchain` · [Source](https://github.com/langchain-ai/langchain) · [PyPI](https://pypi.org/project/langchain/)
- **[LlamaIndex](https://docs.llamaindex.ai/)** - Data framework for retrieval-augmented LLM applications.  
  `pip install llama-index` · [Source](https://github.com/run-llama/llama_index) · [PyPI](https://pypi.org/project/llama-index/)
- **[Haystack](https://haystack.deepset.ai/)** - LLM and search framework for retrieval, question answering, and pipelines.  
  `pip install haystack-ai` · [Docs](https://docs.haystack.deepset.ai/) · [Source](https://github.com/deepset-ai/haystack) · [PyPI](https://pypi.org/project/haystack-ai/)
#### AI agents, RAG, and vector search

- **[LangGraph](https://langchain-ai.github.io/langgraph/)** - Stateful agent and workflow framework built for controllable LLM applications.  
  `pip install langgraph` · [Source](https://github.com/langchain-ai/langgraph) · [PyPI](https://pypi.org/project/langgraph/)
- **[CrewAI](https://docs.crewai.com/)** - Framework for coordinating role-based AI agents and task workflows.  
  `pip install crewai` · [Source](https://github.com/crewAIInc/crewAI) · [PyPI](https://pypi.org/project/crewai/)
- **[AutoGen](https://microsoft.github.io/autogen/stable/)** - Microsoft framework for building event-driven and multi-agent AI applications.  
  `pip install autogen-agentchat` · [Source](https://github.com/microsoft/autogen) · [PyPI](https://pypi.org/project/autogen-agentchat/)
- **[Chroma](https://docs.trychroma.com/)** - Open-source embedding database for local and application-focused RAG workflows.  
  `pip install chromadb` · [Source](https://github.com/chroma-core/chroma) · [PyPI](https://pypi.org/project/chromadb/)
- **[Qdrant Client](https://python-client.qdrant.tech/)** - Python client for the Qdrant vector database.  
  `pip install qdrant-client` · [Source](https://github.com/qdrant/qdrant-client) · [PyPI](https://pypi.org/project/qdrant-client/)
- **[Weaviate Client](https://weaviate.io/developers/weaviate/client-libraries/python)** - Python client for Weaviate vector search and knowledge graph features.  
  `pip install weaviate-client` · [Source](https://github.com/weaviate/weaviate-python-client) · [PyPI](https://pypi.org/project/weaviate-client/)
#### Model evaluation, explainability, and MLOps

- **[Ragas](https://docs.ragas.io/)** - Evaluation framework for retrieval-augmented generation systems.  
  `pip install ragas` · [Source](https://github.com/explodinggradients/ragas) · [PyPI](https://pypi.org/project/ragas/)
- **[DeepEval](https://deepeval.com/docs/getting-started)** - LLM evaluation framework for tests, metrics, and regression checks.  
  `pip install deepeval` · [Source](https://github.com/confident-ai/deepeval) · [PyPI](https://pypi.org/project/deepeval/)
- **[Evidently](https://docs.evidentlyai.com/)** - Model and data monitoring library for ML quality and drift analysis.  
  `pip install evidently` · [Source](https://github.com/evidentlyai/evidently) · [PyPI](https://pypi.org/project/evidently/)
- **[SHAP](https://shap.readthedocs.io/)** - Model explanation library based on Shapley-value methods.  
  `pip install shap` · [Source](https://github.com/shap/shap) · [PyPI](https://pypi.org/project/shap/)
- **[LIME](https://lime-ml.readthedocs.io/)** - Local interpretable model explanation library.  
  `pip install lime` · [Source](https://github.com/marcotcr/lime) · [PyPI](https://pypi.org/project/lime/)
- **[MLflow](https://mlflow.org/docs/latest/)** - Platform for experiment tracking, model packaging, registry, and deployment workflows.  
  `pip install mlflow` · [Source](https://github.com/mlflow/mlflow) · [PyPI](https://pypi.org/project/mlflow/)
- **[BentoML](https://docs.bentoml.com/)** - Model serving and packaging framework for production AI services.  
  `pip install bentoml` · [Source](https://github.com/bentoml/BentoML) · [PyPI](https://pypi.org/project/bentoml/)
#### Full-stack, lightweight, and API web frameworks

- **[Starlette](https://www.starlette.io/)** - Lightweight ASGI framework and toolkit used by several API frameworks.  
  `pip install starlette` · [Source](https://github.com/encode/starlette) · [PyPI](https://pypi.org/project/starlette/)
- **[Litestar](https://docs.litestar.dev/)** - ASGI web framework for APIs, services, and application backends.  
  `pip install litestar` · [Source](https://github.com/litestar-org/litestar) · [PyPI](https://pypi.org/project/litestar/)
- **[Sanic](https://sanic.dev/)** - Async web framework designed for high-throughput services.  
  `pip install sanic` · [Source](https://github.com/sanic-org/sanic) · [PyPI](https://pypi.org/project/sanic/)
- **[Quart](https://quart.palletsprojects.com/)** - Async Python web framework compatible with many Flask patterns.  
  `pip install quart` · [Source](https://github.com/pallets/quart) · [PyPI](https://pypi.org/project/quart/)
- **[Falcon](https://falcon.readthedocs.io/)** - Minimal framework for fast HTTP APIs and microservices.  
  `pip install falcon` · [Source](https://github.com/falconry/falcon) · [PyPI](https://pypi.org/project/falcon/)
- **[Django REST Framework](https://www.django-rest-framework.org/)** - Toolkit for building Web APIs on top of Django.  
  `pip install djangorestframework` · [Source](https://github.com/encode/django-rest-framework) · [PyPI](https://pypi.org/project/djangorestframework/)
#### ASGI, WSGI, and service infrastructure

- **[Uvicorn](https://uvicorn.dev/)** - ASGI server commonly used with FastAPI, Starlette, and other async apps.  
  `pip install uvicorn` · [Source](https://github.com/Kludex/uvicorn) · [PyPI](https://pypi.org/project/uvicorn/)
- **[Hypercorn](https://hypercorn.readthedocs.io/)** - ASGI and WSGI server supporting HTTP/1, HTTP/2, and HTTP/3 workflows.  
  `pip install hypercorn` · [Source](https://github.com/pgjones/hypercorn) · [PyPI](https://pypi.org/project/hypercorn/)
- **[Gunicorn](https://gunicorn.org/)** - Production WSGI server commonly used for Python web applications.  
  `pip install gunicorn` · [Docs](https://docs.gunicorn.org/) · [Source](https://github.com/benoitc/gunicorn) · [PyPI](https://pypi.org/project/gunicorn/)
- **[Waitress](https://docs.pylonsproject.org/projects/waitress/en/stable/)** - Pure-Python WSGI server for production and platform-compatible deployment.  
  `pip install waitress` · [Source](https://github.com/Pylons/waitress) · [PyPI](https://pypi.org/project/waitress/)
#### GraphQL, WebSockets, and authentication

- **[Strawberry](https://strawberry.rocks/)** - Modern Python GraphQL library using type annotations.  
  `pip install strawberry-graphql` · [Source](https://github.com/strawberry-graphql/strawberry) · [PyPI](https://pypi.org/project/strawberry-graphql/)
- **[Ariadne](https://ariadnegraphql.org/)** - Schema-first GraphQL library for Python services.  
  `pip install ariadne` · [Source](https://github.com/mirumee/ariadne) · [PyPI](https://pypi.org/project/ariadne/)
- **[Graphene](https://docs.graphene-python.org/)** - Code-first GraphQL framework for Python.  
  `pip install graphene` · [Source](https://github.com/graphql-python/graphene) · [PyPI](https://pypi.org/project/graphene/)
- **[websockets](https://websockets.readthedocs.io/)** - Asyncio-based library for WebSocket clients and servers.  
  `pip install websockets` · [Source](https://github.com/python-websockets/websockets) · [PyPI](https://pypi.org/project/websockets/)
- **[python-socketio](https://python-socketio.readthedocs.io/)** - Socket.IO client and server library for Python.  
  `pip install python-socketio` · [Source](https://github.com/miguelgrinberg/python-socketio) · [PyPI](https://pypi.org/project/python-socketio/)
- **[Authlib](https://docs.authlib.org/)** - OAuth, OpenID Connect, and JOSE implementation for Python.  
  `pip install Authlib` · [Source](https://github.com/lepture/authlib) · [PyPI](https://pypi.org/project/Authlib/)
- **[PyJWT](https://pyjwt.readthedocs.io/)** - JSON Web Token implementation for Python.  
  `pip install PyJWT` · [Source](https://github.com/jpadilla/pyjwt) · [PyPI](https://pypi.org/project/PyJWT/)
- **[django-allauth](https://docs.allauth.org/)** - Authentication, registration, account management, and social login for Django.  
  `pip install django-allauth` · [Source](https://github.com/pennersr/django-allauth) · [PyPI](https://pypi.org/project/django-allauth/)
#### Background work, caching, and API operations

- **[RQ](https://python-rq.org/)** - Simple Redis-backed job queue for Python.  
  `pip install rq` · [Source](https://github.com/rq/rq) · [PyPI](https://pypi.org/project/rq/)
- **[Dramatiq](https://dramatiq.io/)** - Background task processing library with RabbitMQ and Redis brokers.  
  `pip install dramatiq` · [Source](https://github.com/Bogdanp/dramatiq) · [PyPI](https://pypi.org/project/dramatiq/)
- **[Huey](https://huey.readthedocs.io/)** - Small task queue supporting Redis, SQLite, and in-memory storage.  
  `pip install huey` · [Source](https://github.com/coleifer/huey) · [PyPI](https://pypi.org/project/huey/)
- **[redis-py](https://redis.readthedocs.io/)** - Python client for Redis databases and related services.  
  `pip install redis` · [Source](https://github.com/redis/redis-py) · [PyPI](https://pypi.org/project/redis/)
- **[cachetools](https://cachetools.readthedocs.io/)** - Extensible memoizing collections and decorators.  
  `pip install cachetools` · [Source](https://github.com/tkem/cachetools) · [PyPI](https://pypi.org/project/cachetools/)
- **[slowapi](https://slowapi.readthedocs.io/)** - Rate-limiting extension for Starlette and FastAPI applications.  
  `pip install slowapi` · [Source](https://github.com/laurentS/slowapi) · [PyPI](https://pypi.org/project/slowapi/)
- **[drf-spectacular](https://drf-spectacular.readthedocs.io/)** - OpenAPI 3 schema generation for Django REST Framework.  
  `pip install drf-spectacular` · [Source](https://github.com/tfranzel/drf-spectacular) · [PyPI](https://pypi.org/project/drf-spectacular/)
#### Web scraping and extraction

- **[lxml](https://lxml.de/)** - Fast XML and HTML processing library based on libxml2 and libxslt.  
  `pip install lxml` · [Source](https://github.com/lxml/lxml) · [PyPI](https://pypi.org/project/lxml/)
- **[parsel](https://parsel.readthedocs.io/)** - HTML and XML extraction library used by Scrapy selectors.  
  `pip install parsel` · [Source](https://github.com/scrapy/parsel) · [PyPI](https://pypi.org/project/parsel/)
- **[MechanicalSoup](https://mechanicalsoup.readthedocs.io/)** - Stateful browser-like web interaction library built on Requests and Beautiful Soup.  
  `pip install MechanicalSoup` · [Source](https://github.com/MechanicalSoup/MechanicalSoup) · [PyPI](https://pypi.org/project/MechanicalSoup/)
- **[trafilatura](https://trafilatura.readthedocs.io/)** - Web text extraction library focused on main-content extraction.  
  `pip install trafilatura` · [Source](https://github.com/adbar/trafilatura) · [PyPI](https://pypi.org/project/trafilatura/)
#### SQL toolkits and ORMs

- **[SQLModel](https://sqlmodel.tiangolo.com/)** - Data-model and ORM library combining SQLAlchemy and Pydantic patterns.  
  `pip install sqlmodel` · [Source](https://github.com/fastapi/sqlmodel) · [PyPI](https://pypi.org/project/sqlmodel/)
- **[Peewee](https://docs.peewee-orm.com/)** - Small ORM with a compact API for relational databases.  
  `pip install peewee` · [Source](https://github.com/coleifer/peewee) · [PyPI](https://pypi.org/project/peewee/)
- **[Tortoise ORM](https://tortoise.github.io/)** - Async ORM inspired by Django's ORM design.  
  `pip install tortoise-orm` · [Source](https://github.com/tortoise/tortoise-orm) · [PyPI](https://pypi.org/project/tortoise-orm/)
- **[Pony ORM](https://ponyorm.org/)** - ORM that supports expressive Python generator syntax for queries.  
  `pip install pony` · [Source](https://github.com/ponyorm/pony) · [PyPI](https://pypi.org/project/pony/)
#### PostgreSQL, MySQL, and SQLite

- **[psycopg](https://www.psycopg.org/psycopg3/docs/)** - Modern PostgreSQL adapter for Python.  
  `pip install psycopg` · [Source](https://github.com/psycopg/psycopg) · [PyPI](https://pypi.org/project/psycopg/)
- **[asyncpg](https://magicstack.github.io/asyncpg/current/)** - Fast asyncio PostgreSQL client library.  
  `pip install asyncpg` · [Source](https://github.com/MagicStack/asyncpg) · [PyPI](https://pypi.org/project/asyncpg/)
- **[pg8000](https://codeberg.org/tlocke/pg8000)** - Pure-Python PostgreSQL driver.  
  `pip install pg8000` · [PyPI](https://pypi.org/project/pg8000/)
- **[PyMySQL](https://pymysql.readthedocs.io/)** - Pure-Python MySQL client library.  
  `pip install PyMySQL` · [Source](https://github.com/PyMySQL/PyMySQL) · [PyPI](https://pypi.org/project/PyMySQL/)
- **[mysql-connector-python](https://dev.mysql.com/doc/connector-python/en/)** - Oracle-supported MySQL driver for Python.  
  `pip install mysql-connector-python` · [Source](https://github.com/mysql/mysql-connector-python) · [PyPI](https://pypi.org/project/mysql-connector-python/)
- **[aiosqlite](https://aiosqlite.omnilib.dev/)** - Asyncio bridge for the standard-library SQLite module.  
  `pip install aiosqlite` · [Source](https://github.com/omnilib/aiosqlite) · [PyPI](https://pypi.org/project/aiosqlite/)
- **[sqlite-utils](https://sqlite-utils.datasette.io/)** - CLI and Python library for working with SQLite databases.  
  `pip install sqlite-utils` · [Source](https://github.com/simonw/sqlite-utils) · [PyPI](https://pypi.org/project/sqlite-utils/)
#### Document, graph, search, and analytics databases

- **[PyMongo](https://pymongo.readthedocs.io/)** - Official MongoDB driver for Python.  
  `pip install pymongo` · [Source](https://github.com/mongodb/mongo-python-driver) · [PyPI](https://pypi.org/project/pymongo/)
- **[Motor](https://motor.readthedocs.io/)** - Asyncio MongoDB driver built on PyMongo.  
  `pip install motor` · [Source](https://github.com/mongodb/motor) · [PyPI](https://pypi.org/project/motor/)
- **[Beanie](https://beanie-odm.dev/)** - Async MongoDB object-document mapper based on Pydantic.  
  `pip install beanie` · [Source](https://github.com/BeanieODM/beanie) · [PyPI](https://pypi.org/project/beanie/)
- **[Neo4j Python Driver](https://neo4j.com/docs/python-manual/current/)** - Official Python driver for Neo4j graph databases.  
  `pip install neo4j` · [Source](https://github.com/neo4j/neo4j-python-driver) · [PyPI](https://pypi.org/project/neo4j/)
- **[Elasticsearch Python Client](https://elasticsearch-py.readthedocs.io/)** - Official Python client for Elasticsearch.  
  `pip install elasticsearch` · [Source](https://github.com/elastic/elasticsearch-py) · [PyPI](https://pypi.org/project/elasticsearch/)
- **[OpenSearch Python Client](https://opensearch-project.github.io/opensearch-py/)** - Python client for OpenSearch clusters.  
  `pip install opensearch-py` · [Source](https://github.com/opensearch-project/opensearch-py) · [PyPI](https://pypi.org/project/opensearch-py/)
- **[Meilisearch Python](https://python-sdk.meilisearch.com/)** - Python SDK for Meilisearch search applications.  
  `pip install meilisearch` · [Source](https://github.com/meilisearch/meilisearch-python) · [PyPI](https://pypi.org/project/meilisearch/)
- **[ClickHouse Connect](https://clickhouse.com/docs/integrations/language-clients/python/intro)** - Official ClickHouse driver and SQLAlchemy support package.  
  `pip install clickhouse-connect` · [Source](https://github.com/ClickHouse/clickhouse-connect) · [PyPI](https://pypi.org/project/clickhouse-connect/)
#### Testing, coverage, and test data

- **[tox](https://tox.wiki/)** - Test automation tool for running checks across Python versions and environments.  
  `pip install tox` · [Source](https://github.com/tox-dev/tox) · [PyPI](https://pypi.org/project/tox/)
- **[nox](https://nox.thea.codes/)** - Python-based automation tool for tests, linting, and release sessions.  
  `pip install nox` · [Source](https://github.com/wntrblm/nox) · [PyPI](https://pypi.org/project/nox/)
- **[Hypothesis](https://hypothesis.readthedocs.io/)** - Property-based testing library for generating test cases.  
  `pip install hypothesis` · [Source](https://github.com/HypothesisWorks/hypothesis) · [PyPI](https://pypi.org/project/hypothesis/)
- **[pytest-mock](https://pytest-mock.readthedocs.io/)** - Thin pytest wrapper around the standard-library mock API.  
  `pip install pytest-mock` · [Source](https://github.com/pytest-dev/pytest-mock) · [PyPI](https://pypi.org/project/pytest-mock/)
- **[VCR.py](https://vcrpy.readthedocs.io/)** - Records and replays HTTP interactions for deterministic tests.  
  `pip install vcrpy` · [Source](https://github.com/kevin1024/vcrpy) · [PyPI](https://pypi.org/project/vcrpy/)
- **[coverage.py](https://coverage.readthedocs.io/)** - Code coverage measurement tool for Python.  
  `pip install coverage` · [Source](https://github.com/nedbat/coveragepy) · [PyPI](https://pypi.org/project/coverage/)
#### Formatting, linting, typing, and security analysis

- **[isort](https://pycqa.github.io/isort/)** - Import sorting tool for Python files.  
  `pip install isort` · [Source](https://github.com/PyCQA/isort) · [PyPI](https://pypi.org/project/isort/)
- **[Flake8](https://flake8.pycqa.org/)** - Wrapper around PyFlakes, pycodestyle, and McCabe checks.  
  `pip install flake8` · [Source](https://github.com/PyCQA/flake8) · [PyPI](https://pypi.org/project/flake8/)
- **[Pylint](https://pylint.readthedocs.io/)** - Static analysis tool for code quality and style checks.  
  `pip install pylint` · [Source](https://github.com/pylint-dev/pylint) · [PyPI](https://pypi.org/project/pylint/)
- **[Pyright](https://microsoft.github.io/pyright/)** - Static type checker and language-server engine for Python.  
  `pip install pyright` · [Source](https://github.com/microsoft/pyright) · [PyPI](https://pypi.org/project/pyright/)
- **[Bandit](https://bandit.readthedocs.io/)** - Security linter for common Python code risks.  
  `pip install bandit` · [Source](https://github.com/PyCQA/bandit) · [PyPI](https://pypi.org/project/bandit/)
- **[pip-audit](https://pypi.org/project/pip-audit/)** - Audits Python environments and requirement files for known vulnerabilities.  
  `pip install pip-audit` · [Source](https://github.com/pypa/pip-audit)
#### Profiling, debugging, and benchmarking

- **[py-spy](https://github.com/benfred/py-spy)** - Sampling profiler for Python programs.  
  `pip install py-spy` · [PyPI](https://pypi.org/project/py-spy/)
- **[Scalene](https://github.com/plasma-umass/scalene)** - CPU, GPU, and memory profiler for Python.  
  `pip install scalene` · [PyPI](https://pypi.org/project/scalene/)
- **[line_profiler](https://kernprof.readthedocs.io/)** - Line-by-line profiler for Python functions.  
  `pip install line_profiler` · [Source](https://github.com/pyutils/line_profiler) · [PyPI](https://pypi.org/project/line_profiler/)
- **[pytest-benchmark](https://pytest-benchmark.readthedocs.io/)** - pytest plugin for measuring and comparing benchmark results.  
  `pip install pytest-benchmark` · [Source](https://github.com/ionelmc/pytest-benchmark) · [PyPI](https://pypi.org/project/pytest-benchmark/)
#### Packaging, environments, and release tooling

- **[setuptools](https://setuptools.pypa.io/)** - Core Python packaging build system and library.  
  `pip install setuptools` · [Source](https://github.com/pypa/setuptools) · [PyPI](https://pypi.org/project/setuptools/)
- **[Hatch](https://hatch.pypa.io/)** - Project manager and build backend for Python packages.  
  `pip install hatch` · [Source](https://github.com/pypa/hatch) · [PyPI](https://pypi.org/project/hatch/)
- **[Flit](https://flit.pypa.io/)** - Simple packaging tool for Python modules and packages.  
  `pip install flit` · [Source](https://github.com/pypa/flit) · [PyPI](https://pypi.org/project/flit/)
- **[PDM](https://pdm-project.org/)** - Modern Python package and dependency manager.  
  `pip install pdm` · [Source](https://github.com/pdm-project/pdm) · [PyPI](https://pypi.org/project/pdm/)
- **[pipx](https://pipx.pypa.io/)** - Installs and runs Python applications in isolated environments.  
  `pip install pipx` · [Source](https://github.com/pypa/pipx) · [PyPI](https://pypi.org/project/pipx/)
- **[virtualenv](https://virtualenv.pypa.io/)** - Tool for creating isolated Python environments.  
  `pip install virtualenv` · [Source](https://github.com/pypa/virtualenv) · [PyPI](https://pypi.org/project/virtualenv/)
- **[pre-commit](https://pre-commit.com/)** - Framework for managing and running Git hooks.  
  `pip install pre-commit` · [Source](https://github.com/pre-commit/pre-commit) · [PyPI](https://pypi.org/project/pre-commit/)
- **[Commitizen](https://commitizen-tools.github.io/commitizen/)** - Commit message and versioning helper for conventional releases.  
  `pip install commitizen` · [Source](https://github.com/commitizen-tools/commitizen) · [PyPI](https://pypi.org/project/commitizen/)
#### Documentation generation

- **[pdoc](https://pdoc.dev/)** - API documentation generator for Python projects.  
  `pip install pdoc` · [Source](https://github.com/mitmproxy/pdoc) · [PyPI](https://pypi.org/project/pdoc/)
- **[pydoctor](https://pydoctor.readthedocs.io/)** - API documentation generator used by Twisted and other projects.  
  `pip install pydoctor` · [Source](https://github.com/twisted/pydoctor) · [PyPI](https://pypi.org/project/pydoctor/)
#### CLI and terminal applications

- **[Textual](https://textual.textualize.io/)** - Framework for building terminal user interfaces.  
  `pip install textual` · [Source](https://github.com/Textualize/textual) · [PyPI](https://pypi.org/project/textual/)
- **[prompt_toolkit](https://python-prompt-toolkit.readthedocs.io/)** - Library for interactive command-line applications and shells.  
  `pip install prompt_toolkit` · [Source](https://github.com/prompt-toolkit/python-prompt-toolkit) · [PyPI](https://pypi.org/project/prompt_toolkit/)
- **[questionary](https://questionary.readthedocs.io/)** - Interactive command-line prompts for Python applications.  
  `pip install questionary` · [Source](https://github.com/tmbo/questionary) · [PyPI](https://pypi.org/project/questionary/)
- **[InquirerPy](https://inquirerpy.readthedocs.io/)** - Interactive prompt library inspired by Inquirer.js.  
  `pip install InquirerPy` · [Source](https://github.com/kazhala/InquirerPy) · [PyPI](https://pypi.org/project/InquirerPy/)
#### Desktop, mobile, dashboard, and game interfaces

- **[PySide6](https://doc.qt.io/qtforpython-6/)** - Qt for Python bindings with LGPL and commercial licensing options.  
  `pip install PySide6` · [Source](https://code.qt.io/cgit/pyside/pyside-setup.git/) · [PyPI](https://pypi.org/project/PySide6/)
- **[PyQt6](https://www.riverbankcomputing.com/static/Docs/PyQt6/)** - Riverbank Qt bindings for Python; evaluate GPL and commercial licensing needs.  
  `pip install PyQt6` · [Source](https://www.riverbankcomputing.com/software/pyqt/) · [PyPI](https://pypi.org/project/PyQt6/)
- **[wxPython](https://docs.wxpython.org/)** - Python bindings for the native wxWidgets GUI toolkit.  
  `pip install wxPython` · [Source](https://github.com/wxWidgets/Phoenix) · [PyPI](https://pypi.org/project/wxPython/)
- **[Dear PyGui](https://dearpygui.readthedocs.io/)** - GPU-accelerated GUI framework for tools, dashboards, and prototypes.  
  `pip install dearpygui` · [Source](https://github.com/hoffstadt/DearPyGui) · [PyPI](https://pypi.org/project/dearpygui/)
- **[Kivy](https://kivy.org/doc/stable/)** - Framework for multitouch desktop and mobile applications.  
  `pip install Kivy` · [Source](https://github.com/kivy/kivy) · [PyPI](https://pypi.org/project/Kivy/)
- **[Flet](https://flet.dev/docs/)** - Framework for building Flutter-powered apps from Python.  
  `pip install flet` · [Source](https://github.com/flet-dev/flet) · [PyPI](https://pypi.org/project/flet/)
- **[pygame-ce](https://pyga.me/docs/)** - Community edition of pygame for 2D games and multimedia projects.  
  `pip install pygame-ce` · [Source](https://github.com/pygame-community/pygame-ce) · [PyPI](https://pypi.org/project/pygame-ce/)
- **[Arcade](https://api.arcade.academy/)** - Modern Python framework for 2D games.  
  `pip install arcade` · [Source](https://github.com/pythonarcade/arcade) · [PyPI](https://pypi.org/project/arcade/)
#### Multimedia, documents, and OCR

- **[MoviePy](https://zulko.github.io/moviepy/)** - Video editing and compositing library for Python.  
  `pip install moviepy` · [Source](https://github.com/Zulko/moviepy) · [PyPI](https://pypi.org/project/moviepy/)
- **[imageio](https://imageio.readthedocs.io/)** - Library for reading and writing image and video data.  
  `pip install imageio` · [Source](https://github.com/imageio/imageio) · [PyPI](https://pypi.org/project/imageio/)
- **[PyAV](https://pyav.org/docs/stable/)** - Pythonic bindings for FFmpeg libraries.  
  `pip install av` · [Source](https://github.com/PyAV-Org/PyAV) · [PyPI](https://pypi.org/project/av/)
- **[librosa](https://librosa.org/doc/latest/)** - Audio and music analysis library.  
  `pip install librosa` · [Source](https://github.com/librosa/librosa) · [PyPI](https://pypi.org/project/librosa/)
- **[SoundFile](https://python-soundfile.readthedocs.io/)** - Audio file reading and writing library based on libsndfile.  
  `pip install soundfile` · [Source](https://github.com/bastibe/python-soundfile) · [PyPI](https://pypi.org/project/soundfile/)
- **[PyMuPDF](https://pymupdf.readthedocs.io/)** - High-performance PDF and document processing bindings for MuPDF.  
  `pip install PyMuPDF` · [Source](https://github.com/pymupdf/PyMuPDF) · [PyPI](https://pypi.org/project/PyMuPDF/)
- **[pdfplumber](https://github.com/jsvine/pdfplumber)** - PDF text, table, and layout extraction library.  
  `pip install pdfplumber` · [PyPI](https://pypi.org/project/pdfplumber/)
- **[ReportLab](https://docs.reportlab.com/reportlab/userguide/)** - PDF generation toolkit for documents and reports.  
  `pip install reportlab` · [Source](https://github.com/MrBitBucket/reportlab-mirror) · [PyPI](https://pypi.org/project/reportlab/)
- **[openpyxl](https://openpyxl.readthedocs.io/)** - Reads and writes Excel `.xlsx` files.  
  `pip install openpyxl` · [Source](https://foss.heptapod.net/openpyxl/openpyxl) · [PyPI](https://pypi.org/project/openpyxl/)
- **[python-docx](https://python-docx.readthedocs.io/)** - Creates and updates Microsoft Word `.docx` files.  
  `pip install python-docx` · [Source](https://github.com/python-openxml/python-docx) · [PyPI](https://pypi.org/project/python-docx/)
- **[XlsxWriter](https://xlsxwriter.readthedocs.io/)** - Writes Excel `.xlsx` files with charts, formatting, and formulas.  
  `pip install XlsxWriter` · [Source](https://github.com/jmcnamara/XlsxWriter) · [PyPI](https://pypi.org/project/XlsxWriter/)
- **[pytesseract](https://github.com/madmaze/pytesseract)** - Python wrapper for the Tesseract OCR engine.  
  `pip install pytesseract` · [PyPI](https://pypi.org/project/pytesseract/)
#### Cloud, containers, and remote execution

- **[boto3](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html)** - AWS SDK for Python.  
  `pip install boto3` · [Source](https://github.com/boto/boto3) · [PyPI](https://pypi.org/project/boto3/)
- **[google-cloud-storage](https://cloud.google.com/python/docs/reference/storage/latest)** - Google Cloud Storage client library for Python.  
  `pip install google-cloud-storage` · [Source](https://github.com/googleapis/google-cloud-python/tree/main/packages/google-cloud-storage) · [PyPI](https://pypi.org/project/google-cloud-storage/)
- **[azure-identity](https://learn.microsoft.com/en-us/python/api/overview/azure/identity-readme)** - Azure authentication client library for Python SDKs.  
  `pip install azure-identity` · [Source](https://github.com/Azure/azure-sdk-for-python) · [PyPI](https://pypi.org/project/azure-identity/)
- **[Docker SDK for Python](https://docker-py.readthedocs.io/)** - Python client for Docker Engine APIs.  
  `pip install docker` · [Source](https://github.com/docker/docker-py) · [PyPI](https://pypi.org/project/docker/)
- **[Kubernetes Python Client](https://k8s-python.readthedocs.io/en/stable/)** - Official Kubernetes API client for Python.  
  `pip install kubernetes` · [Source](https://github.com/kubernetes-client/python) · [PyPI](https://pypi.org/project/kubernetes/)
- **[Pulumi](https://www.pulumi.com/docs/iac/languages-sdks/python/)** - Infrastructure-as-code SDK with Python support.  
  `pip install pulumi` · [Source](https://github.com/pulumi/pulumi) · [PyPI](https://pypi.org/project/pulumi/)
- **[Paramiko](https://www.paramiko.org/)** - SSHv2 protocol library for Python.  
  `pip install paramiko` · [Source](https://github.com/paramiko/paramiko) · [PyPI](https://pypi.org/project/paramiko/)
#### Configuration, observability, and scheduling

- **[Dynaconf](https://www.dynaconf.com/)** - Layered configuration management for Python applications.  
  `pip install dynaconf` · [Source](https://github.com/dynaconf/dynaconf) · [PyPI](https://pypi.org/project/dynaconf/)
- **[python-dotenv](https://saurabh-kumar.com/python-dotenv/)** - Loads environment variables from `.env` files.  
  `pip install python-dotenv` · [Source](https://github.com/theskumar/python-dotenv) · [PyPI](https://pypi.org/project/python-dotenv/)
- **[Hydra](https://hydra.cc/)** - Configuration framework for complex applications and experiments.  
  `pip install hydra-core` · [Source](https://github.com/facebookresearch/hydra) · [PyPI](https://pypi.org/project/hydra-core/)
- **[OmegaConf](https://omegaconf.readthedocs.io/)** - Hierarchical configuration system used by Hydra and ML projects.  
  `pip install omegaconf` · [Source](https://github.com/omry/omegaconf) · [PyPI](https://pypi.org/project/omegaconf/)
- **[structlog](https://www.structlog.org/)** - Structured logging library for Python applications.  
  `pip install structlog` · [Source](https://github.com/hynek/structlog) · [PyPI](https://pypi.org/project/structlog/)
- **[OpenTelemetry Python](https://opentelemetry.io/docs/languages/python/)** - Tracing, metrics, and logs instrumentation for Python services.  
  `pip install opentelemetry-api` · [Source](https://github.com/open-telemetry/opentelemetry-python) · [PyPI](https://pypi.org/project/opentelemetry-api/)
- **[prometheus_client](https://prometheus.github.io/client_python/)** - Prometheus instrumentation client for Python.  
  `pip install prometheus-client` · [Source](https://github.com/prometheus/client_python) · [PyPI](https://pypi.org/project/prometheus-client/)
- **[APScheduler](https://apscheduler.readthedocs.io/)** - Advanced in-process task scheduler.  
  `pip install APScheduler` · [Source](https://github.com/agronholm/apscheduler) · [PyPI](https://pypi.org/project/APScheduler/)
#### Workflow orchestration, messaging, networking, and security primitives

- **[Apache Airflow](https://airflow.apache.org/docs/)** - Workflow orchestration platform for scheduled data pipelines.  
  `pip install apache-airflow` · [Source](https://github.com/apache/airflow) · [PyPI](https://pypi.org/project/apache-airflow/)
- **[Prefect](https://docs.prefect.io/)** - Workflow orchestration framework for data and automation pipelines.  
  `pip install prefect` · [Source](https://github.com/PrefectHQ/prefect) · [PyPI](https://pypi.org/project/prefect/)
- **[Dagster](https://docs.dagster.io/)** - Data orchestration platform for assets, pipelines, and observability.  
  `pip install dagster` · [Source](https://github.com/dagster-io/dagster) · [PyPI](https://pypi.org/project/dagster/)
- **[Kedro](https://kedro.org/)** - Open-source Python framework for creating reproducible, maintainable, and modular data science and machine learning pipelines.
  `pip install kedro` · [Docs](https://docs.kedro.org/) · [Source](https://github.com/kedro-org/kedro) · [PyPI](https://pypi.org/project/kedro/) · License: Apache-2.0
- **[Kombu](https://docs.celeryq.dev/projects/kombu/en/stable/)** - Messaging library used by Celery for broker integrations.  
  `pip install kombu` · [Source](https://github.com/celery/kombu) · [PyPI](https://pypi.org/project/kombu/)
- **[pika](https://pika.readthedocs.io/)** - RabbitMQ AMQP client library for Python.  
  `pip install pika` · [Source](https://github.com/pika/pika) · [PyPI](https://pypi.org/project/pika/)
- **[confluent-kafka](https://docs.confluent.io/platform/current/clients/confluent-kafka-python/html/index.html)** - Confluent-supported Apache Kafka client for Python.  
  `pip install confluent-kafka` · [Source](https://github.com/confluentinc/confluent-kafka-python) · [PyPI](https://pypi.org/project/confluent-kafka/)
- **[cryptography](https://cryptography.io/)** - Cryptographic recipes and primitives for Python.  
  `pip install cryptography` · [Source](https://github.com/pyca/cryptography) · [PyPI](https://pypi.org/project/cryptography/)
- **[PyNaCl](https://pynacl.readthedocs.io/)** - Python bindings for libsodium cryptographic primitives.  
  `pip install PyNaCl` · [Source](https://github.com/pyca/pynacl) · [PyPI](https://pypi.org/project/PyNaCl/)

## Specialized and Niche Domains

Specialized projects are included more conservatively. They should have a clear use case, credible documentation, an official source, a recognizable license, and either active maintenance or durable practical value. Legacy projects are labeled when they remain relevant for existing systems but should be evaluated carefully for new work.

#### Civil, structural, finite-element, and geotechnical engineering

- **[AgentFEM](https://haoming-luo.github.io/agentfem/)** - Readable finite-element workflows and an agent-friendly CLI for structural and thermal calculations with result verification.
  `pip install agentfem` (requires a compatible FEniCSx/PETSc environment) · [Source](https://github.com/haoming-luo/agentfem) · [PyPI](https://pypi.org/project/agentfem/) · License: Apache-2.0 · Labels: `Specialized`, `Emerging`
- **[OpenSeesPy](https://openseespydoc.readthedocs.io/)** - Python interface to OpenSees for earthquake and structural simulations.  
  `pip install openseespy` · [Source](https://github.com/zhuminjie/OpenSeesPy) · [PyPI](https://pypi.org/project/openseespy/)
- **[anaStruct](https://anastruct.readthedocs.io/)** - 2D structural analysis library for beams and frames.  
  `pip install anastruct` · [Source](https://github.com/ritchie46/anaStruct) · [PyPI](https://pypi.org/project/anastruct/)
- **[sectionproperties](https://sectionproperties.readthedocs.io/)** - Cross-section analysis library for structural engineering.  
  `pip install sectionproperties` · [Source](https://github.com/robbievanleeuwen/section-properties) · [PyPI](https://pypi.org/project/sectionproperties/)
- **[PyNite](https://pynite.readthedocs.io/)** - Finite-element library for structural engineering models.  
  `pip install PyNiteFEA` · [Source](https://github.com/JWock82/Pynite) · [PyPI](https://pypi.org/project/PyNiteFEA/)
- **[SfePy](https://sfepy.org/doc-devel/)** - Finite-element analysis library for multiphysics simulations.  
  `pip install sfepy` · [Source](https://github.com/sfepy/sfepy) · [PyPI](https://pypi.org/project/sfepy/)
#### Hydraulic and water resources engineering

- **[FloPy](https://flopy.readthedocs.io/)** - Python tools for MODFLOW groundwater models.  
  `pip install flopy` · [Source](https://github.com/modflowpy/flopy) · [PyPI](https://pypi.org/project/flopy/)
- **[WNTR](https://usepa.github.io/WNTR/)** - Water network resilience and simulation library.  
  `pip install wntr` · [Source](https://github.com/USEPA/WNTR) · [PyPI](https://pypi.org/project/wntr/)
- **[PySWMM](https://pyswmm.github.io/pyswmm/)** - Python interface for EPA SWMM stormwater simulations.  
  `pip install pyswmm` · [Source](https://github.com/pyswmm/pyswmm) · [PyPI](https://pypi.org/project/pyswmm/)
- **[PySlope](https://pyslope.readthedocs.io/)** - Slope-stability analysis library for geotechnical engineering.  
  `pip install pyslope` · [Source](https://github.com/JesseBonanno/PySlope) · [PyPI](https://pypi.org/project/pyslope/)
#### Transportation engineering

- **[OSMnx](https://osmnx.readthedocs.io/)** - Street network and geospatial analysis library based on OpenStreetMap data.  
  `pip install osmnx` · [Source](https://github.com/gboeing/osmnx) · [PyPI](https://pypi.org/project/osmnx/)
- **[AequilibraE](https://www.aequilibrae.com/latest/python/index.html)** - Transportation modeling library for traffic assignment and planning workflows.  
  `pip install aequilibrae` · [Source](https://github.com/AequilibraE/aequilibrae) · [PyPI](https://pypi.org/project/aequilibrae/)
#### Mechanical engineering, thermodynamics, fluids, and control systems

- **[CoolProp](https://coolprop.org/)** - Thermophysical property library for fluids and mixtures.  
  `pip install CoolProp` · [Source](https://github.com/CoolProp/CoolProp) · [PyPI](https://pypi.org/project/CoolProp/)
- **[Cantera](https://cantera.org/)** - Chemical kinetics, thermodynamics, and transport process library.  
  `pip install Cantera` · [Docs](https://cantera.org/stable/) · [Source](https://github.com/Cantera/cantera) · [PyPI](https://pypi.org/project/Cantera/)
- **[fluids](https://fluids.readthedocs.io/)** - Fluid dynamics calculations for engineering design.  
  `pip install fluids` · [Source](https://github.com/CalebBell/fluids) · [PyPI](https://pypi.org/project/fluids/)
- **[ht](https://ht.readthedocs.io/)** - Heat-transfer engineering calculations.  
  `pip install ht` · [Source](https://github.com/CalebBell/ht) · [PyPI](https://pypi.org/project/ht/)
- **[python-control](https://python-control.readthedocs.io/)** - Analysis and design tools for feedback control systems.  
  `pip install control` · [Source](https://github.com/python-control/python-control) · [PyPI](https://pypi.org/project/control/)
#### Electrical engineering, electronics, circuit simulation, and signal processing

- **[Lcapy](https://lcapy.readthedocs.io/)** - Circuit analysis and signal-processing library using symbolic methods.  
  `pip install lcapy` · [Source](https://github.com/mph-/lcapy) · [PyPI](https://pypi.org/project/lcapy/)
- **[PySpice](https://pyspice.fabrice-salvaire.fr/)** - Python interface for SPICE circuit simulation.  
  `pip install PySpice` · [Source](https://github.com/PySpice-org/PySpice) · [PyPI](https://pypi.org/project/PySpice/)
- **[SKiDL](https://skidl.readthedocs.io/)** - Python library for describing electronic circuits and generating netlists.  
  `pip install skidl` · [Source](https://github.com/devbisme/skidl) · [PyPI](https://pypi.org/project/skidl/)
- **[PyWavelets](https://pywavelets.readthedocs.io/)** - Wavelet transform library for signal and image processing.  
  `pip install PyWavelets` · [Source](https://github.com/PyWavelets/pywt) · [PyPI](https://pypi.org/project/PyWavelets/)
#### CAD, computational geometry, BIM, and IFC

- **[CadQuery](https://cadquery.readthedocs.io/)** - Parametric CAD scripting library for Python.  
  `pip install cadquery` · [Source](https://github.com/CadQuery/cadquery) · [PyPI](https://pypi.org/project/cadquery/)
- **[trimesh](https://trimesh.org/)** - 3D mesh processing library for computational geometry.  
  `pip install trimesh` · [Source](https://github.com/mikedh/trimesh) · [PyPI](https://pypi.org/project/trimesh/)
- **[IfcOpenShell](https://docs.ifcopenshell.org/)** - Open-source toolkit for IFC and BIM data.  
  `pip install ifcopenshell` · [Source](https://github.com/IfcOpenShell/IfcOpenShell) · [PyPI](https://pypi.org/project/ifcopenshell/)
- **[COMPAS](https://compas.dev/)** - Computational framework for architecture, engineering, fabrication, and robotics.  
  `pip install compas` · [Source](https://github.com/compas-dev/compas) · [PyPI](https://pypi.org/project/compas/)
#### Robotics, UAVs, embedded systems, and industrial automation

- **[PyBullet](https://pybullet.org/)** - Python module for physics simulation and robotics experiments.  
  `pip install pybullet` · [Source](https://github.com/bulletphysics/bullet3) · [PyPI](https://pypi.org/project/pybullet/)
- **[Robotics Toolbox for Python](https://petercorke.github.io/robotics-toolbox-python/)** - Robotics modeling, kinematics, and dynamics tools.  
  `pip install roboticstoolbox-python` · [Source](https://github.com/petercorke/robotics-toolbox-python) · [PyPI](https://pypi.org/project/roboticstoolbox-python/)
- **[MAVSDK-Python](https://mavsdk.mavlink.io/main/en/python/)** - Python SDK for MAVLink drones and UAV applications.  
  `pip install mavsdk` · [Source](https://github.com/mavlink/MAVSDK-Python) · [PyPI](https://pypi.org/project/mavsdk/)
- **[pymavlink](https://mavlink.io/en/mavgen_python/)** - Python MAVLink protocol implementation.  
  `pip install pymavlink` · [Source](https://github.com/ArduPilot/pymavlink) · [PyPI](https://pypi.org/project/pymavlink/)
- **[pyserial](https://pyserial.readthedocs.io/)** - Serial-port communication library.  
  `pip install pyserial` · [Source](https://github.com/pyserial/pyserial) · [PyPI](https://pypi.org/project/pyserial/)
- **[pymodbus](https://pymodbus.readthedocs.io/)** - Modbus protocol implementation for clients and servers.  
  `pip install pymodbus` · [Source](https://github.com/pymodbus-dev/pymodbus) · [PyPI](https://pypi.org/project/pymodbus/)
- **[python-can](https://python-can.readthedocs.io/)** - CAN bus support for Python.  
  `pip install python-can` · [Source](https://github.com/hardbyte/python-can) · [PyPI](https://pypi.org/project/python-can/)
#### Mathematics, optimization, physics, and quantum computing

- **[SymPy](https://www.sympy.org/)** - Symbolic mathematics library for algebra, calculus, and exact computation.  
  `pip install sympy` · [Docs](https://docs.sympy.org/) · [Source](https://github.com/sympy/sympy) · [PyPI](https://pypi.org/project/sympy/)
- **[mpmath](https://mpmath.org/)** - Arbitrary-precision floating-point arithmetic library.  
  `pip install mpmath` · [Source](https://github.com/mpmath/mpmath) · [PyPI](https://pypi.org/project/mpmath/)
- **[CVXPY](https://www.cvxpy.org/)** - Convex optimization modeling language for Python.  
  `pip install cvxpy` · [Source](https://github.com/cvxpy/cvxpy) · [PyPI](https://pypi.org/project/cvxpy/)
- **[PuLP](https://coin-or.github.io/pulp/)** - Linear programming modeler for optimization problems.  
  `pip install PuLP` · [Source](https://github.com/coin-or/pulp) · [PyPI](https://pypi.org/project/PuLP/)
- **[OR-Tools](https://developers.google.com/optimization)** - Google optimization toolkit for routing, scheduling, and mathematical programming.  
  `pip install ortools` · [Source](https://github.com/google/or-tools) · [PyPI](https://pypi.org/project/ortools/)
- **[Pyomo](https://pyomo.readthedocs.io/)** - Optimization modeling language for mathematical programming.  
  `pip install Pyomo` · [Source](https://github.com/Pyomo/pyomo) · [PyPI](https://pypi.org/project/Pyomo/)
- **[QuTiP](https://qutip.org/)** - Quantum Toolbox in Python for open quantum systems.  
  `pip install qutip` · [Docs](https://qutip.readthedocs.io/en/latest/) · [Source](https://github.com/qutip/qutip) · [PyPI](https://pypi.org/project/qutip/)
- **[Qiskit](https://docs.quantum.ibm.com/guides)** - IBM-supported SDK for quantum computing workflows.  
  `pip install qiskit` · [Source](https://github.com/Qiskit/qiskit) · [PyPI](https://pypi.org/project/qiskit/)
#### Astronomy, chemistry, materials science, biology, and bioinformatics

- **[Astropy](https://docs.astropy.org/)** - Core astronomy package for coordinates, units, tables, and FITS data.  
  `pip install astropy` · [Source](https://github.com/astropy/astropy) · [PyPI](https://pypi.org/project/astropy/)
- **[SunPy](https://docs.sunpy.org/)** - Solar physics data analysis environment.  
  `pip install sunpy` · [Source](https://github.com/sunpy/sunpy) · [PyPI](https://pypi.org/project/sunpy/)
- **[RDKit](https://www.rdkit.org/docs/)** - Cheminformatics toolkit for molecules, fingerprints, and reactions.  
  `pip install rdkit` · [Source](https://github.com/rdkit/rdkit) · [PyPI](https://pypi.org/project/rdkit/)
- **[ASE](https://wiki.fysik.dtu.dk/ase/)** - Atomic Simulation Environment for atomistic modeling workflows.  
  `pip install ase` · [Source](https://gitlab.com/ase/ase) · [PyPI](https://pypi.org/project/ase/)
- **[pymatgen](https://pymatgen.org/)** - Materials analysis library for computational materials science.  
  `pip install pymatgen` · [Source](https://github.com/materialsproject/pymatgen) · [PyPI](https://pypi.org/project/pymatgen/)
- **[Biopython](https://biopython.org/wiki/Documentation)** - Core library for computational biology and bioinformatics.  
  `pip install biopython` · [Source](https://github.com/biopython/biopython) · [PyPI](https://pypi.org/project/biopython/)
- **[Scanpy](https://scanpy.readthedocs.io/)** - Single-cell analysis toolkit built around AnnData.  
  `pip install scanpy` · [Source](https://github.com/scverse/scanpy) · [PyPI](https://pypi.org/project/scanpy/)
- **[pysam](https://pysam.readthedocs.io/)** - Python interface for SAM/BAM/CRAM and genomic file formats.  
  `pip install pysam` · [Source](https://github.com/pysam-developers/pysam) · [PyPI](https://pypi.org/project/pysam/)
#### Neuroscience, medical imaging, healthcare data, GIS, and remote sensing

- **[MNE-Python](https://mne.tools/stable/)** - Neurophysiological data analysis library for EEG, MEG, and related signals.  
  `pip install mne` · [Source](https://github.com/mne-tools/mne-python) · [PyPI](https://pypi.org/project/mne/)
- **[Nilearn](https://nilearn.github.io/stable/)** - Machine-learning tools for neuroimaging data.  
  `pip install nilearn` · [Source](https://github.com/nilearn/nilearn) · [PyPI](https://pypi.org/project/nilearn/)
- **[SimpleITK](https://simpleitk.readthedocs.io/)** - Simplified interface to the Insight Toolkit for medical image analysis.  
  `pip install SimpleITK` · [Source](https://github.com/SimpleITK/SimpleITK) · [PyPI](https://pypi.org/project/SimpleITK/)
- **[NiBabel](https://nipy.org/nibabel/)** - Access to neuroimaging file formats such as NIfTI.  
  `pip install nibabel` · [Source](https://github.com/nipy/nibabel) · [PyPI](https://pypi.org/project/nibabel/)
- **[pydicom](https://pydicom.github.io/)** - Reads, writes, and modifies DICOM medical imaging files.  
  `pip install pydicom` · [Source](https://github.com/pydicom/pydicom) · [PyPI](https://pypi.org/project/pydicom/)
- **[GeoPandas](https://geopandas.org/)** - Extends pandas with geospatial data types and operations.  
  `pip install geopandas` · [Source](https://github.com/geopandas/geopandas) · [PyPI](https://pypi.org/project/geopandas/)
- **[Rasterio](https://rasterio.readthedocs.io/)** - Raster geospatial data access built on GDAL.  
  `pip install rasterio` · [Source](https://github.com/rasterio/rasterio) · [PyPI](https://pypi.org/project/rasterio/)
- **[pyproj](https://pyproj4.github.io/pyproj/stable/)** - Python interface to PROJ coordinate transformations.  
  `pip install pyproj` · [Source](https://github.com/pyproj4/pyproj) · [PyPI](https://pypi.org/project/pyproj/)
- **[Cartopy](https://scitools.org.uk/cartopy/docs/latest/)** - Geospatial plotting library for maps and projections.  
  `pip install Cartopy` · [Source](https://github.com/SciTools/cartopy) · [PyPI](https://pypi.org/project/Cartopy/)
- **[earthengine-api](https://developers.google.com/earth-engine/guides/python_install)** - Python client for Google Earth Engine.  
  `pip install earthengine-api` · [Source](https://github.com/google/earthengine-api) · [PyPI](https://pypi.org/project/earthengine-api/)
#### Climate, environmental science, oceanography, and meteorology

- **[cfgrib](https://github.com/ecmwf/cfgrib)** - Python interface for reading GRIB files through ecCodes.  
  `pip install cfgrib` · [PyPI](https://pypi.org/project/cfgrib/)
- **[MetPy](https://unidata.github.io/MetPy/latest/)** - Meteorological data analysis and visualization library.  
  `pip install MetPy` · [Source](https://github.com/Unidata/MetPy) · [PyPI](https://pypi.org/project/MetPy/)
- **[Iris](https://scitools-iris.readthedocs.io/)** - Analysis and visualization library for meteorological and oceanographic datasets.  
  `pip install scitools-iris` · [Source](https://github.com/SciTools/iris) · [PyPI](https://pypi.org/project/scitools-iris/)
- **[OceanParcels](https://docs.oceanparcels.org/)** - Lagrangian particle tracking for ocean simulations.  
  `pip install parcels` · [Source](https://github.com/OceanParcels/parcels) · [PyPI](https://pypi.org/project/parcels/)
#### Quantitative finance, algorithmic trading, risk, econometrics, and causal inference

- **[QuantLib](https://www.quantlib.org/)** - Quantitative finance library with Python bindings.  
  `pip install QuantLib` · [Source](https://github.com/lballabio/QuantLib-SWIG) · [PyPI](https://pypi.org/project/QuantLib/)
- **[vectorbt](https://vectorbt.dev/)** - Vectorized backtesting and quantitative analysis toolkit.  
  `pip install vectorbt` · [Source](https://github.com/polakowo/vectorbt) · [PyPI](https://pypi.org/project/vectorbt/)
- **[backtrader](https://www.backtrader.com/docu/)** - Backtesting framework for trading strategies; evaluate maintenance status before new projects.  
  `pip install backtrader` · [Source](https://github.com/mementum/backtrader) · [PyPI](https://pypi.org/project/backtrader/) · Labels: `Legacy`
- **[zipline-reloaded](https://zipline.ml4trading.io/)** - Community-maintained continuation of Zipline for algorithmic trading research.  
  `pip install zipline-reloaded` · [Source](https://github.com/stefan-jansen/zipline-reloaded) · [PyPI](https://pypi.org/project/zipline-reloaded/)
- **[PyPortfolioOpt](https://pyportfolioopt.readthedocs.io/)** - Portfolio optimization library for allocation research.  
  `pip install PyPortfolioOpt` · [Source](https://github.com/robertmartin8/PyPortfolioOpt) · [PyPI](https://pypi.org/project/PyPortfolioOpt/)
- **[Riskfolio-Lib](https://riskfolio-lib.readthedocs.io/)** - Portfolio optimization and risk analysis library.  
  `pip install Riskfolio-Lib` · [Source](https://github.com/dcajasn/Riskfolio-Lib) · [PyPI](https://pypi.org/project/Riskfolio-Lib/)
- **[arch](https://arch.readthedocs.io/)** - ARCH and other econometric models for financial time series.  
  `pip install arch` · [Source](https://github.com/bashtage/arch) · [PyPI](https://pypi.org/project/arch/)
- **[statsmodels](https://www.statsmodels.org/)** - Statistical models, hypothesis tests, and econometrics.  
  `pip install statsmodels` · [Source](https://github.com/statsmodels/statsmodels) · [PyPI](https://pypi.org/project/statsmodels/)
- **[DoWhy](https://www.pywhy.org/dowhy/)** - Causal inference library focused on explicit causal assumptions.  
  `pip install dowhy` · [Source](https://github.com/py-why/dowhy) · [PyPI](https://pypi.org/project/dowhy/)
#### Accounting, business process automation, forecasting, and time-series analysis

- **[Beancount](https://beancount.github.io/docs/)** - Plain-text double-entry accounting system.  
  `pip install beancount` · [Source](https://github.com/beancount/beancount) · [PyPI](https://pypi.org/project/beancount/)
- **[RPA Framework](https://rpaframework.org/)** - Python libraries for robotic process automation.  
  `pip install rpaframework` · [Source](https://github.com/robocorp/rpaframework) · [PyPI](https://pypi.org/project/rpaframework/)
- **[StatsForecast](https://github.com/Nixtla/statsforecast/)** - Fast statistical forecasting models for time-series data.  
  `pip install statsforecast` · [Docs](https://nixtlaverse.nixtla.io/statsforecast/) · [Source](https://github.com/Nixtla/statsforecast) · [PyPI](https://pypi.org/project/statsforecast/)
- **[sktime](https://www.sktime.net/)** - Unified framework for time-series machine learning.  
  `pip install sktime` · [Source](https://github.com/sktime/sktime) · [PyPI](https://pypi.org/project/sktime/)
- **[Darts](https://unit8co.github.io/darts/)** - Time-series forecasting and anomaly detection library.  
  `pip install u8darts` · [Source](https://github.com/unit8co/darts) · [PyPI](https://pypi.org/project/u8darts/)
#### Cybersecurity, digital forensics, packet analysis, network automation, and reverse engineering

- **[yara-python](https://yara.readthedocs.io/)** - Python bindings for YARA malware identification rules.  
  `pip install yara-python` · [Source](https://github.com/VirusTotal/yara-python) · [PyPI](https://pypi.org/project/yara-python/)
- **[Volatility 3](https://volatility3.readthedocs.io/)** - Memory forensics framework.  
  `pip install volatility3` · [Source](https://github.com/volatilityfoundation/volatility3) · [PyPI](https://pypi.org/project/volatility3/)
- **[pwntools](https://docs.pwntools.com/)** - CTF and exploit-development support library.  
  `pip install pwntools` · [Source](https://github.com/Gallopsled/pwntools) · [PyPI](https://pypi.org/project/pwntools/)
- **[Impacket](https://github.com/fortra/impacket)** - Network protocol toolkit often used in security research and administration.  
  `pip install impacket` · [PyPI](https://pypi.org/project/impacket/)
- **[pyshark](https://kiminewt.github.io/pyshark/)** - Python wrapper for tshark packet capture and parsing.  
  `pip install pyshark` · [Source](https://github.com/KimiNewt/pyshark) · [PyPI](https://pypi.org/project/pyshark/)
- **[Netmiko](https://ktbyers.github.io/netmiko/)** - Multi-vendor network device SSH automation library.  
  `pip install netmiko` · [Source](https://github.com/ktbyers/netmiko) · [PyPI](https://pypi.org/project/netmiko/)
- **[NAPALM](https://napalm.readthedocs.io/)** - Network automation abstraction library for multiple vendors.  
  `pip install napalm` · [Source](https://github.com/napalm-automation/napalm) · [PyPI](https://pypi.org/project/napalm/)
- **[Nornir](https://nornir.readthedocs.io/)** - Python automation framework for network operations.  
  `pip install nornir` · [Source](https://github.com/nornir-automation/nornir) · [PyPI](https://pypi.org/project/nornir/)
- **[AsyncSSH](https://asyncssh.readthedocs.io/)** - Asynchronous SSHv2 client and server library.  
  `pip install asyncssh` · [Source](https://github.com/ronf/asyncssh) · [PyPI](https://pypi.org/project/asyncssh/)
- **[angr](https://docs.angr.io/)** - Binary analysis platform for reverse engineering and program analysis.  
  `pip install angr` · [Source](https://github.com/angr/angr) · [PyPI](https://pypi.org/project/angr/)
- **[Capstone](https://www.capstone-engine.org/lang_python.html)** - Disassembly framework with Python bindings.  
  `pip install capstone` · [Source](https://github.com/capstone-engine/capstone) · [PyPI](https://pypi.org/project/capstone/)
- **[LIEF](https://lief.re/doc/latest/)** - Library for parsing and modifying executable formats.  
  `pip install lief` · [Source](https://github.com/lief-project/LIEF) · [PyPI](https://pypi.org/project/lief/)
#### Creative coding, game development, 3D graphics, point clouds, animation, music, and audio

- **[Open3D](https://www.open3d.org/docs/)** - 3D data processing library for point clouds, meshes, and scenes.  
  `pip install open3d` · [Source](https://github.com/isl-org/Open3D) · [PyPI](https://pypi.org/project/open3d/)
- **[PyVista](https://docs.pyvista.org/)** - 3D plotting and mesh analysis built on VTK.  
  `pip install pyvista` · [Source](https://github.com/pyvista/pyvista) · [PyPI](https://pypi.org/project/pyvista/)
- **[VTK](https://docs.vtk.org/en/latest/api/python.html)** - Visualization Toolkit bindings for scientific 3D visualization.  
  `pip install vtk` · [Source](https://gitlab.kitware.com/vtk/vtk) · [PyPI](https://pypi.org/project/vtk/)
- **[ModernGL](https://moderngl.readthedocs.io/)** - Pythonic OpenGL wrapper for graphics applications.  
  `pip install moderngl` · [Source](https://github.com/moderngl/moderngl) · [PyPI](https://pypi.org/project/moderngl/)
- **[Manim](https://docs.manim.community/)** - Animation engine for mathematical videos.  
  `pip install manim` · [Source](https://github.com/ManimCommunity/manim) · [PyPI](https://pypi.org/project/manim/)
- **[pretty_midi](https://craffel.github.io/pretty-midi/)** - Utility library for MIDI file analysis and manipulation.  
  `pip install pretty_midi` · [Source](https://github.com/craffel/pretty-midi) · [PyPI](https://pypi.org/project/pretty_midi/)
- **[sounddevice](https://python-sounddevice.readthedocs.io/)** - PortAudio bindings for real-time audio input and output.  
  `pip install sounddevice` · [Source](https://github.com/spatialaudio/python-sounddevice) · [PyPI](https://pypi.org/project/sounddevice/)
- **[py5](https://py5coding.org/)** - Creative coding framework inspired by Processing.  
  `pip install py5` · [Source](https://github.com/py5coding/py5generator) · [PyPI](https://pypi.org/project/py5/)

### Legacy or Limited-Maintenance Projects

- **backtrader** is included as `Legacy` because existing trading research and examples still depend on it, but new projects should compare it with maintained alternatives such as `vectorbt`, `zipline-reloaded`, or domain-specific backtesting stacks.

## Library Comparison Guides

These tables explain tradeoffs. They do not declare universal winners.

### pandas vs Polars vs Dask vs PySpark

| Project | Strength | Best fit |
| --- | --- | --- |
| pandas | Broad compatibility and mature ecosystem | Single-machine workflows and general analysis |
| Polars | Fast columnar engine with lazy evaluation | Performance-sensitive local analytics |
| Dask | Parallelizes Python analytics APIs | Scaling Python workflows across cores or clusters |
| PySpark | Spark ecosystem integration | Large cluster-based data engineering |

### Django vs Flask vs FastAPI

| Project | Strength | Best fit |
| --- | --- | --- |
| Django | Integrated ORM, admin, auth, and conventions | Full web applications |
| Flask | Small core and flexible extension model | Simple services and custom architectures |
| FastAPI | Typed API design and OpenAPI generation | Modern HTTP APIs |

### Requests vs HTTPX vs aiohttp

| Project | Strength | Best fit |
| --- | --- | --- |
| Requests | Simple synchronous API | Scripts and straightforward clients |
| HTTPX | Sync and async support with modern transports | Services that may need both modes |
| aiohttp | Async client and server toolkit | asyncio-heavy applications |

### Selenium vs Playwright

| Project | Strength | Best fit |
| --- | --- | --- |
| Selenium | Long-established browser automation standard | Existing grids and broad browser infrastructure |
| Playwright | Modern auto-waiting and test ergonomics | New browser tests and JavaScript-heavy apps |

### Beautiful Soup vs lxml vs Scrapy

| Project | Strength | Best fit |
| --- | --- | --- |
| Beautiful Soup | Forgiving HTML parsing | Small extraction jobs |
| lxml | Fast XML/HTML parsing | Performance-sensitive parsing |
| Scrapy | Crawler framework | Large scraping projects |

### PyTorch vs TensorFlow vs JAX

| Project | Strength | Best fit |
| --- | --- | --- |
| PyTorch | Dynamic research-friendly framework | Research and flexible model development |
| TensorFlow | Production tooling and deployment ecosystem | Teams using TensorFlow Serving, Lite, or JS |
| JAX | Composable transformations and accelerators | Research in differentiable systems |

### pytest vs unittest

| Project | Strength | Best fit |
| --- | --- | --- |
| pytest | Rich fixtures and plugin ecosystem | Most new Python test suites |
| unittest | Standard-library xUnit framework | Dependency-free or legacy-compatible tests |

### Click vs Typer vs argparse

| Project | Strength | Best fit |
| --- | --- | --- |
| Click | Mature composable CLI framework | Complex command trees |
| Typer | Click-based and type-hint friendly | Modern typed CLIs |
| argparse | Standard library | Dependency-free scripts |

### PyQt/PySide vs Tkinter vs Kivy vs Flet

| Project | Strength | Best fit |
| --- | --- | --- |
| PyQt/PySide | Qt desktop ecosystem | Native desktop apps |
| Tkinter | Included with many Python installs | Small built-in GUIs |
| Kivy | Touch and mobile-oriented apps | Cross-platform interactive apps |
| Flet | Flutter-backed UI from Python | Rapid app-style interfaces |

### Celery vs RQ vs Dramatiq

| Project | Strength | Best fit |
| --- | --- | --- |
| Celery | Feature-rich distributed task queue | Complex production task systems |
| RQ | Simple Redis queue | Small background job needs |
| Dramatiq | Focused worker library | Reliable queue processing with less surface area |

### Airflow vs Prefect vs Dagster

| Project | Strength | Best fit |
| --- | --- | --- |
| Airflow | Scheduler-centered DAG platform | Established batch orchestration |
| Prefect | Python-native flows and operational UI | Dynamic workflows |
| Dagster | Software-defined assets and observability | Data platform engineering |

### Matplotlib vs Plotly vs Altair vs Bokeh

| Project | Strength | Best fit |
| --- | --- | --- |
| Matplotlib | Flexible static plotting | Publication and scientific plots |
| Plotly | Interactive browser charts | Dashboards and exploration |
| Altair | Declarative grammar | Concise statistical visualization |
| Bokeh | Interactive web visualization server | Custom browser visualizations |

### SQLAlchemy vs SQLModel vs Django ORM

| Project | Strength | Best fit |
| --- | --- | --- |
| SQLAlchemy | Powerful ORM and SQL toolkit | General relational applications |
| SQLModel | Pydantic-friendly SQLAlchemy layer | Typed FastAPI-adjacent apps |
| Django ORM | Integrated into Django | Django projects |

### OpenCV vs Pillow vs scikit-image

| Project | Strength | Best fit |
| --- | --- | --- |
| OpenCV | Computer vision and video algorithms | Real-time and CV-heavy workflows |
| Pillow | Basic image file operations | Simple image manipulation |
| scikit-image | Scientific image algorithms | Research and analysis |

### PyMuPDF vs pypdf vs pdfplumber

| Project | Strength | Best fit |
| --- | --- | --- |
| PyMuPDF | Fast rendering and document access | Inspection and rendering |
| pypdf | Pure-Python PDF manipulation | Merge, split, metadata, forms |
| pdfplumber | Text and table extraction | Layout-aware extraction |

### GeoPandas vs Rasterio vs GDAL

| Project | Strength | Best fit |
| --- | --- | --- |
| GeoPandas | Vector geospatial dataframes | Shapefiles and vector operations |
| Rasterio | Raster data access | Imagery and gridded data |
| GDAL | Underlying geospatial toolkit | Format conversion and advanced geospatial operations |

### SHAP vs LIME vs InterpretML

| Project | Strength | Best fit |
| --- | --- | --- |
| SHAP | Shapley-value explanations | Model explanation with strong theory |
| LIME | Local surrogate explanations | Quick local interpretability |
| InterpretML | Glass-box models and dashboards | Interpretable ML workflows |

### MLflow vs Weights & Biases vs DVC

| Project | Strength | Best fit |
| --- | --- | --- |
| MLflow | Experiment and model lifecycle tracking | Model registry and run tracking |
| Weights & Biases | Hosted experiment tracking and collaboration | Team ML observability |
| DVC | Data and model versioning | Reproducible data workflows |

### LangChain vs LlamaIndex vs Haystack

| Project | Strength | Best fit |
| --- | --- | --- |
| LangChain | Application and agent orchestration | Tool-rich LLM apps |
| LlamaIndex | Data connectors and retrieval | RAG over private data |
| Haystack | Search and QA pipelines | Production retrieval systems |

### CrewAI vs LangGraph vs AutoGen

| Project | Strength | Best fit |
| --- | --- | --- |
| CrewAI | Role-based agent teams | Task-oriented multi-agent prototypes |
| LangGraph | Explicit state graphs | Controllable agent workflows |
| AutoGen | Event-driven multi-agent framework | Research and complex agent coordination |

## Emerging Projects

Emerging projects are credible but should still be evaluated carefully. Inclusion here means the project has an official source, documentation, a real use case, and visible development or organizational support; it does not mean the project is mature enough for every production environment.

- **[marimo](https://docs.marimo.io/)** - Reactive Python notebook designed for reproducible apps and scripts.  
  `pip install marimo` · [Source](https://github.com/marimo-team/marimo) · [PyPI](https://pypi.org/project/marimo/) · Labels: `Emerging`
- **[Reflex](https://reflex.dev/docs/getting-started/introduction/)** - Full-stack Python web framework for reactive applications.  
  `pip install reflex` · [Source](https://github.com/reflex-dev/reflex) · [PyPI](https://pypi.org/project/reflex/) · Labels: `Emerging`
- **[NiceGUI](https://nicegui.io/documentation)** - Python framework for browser-based user interfaces.  
  `pip install nicegui` · [Source](https://github.com/zauberzeug/nicegui) · [PyPI](https://pypi.org/project/nicegui/) · Labels: `Emerging`
- **[Pydantic AI](https://ai.pydantic.dev/)** - Agent framework from the Pydantic team built around typed Python patterns.  
  `pip install pydantic-ai` · [Source](https://github.com/pydantic/pydantic-ai) · [PyPI](https://pypi.org/project/pydantic-ai/) · Labels: `Emerging`
- **[DSPy](https://dspy.ai/)** - Framework for programming and optimizing language-model pipelines.  
  `pip install dspy` · [Source](https://github.com/stanfordnlp/dspy) · [PyPI](https://pypi.org/project/dspy/) · Labels: `Emerging`
- **[Instructor](https://python.useinstructor.com/)** - Structured-output library for LLM responses using Python types.  
  `pip install instructor` · [Source](https://github.com/instructor-ai/instructor) · [PyPI](https://pypi.org/project/instructor/) · Labels: `Emerging`
- **[LanceDB](https://lancedb.github.io/lancedb/)** - Developer-friendly vector database built on Lance columnar storage.  
  `pip install lancedb` · [Source](https://github.com/lancedb/lancedb) · [PyPI](https://pypi.org/project/lancedb/) · Labels: `Emerging`
- **[Narwhals](https://narwhals-dev.github.io/narwhals/)** - Lightweight dataframe compatibility layer for multiple dataframe libraries.  
  `pip install narwhals` · [Source](https://github.com/narwhals-dev/narwhals) · [PyPI](https://pypi.org/project/narwhals/) · Labels: `Emerging`
- **[deltalake](https://delta-io.github.io/delta-rs/python/)** - Python bindings for Delta Lake through the delta-rs project.  
  `pip install deltalake` · [Source](https://github.com/delta-io/delta-rs) · [PyPI](https://pypi.org/project/deltalake/) · Labels: `Emerging`
- **[Granian](https://github.com/emmett-framework/granian)** - Rust-based HTTP server for Python ASGI, WSGI, and RSGI applications.  
  `pip install granian` · [PyPI](https://pypi.org/project/granian/) · Labels: `Emerging`
- **[Robyn](https://robyn.tech/)** - Rust-backed async web framework for Python.  
  `pip install robyn` · [Source](https://github.com/sparckles/Robyn) · [PyPI](https://pypi.org/project/robyn/) · Labels: `Emerging`
- **[FastStream](https://faststream.ag2.ai/latest/)** - Framework for building event-driven services with brokers such as Kafka and RabbitMQ.  
  `pip install faststream` · [Source](https://github.com/airtai/faststream) · [PyPI](https://pypi.org/project/faststream/) · Labels: `Emerging`
- **[smolagents](https://huggingface.co/docs/smolagents/)** - Small agent framework from Hugging Face for tool-using LLM systems.  
  `pip install smolagents` · [Source](https://github.com/huggingface/smolagents) · [PyPI](https://pypi.org/project/smolagents/) · Labels: `Emerging`
- **[Outlines](https://dottxt-ai.github.io/outlines/)** - Structured generation library for constrained LLM outputs.  
  `pip install outlines` · [Source](https://github.com/dottxt-ai/outlines) · [PyPI](https://pypi.org/project/outlines/) · Labels: `Emerging`
- **[Guardrails AI](https://www.guardrailsai.com/docs/)** - Validation framework for structured and policy-constrained LLM outputs.  
  `pip install guardrails-ai` · [Source](https://github.com/guardrails-ai/guardrails) · [PyPI](https://pypi.org/project/guardrails-ai/) · Labels: `Emerging`

## Selection Criteria

A project should generally have:

- A clear purpose and legitimate use case.
- An official source repository.
- Official documentation or a maintained project site.
- A recognized open-source license or clearly documented licensing model.
- Evidence of current maintenance or enduring value.
- Reasonable installation instructions and package-manager availability where applicable.
- A security posture appropriate for its category.

GitHub stars alone are not enough. Release recency, contributor activity, issue and pull-request health, documentation quality, ecosystem adoption, security posture, whether a project has been superseded, and whether a repository is archived all matter.

## Status Labels

- `Essential` - broadly useful across many Python projects.
- `Popular` - widely adopted or commonly recognized in its category.
- `Modern` - reflects current Python practices or newer ecosystem direction.
- `Performance-focused` - chosen when speed, memory use, or scaling is a major reason to evaluate it.
- `Beginner-friendly` - especially approachable for new users.
- `Specialized` - valuable in a focused technical, scientific, or industry domain.
- `Emerging` - credible and active, but less established than long-running defaults.
- `Legacy` - historically or practically relevant, but should be evaluated carefully before new adoption.

## Contributing

Contributions are welcome when they improve accuracy, clarity, and maintainability. Useful contributions include new library suggestions, official link corrections, better descriptions, category improvements, maintenance-status corrections, and removal proposals for obsolete projects.

Before opening a pull request, read [CONTRIBUTING.md](CONTRIBUTING.md). New entries should include the project name, category, one-sentence rationale, official documentation, canonical source repository, PyPI link when applicable, license, and evidence of current maintenance or enduring relevance.

## Disclaimer

Projects listed here belong to their respective owners. Inclusion is informational and does not imply endorsement, sponsorship, affiliation, or a guarantee of package safety. Users should independently evaluate security, licensing, compatibility, maintenance status, and operational risk before installing or deploying any dependency.
