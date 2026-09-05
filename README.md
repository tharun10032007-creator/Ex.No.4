# EXP 4: Generate the Prompt and Evaluate Different Prompt Patterns


## Aim

To generate prompts using different prompt patterns such as Zero-shot Prompting, Few-shot Prompting, Chain of Thought, Persona Pattern, Reverse Prompting, Graph Prompting, and Active Prompting for a manufacturing automation use case, compare the responses from different AI tools, and evaluate them using a rubric.


# Explanation (Use Case)

## Use Case: Smart Manufacturing Automation using IoT

The manufacturing industry aims to reduce manual monitoring and improve operational efficiency through automation. IoT sensors and embedded controllers continuously monitor machinery, collect real-time data, and perform predictive maintenance to minimize equipment failures. The system also enables remote monitoring, energy optimization, and improved production quality.

**Target Audience:**
Manufacturing companies in the automotive, electronics, and food processing industries.

### Main Objectives

* Improve production efficiency by 30%.
* Minimize machinery downtime through predictive maintenance.
* Enable real-time monitoring and remote control.
* Reduce energy consumption by optimizing manufacturing processes.


# Procedure

1. Define the manufacturing automation scenario and objectives.
2. Identify the prompt patterns to be evaluated.
3. Create prompts for each prompting technique.
4. Execute the prompts using AI tools such as ChatGPT, Google Gemini, and Microsoft Copilot.
5. Collect the generated responses.
6. Compare the responses using evaluation criteria.
7. Evaluate the responses using a rubric.
8. Document the observations and results.

---

# Prompt Patterns

## 1. Zero-Shot Prompt

### Prompt

```text
Explain how IoT and embedded systems can automate a manufacturing plant. Include the benefits, major components, and real-world applications.
```

### Result

IoT and embedded systems automate manufacturing by using sensors to collect real-time data from machines. Embedded controllers process the data and communicate with cloud platforms for monitoring and analysis. This enables predictive maintenance, reduces manual intervention, improves production efficiency, lowers energy consumption, and minimizes downtime. Common applications include automotive assembly lines, food processing plants, and electronics manufacturing.

---

## 2. Few-Shot Prompt

### Prompt

```text
Example 1

Input:
How is IoT used in agriculture?

Output:
IoT sensors monitor soil moisture, temperature, and crop health to improve agricultural productivity.

Example 2

Input:
How is IoT used in healthcare?

Output:
IoT devices monitor patient health, track vital signs, and send alerts to healthcare providers.

Now answer:

How is IoT used in smart manufacturing?
```

### Result

IoT is used in smart manufacturing by connecting machines through sensors that continuously monitor temperature, vibration, pressure, and machine performance. The collected data is analyzed to detect faults early, schedule predictive maintenance, optimize production, and improve product quality. This results in increased efficiency, reduced maintenance costs, and improved operational reliability.

---

## 3. Chain of Thought Prompt

### Prompt

```text
Think step-by-step before answering.

Explain how an IoT-based manufacturing automation system works from data collection to predictive maintenance. Describe each stage in sequence.
```

### Result

1. IoT sensors collect operational data from manufacturing equipment.
2. Embedded controllers process and filter the collected data.
3. The processed data is transmitted to cloud servers.
4. AI algorithms analyze the data to identify performance trends.
5. Predictive maintenance models detect potential equipment failures.
6. Maintenance alerts are sent to operators before failures occur.
7. Operators perform preventive maintenance, reducing downtime and improving productivity.


## 4. Persona Pattern

### Prompt

```text
You are a senior Industrial IoT Engineer with 15 years of experience in smart manufacturing.

Explain to a factory manager how IoT automation improves production efficiency, reduces downtime, and saves energy.
```

### Result

Implementing IoT automation allows continuous monitoring of production equipment, enabling early detection of machine faults and reducing unexpected breakdowns. Predictive maintenance minimizes downtime while real-time process optimization improves productivity. Energy monitoring systems identify inefficient equipment, helping reduce electricity consumption and operational costs. Overall, IoT increases production efficiency and enhances product quality.


## 5. Reverse Prompting

### Prompt

```text
Here is the desired output:

"The manufacturing plant achieved 30% higher productivity, reduced downtime through predictive maintenance, and lowered energy consumption using IoT automation."

Generate the prompt that would most likely produce this response from an AI assistant.
```

### Result

**Generated Prompt**

```text
Explain how implementing IoT-based automation in a manufacturing plant can improve productivity, reduce equipment downtime through predictive maintenance, and optimize energy consumption. Include measurable business benefits.
```


## 6. Graph Prompting

### Prompt

```text
Represent the architecture of an IoT-based manufacturing automation system as a flow diagram showing the relationship between sensors, embedded controllers, cloud platform, analytics, predictive maintenance, and factory operators.
```

### Result

```text
           IoT Sensors
                │
                ▼
    Embedded Controllers
                │
                ▼
        Cloud Platform
                │
                ▼
        AI/Data Analytics
                │
        ┌───────┴────────┐
        ▼                ▼
Predictive         Real-Time
Maintenance       Monitoring
        │                │
        └───────┬────────┘
                ▼
       Factory Operators
```

---

## 7. Active Prompting

### Prompt

```text
Before answering, identify any missing information that would help provide a better solution.

Then explain how an IoT-based manufacturing automation system can improve efficiency and reduce machinery downtime.
```

### Result

**Clarification Requested**

* What type of manufacturing industry is being considered?
* What types of machines are currently used?
* Is cloud-based or edge-based monitoring preferred?

**Final Response**

An IoT-based manufacturing automation system improves efficiency by continuously collecting operational data from machines using sensors. AI analyzes this data to detect abnormal patterns and predict equipment failures before they occur. Real-time monitoring enables faster decision-making, while predictive maintenance reduces downtime and maintenance costs. Energy usage is optimized by monitoring machine performance and eliminating unnecessary power consumption, resulting in improved productivity and operational efficiency.



# Comparative Evaluation of Prompt Patterns

| Prompt Pattern    | Purpose                                 | Advantages                       | Limitations                       |
| ----------------- | --------------------------------------- | -------------------------------- | --------------------------------- |
| Zero-shot         | Answers directly without examples       | Fast and simple                  | May miss detailed context         |
| Few-shot          | Uses examples to guide responses        | More consistent outputs          | Requires sample examples          |
| Chain of Thought  | Produces step-by-step reasoning         | Better logical explanations      | Generates longer responses        |
| Persona Pattern   | Responds from a specific role           | Professional and domain-specific | Depends on assigned persona       |
| Reverse Prompting | Generates prompts from expected output  | Useful for prompt engineering    | Requires predefined output        |
| Graph Prompting   | Represents system visually              | Easy to understand architecture  | Limited in text-only environments |
| Active Prompting  | Requests clarification before answering | Produces more accurate responses | Requires additional interaction   |



# AI Tool Comparison

| Evaluation Criteria | ChatGPT   | Google Gemini | Microsoft Copilot |
| ------------------- | --------- | ------------- | ----------------- |
| Accuracy            | Excellent | Very Good     | Very Good         |
| Clarity             | Excellent | Good          | Good              |
| Logical Reasoning   | Excellent | Very Good     | Good              |
| Creativity          | Excellent | Good          | Good              |
| Technical Detail    | Excellent | Good          | Good              |



# Evaluation Rubric

| Criteria          | Weight | ChatGPT | Gemini | Copilot |
| ----------------- | ------ | ------- | ------ | ------- |
| Accuracy          | 5      | 5       | 4      | 4       |
| Relevance         | 5      | 5       | 5      | 4       |
| Clarity           | 5      | 5       | 4      | 4       |
| Completeness      | 5      | 5       | 4      | 4       |
| Logical Reasoning | 5      | 5       | 4      | 4       |
| **Total**         | **25** | **25**  | **21** | **20**  |



# Result

The prompt patterns—Zero-shot Prompting, Few-shot Prompting, Chain of Thought, Persona Pattern, Reverse Prompting, Graph Prompting, and Active Prompting—were successfully implemented for the Smart Manufacturing Automation use case. The generated responses demonstrated that each prompting technique offers unique advantages depending on the task. ChatGPT produced the most comprehensive, accurate, and logically structured responses, while Google Gemini and Microsoft Copilot also generated relevant outputs with minor differences in detail and reasoning. Based on the evaluation rubric, ChatGPT achieved the highest overall score, demonstrating the effectiveness of well-designed prompt engineering techniques for solving real-world manufacturing automation problems.
