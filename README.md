**Project Name:** Latent Semantic Analysis



**Description:**
This repository contains an implementation of Latent Semantic Indexing (LSI) from scratch. LSI is a technique utilized in natural language processing and information retrieval to analyze relationships between a set of documents and the terms they contain. It generates a set of concepts related to the documents and terms, aiding in better understanding and organizing large text corpora.

**Author:**

- Ramin Babazade
- Email: rambzd@gmail.com

---

## Table of Contents

1. [Introduction](#introduction)
2. [Project Structure](#project-structure)
3. [Usage](#usage)
4. [Dependencies](#dependencies)
5. [Development](#development)
6. [License](#license)


## Project Structure

The project structure is organized as follows:

```
Latent_Semantic_Analysis
│
├── Latent_Semantic_Analysis/
│   ├── LSA_MAIN.ipynb
│   └── ... (source code files)
│
├── README.md
├── stopwords.txt
├── body.csv
└── ... (other project files)

## Usage

To use this LSI implementation:

1. **Clone**: Clone this repository.

2. **Explore Notebooks**: Open and explore `LSA_MAIN.ipynb` for the main implementation, `LSA_Test.ipynb` for testing, and `latent_semantic_analysis.ipynb` for additional experiments.

3. **Review Data**: Check `body.csv` for sample text data structure.

4. **Stopwords**: Ensure alignment of stopwords in `stopwords.py` and `stopwords.txt`.

5. **Contribute**: Extend functionalities, improve tests, or provide feedback.

6. **Acknowledge**: Appreciate contributors listed in README.

7. **Run Tests**: Execute tests using `testproject.py`.

8. **Experiment**: Try different datasets, parameters, and preprocessing techniques.

9. **Document**: Record findings and modifications.


## Dependencies

The project depends on the following Python packages:

- Python 3.12
- scikit-learn 1.3.0
- ipykernel 6.25.2 (for development)


These dependencies are managed using Poetry, a Python dependency management tool.


## Development

If you wish to contribute to this project or further develop it, consider the following:

- Fork the repository on GitHub.

- Create a new branch for your changes:

  ```bash
  git checkout -b feature/your-feature-name
  ```

- Make your changes and commit them with meaningful messages:

  ```bash
  git commit -m "Add feature/fix: Description of your changes"
  ```

- Push your changes to your forked repository:

  ```bash
  git push origin feature/your-feature-name
  ```

- Create a pull request on the original repository to propose your changes.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



Contributors:
Name: Rambzd
Latest Commit: Query Processing Done (e69b209)
Contributions: Query processing implementation and testing.
