# CMPT 419 Project Report (Draft)
Author: Danny Liu  
# Table of Contents
1. [Abstract](#abstract)
2. [Visual Abstract](#visual-abstract)
3. [Introduction](#introduction)
4. [Related Work](#related-work)
5. [Methods](#methods)
6. [Results](#results)
7. [Discussion](#discussion)
8. [Artifacts](#artifacts)

## Abstract

Highly capable open-source LLMs are increasingly becoming available [1].  
[1] https://dl.acm.org/doi/pdf/10.1145/3584931.3608438

[OpenWebUI](https://github.com/open-webui/open-webui) is a great open-source user interface for Large Language Models (LLMs). It provides a ChatGPT-like UI for running open-source LLMs locally through [Ollama](https://github.com/ollama/ollama), and also integrates seamlessly with OpenAI models with an API key. As a daily user myself, my main motivation to contribute to this project is to help improve the best open-source user interface for LLMs, which align with the human-centric AI focus of CMPT419.

## Visual Abstract
- feat: OLED dark theme (https://github.com/open-webui/open-webui/pull/1325)
![image](https://github.com/dannyl1u/cmpt419_spring2024/assets/45186464/d9094d35-7161-434b-ba39-549724d3714a)
  
- feat: system os light/dark mode option (https://github.com/open-webui/open-webui/pull/1115)  
![image](https://github.com/dannyl1u/cmpt419_spring2024/assets/45186464/73bf84b0-513e-4a0b-bc93-d5666b3707c8) 

- feat: delete message (https://github.com/open-webui/open-webui/pull/789, https://github.com/open-webui/open-webui/pull/1004)  
![image](https://github.com/dannyl1u/cmpt419_spring2024/assets/45186464/a4a257ee-5bc1-4bba-8155-fa383c23b976)  

- feat: show prompt token/s in perf info (https://github.com/open-webui/open-webui/pull/784)  
![image](https://github.com/dannyl1u/cmpt419_spring2024/assets/45186464/84eb56e1-c45f-44cc-b47d-929a4166e6ed)  


## Introduction

ChatGPT is used and loved by many but is closed-source, proprietary software owned by OpenAI. Open WebUI provides a user interface for using local open-source LLMs with a look and feel that is similar to the ChatGPT that we are familiar with.

## Related work
Existing user interfaces for Ollama:  
- https://github.com/ollama/ollama?tab=readme-ov-file#community-integrations

Reference links:  
- https://github.com/ollama/ollama
- https://github.com/ggerganov/llama.cpp


## Methods

// TODO

## Results

// TODO

## Discussion

My contributions in the OpenWebUI project focuses on the human-centric aspect of AI. I am interested in exploring how interfaces for AI/ML can be improved to better support humans in everyday use (i.e. HCI in AI/ML tools). As OpenWebUI is an open-source project that has become quite popular recently (10k+ stars), it has been interesting to see what kind of features/changes are being requested and/or implemented by the community. I think that OpenWebUI is quite innovative in the LLM chatbot UI space as it has many features that improve the user experience of interacting with a LLM that popular closed-source chatbots do not have. For example, OpenWebUI now has a feature that allows the user to delete a message/response pair, which I find quite useful. Overall, the HCI aspects of LLM chatbots really interest me and working on OpenWebUI has given me the opportunity to explore how applications can improve the user experience and make interactions with advanced AI systems more natural, efficient, and enjoyable.

## Artifacts
https://github.com/open-webui/open-webui/pulls?q=is%3Apr+author%3Adannyl1u+is%3Aclosed  
// TODO: add video recordings/screenshots of implemented features
