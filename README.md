Model weights urls <p>
VIT: https://www.kaggle.com/models/case143/vit-best/ <p>
RESCNN: https://www.kaggle.com/models/case143/cnn/ <p>
CNN: https://www.kaggle.com/models/case143/rescnn/ <p>
ENSEMBLE: https://www.kaggle.com/models/case143/ensemble-fai/ <p>

Navigate to the DEMO folder and open the notebook demo.ipynb  <p>

Install all required packages and libraries using the command pip install requirements.txt  <p>

Download the model weights from the provided links and verify that the paths of the model weights correspond to their location on the device. If not, replace them with the correct directory path.  <p>

Run all cells before the heading "Pre-defined inputs” for initializing required functions, models, and obtaining an array label_samples containing 6 subsets. Here, the array index i in label_samples corresponds to the encoded label ID of a class and stores all records pertaining to that particular class as a dataset.  <p>

To test data using predefined inputs, which contain 5 images belonging to each class, run the cell under the heading ‘Pre-defined inputs’. <p>

To test using user-defined inputs, create a dictionary using samples from label_samples to create a new test dataset in the format {“image”: [], “label”: []}. To view images to be included in the input, call function view_image(). Finally the function defined_inputs(data) to create a data loader for the new test dataset.  <p>

Run cells under the heading 'Test Data' to test the performance of all models on the test data. To test performance on specific models, alter the models parameter of the function classify() 
