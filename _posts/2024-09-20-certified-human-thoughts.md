---
layout: post
title: "💯 certified human thoughts"
date: 2024-09-20 12:00:00 -0000
categories: thoughts
---
These thoughts have been long overdue.

What are human thoughts and with the ubiquity of a certain chat bot, why have we all become obsessed with authenticity?

There is no place where this is more obvious than in education. A field I got quite familiar with.

I spent some time working on plagiarism detection. This was just after transformer based LLM's were discovered but prior to the public release of GPT3. Being where we were, we all saw the writing on the wall. I distinctly remember a coworker sharing with me the BERT paper, that was cool! Another shared the [Language Models are Unsupervised Multitask Learners](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf). I read the damn abstract twice, and distinctly remember wondering if it was some kind of joke or If I was misunderstanding the paper.

There were projects kicked off to see if stylometric detection was possible (spoiler: it was and is). However the project never saw the light of day and for good reason, its detection logic could not be easily verified by the user, in our case a teacher. This is important, charges of plagiarism carry severe consequences. Verification is not only important but critical to the actual reliability of the product, our product's accuracy was high but not 100%. Plagiarism can be easily verified by a human but [stylometric-based algorithms](https://en.wikipedia.org/wiki/Stylometry) typically cannot. In addition, no algorithm is 100% accurate, forget about even talking about recall.

Since then, there is no doubt that ChatGPT has touched nearly all take-home writing assignments to some degree.

Educators facing existential crises to their teaching plan screamed in horror and startups swooped in rescuing from being disrupted. I find this a bit funny and ironic.

I question as to why even try to detect such impossibilities? If we are to assess students on their writing, let's do it in a controlled environment, otherwise who are we to say that the student came up with those words themselves? Perhaps they heard them in a dream. How naive of me?

For one, I side with OpenAI with them not releasing their latest-gen llm-detecting trained model, though they did cave in and release [a previous gen, bert-based model, trained to detect GPT2](https://huggingface.co/openai-community/roberta-base-openai-detector).

Llama-3.1-8B-Instruct Perplexity: 25.22
