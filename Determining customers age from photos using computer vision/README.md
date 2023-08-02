| Project | Description | Technologies used | 
| :---------------------- | :---------------------- | :---------------------- |
| Determining customers age from photos using computer vision | A chain supermarket is implementing a computer vision system to process photos of customers. Photo capture in the checkout area is supposed to help determine the age of customers, analyze their purchases and suggest products that may be of interest to customers in that age group. It will also monitor cashiers' integrity when selling alcohol. A model has been built to approximate a person's age based on their photo.| Python, Keras |

## Summary
To solve the task, the ResNet50 architecture with a backbone, Adam optimizer, and ReLU activation function was used. The achieved MAE value of 5.7312 is below the specified maximum (7), so the condition is met.

Regarding the model's application, due to the prevalence of people aged 25-40 in the original data, the model will perform best in recognizing visitors of this age group. To improve the accuracy of recognizing minors and avoid selling alcohol to them, the model should be fine-tuned on a dataset of faces younger than 18-21 with more accurate labeling. With the recommendation of potentially interesting products based on age, the obtained model will perform well. However, it is advisable to fine-tune the model on photos of people older than 45 to improve their recommendations.
