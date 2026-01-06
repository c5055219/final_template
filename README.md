# final_template
README - CROSS MODAL ATTENTION-Baseline Multimodal Model
OVERVIEW 
This project focuses on multimodal sequence prediction using deep learning techniques in PyTorch. 
This project explores how a deep learning model can combine image and text information and use past data to predict what comes next.
This project has two models that are implemented in it:
1.	Baseline Multimodal Model – this model simply combines image features and text features and learns from the sequence using a GRU.
2.	Cross-Modal Attention Model – this model allows images to focus on relevant parts of the text and text to focus on relevant parts of the images. 
The models are trained using synthetic multimodal data and this project helps demonstrate how attention mechanisms can improve learning when working with multiple data types.
FEATURES
•	Uses both images and text as input 
•	Implements GRU for temporal learning 
•	Includes a Cross-Modal Attention 
•	Learns from sequences 
•	Compares performance with a baseline model 
•	Visualizes training loss using graphs 
•	Runs efficiently on GPU (Google Colab)
TECHNOLOGIES 
•	Python 
•	Pytorch 
•	Numpy
•	Matplotlib
•	Google Colab
 
TRAINING PROCESS
•	Loss Function: Mean Squared Error(MSE)
•	Baseline model trained for epochs 10 
•	Attention model trained for 20 epochs 
Loss Functions Used
•	 Image reconstruction loss – measures how well image features are predicted
•	 Text Prediction loss- evalutes next-token prediction 
•	Context Loss – ensures consistency across image patterns 
•	 Final loss – weighted combination of all losses
LICENCES
MIT



 


