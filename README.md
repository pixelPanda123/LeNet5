LeNet-5 Digit Classifier (PyTorch)

This project is a clean and modular implementation of LeNet-5, one of the earliest convolutional neural networks, trained on the MNIST dataset for handwritten digit classification.

It includes:
    A modular PyTorch implementation of the LeNet-5 architecture

    A full training + testing pipeline

    Live loss visualization using Visdom

    Exporting the trained model to ONNX format

**Steps to setup the project**
*Create a Virtual Environment*
python3 -m venv venv
source venv/bin/activate      

pip install --upgrade pip setuptools wheel
pip install -r requirements.txt


*Training*
First setup the visdom server: 

python3 -m visdom.server

then 

python3 run.py 
