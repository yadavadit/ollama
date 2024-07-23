Here is the README formatted for GitHub, ensuring the markdown will render correctly when copied directly into your repository:

---

# Running Llama3 and Phi3 Models Locally

## Overview

This repository demonstrates the setup, execution, and interaction with two large language models (LLMs) on a local Windows system: **Llama3** and **Phi3**. The setup includes downloading the models and installing them.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
  - [Llama3](#llama3)
  - [Phi3](#phi3)
- [Running the Models](#running-the-models)
  - [Running Llama3](#running-llama3)
  - [Running Phi3](#running-phi3)
- [Comparative Analysis](#comparative-analysis)
- [Repository Contents](#repository-contents)
- [Video Demonstration](#video-demonstration)
- [References](#references)

## Prerequisites

- **Operating System**: Windows 10 or later

## Installation- SetUp

### Llama3 and phi3

1. **Download ollama**

## Running the Models

### Running Llama3

1. **Run the Model**:
    ```sh
    ollama run llama3
    ```
2. **Verify Setup**:  
   Use the following command to interact with Llama3:
    ```sh
    "question":"How are you?"
    ```
   Expected response:
    ```json
    "answer": "I'm just an AI, so I don't have emotions or personal experiences like humans do. However, I am functioning properly and ready to assist with any questions or tasks you may have. How can I help you today?"
    ```

### Running Phi3

1. **Run the Model**:
    ```sh
    ollama run phi3
    ```
2. **Verify Setup**:  
   Use the following command to interact with Phi3:
    ```sh
    "question":"How are you?"
    ```
   Expected response:
    ```json
    "answer": "I'm doing well! As an AI, I don't have feelings, but I'm functioning optimally. How about you? How may I assist you today?."
    ```

## Comparative Analysis

Both models were tested with the same prompt to evaluate their performance:

### Prompt: "Solve: 10+87-90-34+76*100+70%5-33+90"

- **Llama3 Response**:
    ```json
    {"answer": "Therefore, the final result is:7665"}
    ```
- **Phi3 Response**:
    ```json
    {"answer": "The result is 7630"}
    ```

Both models provided the different answers. 

## Repository Contents

- **README.md**: This file, detailing the setup and usage instructions.
- **setup-scripts/**: Contains scripts for downloading, installing, and running the models.

## Video Demonstration

A video demonstrating the setup and interaction process is available on YouTube: (https://youtu.be/UCdpnT1dlxc).

## References

- [Llama3 GitHub Repository](https://github.com/Ollama/llama3)
- [Phi3 GitHub Repository](https://github.com/Ollama/phi3)
- [50 Open-Source Options for Running LLMs Locally](https://medium.com/thedeephub/50-open-sour
