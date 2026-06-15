
# Prompt Engineering Assessment

## Topic

**Basics of Prompt Engineering**

### Lesson 2: Spot the Gaps - Understanding What Makes a Weak Prompt

---

# Exercise 1: Identify the Prompt Technique

### Prompt

> Summarize the following paragraph in one sentence.

### Answer

**Technique:** Zero-Shot Prompting

**Reason:** The AI is asked to perform a task without being given any examples.

---

# Exercise 2: Prompt Recognition

### Prompt

> Example:
> Question: What is AI?
> Answer: AI refers to machines that can perform tasks requiring human intelligence.
>
> Now answer: What is Prompt Engineering?

### Answer

**Technique:** One-Shot Prompting

**Reason:** One example is provided before asking the new question.

---

# Exercise 3: Choose the Correct Technique

### Scenario

You want AI to follow the same writing style every time while generating responses.

### Answer

**Technique:** Few-Shot Prompting

**Reason:** Multiple examples help the AI learn and consistently follow a specific pattern or writing style.

---

# Exercise 4: One-Shot Prompt Creation

### Prompt

```text
Example:

Customer:
My order arrived late.

Response:
Thank you for reaching out. We apologize for the delay and appreciate your patience. Our team is looking into the issue and will update you shortly.

New Customer Complaint:
The product I received is damaged.

Write a polite response.
```

### Explanation

This is a One-Shot Prompt because one example is provided to guide the tone and structure of the response.

---

# Exercise 5: Rewrite Using Correct Technique

### Original Prompt

```text
Make this sound professional:
"Send this now."
```

### Improved Prompt

```text
Example:

Original:
Can you send this?

Professional:
Could you please send this at your earliest convenience?

Now rewrite professionally:

"Send this now."
```

### Technique Used

**One-Shot Prompting**

---

# Exercise 6: True or False

### Statement

> Few-shot prompting is used when the task is very simple and well-known.

### Answer

**False**

### Explanation

Few-shot prompting is generally used when consistency, style, or complex patterns are important and examples are needed.

---

# Exercise 7: Prompt Comparison

### Prompt A

```text
Write a product description.
```

### Prompt B

```text
Write a 3-sentence product description for a budgeting app targeting young professionals.
```

### Answer

**Prompt B**

### Reason

Prompt B includes:

* Clear audience
* Context
* Length requirement
* Specific task

This results in more accurate and useful output.

---

# Exercise 8: Technique Selection

### Scenario

You want AI to consistently follow the same writing style across multiple outputs.

### Answer

**Technique:** Few-Shot Prompting

### Reason

Multiple examples help establish and maintain a consistent writing pattern.

---

# Exercise 9: Bonus Challenge

### Fill in the blanks

* Simple task, no examples → **Zero-Shot Prompting**
* One example to guide style → **One-Shot Prompting**
* Multiple examples to train pattern → **Few-Shot Prompting**

---

# Gap Analysis Example

## Weak Prompt

```text
Write a blog post.
```

## Missing Elements

* Role
* Audience
* Context
* Tone
* Output Format

## Improved Prompt

```markdown
# Role

You are an expert content marketer.

# Task

Write a blog post.

# Audience

Working professionals.

# Topic

5 Ways AI Improves Productivity.

# Tone

Professional and informative.

# Output Format

Title

Introduction

Main Points

Conclusion
```

## Why It Is Better

The improved prompt provides clear instructions, audience targeting, tone guidance, and output structure, resulting in more relevant and higher-quality responses.

---

# Key Learnings

* Zero-Shot Prompting is useful for simple tasks.
* One-Shot Prompting uses a single example to guide output.
* Few-Shot Prompting uses multiple examples to improve consistency.
* Strong prompts include context, audience, tone, and format.
* Identifying missing prompt elements helps improve AI responses.

