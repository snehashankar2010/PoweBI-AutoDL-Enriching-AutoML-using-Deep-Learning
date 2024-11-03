# AutoDL_Implementation
#### ( Presented in 14th International Conference on Computing, Communication and Networking Technologies (ICCCNT). )

###Overview of PowerBI's Advanced Capabilities and Proposed Enhancements Using AutoDL**

PowerBI, Microsoft’s advanced graphical analytics tool, leverages AI and ML to deliver valuable predictions and insights through the AutoML feature. However, AutoML faces challenges when working with extensive datasets. This study proposes the integration of deep learning (DL) through a new framework called AutoDL, which aims to enhance PowerBI's analytical capacity, particularly for big data scenarios.

### Background and Motivation

- **Rise of Big Data**: Increased interconnectivity and IoT have led to massive datasets, posing challenges for traditional AutoML due to scalability limitations.
- **Need for AutoDL**: To address these limitations, AutoDL integrates deep learning models to better handle large data volumes, promising improved accuracy and prediction capabilities.

### Methodology

- **Data Sets Utilized**:
  - *Keylogger Dataset*: Contains 500,000 instances with 85 features, used to test AutoDL’s performance on security-related big data.
  - *Jigsaw Toxic Comments Dataset*: Comprising approximately 200,000 entries, utilized to assess predictive accuracy for comment toxicity analysis.

- **Deep Learning Models Employed**:
  - *Artificial Neural Network (ANN)*: Emulates human cognitive processes to extract complex data patterns.
  - *RNN Variants* (Simple RNN, Bidirectional RNN, LSTM, and GRU): Specialized in handling sequential data, improving performance on time-sensitive and text-based inputs.

### Results and Comparison

- **AutoML vs. AutoDL**:
  - For the Keylogger dataset, AutoML struggled with data volume, while AutoDL achieved an AUC score of 89.7%.
  - For the Jigsaw dataset, AutoDL outperformed AutoML’s 82% AUC, with Bidirectional RNN and LSTM models achieving over 95% AUC.

### Conclusion and Future Work

- **Enhanced Predictive Power**: AutoDL demonstrated superior performance on big data, suggesting its potential as a PowerBI plugin.
- **Proposed Improvements**: Future work includes time optimization, expanding algorithm options, and extending AutoDL capabilities to analyze unstructured data, such as images and audio.

In conclusion, AutoDL offers a promising enhancement to PowerBI, positioning it to better serve the needs of large-scale data analysis and advanced visualization for businesses and individuals alike.
