# Machine Learning with PyTorch and Scikit-Learn

This project follows the examples and exercises from Sebastian Raschka's book **"Machine Learning with PyTorch and Scikit-Learn"**.

## About

This repository contains code implementations, experiments, and learning materials based on the comprehensive machine learning guide by Sebastian Raschka. The book covers fundamental machine learning concepts and their practical implementation using PyTorch and scikit-learn.

## Book Reference

📚 **Book**: Machine Learning with PyTorch and Scikit-Learn
👨‍💻 **Author**: Sebastian Raschka
🌐 **Blog Post**: https://sebastianraschka.com/blog/2022/ml-pytorch-book.html

## Environment Setup

The project includes a Python environment check script to ensure all required dependencies are properly installed.

### Prerequisites

- Python 3.9
- Virtual environment (recommended)

### Required Packages

- numpy = 1.21.2
- scipy = 1.7.0
- matplotlib = 3.4.3
- scikit-learn = 1.0
- pandas = 1.3.2
- PyTorch (will be added as we progress)

### Environment Check

Run the environment check script to verify your setup:

```bash
python python_env_check.py
```

## Getting Started

1. **Clone this repository**
   ```bash
   git clone <your-repo-url>
   cd ml-torch-raschka
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv env
   source env/bin/activate  # On macOS/Linux
   # or
   env\Scripts\activate     # On Windows
   ```

3. **Install required packages**
   ```bash
   pip install numpy scipy matplotlib scikit-learn pandas torch torchvision
   ```

4. **Verify your environment**
   ```bash
   python python_env_check.py
   ```

## Project Structure

```
ml-torch-raschka/
├── README.md              # This file
├── .gitignore            # Git ignore rules
├── python_env_check.py   # Environment verification script
├── env/                  # Virtual environment (not tracked)
└── ...                   # Additional chapters and examples (to be added)
```

## Learning Path

This project will follow the book's structure, covering:

- **Part 1**: Introduction to Machine Learning
- **Part 2**: Fundamentals of Machine Learning with Scikit-Learn
- **Part 3**: Deep Learning with PyTorch
- **Part 4**: Advanced Topics

Each section will include:
- Code examples from the book
- Personal notes and insights
- Additional experiments and variations
- Practice exercises

## Contributing

This is a personal learning repository. Feel free to fork and adapt for your own learning journey!

## Resources

- 📖 [Official Book Page](https://sebastianraschka.com/blog/2022/ml-pytorch-book.html)
- 🐙 [Author's GitHub](https://github.com/rasbt)
- 📚 [PyTorch Documentation](https://pytorch.org/docs/)
- 🔬 [Scikit-Learn Documentation](https://scikit-learn.org/stable/)

## License

This project is for educational purposes following the examples in Sebastian Raschka's book. Please refer to the book's license for any restrictions on the original content.