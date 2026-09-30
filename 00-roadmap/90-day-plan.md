# 90-Day Foundation Plan

Dates: 2026-10-01 to 2026-12-31  
Expected workload: 12–15 hours per week

The purpose of this phase is not to become an ML engineer in three months. It is to establish the habits and minimum evidence needed to start university well.

## Weekly allocation

- Programming: 6 hours
- Mathematics: 4 hours
- English technical communication: 3 hours
- Documentation and review: 2 hours

## Week 1 — Python and command line

- Read Python Tutorial sections 3–5.
- Read MIT Missing Semester lecture 1.
- Practise variables, conditions, loops, functions, lists, dictionaries, and files.
- Create a small command-line program.
- Commit it with a README.

## Week 2 — Python structure and Git

- Read Python Tutorial sections 6–9.
- Read MIT Missing Semester lecture 2.
- Learn modules, classes, exceptions, virtual environments, and `pytest`.
- Add tests to the week 1 program.
- Make at least three meaningful commits.

## Week 3 — Linear algebra and NumPy

- Watch 3Blue1Brown: Vectors, Linear transformations, Matrix multiplication.
- Read Mathematics for Machine Learning Chapter 2.
- Read the NumPy Quickstart.
- Implement matrix multiplication and linear regression with NumPy.

## Week 4 — Probability and gradients

- Review probability, expectation, variance, and conditional probability.
- Read Mathematics for Machine Learning sections on probability and optimisation.
- Implement linear regression training with gradient descent.
- Compare manual gradients with a closed-form solution.

## Week 5 — Classical machine learning

- Read the scikit-learn Getting Started guide.
- Train logistic regression and a tree-based classifier.
- Learn train/validation/test splits and cross-validation.
- Record the baseline result before tuning.

## Week 6 — Evaluation and honest experiments

- Read scikit-learn model evaluation documentation.
- Learn precision, recall, F1, ROC-AUC, and confusion matrices.
- Identify leakage and common evaluation mistakes.
- Write a short experiment report explaining what worked and what failed.

## Week 7 — Model serving baseline

- Read the FastAPI tutorial.
- Serve a trained model through an HTTP endpoint.
- Add input validation and structured logging.
- Document how to install, run, and test the service.

## Week 8 — Measurement

- Measure cold-start time, single-request latency, concurrent latency, and memory usage.
- Separate model-loading time from inference time.
- Record hardware, software versions, batch size, and test commands.
- Produce a benchmark table.

## Week 9 — First optimisation

- Compare at least two batch sizes.
- Test model warm-up and caching where relevant.
- Change one variable at a time.
- Explain latency and throughput trade-offs.

## Week 10 — Optional ONNX comparison

- Export the model to ONNX if the model supports it.
- Compare correctness and performance with the original implementation.
- Document compatibility problems instead of hiding them.
- Summarise when the optimisation is worthwhile and when it is not.

## Week 11 — Tests and reproducibility

- Add `pytest` tests.
- Add a `requirements.txt` or equivalent environment file.
- Use a fixed random seed and include sample input.
- Test from a clean environment.

## Week 12 — Review and presentation

- Rewrite the project README for a reader who has never seen the code.
- Include architecture, results, limitations, and next steps.
- Record a 3–5 minute explanation in English.
- Review whether performance and systems work felt engaging.
- Update the 2027 university plan based on the result.

## Completion criteria

- [ ] Python project runs from a clean setup.
- [ ] Model service accepts input and returns predictions.
- [ ] Benchmark results are reproducible.
- [ ] Code has tests and an environment file.
- [ ] README explains purpose, method, results, and limitations.
- [ ] At least 20 meaningful commits.
- [ ] One English project presentation.