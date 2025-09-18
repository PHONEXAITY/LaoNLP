# LaoNLP 🇱🇦 

**Open Lao Language AI - Making Lao a first-class citizen in modern AI**

[![Python 3.11](https://img.shields.io/badge/python-3.11-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

LaoNLP is an open-source project that provides comprehensive NLP tools and resources for the Lao language. Our goal is to build high-quality datasets, core NLP tools, and baseline models that researchers and developers can use to advance Lao language technology.

## 🎯 Vision

Make Lao a first-class citizen in modern AI by building open datasets, core NLP tools, and baseline models that anyone can use.

## ✨ Features

### Current (v0.1)
- 🏗️ Project structure and development setup
- 📊 Data collection and preprocessing tools

### Planned
- 📝 **Text Processing**: Word segmentation, sentence tokenization
- 🏷️ **POS Tagging**: Part-of-speech tagging with XLM-RoBERTa
- ✅ **Spell Checker**: Edit distance + language model based correction
- 🔄 **Translation**: Lao ↔ English, Lao ↔ Thai baseline models
- 📚 **Datasets**: Large-scale Lao corpus + parallel translation data
- 🚀 **API**: RESTful API for all NLP functions
- 🌐 **Web Demo**: Interactive web interface

## 🚀 Quick Start

### Installation

```bash
# Clone the repository
git clone https://github.com/PHONEXAITY/laonlp.git
cd laonlp

# Install dependencies
pip install -e ".[dev]"

# Setup pre-commit hooks
pre-commit install
```

### Basic Usage

```python
import laonlp

# Word segmentation
text = "ສະບາຍດີ ຂ້ອຍເປັນນັກພັດທະນາ"
segments = laonlp.segment(text)
print(segments)  # ['ສະບາຍດີ', 'ຂ້ອຍ', 'ເປັນ', 'ນັກພັດທະນາ']

# POS tagging (coming soon)
# pos_tags = laonlp.pos_tag(segments)

# Spell checking (coming soon)  
# corrected = laonlp.spell_check(text)
```

## 📊 Datasets

We're building comprehensive Lao language datasets:

- **Monolingual**: News, Wikipedia, government documents, social media
- **Parallel**: Lao-English and Lao-Thai translation pairs
- **Annotated**: POS-tagged and segmented text for training

All datasets will be released under open licenses on Hugging Face Hub.

## 🛠️ Development

### Project Structure

```
laonlp-project/
├── data/                    # Raw, interim, processed datasets
├── tools/                   # Scrapers, cleaners, converters
├── models/                  # Training configs, checkpoints
├── packages/laonlp/         # Main Python package
├── apps/                    # API and web demo
├── docs/                    # Documentation
└── tests/                   # Test suite
```

### Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests
5. Submit a pull request

## 📈 Roadmap

- **Phase 1** (Sep-Oct 2025): Data collection & preparation
- **Phase 2** (Nov 2025-Jan 2026): Core NLP tools
- **Phase 3** (Feb-May 2026): Models & open source
- **Phase 4** (Jun-Aug 2026): Product & showcase

## 📄 License

This project is licensed under PXDEV License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Thanks to the Lao language community
- Inspired by successful NLP projects like spaCy and Hugging Face
- Built with modern tools: PyTorch, Transformers, FastAPI

## 📞 Contact

- **Issues**: [GitHub Issues](https://github.com/PHONEXAITY/laonlp/issues)
- **Email**: phoneyang1@gmail.com
- **LInkedin**: [@laonlp](https://www.linkedin.com/in/phonexay-chongserchayer-6a0426190/)

---

**ໂຄງການນີ້ແມ່ນການອຸທິດຕົນເພື່ອຊຸມຊົນພາສາລາວ** 🇱🇦