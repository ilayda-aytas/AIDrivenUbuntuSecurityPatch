# Title
This project is ...

---

### Table of Contents
- [Prerequisites](#prerequisites)
- [Architecture](#architecture)
- [Features](#features)
- [Demo](#demo)
- [Dataset](#dataset)
- [Reports](#reports)
- [Installation](#installation)
- [Tests](#tests)
- [File Structure](#file-structure)
- [Version Control System](#version-control-system)
- [Upcoming](#upcoming)
- [Documentations](#documentations)
- [License](#license)
- [Links](#links)
- [Team](#team)
- [Contact](#contact)
- [Citation](#citation)

---

### Prerequisites
- Python 3.11
- GPU _(min 4GB)_

---

### Architecture
![Architecture](docs/img/Image.gif)

---

### Features
- [x] Feature 1
- [x] Feature 2
- [x] Feature 3

---

### Demo
[Video](videoURL)
[![Video](önizlemeGörseliURLsi)](videoURL)
![GIF](draft.gif)

---

### Dataset
##### Overview
The dataset used in this project is sourced from [Dataset Source Name]. It contains comprehensive information about [describe the dataset contents briefly, e.g., customer transactions, sensor readings, etc.]. The dataset is crucial for training and evaluating our models.

##### Download
To access the dataset, follow these steps:

1. Visit the [Dataset Source Website](soruce.org)
2. Download the dataset file, usually provided in a compressed format (_e.g., .zip, .tar.gz_).
3. Extract the contents of the downloaded file to a directory of your choice.

Alternatively, you can use the following command to download the dataset directly:

```Bash
wget https://example.com/dataset/download_link.zip -O dataset.zip
unzip dataset.zip -d path/to/dataset
```

##### Structure

```Text
path/to/dataset/
├── train/
│   ├── class_1/
│   │   ├── image_1.jpg
│   │   ├── image_2.jpg
│   │   └── ...
│   ├── class_2/
│   │   ├── image_1.jpg
│   │   ├── image_2.jpg
│   │   └── ...
│   └── ...
├── test/
│   ├── class_1/
│   │   ├── image_1.jpg
│   │   ├── image_2.jpg
│   │   └── ...
│   ├── class_2/
│   │   ├── image_1.jpg
│   │   ├── image_2.jpg
│   │   └── ...
│   └── ...
└── labels.csv
```

- `train/`: Contains training data, organized into subdirectories for each class.
- `test/`: Contains testing data, organized similarly to the training data.
- `labels.csv`: Contains metadata and labels for the dataset entries.

---

### Reports
![Report](docs/img/Report.jpg)

---

### Installation

##### Linux/Ubuntu
```bash
sudo apt update -y && sudo apt upgrade -y
```
```bash
git clone https://github.com/Repo
```
```bash
cd Repo
```
```bash
conda env create -f environment.yaml
```
```bash
conda activate environment
```

##### Environment
`.env` file sample: 
```Text
OPENAI_API_KEY=your_api_key
HUGGINGFACE_API_KEY=your_api_key
```

---

### Tests

##### Unit Tests
```bash
python -m unittest test.unit.test
```

---

### File Structure

```Text
.
├── CHANGELOG.md
├── environment.yaml
├── LICENCE
├── README.md
├── requirements.txt
├── RESOURCES.md
└── TODO.md

1 directory, 7 files
```

---

### Version Control System
##### Releases
- [v0.1](https://github.com/organization_name/repo_name/archive/refs/tags/v0.1.zip) _.zip_
- [v0.1](https://github.com/organization_name/repo_name/archive/refs/tags/v0.1.tar.gz) _.tar.gz_
##### Branches
- [BranchName](https://github.com/organization_name/repo_name/tree/Stream)

##### Related Repos
- [RepoName](https://github.com/organization_name/repo_name)

---

### Upcoming
- [ ] Feature 1
- [ ] Bug Fix 1
- [ ] New Pipeline
- [ ] New Model

---

### Documentations
##### Other Readmes
- [TURKISH README](README_TR.md)

##### TO DO
- [TODO](TODO.md)

##### Contributing
- [CONTRIBUTING](CONTRIBUTING.md)

##### Licence
- [LICENCE](LICENCE)

##### Resources
- [RESOURCES](RESOURCES.md)

For more detailed documentation (_including detailed usage of modules, the mathematical formulas and theorems on which the modules are based_), please visit the `.docs/documentation` directory.

---

### Links
- [Github](https://github.com/repo)
- [Website](https://company_name.com/en)
- [Linkedin](https://www.linkedin.com/company/company_name/)

---

### Team
- [Bunyamin Ergen](https://www.linkedin.com/in/bunyaminergen)

---

### Contact
- [Mail](mailto:info@example.com)

---

### Citation
- Reference to cite if you use Voice in a paper or research project:
``` text
@software{software_2024,
author = {Ergen},
doi = {00.0000/zenodo.0000},
month = {01},
title = {{software_2024}},
url = {https://github.com/repo_name},
year = {2024}
}
```

---
