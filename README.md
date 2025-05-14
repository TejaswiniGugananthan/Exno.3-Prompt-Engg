# Exno.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### DATE:                                                                            
### REGISTER NUMBER : 212222230157 
### Aim: 
To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts.

### Algorithm:  1. Direct Instruction Prompts
Objective: Guide the chatbot to respond concisely to customer inquiries.
Prompt Pattern:
Prompt: "When a customer asks for the status of their order, reply with: 'Your order is currently being processed and will be delivered by [date].'"
2. Contextual Prompting
Objective: Incorporate specific context to provide detailed answers based on the user’s previous interaction.
Prompt Pattern:
Prompt: "If the customer previously mentioned that they haven’t received their order, say, 'I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.'"
3. Persona-Based Prompting
Objective: Design the chatbot to adopt a specific persona, making the interaction more engaging.
Prompt Pattern:
Prompt: "Pretend you are a friendly, helpful customer service representative. Use a conversational tone, such as 'Hey there! I’m here to help with any questions you might have. Let’s get your issue sorted!'"
4. Few-Shot Prompting
Objective: Teach the AI how to respond using a few examples, enabling it to generalize for similar situations.
Prompt Pattern:
Prompt: "Here are some examples of how to handle technical questions:
'My phone isn't charging.' → 'Have you tried using a different cable? If that doesn’t work, it may be an issue with the port.'
'The screen is flickering.' → 'It sounds like a display issue. Have you tried restarting the device?'
Now, respond to: 'My app keeps crashing.'"
5. Chain of Thought Prompting
Objective: Use a step-by-step reasoning approach for resolving more complex or technical issues.
Prompt Pattern:
Prompt: "When a customer reports their laptop overheating, guide them through the following steps:
Ask if they are using the laptop on a soft surface.
Suggest moving the laptop to a flat, hard surface for better airflow.
Ask if they’ve cleaned the vents recently.
Recommend restarting the device to see if the issue persists.
Now, solve: 'My laptop fan is making a loud noise.'"
6. Instruction with Constraints
Objective: Instruct the chatbot to provide assistance while adhering to specific constraints (e.g., response length or tone).
Prompt Pattern:
Prompt: "Respond to order inquiries in no more than 50 words and avoid using technical jargon. For example, 'Your order is on the way and should arrive by [date]. Feel free to reach out if you need anything else.'"
7. Reflective Prompting
Objective: Ensure that the chatbot reflects the user’s query back to them before providing a response, reducing misunderstandings.
Prompt Pattern:
Prompt: "When a customer asks for help, first reflect their question back to them. For example, if they ask 'How can I reset my password?' respond with 'You're asking how to reset your password, correct? Here’s how you can do it.'"
Result: The various types of Prompts are executed successfully.

# Prompt:
Generative the basic steps for analysing the machine learning model


# Output:
1. Understanding the Problem: The first step in analyzing a machine learning model is to understand the
problem you're trying to solve. This involves identifying whether the task is classification, regression, or
clustering. You should also clearly define your target variable, which is the value you want your model to
predict or classify.
2. Data Collection: Next, you need to collect data relevant to your problem. This data can come from various
sources such as CSV files, APIs, or databases. It is important to ensure that the data is accurate, recent, and
suitable for the problem you are addressing.
3. Data Preprocessing: Once the data is collected, it needs to be cleaned and prepared. This involves handling
missing values, removing duplicate entries, and converting categorical data into numerical form using
encoding techniques. If the data contains numerical values with different scales, normalization or
standardization may also be required to improve model performance.
4. Splitting the Data: After preprocessing, the dataset is divided into different parts. Typically, the data is split
into a training set and a testing set, with around 70 to 80 percent of the data used for training and the rest for
testing. Sometimes, a validation set is also created to help tune the model’s hyperparameters without affecting
the test data.
5. Training the Model: At this stage, a machine learning algorithm is chosen based on the type of problem.
Algorithms like Decision Trees, Support Vector Machines, or Linear Regression may be used. The model is
trained using the training dataset, and initial hyperparameters are set depending on the chosen algorithm.
6. Making Predictions: After training, the model is used to make predictions on the testing dataset. These
predictions are then compared to the actual results to see how well the model is performing on unseen data.
7. Evaluating the Model: To evaluate the performance of the model, different metrics are used. For
classification tasks, metrics such as accuracy, precision, recall, and F1-score are common. For regression tasks,
mean squared error (MSE) and R² score are often used. A confusion matrix is also helpful in understanding
classification results in more detail.
8. Visualizing the Results: Visualization is a key step in understanding how well the model performs. Graphs
such as the confusion matrix heatmap, ROC curve, and loss or accuracy curves can give insights into model
behavior. Feature importance graphs can show which inputs are most influential in making predictions.
9. Tuning the Model: If the model does not perform as expected, hyperparameter tuning is done. This can be
achieved through grid search or random search techniques. Cross-validation is also applied to make sure the
model generalizes well to different datasets.
10. Deployment and Monitoring: Finally, the model is deployed in a real-world application where it can start
making predictions for actual users. After deployment, the model must be monitored to ensure that its
performance remains consistent. If the model starts to degrade due to new or changing data, it may need to
be retrained or updated.


# Result: 
Thus the Prompts were exected succcessfully .



