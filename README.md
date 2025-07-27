# Pattern Recognition Using Neural Networks on FPGA

This project focuses on implementing a digit recognition system using a neural network on an FPGA. The system is trained to recognize handwritten digits (0–9), addressing the challenge of diverse writing styles. The trained model is converted to a hardware description and deployed onto an FPGA board for real-time digit classification.

## 🔧 Components & Tools Used
- Xilinx Spartan-6 / Artix-7 FPGA (or similar)
- Verilog/VHDL
- MATLAB / Python (for dataset preprocessing and model training)
- MNIST-like dataset of handwritten digits
- Xilinx Vivado / ISE Design Suite

## 📋 Features
- Recognizes digits 0 to 9 from handwritten input
- Uses a trained neural network model converted into HDL
- Processes input features and classifies digit in real-time
- Resource-optimized for FPGA implementation

## 🛠️ How It Works
1. Preprocess dataset of handwritten digits to extract pixel values.
2. Train a lightweight feedforward neural network using MATLAB/Python.
3. Convert the trained model into fixed-point logic compatible with HDL.
4. Implement the network in Verilog/VHDL.
5. Synthesize and deploy on FPGA board.
6. Input test digit via simulated data or peripheral interface; receive prediction output.

## 🎯 Applications
- OCR systems (offline character recognition)
- Embedded digit recognition in smart devices
- Real-time educational demos of AI on hardware

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
