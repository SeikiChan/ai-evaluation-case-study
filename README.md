# AI Evaluation Case Study

A human-evaluation pilot comparing GPT and Claude on 25 frozen multilingual dialogue and instruction-following cases.

## Results

- **25** test cases and **50** model responses
- **25** pairwise comparisons: GPT won **13**, Claude won **4**, and **8** were ties
- Dimensions: instruction following, factual accuracy, grounding, relevance, and Chinese naturalness
- Model labels recorded in the study: GPT 5.6 ins; Claude sonnet 5.5 low

These results describe this case set and this evaluation only. They are not a benchmark or a general ranking of either model. Untested dimensions are marked N/A and excluded from that dimension's average.

## Read the case study

[Open the full 25-case English portfolio report](docs/portfolio_case_study_25_cases.md). Each case includes its prompt, expected behavior, verbatim GPT and Claude responses, evidence for the scores, a five-dimension score table, and a pairwise outcome. Model responses remain in the language originally returned.

## Evaluation method

Both systems received the same frozen prompt for each case. Each response was scored independently on a 1–5 scale before pairwise comparison. Scores are tied to specific response evidence; unsupported claims, missed constraints, and unnecessary elaboration are considered separately.

## Limitations

This is a 25-case, single-rater pilot. Case selection and evaluator judgment affect the results; do not generalize them to production behavior or overall model quality.
