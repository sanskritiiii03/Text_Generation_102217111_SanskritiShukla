# Text_Generation_102217111_SanskritiShukla
Text Generation Model Evaluation
Overview
This project evaluates various text generation models based on multiple performance metrics and ranks them using the TOPSIS method. The models compared include:

GPT-4
Gemini 1.5 Pro
Claude 2.1
LLaMA 2
MPT-30B
The evaluation focuses on key aspects such as Perplexity (PPL), BLEU Score, ROUGE Score, Diversity Metrics, Latency, and Memory Usage, providing a comprehensive comparison.

Methodology
Evaluation Metrics
Perplexity (PPL) – Measures how well a model predicts a dataset (lower is better).
BLEU Score – Assesses text quality against a reference (higher is better).
ROUGE Score – Evaluates similarity to reference text (higher is better).
Diversity Metrics – Measures variation in generated text (higher is better).
Latency – Tracks response time (lower is better).
Memory Usage – Assesses computational efficiency (lower is better).
TOPSIS Ranking
The Technique for Order of Preference by Similarity to Ideal Solution (TOPSIS) is used to rank models based on their proximity to an ideal performance benchmark.

How to Run the Evaluation
To run the evaluation, follow these steps:

Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-repo/Text-Generation-Evaluation.git  
cd Text-Generation-Evaluation  
Run the notebook:

Open the Jupyter Notebook and execute the cells to analyze model performance.
This evaluation helps in selecting the most suitable model based on factors like accuracy, creativity, and efficiency.

Analysis of Model Performance
Decision Matrix Analysis
The decision matrix presents each model’s performance across different evaluation metrics.

Key Observations:
GPT-4 excels in most areas but has higher latency and memory usage.
Gemini 1.5 Pro leads in BLEU and diversity, making it ideal for creative tasks.
Claude 2.1 ranks highest in ROUGE, making it well-suited for summarization.
LLaMA 2 & MPT-30B offer open-source alternatives but lag behind in overall performance.
TOPSIS Ranking Insights
A bar chart visualizes the TOPSIS ranking, balancing all metrics to determine the most optimal model.

Rank Summary:
GPT-4 – Best all-rounder but resource-intensive.
Gemini 1.5 Pro – Excels in BLEU and diversity.
Claude 2.1 – Strong in ROUGE but weaker in diversity.
LLaMA 2 – Decent performance but slower with higher resource usage.
MPT-30B – Competitive but falls short in overall efficiency.
Graph Interpretations
Decision Matrix Heatmap:
Darker shades indicate stronger performance. GPT-4 and Gemini 1.5 Pro dominate across multiple metrics.
TOPSIS Bar Chart:
GPT-4 and Gemini 1.5 Pro rank at the top, with Claude 2.1 closely behind.
Conclusion
If you prioritize efficiency and creativity, Gemini 1.5 Pro is a great option.
If accuracy and robustness are key, GPT-4 is the best choice.
For summarization tasks, Claude 2.1 performs exceptionally well.
LLaMA 2 & MPT-30B are viable open-source alternatives, but with some performance trade-offs.
Each model has its strengths and limitations—choosing the right one depends on your specific use case.

