# **EXP 5: Comparing Prompting Techniques Through Engineering Problem-Solving Scenarios**

## **1. Aim**

To compare different prompting techniques and evaluate their effectiveness in solving a real-world engineering problem based on relevance, accuracy, completeness, clarity, feasibility, and usefulness.

## **2. Project Title**

**AI-Based Crop Disease Detection Using Computer Vision**

## **3. Problem Statement**

Farmers may find it difficult to identify crop diseases at an early stage by visually examining plant leaves. Late detection can lead to reduced crop yield and increased losses. The proposed system uses computer vision and machine learning to analyse leaf images and classify them as healthy or diseased.

The challenge is to develop an accurate, affordable, and practical crop disease detection system.

## **4. Selected Engineering Scenario**

- **Domain:** Artificial Intelligence and Machine Learning
- **Technology:** Python, CNN, TensorFlow, OpenCV
- **Input:** Images of crop leaves
- **Output:** Predicted disease class and confidence score
- **Objective:** Detect crop diseases early and assist farmers in making informed decisions.

## **5. Base Prompt (Naïve Prompt)**

**Prompt 1:**

Suggest a method to detect crop diseases using computer vision.

**AI-generated output:**

Computer vision can be used to detect crop diseases by analysing images of plant leaves. A Convolutional Neural Network (CNN) can be trained using labelled images of healthy and diseased leaves. Python libraries such as TensorFlow and OpenCV can be used to preprocess images, train the model, and predict diseases from new images.

## **6. Improved Prompts Using Different Techniques**

### **Technique 1: Role-Based Prompting**

Act as an AI and machine learning engineer. Design a crop disease detection system using computer vision. Explain the system architecture, required tools, dataset preparation, model training, evaluation metrics, and deployment method. Recommend a practical solution for a student engineering project.

**AI-generated output:**

A practical solution is to build a CNN-based image classification system using Python and TensorFlow.

1. Collect labelled healthy and diseased leaf images.
2. Resize and normalize the images.
3. Split the dataset into training, validation, and test sets.
4. Train a CNN or use transfer learning with MobileNetV2.
5. Evaluate the model using accuracy, precision, recall, F1-score, and a confusion matrix.
6. Deploy the trained model using Flask or Streamlit.

This approach is suitable for a student project because the system can be developed using open-source tools.

### **Technique 2: Step-by-Step Prompting**

Develop a crop disease detection system using computer vision. Explain the solution step by step, starting from dataset collection and image preprocessing, followed by model selection, training, testing, disease prediction, and deployment. For each step, mention the tools required and the expected output.

**AI-generated output:**

1. **Dataset collection:** Obtain labelled crop leaf images from a reliable dataset.
2. **Preprocessing:** Resize images, normalize pixel values, and apply appropriate data augmentation.
3. **Model selection:** Choose a CNN or a pretrained image classification model.
4. **Training:** Train the model using training images and tune it using validation images.
5. **Testing:** Evaluate performance on previously unseen test images.
6. **Prediction:** Accept a leaf image and return the predicted class.
7. **Deployment:** Build a simple web interface using Streamlit or Flask.

The final system accepts an image and produces a predicted disease class with an associated confidence score.

### **Technique 3: Constraint-Based Prompting**

Design a crop disease detection project under the following constraints: use Python and free, open-source tools; assume a limited student budget and access to a standard laptop; use a publicly available labelled dataset; keep the system simple enough for a college project; and evaluate it using appropriate classification metrics. Explain the architecture, limitations, and implementation plan. Do not claim a specific accuracy without experimental evidence.

**AI-generated output:**

A cost-effective solution is to use Python, TensorFlow or Keras, OpenCV, and a publicly available labelled leaf image dataset.

- Use transfer learning with a lightweight pretrained model such as MobileNetV2.
- Perform image preprocessing and data augmentation.
- Train using a GPU if available, or reduce the batch size and image resolution when using a CPU.
- Measure accuracy, precision, recall, F1-score, and inference time.
- Deploy a basic interface using Streamlit.

The main limitations are poor performance on unfamiliar diseases, differences in lighting and backgrounds, dataset imbalance, and hardware constraints. Actual accuracy must be measured during testing.

### **Technique 4: Structured Output Prompting**

Act as a machine learning engineer. Propose a crop disease detection system using computer vision. Present your answer under these headings: (1) Problem, (2) Proposed Solution, (3) Software Requirements, (4) Dataset, (5) Algorithm, (6) Implementation Steps, (7) Evaluation Metrics, (8) Limitations, and (9) Expected Outcome. Use concise technical explanations and distinguish expected results from experimentally verified results.

**AI-generated output:**

1. **Problem:** Early identification of crop diseases is difficult through manual inspection alone.
2. **Proposed Solution:** Classify leaf images using a trained image classification model.
3. **Software Requirements:** Python, TensorFlow/Keras, OpenCV, NumPy, and Streamlit.
4. **Dataset:** A labelled dataset containing healthy and diseased leaf images.
5. **Algorithm:** CNN or transfer learning using MobileNetV2.
6. **Implementation Steps:** Data collection, preprocessing, model training, validation, testing, and deployment.
7. **Evaluation Metrics:** Accuracy, precision, recall, F1-score, and confusion matrix.
8. **Limitations:** Dataset quality, environmental variations, and unseen disease categories.
9. **Expected Outcome:** A prototype that predicts disease categories from uploaded leaf images. Its actual performance must be established through testing.

### **Technique 5: Context-Based Prompting**

I am a computer science engineering student developing a low-cost crop disease detection prototype for farmers. The system must accept a photograph of a plant leaf, classify it as healthy or belonging to a supported disease category, and display the prediction. Design a solution using Python and computer vision. Explain how to handle low-quality images, unseen diseases, class imbalance, and incorrect predictions. Include a testing strategy and practical deployment recommendations.

**AI-generated output:**

The system can use a lightweight CNN or transfer learning model trained on labelled leaf images. The application should check image quality, preprocess images, and display the predicted class with a confidence score.

To improve reliability, the system should use balanced training data, data augmentation, independent test images, and confidence-based warnings. Images that are blurry or outside the supported disease categories should be flagged for further inspection rather than confidently classified. A Streamlit application can provide a simple user interface.

## **7. Comparison and Evaluation Table**

| Prompting technique | Quality  | Accuracy potential | Depth         | Usefulness                      |
| ------------------- | -------- | ------------------ | ------------- | ------------------------------- |
| Naïve prompt        | Moderate | Moderate           | Low           | Basic understanding             |
| Role-based          | High     | High potential     | High          | Expert-oriented guidance        |
| Step-by-step        | High     | High potential     | High          | Implementation guidance         |
| Constraint-based    | High     | High potential     | High          | Practical and affordable design |
| Structured output   | High     | High potential     | Moderate–High | Well-organized report           |
| Context-based       | High     | High potential     | Very high     | Real-world problem solving      |

*Note: These are qualitative evaluations of the generated responses, not measured benchmark scores. Accuracy potential does not mean that the AI response or the proposed model has been experimentally verified.*

## **8. Analysis and Observations**

1. The naïve prompt produced a general solution but lacked detailed implementation steps.
2. Role-based prompting provided a more technically focused response.
3. Step-by-step prompting improved clarity and made the implementation process easier to follow.
4. Constraint-based prompting addressed budget, hardware, and practical limitations.
5. Structured output prompting organized the information into clear sections suitable for a project report.
6. Context-based prompting considered real-world challenges such as poor image quality and unseen diseases.

### **Does ChatGPT consistently provide better results with improved prompts?**

Generally, detailed prompts produced more relevant, organized, and actionable answers in this experiment. However, a simple prompt may work equally well when the question is straightforward. Improved prompting does not guarantee factual correctness; technical claims must still be verified.

## **9. Final Selected Prompting Technique**

**Selected technique: Context-based prompting combined with step-by-step and constraint-based prompting.**

This combination is selected because it addresses the actual engineering problem, implementation requirements, resource limitations, and reliability concerns.

## **10. Refined / Final Prompt**

Act as an experienced AI and machine learning engineer. I am a computer science engineering student developing a low-cost crop disease detection system using computer vision.

Design a complete and practical solution using Python, TensorFlow/Keras, OpenCV, and a publicly available labelled dataset.

Include:

1. Problem definition and system architecture.
2. Dataset collection, preprocessing, and data splitting.
3. Model selection and training procedure.
4. Step-by-step implementation plan.
5. Evaluation using accuracy, precision, recall, F1-score, and a confusion matrix.
6. Handling of poor-quality images, class imbalance, and unseen diseases.
7. Deployment using Streamlit or Flask.
8. Hardware requirements, limitations, and possible improvements.

Assume a limited student budget and access to a standard laptop. Recommend free or open-source tools wherever possible. Provide technically accurate, implementable suggestions, and do not invent experimental results. Clearly distinguish expected outcomes from verified results.

## **11. Engineering Validation**

The proposed solution should be validated before it is used in practice.

- **Dataset validation:** Check labels, class balance, and image quality.
- **Data leakage prevention:** Keep training, validation, and test data separate. Where images come from the same plant or capture session, avoid placing closely related images across different splits.
- **Model validation:** Evaluate the final model on unseen test images using multiple classification metrics.
- **Practical validation:** Test with leaf images taken under different lighting conditions and backgrounds.
- **Reliability validation:** Check whether the model can flag uncertain predictions and images outside its supported classes.
- **Deployment validation:** Verify that image uploads, predictions, error handling, and response times work correctly.

The model should not be considered suitable for real-world agricultural decisions until these tests have been completed and the results reviewed.

## **12. Conclusion**

Different prompting techniques influence the relevance, clarity, completeness, and practical usefulness of AI-generated solutions. Context-based, step-by-step, and constraint-based prompts provide useful guidance for engineering problems by specifying the problem, requirements, and limitations. Combining these techniques produces a more actionable solution than a vague prompt alone.

## **RESULT**

The experiment was executed successfully by comparing a naïve prompt with five improved prompting techniques for an AI-based crop disease detection problem. The comparison demonstrated how prompt structure and context can improve the usefulness of ChatGPT's responses. Engineering validation is required to verify the actual system's performance.
