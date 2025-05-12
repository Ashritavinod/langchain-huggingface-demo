# langchain-huggingface-demo

# LangChain with Hugging Face Demo

This repository contains a Google Colab notebook that demonstrates how to use [LangChain](https://www.langchain.com/) with models from [Hugging Face](https://huggingface.co/) to build LLM-powered applications.

 Environment Setup

The notebook installs and configures the following libraries:
- `langchain`
- `langchain_community`
- `huggingface_hub`
- `transformers`
- `accelerate`
- `bitsandbytes`

Hugging Face API tokens are used to authenticate with Hugging Face Hub.

 Features Demonstrated

1. **Basic LLM Interaction**
- Loaded the `google/flan-t5-large` model using `HuggingFaceHub`.
- Ran a translation prompt and a cuisine-based restaurant name generation.

2. **Prompt Engineering with Templates**
- Created reusable `PromptTemplate`s for:
  - Generating restaurant names
  - Suggesting menu items based on cuisine and restaurant name

3. **Chaining LLMs**
- Built chains using `LLMChain` and `SimpleSequentialChain` to:
  - Generate company names based on product types
  - Generate restaurant names and then corresponding menu items

4. **LangChain + Hugging Face Tasks**
- Suggested company names for a given product.
- Retrieved details about a famous football player using their name.

Summary

This notebook showcases key LangChain features:
- LLM initialization
- Prompt engineering
- Chain creation
- Hugging Face integration

It serves as a practical introduction to building LLM-powered applications using LangChain.

Files
- `LangChain_HuggingFace_Demo.ipynb`: The main Colab notebook
- `summary.md`: A written summary of all actions and features demonstrated in the notebook

How to Use
1. Clone the repo or open the notebook in Colab.
2. Replace the Hugging Face token with your own to run the cells.
3. Explore, modify, and build your own chains!



📜 License
This project is open-source and available under the [MIT License](LICENSE).
