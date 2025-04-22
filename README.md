# Project

Azure AI Foundry customization sample datasets

## What are these datasets?

This repository contains a collection of sample datasets that can be used to test and validate various customization techniques on the [Azure AI Foundry](http://ai.azure.com/). These are curated datasets created from various public HuggingFace datasets. These datasets have been created by picking top few items from the HuggingFace samples for various kinds of data: chat, multimodal, etc.

## Purpose of these datasets

- These datasets are meant to be used as a **reference** to understand how to prepare training/validation data to run finetuning and other customization jobs on the [Azure AI Foundry](http://ai.azure.com/). Do not consider these samples as complete datasets for production use.
- These datasets can be used for experimental runs, and to check the end-to-end flows while running customization jobs on the [Azure AI Foundry](http://ai.azure.com/). Note, that any training jobs can incur costs on the subscription.
- The datasets work best for OpenAI models, and may require adjustments for other model families like Llama, Mistral etc.
