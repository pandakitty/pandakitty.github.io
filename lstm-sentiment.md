# Project Deep Dive: Predictive Sentiment Analysis using LSTM

### 1. The Challenge (Problem Statement)
In business analytics, understanding customer sentiment is vital for retention. However, raw consumer reviews are "unstructured" and often messy. The goal was to build a deep learning model that could accurately classify reviews as Positive or Negative to automate feedback analysis.

### 2. Data Preparation & Cleaning
[cite_start]Leveraging my background in translating unstructured physician notes into structured clinical records[cite: 33], I applied the following to the Amazon Reviews dataset:
* **Tokenization:** Breaking sentences into individual word units.
* **Normalization:** Removing stop words and special characters to reduce noise.
* **Padding:** Ensuring all input sequences had a uniform length for the Neural Network.

### 3. Methodology: Why LSTM?
I chose a **Long Short-Term Memory (LSTM)** network because it is a type of Recurrent Neural Network (RNN) capable of learning long-term dependencies. Unlike standard models, LSTMs remember the "context" of words in a sentence, which is crucial for understanding sentiment.

* [cite_start]**Tech Stack:** Python, TensorFlow/Keras, Pandas, NumPy[cite: 11, 13].

### 4. Performance & Results
* [cite_start]**Key Metric:** Achieved an **88% F1 Score**. 
* **Insight:** The model was particularly strong at identifying nuanced negative reviews that keyword-based models often missed.

### 5. Business Impact
[cite_start]Automating this process allows a company to monitor brand health in real-time, triaging customer issues faster—analogous to the triage and initial data collection processes I performed in orthopedic care[cite: 44].
