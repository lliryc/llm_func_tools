# Adaptation SOTA LLMs for Function Calling

## Overview

Function calling in the context of GPT refers to the model's capability to interact with external functions or APIs during a conversation to dynamically retrieve, process, or generate information. When a specific task or query is beyond the model's inherent language understanding and response generation capabilities, it can call functions designed to perform specialized operations. This can include:

- Accessing real-time data
- Performing complex calculations
- Generating images
- Retrieving information from external databases

Function calling enhances the model's utility by extending its functionality, allowing it to provide more accurate, relevant, and contextually appropriate responses. This creates a more robust and versatile AI assistant.

## Limitations of Open-Source Models

The lack of function calling in open-source models limits their capabilities and flexibility. Unlike advanced models that can interact with external APIs to fetch real-time data, perform complex tasks, or integrate with other systems, open-source models are restricted to their built-in features. This limitation means they can't handle queries that require external information or advanced processing as efficiently. As a result, users may find these models less useful and accurate for more complex or dynamic tasks, reducing their potential in creating smart and responsive AI solutions.

## This Repository

In this repository, you will find a guide on how to add the function calling feature to one of the most efficient models used on edge devices - Phi3 Mini. Please check the Jupyter notebook in the repository to learn how to properly modify a pre-trained model.

### Contents

- `FunCall_Phi3_Unsloth_FineTuning.ipynb`: Contains Jupyter notebook with step-by-step instructions for modifying the Phi3 Mini model to support function calling.
- `README.md`: Overview and instructions for using the repository.

### Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/lliryc/llm_func_tools.git
   cd llm_func_tools.git
   ```
2. **Run the Jupyter notebook:**
Open the FunCall_Phi3_Unsloth_FineTuning.ipynb Jupyter notebook in the folder to begin the fine tuning or do inference based on the Phi3 Mini model.

## License
This project is licensed under the Apache V2.0 License. See the LICENSE file for details.