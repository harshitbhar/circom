# circom

### Description:
This project utilizes the hardhat-circom template for circuit design, compilation, and proof generation. It involves writing a correct `circuit.circom` implementation, compiling the circuit to generate intermediaries, generating a proof with specified inputs (A=0, B=1), deploying a Solidity verifier to either the Sepolia or Mumbai Testnet, and finally, calling the `verifyProof()` method on the deployed verifier contract to ensure its correctness.

### Project Components:

1. **Circuit Design (circuit.circom):**
   - Implement the circuit logic correctly in `circuit.circom`.

2. **Compilation and Proof Generation:**
   - Utilize the hardhat-circom template to compile the circuit and generate intermediaries.

3. **Proof Generation:**
   - Generate a proof using the provided inputs, A=0 and B=1.

4. **Solidity Verifier Deployment:**
   - Deploy a Solidity verifier contract to either the Sepolia or Mumbai Testnet.

5. **Verification:**
   - Call the `verifyProof()` method on the deployed verifier contract and assert that the output is true.

6. **Readme File:**
   - Provide comprehensive instructions on executing the project successfully.

### Execution Steps:

1. **Circuit Design:**
   - Write the circuit logic in `circuit.circom` ensuring correctness and efficiency.

2. **Compilation and Proof Generation:**
   - Use the hardhat-circom template to compile the circuit and generate intermediaries.

3. **Proof Generation:**
   - Generate a proof using the provided inputs, A=0 and B=1, following the instructions provided in the template or documentation.

4. **Solidity Verifier Deployment:**
   - Deploy the Solidity verifier contract to either the Sepolia or Mumbai Testnet using Hardhat or other deployment tools.

5. **Verification:**
   - After deployment, call the `verifyProof()` method on the deployed verifier contract and assert that the output is true.

### Readme File:

#### Project Overview:
- Briefly describe the purpose of the project and its significance.

#### Instructions:
1. **Circuit Design:**
   - Provide guidelines on how to write the circuit logic in `circuit.circom`.

2. **Compilation and Proof Generation:**
   - Explain the process of compiling the circuit and generating proofs using the hardhat-circom template.

3. **Solidity Verifier Deployment:**
   - Detail the steps to deploy the Solidity verifier contract to either the Sepolia or Mumbai Testnet.

4. **Verification:**
   - Guide users on how to call the `verifyProof()` method on the deployed verifier contract and ensure the output is true.

#### Dependencies:
- List any dependencies or tools required to execute the project successfully.
.
