
# Comparative Analysis of Hotel Reviews: A Case Study of New York Marriott Marquis and Competitors

## Project Overview

This repository contains the code, data, and documentation for a project that performs a detailed comparative analysis of hotel reviews, focusing on the New York Marriott Marquis and its main competitors in New York City. The analysis aims to derive actionable insights to enhance customer satisfaction and maintain a competitive edge.

## Repository Structure

- **Notebook**: This folder contains Jupyter notebooks that guide the analysis from data preprocessing to visualization. The notebooks include:
  - **1-Dataset_Extracting.ipynb**: Initial data extraction and preprocessing.
  - **2-Detect_Language.ipynb**: Language detection to filter non-English reviews.
  - **3-Topic_modeling_nyc.ipynb**: Topic modeling using BERTopic to identify prevalent themes in the reviews.
  - **4-Transformer.ipynb**: Sentiment analysis using a fine-tuned DistilBERT model.
  - **5-Visualization.ipynb**: Visualization of the results, including sentiment trends, topic distribution, and comparative analysis.

- **Paper and Presentation**: This folder contains the research paper and presentation that summarize the findings of the project. The paper includes detailed methodologies, results, and conclusions. Due to the large size of the dataset, it is not included in the repository but can be downloaded from the source mentioned in the paper.

## Data

The dataset used for this project is a collection of hotel reviews sourced from TripAdvisor and is available in JSON format. It consists of 878,561 reviews from 4,333 hotels. For the purpose of this analysis, we focused on approximately 10,000 reviews related to the New York Marriott Marquis and its top five competitors.

**Note**: The dataset is not included in this repository due to its size. However, you can download it from the source provided in the research paper.

## Installation and Setup

1. **Clone the Repository**:

2. **Create and Activate the Conda Environment**:
   If you prefer using Conda, you can create an environment using the `environment.yml` file:
   ```bash
   conda env create -f environment.yml
   conda activate hotel-reviews-env
   ```

3. **Download the Dataset**:
   Follow the instructions in the research paper to download the dataset. Once downloaded, save the data into the `Notebook/data` folder.

4. **Run the Notebooks**:
   Start with the notebooks in the `Notebook` folder in numerical order to follow the analysis pipeline from data extraction to final visualizations.

## Results and Insights

The project provides a comprehensive analysis including:

- **Topic Modeling**: Identifies key themes in customer reviews using BERTopic.
- **Sentiment Analysis**: Classifies reviews as positive or negative using a transformer-based model.
- **Comparative Analysis**: Compares the New York Marriott Marquis with its competitors in terms of ratings, sentiment, and review topics.
- **Visualizations**: Includes various plots to illustrate trends, distributions, and comparative insights.

## References

- **Data Source**: The dataset can be downloaded from Carnegie Mellon University's website: [TripAdvisor Hotel Review Dataset](https://www.cs.cmu.edu/~jiweil/html/hotel-review.html).
- **Research Paper**: Detailed methodology and results are documented in the provided research paper in the "Paper and Presentation" folder.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or issues, please contact Ali El Masri at almasri.ali92@gmail.com

