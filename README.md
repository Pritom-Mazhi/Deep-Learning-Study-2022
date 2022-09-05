# Deep-Learning-Study-2022

- I have recently read the book **Deep Learning from the Basics - Python and Deep Learning: Theory and Implementation** by **Koki Saitoh**. 
- I tried the codes written in the books to strengthen my understanding on deep learning, and developed a trained model myself using the example mnist dataset mentioned in the book. 
- I converted the code of the model in HDF5 format, then further converted into ONNX and finally NNOIR format. The reason behind the conversion was I wanted to use the saved model in an actcast(https://actcast.io/) application. And NNOIR format is required for using a trained model in an actcast application. Conversion file is to be found as **self/mnist-nn-1-model-coversion.ipynb**.
- A sample actcast model is implemented for this purpose. The plan is to use raspberry pi camera for taking continuous input into the application, and continue classifying the images. And send the data to the server using an API if a certain image object is recognized with more than 90% of probability.
- The next step is to configure the model inside the actcast application to make it ready for taking continuous input and output.
