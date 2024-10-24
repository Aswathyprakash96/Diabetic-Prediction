To model the progression of diabetes using the available independent variables. This model will help healthcare professionals understand how different factors influence the progression of diabetes and potentially aid in designing better treatment plans and preventive measures. The model will provide insights into the dynamics of diabetes progression in patients.
#The Sklearn Diabetes Dataset include following attributes:
age: Age in years
sex: Gender of the patient
bmi: Body mass index
bp: Average blood pressure
s1: Total serum cholesterol (tc)
s2: Low-density lipoproteins (ldl)
s3: High-density lipoproteins (hdl)
s4: Total cholesterol / HDL (tch)
s5: Possibly log of serum triglycerides level (ltg)
s6: Blood sugar level (glu)
Number of Instances: 442
Number of Attributes: The first 10 columns are numeric predictive values.
Target: Column 11 represents a quantitative measure of disease progression one year after baseline.
Artificial Neural Networks (ANNs) are computational models inspired by the way biological neural networks in the human brain function
They are used to recognize patterns and make predictions based on input data.Model implemwntation is done using this method
Basic components:
* Neurons: The basic units of an ANN, similar to biological neurons. 
Each neuron receives inputs, applies a transformation using an activation function, and produces an output.
* Layers:
Input Layer: The first layer that receives input data.
Hidden Layers: Intermediate layers where the network processes inputs. A network can have one or multiple hidden layers.
Output Layer: The final layer that produces the output.
* Weights and Biases:
Each connection between neurons has an associated weight that determines the importance of the input. Biases allow the model to adjust outputs independently of the input.
*Activation Functions:Functions applied to the output of each neuron. Common activation functions include:
Sigmoid: Outputs values between 0 and 1.
ReLU (Rectified Linear Unit): Outputs the input directly if positive; otherwise, it outputs zero.
Tanh: Outputs values between -1 and 1.
Learning Process
Forward Propagation: The input data is passed through the network, layer by layer, until it produces an output.
Loss Function: Measures the difference between the predicted output and the actual target. Common loss functions include Mean Squared Error (MSE) for regression tasks and Cross-Entropy for classification.
Backpropagation: A technique used to update the weights and biases based on the error calculated by the loss function. The goal is to minimize this error over time through iterative training.
APPLICATIONS:
Image and Speech Recognition: For tasks like facial recognition and voice commands.
Natural Language Processing: For understanding and generating human language.
Medical Diagnosis: To analyze patient data and assist in diagnosing diseases.
Finance: For predicting stock prices and assessing risks.

I n the given diabetic datset, i have implemented it using the ANN method, consisting of input layers,output layers and data is calculated, model is trained, accuracy tested using MSE AND R2_score, since the values were huge
i  done an hypertunning test, where activation function was replaced by tan h
