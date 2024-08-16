## Problem
* We want to evaluate the quality of a question-and-answer application for a document (QA APP).
* Evaluating an LLM application is not easy because, for the same questions, the answers can be slightly different.
* A traditional evaluation system like those used for conventional software applications cannot be applied.

## Solution
* We will prepare a list of questions for which we know the answers and ask them to the QA APP using a RetrievalQA chain for manual evaluation.
* Then we will use a QAEvalChain to have the app itself check if its answers match the evaluation answers.
