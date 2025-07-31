[<img src="https://qbraid-static.s3.amazonaws.com/logos/Launch_on_qBraid_white.png" width="150">](https://account.qbraid.com?gitHubUrl=https://github.com/qBraid/oqi-hacks-2025.git)

# [SEA Quantathon for Social Good: 2025 Thailand](https://sites.google.com/view/sea-quantathon/home?authuser=0) 🇹🇭

## 🌟 About the Hackathon

The OQI Hackathon is targeted at undergraduate and graduate students in STEM, machine learning, data science, quantum computing, social science, or other relevant fields, from the Southeast Asia region. The main theme of the hackathon is to align with UN's Sustainable Development Goals (SDGs) and Thailand's national development strategies, focusing on:

- **Healthcare and Medicine**: Tropical disease research and telemedicine
- **Climate Change**: Quantum solutions for environmental challenges
- **Renewable Energy**: Solar and wind energy optimization


## 💻 Setup Guide
1. **qBraid Account**: Register at [qbraid.com](https://qbraid.com)
2. **Enter Access Code**: 
   - Navigate to [account.qbraid.com](https://account.qbraid.com) and click on "Manage" subscription. 
   - Enter the access code provided by the organizers in the "Access Key" field. This should provide you qBraid credits for the hackathon.
3. **Development Environment**: 
   - Cloud: 
     - Launch the [qBraid Lab](https://docs.qbraid.com/lab/user-guide/getting-started) platform by clicking on the "[Launch on qBraid Lab](https://account.qbraid.com/?gitHubUrl=https://github.com/OpenQuantumInstitute/oqi-hacks-2025.git)" button 
     - Navigate to the "Environment Manager Extension" in the right sidebar and click on "Add"
     - Search and install the "qBraid-SDK" environment 
     - See qBraid documentation for more details on [installing Environments](https://docs.qbraid.com/lab/user-guide/environments#install-environment).
   - Local: 
     - Use [qBraid VSCode Extension Pack](https://docs.qbraid.com/vscode/user-guide/overview#extension-packs) to monitor jobs, devices or use the pre-built Python environments locally.
     - See [qBraid's VSCode documentation](https://docs.qbraid.com/vscode/user-guide/quantum-console) for more details about activating the qBraid-SDK environment.


##  Technical challenge 
Create a program that applies one or more quantum algorithms to a social good problem of your choice.

Quantum algorithm examples:

- Shor's algorithm
- Grover's search
- Variational Quantum Eigensolver (VQE)
- Quantum Approximate Optimization Algorithm (QAOA)

Social good topic examples:

- Healthcare
- Science (e.g. AI, cryptography, biochemistry)
- Environment (climate)
- Education & Literacy
- Food Securities
- Crisis & Public Safety
- Financial Modeling

Implementation requirements:

- Must utilize quantum hardware available through Amazon Braket via qBraid or through direct access.
- Must utilize a Braket simulator or emulator made available via access code.
- You are also free to use any other technology which allows you to solve the challenge.

## qBraid / Braket Tutorials

Here, we provide useful tutorials on how to use qBraid, along with tutorials on quantum computing, using Amazon Braket -

[qBraid Lab and software demos](https://github.com/qbraid/qbraid-lab-demo)

[Amazon Braket Algorithms Library](https://github.com/amazon-braket/amazon-braket-algorithm-library?tab=readme-ov-file)

[qBraid-SDK Documentation](https://docs.qbraid.com/sdk/user-guide/overview)

[qbraid-runtime with Braket devices](https://github.com/qBraid/qbraid-lab-demo/blob/main/qbraid_sdk/qbraid_runtime_qbraid_provider_aws.ipynb)


## Submission Guidelines 

- Each team must submit a project report, a working Jupyter notebook solution and a presentation slide deck. 
- The resources should be submitted via a Pull Request to the current repository. 
- Your project resources should be organized in the following structure:
  ```
  thailand/
    ├── README.md
    ├── team_name/
    │   ├── project_report.pdf
    │   ├── presentation.pdf
    │   └── working_notebook.ipynb
    │   └── resources/
    │       ├── other_resources_you_want_to_include
  ```


## Access to QPUs

For the purposes of this hackathon, we have shortlisted 2 gate based quantum computers that are available on qBraid via AWS i.e. **IQM Garnet** and **Rigetti Ankaa-3**. For solutions requiring Hamiltonian simulation, we have shortlisted **Quera Aquila**. 

*Teams will have access to QPUs only if they have successfully demonstrated the following*:

a. Ran and passed on emulator or simulator.

b. Passed the syntax checker, if available.

c. The cost is reasonable, we believe this will be a good exercise on understanding how to calculate your costs. View QPU pricing on qBraid - 
- [IQM Garnet](https://www.qbraid.com/pricing)
- [Rigetti Ankaa-3](https://www.qbraid.com/pricing)
- [Quera Aquila](https://www.qbraid.com/pricing)

d. The project is fully fleshed out and compelling. We aim to update on a case by case basis.
