# llm-papers
  Best LLM papers

# Format 
  - [ Month/Year ] [ **Title **] [ PDF ] [ GIT ] [ Takeaway ] 

# Papers
 - [ 05/2024 ] [ **A Careful Examination of Large Language Model Performance on Grade School Arithmetic**] [ [ PDF ](https://arxiv.org/pdf/2405.00332) ] [ GIT ] [ In this study, the authors introduce GSM1k, a dataset designed to assess overfitting in large language models (LLMs) on the GSM8k benchmark. Benchmarking reveals significant data contamination, with some models showing up to a 13% performance drop. The Mistral and Phi model families consistently overfit across various sizes and versions. Analysis indicates a positive correlation between generating GSM8k data points and performance gaps, suggesting data contamination as a key factor. However, many advanced models, especially frontier ones like Gemini, GPT, and Claude, exhibit minimal overfitting and robust generalizable mathematical reasoning. ] 
  
  - [ 02/2024 ] [ **More Agents Is All You Need**] [ [ PDF ](https://arxiv.org/pdf/2402.05120v1) ] [ [ GIT ](https://anonymous.4open.science/r/more_agent_is_all_you_need/README.md) ] [ In this study, increasing instantiated LLM agents improves performance on complex tasks using a straightforward sampling-and-voting method. Performance gains vary with task difficulty, specifically inherent difficulty (I), reasoning step lengths (S), and prior probability (K). ] 

 - [ 08/2023 ] [ **AgentVerse: Facilitating Multi-Agent Collaboration and Exploring Emergent Behaviors** ] [ [ PDF ](https://arxiv.org/pdf/2308.10848) ] [ [ GIT ](https://github.com/OpenBMB/AgentVerse/) ] [ This study introduces AGENTVERSE, a multi-agent framework that enhances task performance through collaboration among autonomous agents using LLMs. The framework consists of four pivotal stages: (1) Expert Recruitment: Adjusting the agent group composition based on task progression. (2) Collaborative Decision-Making: Engaging agents in joint strategy discussions. (3) Action Execution: Implementing actions through environmental interaction. (4) Evaluation: Assessing outcomes and providing feedback for further refinement. AGENTVERSE outperforms single agents in tasks such as text understanding, reasoning, coding, tool utilization, and embodied AI, with emergent collaborative behaviors enhancing group efficiency. ]

 - [ 06/2023 ] [ **LLM Powered Autonomous Agents** ] [ [ github.io ](https://lilianweng.github.io/posts/2023-06-23-agent/) ] [ Great resource for Agents by Lilian Weng at OAI] 

  - [ 05/2023 ] [ **Improving Factuality and Reasoning in Language Models through Multiagent Debate** ] [ [ PDF ](https://arxiv.org/pdf/2305.14325) ] [ [ GIT ](https://composable-models.github.io/llm_debate/) ] [ This study found that increasing the number of agents and debate rounds improves accuracy, though these factors were limited by cost constraints. Extrapolation suggests that while more agents and rounds provide marginal improvements, these gains diminish over time. Additionally, longer debate prompts yield better performance as the number of rounds increases. Summarization can also serve as a tool to extend the context, further enhancing the models' capabilities. ] 
 
  - [ 03/2023 ] [ **Tree of Thoughts: Deliberate Problem Solving with Large Language Models** ] [ [ PDF ](https://arxiv.org/pdf/2305.10601) ] [ [ GIT ](https://github.com/princeton-nlp/tree-of-thought-llm) ] [ The Tree of Thoughts (ToT) framework enhances language models by integrating classical human-like problem-solving methods, resulting in higher-quality answers at the cost of increased computational power. ] 

  - [ 06/2017 ] [ **Attention Is All You Need** ] [ [ PDF ](https://arxiv.org/pdf/1706.03762) ] [ [ GIT ](https://github.com/tensorflow/tensor2tensor) ] [ Authors introduce, Transformer model as the first sequence transduction system entirely reliant on attention mechanisms, eliminating the need for recurrent layers commonly found in encoder-decoder structures. ] 
