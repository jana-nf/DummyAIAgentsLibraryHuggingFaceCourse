# DummyAIAgentsLibraryHuggingFaceCourse


Dummy Agent Library
In this simple example, we're going to code an Agent from scratch.

This notebook is part of the Hugging Face Agents Course, 
a free Course from beginner to expert, where you learn to build Agents.


Agent Course

<img src="https://huggingface.co/datasets/agents-course/course-images/resolve/main/en/communication/share.png" alt="AlfredHuggingFace">


Serverless API

In the Hugging Face ecosystem, there is a convenient feature called Serverless API that allows you to easily run inference on many models. 
There's no installation or deployment required.


To run this notebook, you need a Hugging Face token that you can get from https://hf.co/settings/tokens. 
If you are running this notebook on Google Colab, you can set it up in the "settings" tab under "secrets".
Make sure to call it "HF_TOKEN".

You also need to request access to the Meta Llama models, if you haven't done it before. 
Approval usually takes up to an hour.



Dummy Agent

In the previous sections, we saw that the core of an agent library is to append information in the system prompt.

This system prompt is a bit more complex than the one we saw earlier, but it already contains:

Information about the tools
Cycle instructions (Thought → Action → Observation)

