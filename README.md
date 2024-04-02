# Solana Renaissance 2024: Distri.AI

<p align = "center">
  <img src="https://github.com/distri-group/Solana-Renaissance-2024/assets/154581838/74ea98f0-fc14-4db7-96c7-23ed6ee27893" width="50%"/>
  <img src="https://github.com/distri-group/Solana-Renaissance-2024/assets/154581838/2c380579-0b45-4f7f-82c4-b7578ec7997e" width="35%"/>
</p>

<p align = "center">
  <strong>Source Code</strong>:  <a href="https://github.com/distri-group/DistriAI-Core">Distri.AI-Core</a>  ·  <a href="https://github.com/distri-group/DistriAI-Index">Distri.AI-Index</a>  ·  <a href="https://github.com/distri-group/DistriAI-Interface">Distri.AI-Interface</a>  ·  <a href="https://github.com/distri-group/DistriAI-Node">Distri.AI-Node</a>
</p>

# Table of Contents

- [Table of Contents](#Table-of-Contents)
- [Introduction](#Introduction)
  - [What is Distri.AI](#What-is-Distri.AI)
  - [Why Distri.AI](#Why-Distri.AI)
  - [Distri.AI's Solution](#Distri.AIs-Solution)
- [Demo with testing instructions](#Demo-with-testing-instructions)
- [Presentation](#Presentation)

# Introduction

### What is Distri.AI

Distri.AI has built an ML Hub on [Solana](https://solana.com/), guided by the [MaaS](https://www.emagia.com/resources/glossary/model-as-a-service/) principle. Here, model development and deployment become effortless and secure. Moreover, model creators and dataset providers can distribute their work for free or monetize it.

Ultimately, it establishes a middleware ecosystem that bridges the infrastructure and application layers, aiming to democratize AI development.

![image](https://github.com/distri-group/Solana-Renaissance-2024/assets/154581838/c40405ee-f5bf-4595-a12b-9b562a766c5c)


### Why Distri.AI

An increasing number of GPUs are joining various decentralized networks to contribute computing power. However, concerns about potential data leaks related to model data when using such computing resources are a significant deterrent to the widespread adoption of decentralized computing power.

Distri.AI has addressed these concerns by creating a secure and resilient computing space on these GPU devices, offering an isolated environment that alleviates users' worries. Furthermore, leveraging this kind of space, Distri.AI empowers dataset transactions and the sale of inference API services in a trustless way.

### Distri.AI's Solution

![image](https://github.com/distri-group/Solana-Renaissance-2024/assets/154581838/0939533b-a99d-4edd-a828-145c24db8081)

Distri.AI can be segmented into two components:
- **Distri.AI Hub**: An eco-community tailored for machine learning developers, providing model development services and fostering collaboration and technical discourse among developers.
- **Distri.AI BSI**: An all-in-one MLOps development framework, primarily utilized in two ways:
  - **BSI Dev Environment**: Facilitates the creation of isolated secure computing spaces on untrusted compute nodes, providing an ideal secure environment for flexible model development and deployment.
  - **BSI Executor**: Similar to the Dev Environment, it allows the establishment of isolated secure computing spaces on untrusted compute nodes. However, distinctively, this space operates independently of user control, accepting inputs and autonomously completing computations based on provided data and parameters. Throughout the computation process, all data remains under secure protection.

Next, let’s walk through a use case to further demonstrate what Distri.AI can accomplish.

A language model developer starts by selecting an appropriate pre-trained model from the model categories on the Distri.AI Hub. Then, the developer chooses suitable GPU hardware for development, which can be sourced from any provider. Upon acquiring the hardware, the developer installs Distri.AI BSI and creates a BSI Dev Environment to secure a privacy-protected computing space before proceeding with model development.

Additionally, the developer can select datasets from the dataset categories on the Distri.AI Hub for model fine-tuning. To safeguard the interests of dataset owners, upon purchasing a dataset, the developer sets up a BSI Executor. This privacy-preserving automatic executor computes and outputs results based on inputs from both the dataset owner and the developer, without allowing the developer access to the raw data of the dataset throughout the process.

Finally, after achieving an ideal model, the developer can deploy it within a BSI Executor and sell its inference API services on the Distri.AI Hub. Deploying the model in a BSI Executor offers two clear benefits: 1) As the model owner, the developer can minimize the risk of model leakage to the greatest extent possible. 2) Applications using the inference API can trust that the output comes directly from the specified model, and not any other.

## Demo with testing instructions

Live on Solana Devnet at https://distri.ai/models

<a href="https://www.youtube.com/watch?v=B1xoOCia8xQ">
    <img src="https://github.com/distri-group/Solana-Renaissance-2024/assets/154581838/4ffb9976-fc2a-48f3-ad78-95143be2a6a0" alt="Video Title" width="50%" />
</a>

Clik for the Distri.AI's demo 👆👆👆

## Presentation

<a href="https://www.loom.com/embed/655a289100654e8380197ccd1cb63176">
    <img src="https://github.com/distri-group/Solana-Renaissance-2024/assets/154581838/d04b515a-3c8c-4a46-a3e4-4a7c95cd559b" alt="Video Title" width="50%" />
</a>

Clik to watch the presentation video 👆👆👆
