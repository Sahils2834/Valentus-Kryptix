# Prompt Engineering Experiments

## 1. Objective

The objective of this experiment was to evaluate zero-shot and few-shot prompting, step-by-step prompting for a multi-step reasoning task, and structured JSON output generation.

## 2. Experimental Setup

- **Model:** [Exact model name]
- **Platform:** Google AI Studio or API
- **Date of testing:** [Date]
- **Task:** Prompt engineering and output reliability

## 3. Experiment 1: Zero-Shot vs. Few-Shot Prompting

### Objective
Classify customer feedback as Positive, Negative, or Neutral.

### Test Input
"The delivery was late, but the product quality is excellent."

### Zero-Shot Prompt
[Paste the exact prompt used.]

### Zero-Shot Raw Output
[Paste the exact model output.]

### Few-Shot Prompt
[Paste the exact prompt, including all examples.]

### Few-Shot Raw Output
[Paste the exact model output.]

### Additional Test Results
[If you tested 5–10 feedback inputs, list each input, both outputs, and whether each was correct.]

### Analysis
[Explain whether few-shot examples improved accuracy, consistency, or output formatting. Mention any limitations.]

## 4. Experiment 2: Direct vs. Step-by-Step Prompting

### Problem
A shop buys 24 notebooks for ₹30 each, sells 15 for ₹45 each, and sells the remaining notebooks for ₹25 each. Calculate the total profit or loss.

### Direct Prompt
[Paste the exact prompt.]

### Direct Raw Output
[Paste the exact model output.]

### Step-by-Step Prompt
[Paste the exact prompt.]

### Step-by-Step Raw Output
[Paste the exact model output.]

### Correct Answer
Cost = ₹720. Total revenue = ₹900. Profit = ₹180.

### Analysis
[Compare the accuracy of both outputs, the arithmetic, clarity, and usefulness. State whether step-by-step prompting improved the result.]

## 5. Experiment 3: Structured JSON Output

### Required Schema
- name: string or null
- date: YYYY-MM-DD string or null
- amount: number or null

### Basic Prompt
[Paste the exact prompt.]

### Basic Raw Output
[Paste the exact model output.]

### Improved Prompt
[Paste the exact prompt, including rules and examples.]

### Five Test Inputs and Raw Outputs
For each test, include:
- Exact input
- Exact JSON output
- Valid JSON syntax: Pass/Fail
- Required keys and types: Pass/Fail
- Correct extraction: Pass/Fail

### Success Rate
[Number of fully successful tests] / 5 × 100 = [Actual percentage]%

### Analysis
[Explain which techniques helped reliability and describe any failures.]

## 6. Overall Findings

[Summarize what you learned about examples, reasoning-oriented instructions, explicit schemas, and output reliability.]

## 7. Limitations

[Discuss the small sample size, possible model variability, and any cases where the prompts failed.]

## 8. Conclusion

[Write a short conclusion based on your actual experimental results.]
