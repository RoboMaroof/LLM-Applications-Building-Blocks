# LLM Applications Building Blocks

This repository contains sample code and explanations for various building blocks essential to constructing and fine-tuning Large Language Models (LLMs). It serves as a practical guide, focusing on hands-on examples and detailed notebook explanations for each component involved in building LLM-based applications. This project is a work in progress, with more features and notebooks to be added over time.

## Directory Structure

The current structure of the repository is organized as follows:

```plaintext
LLM-APPLICATIONS-BUILDING-BLOCKS/
│
├── 00_LLM_Concepts/
│ ├── 01_Transformer_basics.ipynb
│ └── 02_LLM_Architecture.ipynb
│ └── 03_LLM_from_scratch.ipynb (WIP)
│ └── 04_Types_of_Attention_in_detail.ipynb (WIP)
│ └── 05_Types_of_Activation_in_detail.ipynb (WIP)
│ └── 06_Memory_Management.ipynb (WIP)
│
├── 01_Data_Prep/
│ └── (Notebooks and scripts for preparing datasets)
│
├── 02_Model_Loading/
│ └── (Notebooks and scripts for loading pre-trained models)
│
├── 03_Quantization/
│ ├── 01_PostTrainingQuantization_Basics.ipynb
│ └── 02_GPTQ.ipynb
│ └── 03_AWQ.ipynb
│ └── 04_Quip.ipynb (WIP)
│ └── 05_GGUF.ipynb (WIP)
│ └── 06_HQQ.ipynb (WIP)
│ └── 07_AQLM.ipynb (TS)
│ └── 08_BitMat.ipynb (TS)
│
├── 04_Pruning/
│ └── (Notebooks and scripts for loading pre-trained models)
│
├── 04_Finetuning/
│ ├── 01_Prompt_Engineering.ipynb
│ └── 02_peft_QLoRA.ipynb
│ └── 03_Knowledge_Distillation.ipynb (WIP)
│
├── 05_Agents/
│ ├── 01_Structured_output.ipynb (TS)
│ └── 02_Function_Calling.ipynb (TS)
│ └── 03_Multi_Agent.ipynb (TS)
│
├── LICENSE
└── README.md
```

### Detailed Overview

1. **00_LLM_Concepts:**
   - **01_Transformer_basics.ipynb**: Introduction to the core concepts behind Transformer models, which are the foundation of most modern LLMs.
   - **02_LLM_Architecture.ipynb**: A deep dive into LLM architectures, covering key components.

2. **01_Data_Prep:**
   - Notebooks and scripts to help prepare datasets for LLM training and evaluation.

3. **02_Model_Loading:**
   - Loading pre-trained models from popular frameworks such as Hugging Face Transformers.

4. **03_Quantization:**
   - **01_PostTrainingQuantization_Basics.ipynb**: Basics of post-training quantization, a technique to optimize LLMs for deployment by reducing model size and inference time.
   - **02_GPTQ.ipynb**: GPTQ, a more advanced quantization technique tailored for transformer models.

5. **04_Finetuning:**
   - **peft_QLoRA.ipynb**: A guide to Parameter Efficient Fine-Tuning (PEFT) using QLoRA, a popular method for fine-tuning LLMs with reduced computational requirements.

6. **05_Agents:**
   - Notebooks and scripts related to building and managing LLM-based agents that can interact with users and perform tasks.

## Contributing

This project is a work in progress, and contributions are welcome. If you have suggestions for additional topics or improvements, feel free to open an issue or submit a pull request.
