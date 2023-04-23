# colab-ipynb
存一些有用的 ipynb

* LangChain教程：https://github.com/gkamradt/langchain-tutorials


```
如果把llm当成是一种编程语言，比如说是java，那langchain我理解就是这个llm里的spring框架

```

```
针对一个LLM模型来说，最基础的逻辑是对这个模型进行API调用，Text In，Text Out，即输入文本，然后基于LLM的能力再输出回文本。但是如果需要充分使用LLM的能力，那么就必须解决几个关键问题：

- 状态感知：即能够知道在当前这次调用中，前面几次调用的上下文状态
- 数据感知：能够喂入更多数据，对当前调用的上下文有更充分的理解，引导LLM针对问题给出正确答案
- 组装能力：即能够对LLM模型的调用形成面向特定任务的自动化运行能力

```