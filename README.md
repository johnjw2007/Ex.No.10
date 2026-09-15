# EX.NO.10 – CONTENT CREATION USING PROMPT PATTERNS

## AIM

To demonstrate the use of different prompting techniques such as Query Decomposition, Decision Making, Answer Engineering, Fact Check List, Tail Generation, Menu Actions, and Semantic Filtering for creating and refining technical content such as reports, articles, case studies, and engineering presentations.

---

## OBJECTIVES

* To understand different prompt patterns.
* To generate engineering content using structured prompts.
* To refine AI-generated content through iterative prompting.
* To evaluate generated content for accuracy, clarity, coherence, completeness, and usefulness.
* To generate presentation-ready technical content using prompts.
* To understand ethical considerations while using AI-generated content.

---

## PROMPT PATTERNS USED

1. Query Decomposition
2. Decision Making
3. Answer Engineering
4. Fact Check List
5. Tail Generation
6. Menu Actions
7. Semantic Filter

---

# TEST CASE SCENARIO 1 – DRONE MISSION PLANNER / COASTAL SURVEILLANCE

## Problem Statement

Develop an AI-based Drone Activity Monitoring and Coastal Surveillance System that can monitor aerial activity in a defined jurisdiction, classify detected objects, verify authorization, identify restricted-zone violations, generate alerts, and maintain evidence records.

### Major Requirements

* Object detection
* Object classification
* Geographic monitoring
* Authorization verification
* Restricted-zone checking
* Alert generation
* Evidence logging
* Operator dashboard

### System Flow

**Detection → Classification → Location Check → Authorization → Alert → Evidence**

---

## Prompt 1 – Basic Prompt

### Input Prompt

> Write a technical report about an AI-based drone surveillance system for coastal law enforcement.

### Sample Output

The AI-based drone surveillance system monitors aerial activity within a defined coastal region. It detects and classifies objects, checks whether drones are authorized, identifies restricted-zone violations, generates alerts, and stores evidence for further investigation.

---

## Prompt 2 – Query Decomposition

### Input Prompt

> Break the drone surveillance problem into smaller technical components including requirements, object detection, object classification, geographic monitoring, authorization verification, restricted-zone checking, alert generation, evidence logging, user interface, and testing.

### Sample Output

The problem is divided into:

1. Requirement Analysis
2. Object Detection
3. Object Classification
4. Geographic Monitoring
5. Authorization Verification
6. Restricted-Zone Detection
7. Alert Generation
8. Evidence Logging
9. Operator Dashboard
10. Testing and Validation

This decomposition makes the complex engineering problem easier to solve systematically.

---

## Prompt 3 – Decision-Making Pattern

### Input Prompt

> Compare YOLO, Faster R-CNN, and SSD for an object-detection component in a drone surveillance system. Compare them based on detection speed, accuracy, computational requirements, and suitability for real-time monitoring.

### Sample Output

The AI compares the three approaches using the requested criteria and provides a structured technical comparison. The final selection should depend on the available hardware, required detection speed, object types, and validation results rather than relying only on a generic recommendation.

---

## Prompt 4 – Answer Engineering

### Input Prompt

> Prepare a complete technical report for the drone surveillance system using the following structure: Introduction, Problem Statement, Existing System, Proposed System, Architecture, Methodology, Technologies Used, Testing, Advantages, Limitations, Future Scope, and Conclusion. Use concise technical language suitable for an engineering project report.

### Sample Output

The generated response follows the requested headings and organizes the system information into a structured engineering report.

---

## Prompt 5 – Fact Check List

### Input Prompt

> Review the generated drone surveillance report and identify technical claims, statistics, legal information, model accuracy values, or performance statements that require verification. Do not present unsupported values as measured results.

### Sample Output

### Fact-Check Items

* Object-detection accuracy → requires experimental validation.
* Processing latency → requires actual measurement.
* Dataset size → verify against the actual dataset.
* Legal or regulatory statements → verify using official sources.
* Model performance comparisons → verify using appropriate benchmarks.
* Hardware requirements → verify through implementation testing.

---

## Prompt 6 – Tail Generation

### Input Prompt

> Continue the technical report by adding a Future Scope section after the limitations section. Maintain the same technical writing style and ensure that the new content logically follows the previous section.

### Sample Output

### Future Scope

Future versions can integrate additional sensors, improved object-classification models, real-time communication mechanisms, advanced geographic analysis, improved evidence management, and larger validated datasets.

---

## Prompt 7 – Menu Actions

### Input Prompt

> After completing the drone surveillance report, provide the user with possible next actions.

### Sample Output

**Available Actions:**

1. Generate system architecture.
2. Generate data-flow diagram.
3. Generate database schema.
4. Generate API design.
5. Generate testing strategy.
6. Generate project presentation.
7. Generate project documentation.

This allows the user to select the next task without rewriting the entire request.

---

## Prompt 8 – Semantic Filtering

### Input Prompt

> Rewrite the drone surveillance explanation for engineering students. Keep the technical concepts but remove unnecessary complexity and use clear, concise language.

### Sample Output

The explanation is transformed into a simpler engineering-level version while preserving important concepts such as detection, classification, geofencing, authorization, alerts, and evidence logging.

---

# TEST CASE SCENARIO 2 – SMART AGRICULTURE ADVISOR

## Problem Statement

Develop an AI-based Smart Agriculture Advisor that analyzes environmental information and provides irrigation recommendations based on soil moisture, temperature, weather information, and crop requirements.

### System Flow

**Sensor Data → AI/Rule-Based Analysis → Irrigation Decision → Farmer Notification**

---

## Prompt 1 – Basic Prompt

### Input Prompt

> Create an article about an AI-based Smart Agriculture Advisor that helps farmers make irrigation decisions.

### Sample Output

A Smart Agriculture Advisor can collect information such as soil moisture and temperature and use this information to provide irrigation recommendations. The system can help farmers monitor field conditions and make more informed irrigation decisions.

---

## Prompt 2 – Query Decomposition

### Input Prompt

> Break the Smart Agriculture Advisor into sensor collection, soil monitoring, weather information, crop requirements, irrigation decision, AI analysis, notification, database, dashboard, and testing components.

### Sample Output

The problem is decomposed into:

**Sensor Collection → Data Processing → Soil Analysis → Weather Analysis → Crop Requirement Analysis → Irrigation Decision → Notification → Data Storage → Dashboard → Testing**

---

## Prompt 3 – Decision-Making Pattern

### Input Prompt

> Compare fixed-threshold, rule-based, and machine-learning approaches for irrigation decisions. Compare them based on implementation complexity, data requirements, explainability, and suitability for an engineering prototype.

### Sample Output

The AI produces a comparison of the three approaches based on the requested engineering criteria. The appropriate approach depends on the prototype requirements, available data, system complexity, and validation requirements.

---

## Prompt 4 – Answer Engineering

### Input Prompt

> Write a technical report on the Smart Agriculture Advisor using the headings: Introduction, Problem Statement, Proposed Solution, System Architecture, Input Data, Processing, Irrigation Decision, User Interface, Testing, Advantages, Limitations, Future Scope, and Conclusion.

### Sample Output

The AI organizes the information according to the requested structure and produces a presentation- and report-ready technical explanation.

---

## Prompt 5 – Fact Check List

### Input Prompt

> Identify all agricultural or technical claims in the generated content that require verification. Do not invent crop-specific statistics or irrigation requirements.

### Sample Output

### Fact-Check Items

* Crop water requirements → verify using appropriate agricultural references.
* Soil-moisture thresholds → validate for the selected crop and soil.
* Weather information → verify data source.
* AI model performance → validate experimentally.
* Water-saving claims → measure using appropriate field experiments.

---

## Prompt 6 – Semantic Filter

### Input Prompt

> Rewrite the Smart Agriculture Advisor article for farmers with basic technical knowledge. Use simple language, practical examples, and avoid unnecessary technical terminology.

### Sample Output

The article is converted into farmer-friendly language while preserving the important system functions and recommendations.

---

# PROMPT ITERATION SUMMARY

| Stage | Prompt Technique    | Purpose                                   |
| ----- | ------------------- | ----------------------------------------- |
| 1     | Basic Prompt        | Generate initial content                  |
| 2     | Query Decomposition | Break complex problems into smaller tasks |
| 3     | Decision Making     | Compare technical alternatives            |
| 4     | Answer Engineering  | Control output structure                  |
| 5     | Fact Check List     | Identify claims requiring verification    |
| 6     | Tail Generation     | Extend existing content                   |
| 7     | Menu Actions        | Provide possible next tasks               |
| 8     | Semantic Filter     | Adapt content to the target audience      |

---

# PPT GENERATION USING PROMPT ENGINEERING

After completing the technical content, a final prompt was used to convert the generated material into a structured engineering presentation.

## PPT Generation Prompt

### Input Prompt

> Create a professional engineering laboratory-record presentation for:
>
> **Ex.No.10 – Content Creation Using Prompt Patterns**
>
> Create a 10–12 slide PPT suitable for a college engineering practical/laboratory presentation.
>
> Keep the presentation technically accurate and easy to understand. Use concise bullet points instead of large paragraphs. Include diagrams, workflow graphics, tables, and visual representations wherever useful.
>
> The presentation should demonstrate the complete prompt-engineering workflow rather than only explaining the theory.
>
> Include the following slides:
>
> **Slide 1 – Title**
>
> Ex.No.10 – Content Creation Using Prompt Patterns
> Subtitle: Engineering Content Generation Using Generative AI
>
> **Slide 2 – Aim & Objectives**
>
> Explain the aim and objectives of using prompt patterns for engineering content generation.
>
> **Slide 3 – Prompt Patterns Explored**
>
> Explain:
>
> * Query Decomposition
> * Decision Making
> * Answer Engineering
> * Fact Check List
> * Tail Generation
> * Menu Actions
> * Semantic Filter
>
> **Slide 4 – Engineering Scenarios**
>
> Present the two selected scenarios:
>
> * Drone Mission Planner / Coastal Surveillance System
> * Smart Agriculture Advisor
>
> **Slide 5 – Drone Mission Planner**
>
> Explain the problem statement, major requirements, and system flow:
>
> **Detection → Classification → Location Check → Authorization → Alert → Evidence**
>
> **Slide 6 – Drone Prompt Iteration**
>
> Demonstrate:
>
> Basic Prompt → Query Decomposition → Decision Making → Answer Engineering → Fact Checking → Final Output
>
> Include actual example prompts from the experiment.
>
> **Slide 7 – Smart Agriculture Advisor**
>
> Explain the problem statement, inputs, processing, and output:
>
> **Sensor Data → AI/Rule-Based Analysis → Irrigation Decision → Farmer Notification**
>
> **Slide 8 – Smart Agriculture Prompt Patterns**
>
> Demonstrate Query Decomposition, Decision Making, Fact Checking, and Semantic Filtering with example prompts.
>
> **Slide 9 – AI Output Evaluation**
>
> Evaluate:
>
> * Coherence
> * Accuracy
> * Completeness
> * Clarity
> * Creativity
> * Tone
> * Structure
> * Practicality
>
> Clearly identify any evaluation scores as illustrative unless experimentally measured.
>
> **Slide 10 – Complete Prompt Engineering Workflow**
>
> Create a visual workflow:
>
> **Engineering Problem → Problem Decomposition → Prompt Design → Initial AI Output → Decision Making → Answer Engineering → Fact Checking → Semantic Filtering → Output Evaluation → Iterative Refinement → Final Content**
>
> **Slide 11 – Ethical Considerations**
>
> Include:
>
> * Verification of AI-generated information
> * Avoiding unsupported statistics
> * Protection of confidential information
> * Copyright and intellectual property
> * Human review
> * Engineering validation
> * Privacy and security
>
> **Slide 12 – Deliverables, Conclusion & Result**
>
> Include the final deliverables, conclusion, and result of the experiment.
>
> Use a clean, modern engineering/AI visual style with consistent typography, diagrams, icons, and spacing. Avoid overcrowding slides. Make the PPT look like an engineering laboratory experiment demonstrating practical prompt engineering rather than a generic business presentation.

---

## SAMPLE PPT OUTPUT

The AI-generated presentation contains:

1. **Title Slide**
2. **Aim and Objectives**
3. **Prompt Patterns**
4. **Selected Engineering Scenarios**
5. **Drone Mission Planner**
6. **Drone Prompt Iteration**
7. **Smart Agriculture Advisor**
8. **Agriculture Prompt Patterns**
9. **AI Output Evaluation**
10. **Prompt Engineering Workflow**
11. **Ethical Considerations**
12. **Conclusion, Result and Deliverables**

---

# EVALUATION

The generated content and presentation can be evaluated using the following criteria:

| Criterion    | Evaluation Focus                      |
| ------------ | ------------------------------------- |
| Coherence    | Logical flow of information           |
| Accuracy     | Technical correctness                 |
| Completeness | Coverage of requirements              |
| Clarity      | Ease of understanding                 |
| Creativity   | Originality of presentation           |
| Tone         | Suitability for the intended audience |
| Structure    | Organization of content               |
| Practicality | Engineering usefulness                |

**Note:** Any numerical evaluation scores used during the experiment should be treated as sample/illustrative observations unless obtained through a controlled evaluation.

---

# ETHICAL CONSIDERATIONS

* AI-generated technical information should be reviewed before use.
* Unsupported statistics should not be presented as experimental results.
* Confidential project information should not be unnecessarily provided to AI systems.
* AI-generated content should be checked for originality and copyright concerns.
* Engineering recommendations should be validated before real-world deployment.
* Human review should remain part of the final content-generation process.

---

# DELIVERABLES

* First Draft
* Refined Content
* Multiple Prompt Versions
* Final Technical Content
* Prompt Repository
* AI Output Evaluation
* Ethical Considerations
* PPT Presentation
* Demonstration

---

# CONCLUSION

Prompt patterns provide a systematic method for generating, refining, structuring, and evaluating engineering content. Query Decomposition helps break complex problems into smaller tasks, Decision Making supports technical comparison, Answer Engineering controls output structure, Fact Check Lists improve verification, Tail Generation extends content, Menu Actions provide next-step choices, and Semantic Filtering adapts the content to the intended audience.

The PPT generation prompt further demonstrates how the refined technical content can be transformed into a structured engineering presentation.

# RESULT

The experiment was successfully performed by applying multiple prompt patterns to two engineering scenarios—Drone Mission Planner/Coastal Surveillance and Smart Agriculture Advisor—and by using iterative prompting to generate refined technical content and a structured engineering presentation.
