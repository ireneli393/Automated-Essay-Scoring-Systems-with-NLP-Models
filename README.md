# Automated-Essay-Scoring-Systems-with-NLP-Models

**Critical Evaluation of Automated Essay Scoring (AES) Systems for English Language Learners**

In this research, we implemented Automated Essay Scoring (AES) systems utilizing DeBERTa, DistilBERT, and GPT-3.5 to evaluate essays written by 8th-12th grade English language learners. These systems were trained to assess essays across six aspects: cohesion, syntax, vocabulary, phraseology, grammar, and conventions. Additional textual features were integrated to delve deeper into the scoring decisions and to compare them with human assessments.


**Model Comparison and Analysis:**

- **DeBERTa:** Utilized for its advanced transformer architecture, which efficiently handles NLP tasks. The model was trained to predict scores across six critical essay evaluation metrics using a combination of mean pooling and linear output layers.
- **DistilBERT:** A more lightweight model, trained similarly to DeBERTa, focused on evaluating the same six linguistic dimensions.
- **GPT-3.5:** Employed through OpenAI's API, GPT-3.5 evaluated essays directly based on prompts, without the traditional training process. It was tasked with assessing the six linguistic aspects using both direct and graded sample approaches.

**Findings:**

- **DeBERTa** and **DistilBERT** demonstrated strong performance in assessing vocabulary but struggled with more complex aspects like grammar and cohesion, reflecting the inherent challenges in automated systems’ ability to interpret nuanced linguistic constructs.
- **GPT-3.5** graded more harshly than both DeBERTa and DistilBERT, with higher RMSE scores indicating greater deviation from human grading. However, GPT-3.5 was consistent in its grading, particularly in detecting structural and grammatical issues.

**Conclusion:**

The analysis revealed that while AES systems like DeBERTa and DistilBERT can approximate human scoring in certain contexts, their efficacy is closely tied to the complexity of the text. These models excel in evaluating vocabulary but struggle with grammar and cohesion, highlighting areas for future improvement in NLP technologies. GPT-3.5, while consistent, applies stricter grading standards, underscoring the need for flexibility in automated grading systems to better mimic human judgment.
