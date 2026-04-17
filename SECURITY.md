# Security Policy

## Supported Versions

eDySec is currently supported in the latest maintained codebase and in the validated execution environment used for development and evaluation.

| Component | Supported |
| --------- | --------- |
| Latest eDySec codebase | :white_check_mark: |
| Ubuntu 22.04 LTS (64-bit) | :white_check_mark: |
| Python 3.10.20 | :white_check_mark: |
| GCC 14.3.0 | :white_check_mark: |
| NVIDIA RTX A6000 (48 GB) | :white_check_mark: |
| TensorFlow 2.11.0 with CUDA support | :white_check_mark: |
| Keras (tf.keras) 2.11.0 | :white_check_mark: |
| NumPy 1.23.5 | :white_check_mark: |
| Pandas 1.5.3 | :white_check_mark: |
| Matplotlib 3.7.1 | :white_check_mark: |
| Seaborn 0.12.2 | :white_check_mark: |
| SciPy 1.9.3 | :white_check_mark: |
| Scikit-learn 1.2.2 | :white_check_mark: |
| Transformers 4.38.2 | :white_check_mark: |
| Joblib 1.3.2 | :white_check_mark: |
| Older or unvalidated environments | :x: |

> **Validated execution platform**
>
> - **Processor:** 13th Gen Intel Core i9-13900K  
> - **Memory:** 128 GB RAM  
> - **GPU:** NVIDIA RTX A6000 with 48 GB memory  
> - **Operating System:** Ubuntu 22.04 LTS (64-bit)  
> - **Python Version:** 3.10.20  
> - **Compiler:** GCC 14.3.0  
> - **TensorFlow Built with CUDA:** Yes  
> - **GPU Available:** Yes  
> - **Detected GPU(s):** GPU:0  

## Reporting a Vulnerability

We take security issues in eDySec seriously. If you discover a vulnerability in the framework, including its analysis pipeline, feature extraction modules, model integration code, or supporting scripts, please report it responsibly to the project maintainers.

When reporting a vulnerability, please include:

- a clear description of the issue,
- steps to reproduce it,
- the affected component or module,
- the potential security impact, and
- any suggested mitigation, if available.

After receiving a report, we will review and validate the issue, assess its impact, and determine an appropriate remediation or mitigation strategy. We kindly request that vulnerabilities not be disclosed publicly until the issue has been investigated and, where applicable, a fix has been prepared.

## Research Prototype Disclaimer

eDySec is a research-oriented prototype developed for dynamic security analysis of Python packages. Although reasonable efforts are made to improve robustness, security, and reproducibility, the framework is not intended to provide the guarantees of a production-hardened commercial security system. Users should evaluate and deploy it accordingly.
