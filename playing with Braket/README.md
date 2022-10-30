# Playing with Braket

I herby present a set of examples around the AWS Braket SDK where I used the SDK to make the following notebooks:
- [**1_local_simulator.ipynb**](./1_local_simulator.ipynb) -  build a quantum circuit and run it on a local simulator
- I use the SDK to run the circuit on a AWS simulators statevector (sv1) and tensor network (tn1) (to do)
- I use the SDK to run the circuit on a real quantum computer (to do)
- I use the SDK to get the results and analyze them (to do)

### using and installing the SDK
Ti use the SDK either downloading the SDK using pip for example or use the AWS console to create a new notebook and use the SDK from there if you have access or account on AWS.

To download the braket SDK, follow the instructions on https://github.com/aws/amazon-braket-sdk-python or pip it by running the following command:
```bash
pip install amazon-braket-sdk
```
### tutorials
I totally encourage checking the official github tutorials available on https://github.com/aws/amazon-braket-examples where the contributors have done a great job in providing a set of examples on how to use the SDK and they update it continously. I have used some of the examples from there to build my own notebooks.