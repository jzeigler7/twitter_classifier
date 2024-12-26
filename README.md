# CS4641Project

## Project Overview

This repository contains the proposal, midterm checkpoint, and final report for our project, including the results, discussion, visualizations, and code files.

## Directory and File Descriptions

### Root Directory

- **index.html**: The main landing page for the project.
- **midterm_checkpoint.html**: Detailed report of the midterm checkpoint, including results, discussion, and visualizations.
- **final_report.html**: Comprehensive final report of the project, including introduction, problem definition, methods, results, discussion, and future research directions. This report integrates all findings and visualizations to provide a complete overview of the project.
- **README.md**: This file, providing an overview of the repository structure and file descriptions.
- **twitter_class.ipynb**: Jupyter notebook containing the code for the Twitter classification task.

### Visuals

- **AccuracyVsNumberNeighbors.png**: Visualization showing the accuracy vs. number of neighbors for the KNN classifier.
- **DistributionOfHumanAndBotTweets.png**: Visualization depicting the distribution of human and bot tweets.
- **accuracyfordifftestsizes.png**: Visualization showing the accuracy for different test sizes.
- **f1scorefordifftestsizes.png**: Visualization depicting the F1 scores for different test sizes.
- **precisionfordifftestsizes.png**: Visualization showing the precision for different test sizes.
- **precisionrecalling.png**: Visualization depicting the precision-recall tradeoff.
- **recallfordifftestsizes.png**: Visualization showing the recall for different test sizes.
- **nn_dropoutrate.png**: Visualization showing the effect of dropout rate on performance metrics for the Neural Network model.
- **nn_hiddenlayers.png**: Visualization showing the effect of units in hidden layers on performance metrics for the Neural Network model.
- **nn_learningrate.png**: Visualization showing the effect of learning rate on performance metrics for the Neural Network model.
- **rf_maxdepth.png**: Visualization showing the effect of max depth on performance metrics for the Random Forest model.
- **rf_minsamples.png**: Visualization showing the effect of min samples split on performance metrics for the Random Forest model.
- **rf_nestimators.png**: Visualization showing the effect of n estimators on performance metrics for the Random Forest model.
- **ComparingModelPerformance.png**: Image comparing the performance of KNN, Random Forest, and Neural Network models.

### Report Sections

- **MobileBERT Embeddings and Data Processing**: We processed the text data using MobileBERT, extracting embeddings and normalizing them. The final DataFrame (`final_df`) contains 17161 rows and 515 columns, with each row representing a tweet and its associated embeddings. We use 511 different features extracted from the text content of each tweet. An important thing to note is that right now we truncate each tweet at 127 characters; using all of the text could improve results.
- **XGBoost Classifier**: Details the issues encountered with the XGBoost classifier due to missing OpenMP runtime and the steps to resolve this issue.
- **KNN Classifier**: Discusses the results obtained using the KNN classifier, including accuracy, precision, recall, and F1 score.
- **Discussion**: Provides a justification for the results and performance analysis of the KNN model.
- **Visuals**: Contains all the visualizations used to support the analysis.
- **Next Steps**: Outlines the future steps to optimize models and explore alternative approaches.
- **Neural Network for Energy Prediction**: Discusses the results and future steps for the neural network model used for energy prediction.
- **Conclusion**: Summarizes the findings and outlines the overall next steps.
- **Why We Use These Models**: Explains the reasons for choosing specific models like XGBoost and KNN.

### How to Navigate

- Start with **index.html** for an overview of the project.
- Refer to **midterm_checkpoint.html** for detailed analysis and discussions.
- Check the Visuals section for graphical representations of the results.
- Use **twitter_class.ipynb** to review and run the code for the Twitter classification task.
- Read **final_report.html** for a comprehensive understanding of the entire project, including the problem definition, methodology, results, and future research directions.
