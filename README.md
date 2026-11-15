# Behavior-Research

[![CI](https://github.com/kapildhinwa2010-dev/Behavior-Research/actions/workflows/ci.yml/badge.svg)](https://github.com/kapildhinwa2010-dev/Behavior-Research/actions/workflows/ci.yml)
[![CodeQL](https://github.com/kapildhinwa2010-dev/Behavior-Research/actions/workflows/codeql.yml/badge.svg)](https://github.com/kapildhinwa2010-dev/Behavior-Research/actions/workflows/codeql.yml)

Model behavior signatures and power-law spectra.

**Part of the [Kapildhinwa2010-dev Toolkit](https://github.com/kapildhinwa2010-dev/Kapildhinwa2010-dev).**

![Python](https://img.shields.io/badge/python-3.9%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## ✨ Features

- Power-law fitting over singular-value spectra
- Deterministic SHA-256 behavior signatures
- Spectral distance between two models

## 📦 Install

```bash
pip install -r requirements.txt
```

## 🚀 Quick start

```python
from behavior_research import behavior_signature, spectral_distance

print(behavior_signature(W))
print(spectral_distance(W1, W2))
```

## 🧪 Tests

```bash
pytest tests/ -v
```

## 📄 License

MIT — see [LICENSE](LICENSE).
