# ACP: Agent Communication Protocol

Instructors: Sandi Besen, Nicholas Renotte

IBM Research's BeeAI 

## What you'll learn

* Build ACP-compliant agents by wrapping them in an ACP server, launch the server to activate the agents, and make them discoverable by ACP clients to enable easy integration within multi-agent systems.

* Chain ACP-compliant agents in linear and hierarchical workflows; use a router agent to delegate tasks to the specialized agents.

* Import ACP-compliant agents into a registry to make them easy to discover and share across teams.

## About this course

Introducing __ACP: Agent Communication Protocol__, a short course built in partnership with IBM Research’s BeeAI and taught by Sandi Besen, AI Research Engineer & Ecosystem Lead at IBM, and Nicholas Renotte, Head of AI Developer Advocacy at IBM.

Building a multi-agent system with agents shared across teams and organizations can be challenging. You may need to write custom integrations each time a team updates their agent design or changes the agent’s framework. The Agent Communication Protocol (ACP) is an open protocol that addresses this challenge by standardizing communication between agents. It provides a unified interface through which agents can collaborate regardless of their frameworks, making it easy to replace an agent with a new version without needing to refactor the entire system.

In this course, you’ll learn to connect agents through ACP. The protocol is based on a client-server architecture: you host an agent built with any framework inside an ACP server, and send requests to the server through an ACP client. You’ll learn how to wrap an agent inside an ACP server and set up an ACP client to connect to the server. You’ll build sequential and hierarchical workflows of agents hosted inside ACP servers, and learn how to manage this workflow on the client side through a process or another agent. 

In detail, you’ll:

* Learn the underlying architecture of ACP and how it enables agents built with different frameworks to work together through a common interface.
* Understand the lifecycle of an ACP Agent (configuration, activation, discovery, execution), and how it compares to other protocols, such as MCP (Model Context Protocol) and A2A (Agent-to-Agent).
* Build a RAG agent with CrewAI and wrap it inside an ACP server.
* Define an ACP Client to make calls to the ACP server you created.
* Define another ACP server, built with Smolagents, and sequentially chain it to the RAG agent.
* Build a hierarchical workflow using a router agent that transforms a user’s query into tasks and delegates the tasks to agents available through ACP servers.
* Build an agent that uses MCP to access tools and ACP to communicate with other agents.
* Import your ACP agents to the BeeAI platform, an open-source registry to discover and share agents easily. 

By the end of the course, you’ll know how to create ACP-compliant agents that can communicate regardless of their frameworks and collaborate to address queries.

## Who should join?

This course is perfect for AI builders who want to easily reuse and connect multiple agents built with different frameworks in a single system, or for anyone curious to learn about the Agent Communication Protocol. Some experience with Python is recommended.

## Course Outline

12 Lessons・8 Code Examples
* Introduction - Video・4 mins
* Why Agent Communication protocol - Video・5 mins
* ACP Core Principles - Video・8 mins
* Building a RAG Agent with CrewAI - Video with code examples・13 mins
* Wrapping the RAG Agent into an ACP Server - Video with code examples・8 mins
* Calling an ACP Agent using the Client - Video with code examples・5 mins
* Wrapping a Smolagents Agent into an ACP Server - Video with code examples・8 mins
* Sequentially Chaining the Agent Calls - Video with code examples・7 mins
* Hierarchically Chaining the Agent Calls using a Router Agent - Video with code examples・12 mins
* Adding MCP to the Hospital Server - Video with code examples・17 mins
* Managing ACP Compliant Agents - Video・9 mins
* Conclusion - Video・1 mins
* Quiz - Reading・1 min
* Appendix – Resources, Tips, and Download - Code examples・1 min

## Instructors

<table>
<tr>
    <td><b>Sandi Besen</b></td>
    <td>AI Research Engineer and Ecosystem Lead at <a href="https://research.ibm.com/">IBM Research</a></td>
     <td><a href="https://www.linkedin.com/in/sandibesen/">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Description of Image">
</a></td>
</tr>
<tr>
    <td><b>Nicholas Renotte</b></td>
    <td>AI Research Engineer and Ecosystem Lead at <a href="https://www.ibm.com/us-en">IBM</a></td>
     <td><a href="https://www.linkedin.com/in/nicholasrenotte/">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Description of Image">
</a></td>
</tr>
</table>

https://www.deeplearning.ai/short-courses/acp-agent-communication-protocol/