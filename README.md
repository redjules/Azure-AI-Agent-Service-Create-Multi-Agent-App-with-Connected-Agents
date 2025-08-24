# Description

I will create a ulti-agetn app with connected agents using Azure AI Agent Service

# Steps

Go to AI Foundry and create a new resource:

![Alt text](assets/1.png)

Rest as default

Open resource and go to Azure AI Foundry portal

![Alt text](assets/2.png)

Deploy base model. We’ll choose gpt-4.0

![Alt text](assets/3.png)

We upload a file about AI instructions.

Give instructions to the RAG agent:

![Alt text](assets/5.png)

Now we’ll build the quiz generator agent:

![Alt text](assets/6.png)

Now the orchestrator agent:

![Alt text](assets/orc.png)

Click Connected agents

![Alt text](assets/7.png)

Same for the Quiz Generator:

We have 2 agents connected to the orchestrator

Go to playground and select the Orchestrator agent:

![Alt text](assets/playground.png)

# Results

And we ask a question:

![Alt text](assets/q1.png)

And we ask another question:

![Alt text](assets/q2.png)

And the results are pretty good!
