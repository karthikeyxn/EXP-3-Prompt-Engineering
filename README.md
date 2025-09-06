## Aim

To evaluate and compare the performance, user experience, and response quality of prompting tools across ChatGPT, Claude, Bard, Cohere Command, and Meta using a controlled use case: Summarizing a technical text.

## Algorithm 

Select Use Case: Text summarization of a short technical paragraph.

Design Common Prompt: Same instruction given to all AI systems.

Collect Outputs: Run the prompt in ChatGPT, Claude, Bard, Cohere Command, and Meta.

Evaluation Criteria:

Accuracy (faithful summary without losing core details)

Clarity & Conciseness (how easy and short the summary is)

Coherence (logical and structured response)

User Experience (formatting, readability, extra helpfulness)

Compare Results: Score each model from 1–5 on criteria.

## Prompt (Used for All Platforms)

"Summarize the following text in 3 bullet points, focusing only on the technical aspects:

Text:
“Artificial Intelligence (AI) models are increasingly being optimized for energy efficiency. One approach is quantization, which reduces the precision of model parameters to lower computational cost. Another method is knowledge distillation, where a smaller model learns from a larger one to achieve comparable accuracy with fewer resources.”

## Outputs (Hypothetical 2024 Behavior)
1. ChatGPT

AI models are optimized for energy efficiency.

Techniques include quantization (reducing parameter precision).

Knowledge distillation transfers knowledge from large to small models.

(Concise, structured, clear)

2. Claude

AI optimization focuses on reducing energy consumption.

Quantization lowers computational cost by reducing parameter precision.

Knowledge distillation lets smaller models mimic larger models while preserving accuracy.

(Slightly more verbose, very clear)

3. Bard

Energy efficiency in AI is achieved through methods like quantization and knowledge distillation.

Quantization minimizes computation by lowering model parameter precision.

Knowledge distillation trains smaller models with guidance from larger ones, balancing efficiency and accuracy.

(Balanced explanation, flows like natural text rather than pure bullets)

4. Cohere Command

AI models are being made energy-efficient.

Quantization reduces precision for lower computational cost.

Knowledge distillation helps smaller models achieve accuracy similar to larger models.

(Direct, to the point, but less stylistic polish)

5. Meta (LLaMA-based platform)

AI energy efficiency efforts include:

Quantization: lowers precision, reducing compute demand.

Knowledge Distillation: smaller models trained from larger ones retain performance.

(Good technical formatting, slightly more academic)

## Result (Comparison Table)
| Platform    | Accuracy (1–5) | Clarity (1–5) | Coherence (1–5) | User Experience (1–5) | **Total** |
| ----------- | -------------- | ------------- | --------------- | --------------------- | --------- |
| **ChatGPT** | 5              | 5             | 5               | 5                     | **20/20** |
| **Claude**  | 5              | 4             | 5               | 4                     | **18/20** |
| **Bard**    | 5              | 4             | 4               | 4                     | **17/20** |
| **Cohere**  | 4              | 4             | 4               | 3                     | **15/20** |
| **Meta**    | 5              | 4             | 5               | 4                     | **18/20** |


✅ Conclusion:

ChatGPT delivered the most concise, accurate, and user-friendly output.

Claude and Meta gave strong technical clarity but slightly verbose.

Bard leaned toward natural, conversational style, sometimes less concise.

Cohere Command was accurate but less polished in readability.
