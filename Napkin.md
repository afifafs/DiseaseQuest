Group 9

1. A web application that uses multiple AI agents to help faculty create and manage educational content.

**Faculty/User → Web App → Backend → AI Agents → Database**

2. We are working with code that we have never touched. Also, there are over 150 branches that exist.  
3. The existing codebase may become the first bottleneck because six developers need to understand and modify interconnected AI-agent behavior without creating conflicting changes  
4. Backend: OpenAI, Chatbots: [Node.js](http://Node.js). Because that’s what the Disease Quest v1 team used last year and we don't want to mess with functionality.  
5. If multiple AI agents can access the same notes when only the Coach Agent should, an agent could generate responses using information it was never intended to receive, making the agent workflow unreliable.  
6. Yes, provided we prioritize fixing the existing functionality before adding new features. If the scope becomes too large, we would cut lower-priority AI enhancements before cutting the core faculty creation and agent-separation requirements.

**AI-Prompt Section: “Diff”**  
1\. The AI identified potential database problems and related kill risks that our group did not initially consider. We focused more on the existing codebase and AI-agent behavior.  
2\. The AI considered different ways we could structure our technology stack. Our group focused on keeping the existing DiseaseQuest v1 stack to avoid disrupting existing functionality.