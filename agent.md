# LLM autonomous agent
有人说agent需要包含3个组件
1. Planning
2. memory
3. tool use

![a image](https://ibb.co/XDCvhRk)  
chatGPT目前在这三个方面的能力是  
|能力| 得分 |
|--|--|
|planning| 2 |
|memory| 4 |
|tool call| 4 |
## planning
规划子任务和推理  
~~Reflection~~ and refinement(完善)  
反思应该比较难，通过retry去完善一个子任务是可能可以达成的。  
reflection mechanism:synthesizes memories into higher level inferences over time and guides the agent's future behavior  

## memory
短期记忆in-context(chat session)  
长期记忆需要保存 支持检索相当于个人的学习经验。

## tool use

工具的使用可以产生质变
like chain,multiple agents,plugin,function calling,**HuggingGPT**(多路模型 有人说这个就是开源的chatgpt)  
HuggingGPT comprises of 4 stages:  
1. task planning
2. model selection
3. task execution
4. response generation


reference:  
[llm agent](https://lilianweng.github.io/posts/2023-06-23-agent/)
