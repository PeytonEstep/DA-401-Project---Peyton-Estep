# DA-401-Project---Peyton-Estep

## Overview
Large-Language Models (LLMs) are increasingly used for mental health advice, raising concerns about their ability to safely respond to vulnerable users. Prior research shows that generative AI can produce overly agreeable (sycophantic) responses and may replicate stigma toward mental health conditions.

This project investigates whether ChatGPT exhibits differential patterns of harmful agreement depending on the user's mental health diagnosis and prompt context.

## Research Question
Do AI systems exhibit higher rates of harmful agreement for certain mental health disorders, particularly stigmatized or complex diagnoses?

## Methods
Dataset: 3,000 AI-generated responses

Design:
- 	30 prompts
- 	6 disorders: Depression, Anxiety, ADHD, BPD, Schizophrenia, AUD
- 	5 topic areas: Stopping Medication, Ghosting Professional, Social Withdrawal, Cognitive Distortion, Safety Concern
- 	100 trials per prompt

Scoring System:
- 	1 = Safe
- 	2 = Ambiguous
- 	3 = Harmful Agreement

Analysis Techniques:
- 	Logistic regression (for classification)
- 	Ordinal logistic regression (inference)
- 	Marginal effects analysis
- 	Linguistic and sentiment analysis

## Key Findings
- AI responses vary significantly by disorder
- Depression -> highest likelihood of harmful agreement
- BPD and Schizophrenia -> more safety-oriented responses
- Prompt framing (topic) also significantly influenced outcomes
- Results suggest AI applies uneven safety guardrails

## Why This Matters
As AI tools are increasingly used for mental health support, inconsistent safety behavior poses real risks. These findings highlight the need for more uniform and clinically-based safety mechanisms in generative AI systems.

## Repository Contents
- 401 Project.html -> jupyter notebook
- First Draft -> first draft of research paper
	
References: 
   Lauderdale, S., Griffin, S., Lahman, K., Eno Mbaba, & Tomlinson, S. (2025). Unveiling Public Stigma for Borderline Personality Disorder: A Comparative Study of Artificial Intelligence and Mental Health Care Providers. Personality and Mental Health, 19(2). https://doi.org/10.1002/pmh.70018 
   McBain, R. K., Bozick, R., Diliberti, M., Zhang, L. A., Zhang, F., Burnett, A., Kofner, A., Rader, B., Breslau, J., Stein, B. D., Mehrotra, A., Pines, L. U., Cantor, J., & Yu, H. (2025). Use of Generative AI for Mental Health Advice Among US Adolescents and Young Adults. JAMA Network Open, 8(11), e2542281. https://doi.org/10.1001/jamanetworkopen.2025.42281
  Mello-Klein, C. (2026, February 23). How can you avoid AI sycophancy? Keep it professional, researchers say. Northeastern Global News. https://news.northeastern.edu/2026/02/23/llm-sycophancy-ai-chatbots/ 
  Moore, J., Grabb, D., Agnew, W., Klyman, K., Chancellor, S., Ong, D. C., & Haber, N. (2025). Expressing stigma and inappropriate responses prevents LLMs from safely replacing mental health providers. ArXiv.org. https://doi.org/10.1145/3715275.3732039 
  Payne, K. (2024, October 26). AI Chatbot Pushed Teen to Kill himself, Lawsuit Alleges. AP News; The Associated Press. https://apnews.com/article/chatbot-ai-lawsuit-suicide-teen-artificial-intelligence-9d48adc572100822fdbc3c90d1456bd0

