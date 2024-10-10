# United Airlines Call Center Efficiency Analysis

## Overview
This project analyzes call center performance with a focus on Average Handling Time (AHT), factors contributing to extended call durations, and opportunities for self-service enhancements in the Interactive Voice Response (IVR) system. It aims to improve operational efficiency and customer satisfaction by identifying key trends in call data and proposing actionable solutions.

## Objectives
1. Explore factors contributing to long Average Handling Time (AHT) and identify key drivers during peak call periods.
2. Analyze transcripts and call reasons to identify issues that can be resolved through self-service options in the IVR system.
3. Develop a predictive model to classify primary call reasons and enhance call routing processes.

## Key Features
- **Data Analysis:** Utilize sentiment analysis and call duration metrics to uncover insights into agent performance and customer satisfaction.
- **IVR Optimization:** Propose specific self-service improvements to reduce unnecessary agent escalations and enhance customer experience.
- **Predictive Modeling:** Implement machine learning techniques to classify call reasons and streamline call handling processes.

## Dataset
The project uses a dataset that includes:
- Call metadata: `call_id`, `customer_id`, `agent_id`, `call_start_datetime`, `call_end_datetime`
- Agent and customer interaction data: `agent_tone`, `customer_tone`, `average_sentiment`, `silence_percent_average`
- Call categorization: `primary_call_reason`
- Transcripts: `call_transcript`

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Results
- Insights: Detailed analysis of call reasons and handling times, showing significant differences between frequent and infrequent call types.
- Proposed IVR Enhancements: Recommendations for self-service options aimed at reducing agent workload and improving customer satisfaction.
- Predictive Model Performance: Insights on the accuracy and limitations of the initial predictive model.

## Conclusion
This analysis highlights critical areas for improvement within the call center operations, emphasizing the need for IVR enhancements and a robust predictive model to streamline processes. Implementing the recommended changes is expected to yield significant benefits in operational efficiency and customer satisfaction.

## Next Steps
1. **Implement IVR Enhancements:**
   - Collaborate with the development team to design and deploy self-service options for common queries identified during the analysis (e.g., billing inquiries).
   - Monitor call volumes and resolution rates to evaluate the effectiveness of these IVR improvements.

2. **Refine Predictive Modeling:**
   - Address the issues of class imbalance in the training dataset to improve model performance.
   - Enhance feature engineering by incorporating additional variables, such as customer sentiment over time, to differentiate call categories effectively.

3. **Continuous Monitoring and Feedback:**
   - Establish a feedback loop to gather insights from agents and customers regarding the new IVR features and call routing processes.
   - Regularly review AHT metrics and customer satisfaction scores to assess the impact of implemented changes and make necessary adjustments.

4. **Training and Development:**
   - Conduct training sessions for agents on new processes and tools introduced through IVR improvements.
   - Foster a culture of continuous improvement by encouraging agents to share insights and suggestions for optimizing customer interactions.

## Contributors
- Vrinda Sharma, Nandini Karmarkar – Data Scientist
