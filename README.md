
# **EX-02: Cross-Platform Prompting – Evaluating Diverse Techniques in AI-Powered Text Summarization**
## Name :Dhivya Dharsini B
## Reg No: 212223240031
## **AIM**:

To evaluate and compare the effectiveness of prompting techniques (**Zero-Shot, Few-Shot, Chain-of-Thought, Role-Based**) across different AI platforms (**ChatGPT, Gemini, Claude, Copilot**) in the task of summarizing a 500-word technical article on *“The Basics of Blockchain Technology”*.
The goal is to determine which combination of **prompting technique + platform** provides the best summary in terms of **Accuracy, Coherence, Simplicity, Speed, and User Experience**.

## **Algorithm**:

1. **Input**:

   * Article: *The Basics of Blockchain Technology* (\~500 words).
   * Platforms: {ChatGPT, Gemini, Claude, Copilot}.
   * Prompting Techniques: {Zero-Shot, Few-Shot, Chain-of-Thought, Role-Based}.

2. **Preparation**:

   * Create standardized prompts for each technique.
   * Define evaluation metrics (1–5 scale):

     * Accuracy
     * Coherence
     * Simplicity
     * Speed
     * User Experience

3. **Execution**:

   * For each platform **P** in {ChatGPT, Gemini, Claude, Copilot}:

     * For each technique **T** in {Zero-Shot, Few-Shot, Chain-of-Thought, Role-Based}:
       a. Provide input article + prompt.
       b. Collect generated summary.
       c. Record time taken (Speed).
       d. Evaluate Accuracy, Coherence, Simplicity, User Experience.
       e. Store results in evaluation table.

4. **Analysis**:

   * Compare average scores across combinations.
   * Identify the best-performing platform + prompting technique.

5. **Output**:

   * Summary of findings.
   * Recommendation for educational summarization tasks.

## **Result (Sample Evaluation Table – ANN Topic)**

| Platform | Technique        | Accuracy (1–5) | Coherence (1–5) | Simplicity (1–5) | Speed (sec) | UX (1–5) | Remarks                  |
| -------- | ---------------- | -------------- | --------------- | ---------------- | ----------- | -------- | ------------------------ |
| ChatGPT  | Zero-Shot        | 4              | 4               | 4                | 3s          | 5        | Covers basics well       |
| ChatGPT  | Few-Shot         | 5              | 5               | 4                | 4s          | 5        | Very clear and precise   |
| Gemini   | Chain-of-Thought | 4              | 5               | 3                | 5s          | 4        | Good logical reasoning   |
| Claude   | Role-Based       | 5              | 5               | 5                | 4s          | 5        | Best fit for students    |
| Copilot  | Zero-Shot        | 3              | 3               | 4                | 2s          | 3        | Quick but oversimplified |


## **Graph (ANN Topic – Average Scores)**

<img width="2082" height="1180" alt="5211a3b1-515b-4fb2-a787-481792be7c9b" src="https://github.com/user-attachments/assets/2d16555a-825c-47c7-9878-2e723c944668" />

## **Best Result:**

* **Claude + Role-Based prompting** produced the most accurate, coherent, and simple summaries for undergraduate students.
* **ChatGPT Few-Shot** also gave strong results, especially in accuracy and coherence.


## **About**:

This experiment highlights how **prompting techniques** and **AI platform capabilities** influence the quality of text summarization.
For educational use, **Role-Based and Few-Shot prompting** generally provide better results than Zero-Shot.
Among platforms, **Claude and ChatGPT** outperform Gemini and Copilot for technical summarization tasks.


## **Resources**:

* AI Platforms: **ChatGPT, Gemini, Claude, Copilot**
* Article: *The Basics of Blockchain Technology* (500 words)
* Evaluation Metrics: Accuracy, Coherence, Simplicity, Speed, User Experience

## Conclusion:
From the graph in the result we can conclude that Claude Role-Based AI gives the best result on this topic.
