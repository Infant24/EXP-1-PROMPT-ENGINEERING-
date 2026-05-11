# EXP-1-PROMPT-ENGINEERING-

## Aim: 
Comprehensive Report on the Fundamentals of Generative AI and Large Language Models (LLMs)
Experiment: Develop a comprehensive report for the following exercises:

Explain the foundational concepts of Generative AI.
Focusing on Generative AI architectures. (like transformers).
Generative AI applications.
Generative AI impact of scaling in LLMs.

## Algorithm:

### 1. Data Preprocessing and Tokenization:
Data Collection: Gather a massive corpus of text data (e.g., books, articles, websites).
Cleaning: Clean the data by removing irrelevant information, special characters, and formatting.
Tokenization: Break the raw text into smaller units called tokens (words or sub-words). This step converts human-readable text into a numerical format that the model can understand.
### 2. Model Architecture and Positional Encoding:
Select a Transformer-based architecture: Choose a model structure, typically a decoder-only model like GPT, designed for generative tasks.
Embeddings: Convert each token into a high-dimensional vector (embedding) that represents its semantic meaning.
Positional Encoding: Add a unique vector to each token's embedding to provide information about its position in the sequence, as the transformer architecture does not inherently understand order.
### 3. Training the Model (Pre-training):
Self-supervised learning: Train the model to predict the next token in a sequence, given the preceding tokens. This is a form of self-supervised learning, as the labels are derived from the data itself.
Loss Function: Use a loss function (e.g., cross-entropy) to measure the difference between the model's predicted token probabilities and the actual next token.
Optimization: Use an optimizer (e.g., Adam) to adjust the model's weights to minimize the loss, allowing the model to learn the patterns and grammar of the language.
### 4. Fine-tuning (Optional):
Task-specific data: Train the pre-trained model on a smaller, specific dataset to adapt it for a particular task, such as summarization, question-answering, or sentiment analysis.
Supervised learning: This phase often involves supervised learning where the model is given examples of inputs and desired outputs for the specific task.
### 5. Inference and Generation:
Input Prompt: Provide the trained model with a starting prompt or a partial sentence.
Token Generation: The model predicts the next token based on the input prompt and its learned knowledge.
Sampling: Choose the next token from the model's predicted probability distribution. Greedy sampling selects the most likely token, while top-k or nucleus sampling introduces randomness for more creative and diverse outputs.
Iterative Process: Repeat the generation process, using the newly generated token as part of the input for the next prediction, until a stop condition is met (e.g., generating an end-of-sequence token or reaching a maximum length).

## Output:

[Foundational Concepts of Generative AI.pdf](https://github.com/user-attachments/files/22081874/Foundational.Concepts.of.Generative.AI.pdf)

## Result

The report is successfully completed.
