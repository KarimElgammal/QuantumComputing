# Playing with Braket

I herby present a set of examples around the AWS Braket SDK where I used the SDK to make the following notebooks:
- [**1_hello_braket.ipynb**](./1_hello_braket.ipynb): build a quantum circuit and run it on a local simulator
- [**2_GHZ_local_simulator**](./2_GHZ_local_simulator.ipynb): build a GHZ quantum circuit and run it on a local simulator
- [**2_GHZ_circuit_on-demand_simulators**](./2_GHZ_circuit_on-demand_simulators.ipynb): build a GHZ quantum circuit and run it on a AWS simulators (sv1, tn1, dm1)
- I use the SDK to run the circuit on a real quantum computer (to do)

## using and installing the SDK
Ti use the SDK either downloading the SDK using pip for example or use the AWS console to create a new notebook and use the SDK from there if you have access or account on AWS.

To download the braket SDK, follow the instructions on https://github.com/aws/amazon-braket-sdk-python or pip it by running the following command:
```bash
pip install amazon-braket-sdk
```
## tutorials
I totally encourage checking the official github tutorials available on https://github.com/aws/amazon-braket-examples where the contributors have done a great job in providing a set of examples on how to use the SDK and they update it continously. I have used some of the examples from there to build my own notebooks.