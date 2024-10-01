---
title: "Fine-tuning LLMs for Enhanced Tourism Recommendations in Tibet"
excerpt: "Addressing hallucination issues in LLMs to improve tourism recommendations in Tibet<br/><img src='/images/500x300.png'>"
collection: portfolio
---
![WorkFlow](/images/tibet_finetuing.png){: .align-right width="300px"}
Since May 2024, I have joined Professor Wang Ke's lab at Sichuan University to integrate LLMs with Tibet tourism. One significant challenge we faced was the **hallucination problem**, where LLMs produced irrelevant or inaccurate responses due to a lack of information about unfamiliar attractions.

To solve this, I fine-tuned LLMs to improve their alignment with tourist needs and local attractions. By collecting descriptions of all tourist attractions in Tibet from the web and fine-tuning the model, I improved hotel information extraction accuracy from **0.47 to 0.98**. Comparative experiments using fine-tuning methods like SFT and ORPO resulted in an average score of **80** in accuracy, relevance, and fluency. The fine-tuned models significantly reduced hallucinations compared to baseline models. 

Our work was accepted at the **ICWOC 2024** conference, and we are now exploring **RAG** techniques for further optimization. You can find the paper [here](https://arxiv.org/abs/2407.13561).
