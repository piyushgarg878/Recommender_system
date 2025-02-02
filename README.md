# Recommendation System with OpenAI and Apache Spark

This repository contains a recommendation system built using OpenAI's language models and Apache Spark, running on Google Colab. The system leverages Spark for large-scale data processing and OpenAI for intelligent recommendations.

## Features
- Uses Apache Spark for distributed data processing.
- Integrates OpenAI's API for generating personalized recommendations.
- Works seamlessly on Google Colab with minimal setup.
- Supports various recommendation techniques like collaborative filtering and content-based filtering.

## Getting Started

### Prerequisites
Ensure you have the following dependencies installed:
- Google Colab (recommended)
- OpenAI API key ([Sign up here](https://openai.com))
- PySpark
- Pandas, NumPy

### Installation

Clone the repository:
```bash
git clone https://github.com/yourusername/recommendation-system.git
cd recommendation-system
```

Run the following in Google Colab:
```python
!pip install openai pyspark pandas numpy
```

### Setup OpenAI API Key
Store your OpenAI API key securely in an environment variable:
```python
import os
os.environ["OPENAI_API_KEY"] = "your-api-key-here"
```

### Running the Notebook
1. Open `recommendation_system.ipynb` in Google Colab.
2. Run all the cells to preprocess data, train the recommendation model, and generate recommendations.
3. View results and analyze recommendations.

## Usage
Modify `data.csv` to include your dataset. The script processes this dataset and generates recommendations based on user preferences.

## Contributing
Feel free to fork this repository and make improvements. Submit a pull request for review.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- [OpenAI](https://openai.com)
- [Apache Spark](https://spark.apache.org)
- [Google Colab](https://colab.research.google.com/)

