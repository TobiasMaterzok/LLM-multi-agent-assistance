# Multi-Agent Assistance Tool 🤖💬🤖💬🤖💬🤖

A Python-based framework simulating multi-agent conversations to deliver strategic insights using OpenAI's GPT-4-Turbo. Ideal for consultants and strategists seeking actionable advice from specialized virtual experts.

**Why Use Multi-Agent Assistance Tool?**  
🔍 **Strategic Insights:** Gain comprehensive advice from a team of specialized virtual experts tailored precisely to your needs.  
🧠 **Smart Conversations:** Engage in multi-round, optimized conversations, ensuring detailed exploration of complex topics.  
🎯 **Tailored Recommendations:** Receive actionable summaries that highlight key themes and strategies for decision-making.  

## Overview 📋
| Feature                    | Description                                                                                                  |
|----------------------------|--------------------------------------------------------------------------------------------------------------|
| **Simulated Conversations**| Orchestrates conversations between virtual assistants and specialized experts, building on past interactions.|
| **Multiple Experts**       | Engages multiple virtual experts in the discussion, each with unique specializations tailored to current needs.|
| **Dynamic Expert Generation**| Automatically creates new experts and prompts based on your initial question and conversation context.    |
| **Comprehensive Summary**  | Provides a clear summary of the conversation, highlighting key themes and actionable recommendations.       |
| **Optimized Prompts**      | Prompts have been meticulously engineered (10000+ characters across 8 prompts) to ensure relevance and clarity.|

## Key Features 🌟
1. **Simulated Multi-Agent Conversations:**
   - Orchestrates conversations between virtual assistants and specialized experts, building on past interactions for more relevant advice.
   - Ensures comprehensive exploration of strategic topics through highly optimized multi-round interactions.

2. **Multiple Experts:**
   - Engages multiple virtual experts in the discussion, each with unique specializations tailored to current needs.

3. **Pre-Configured Company Characters:**
   - Incorporates virtual experts with specific knowledge of the company’s history and internal data, enhancing strategic discussions with contextual accuracy and relevance.

4. **Dynamic Expert Generation:**
   - Automatically creates new experts and prompts based on your initial question and conversation context.

5. **Comprehensive Summary:**
   - Provides a clear summary of the conversation, highlighting key themes and actionable recommendations.

6. **Optimized and Maintainable Prompts:**
   - Prompts have been meticulously engineered (10,000+ characters across 8 prompts) to ensure relevance while maintaining clarity and specificity.
   - Metrics like lexical diversity (>0.4) and token count (average 400 tokens per prompt) were reviewed for delivering effective instructions.

## How It Works 🛠️
1. **Interactive Terminal:**
   - Start by sharing your role and a strategic question through an interactive terminal.
  
2. **Generate Virtual Experts:**
   - The tool dynamically generates experts relevant to your question.
  
3. **Multi-Round Interaction:**
   - Experts discuss your question over several rounds, refining their advice.
  
4. **Executive Summary:**
   - A concise summary synthesizes key themes and actionable recommendations.

## Example Usage 💼
**Role:** Chief Strategy Officer (CSO)  
**Question:**  
*"What strategic steps should we consider to expand into new markets while maintaining our current customer base?"*

**How the Tool Helps:**
1. **Generate Virtual Experts:**
   - The tool creates a panel of virtual experts, such as a Market Expansion Specialist, Customer Retention Analyst, or Employee Satisfaction Advisor.

2. **Multi-Round Interaction:**
   - The experts discuss the CSO's question in multiple rounds, providing strategic insights into market expansion strategies, customer retention mechanisms, and competitive positioning.

3. **Comprehensive Summary:**
   - The final summary synthesizes key themes and actionable recommendations:
     - **Market Expansion Strategies:** Identify high-potential markets and tailor products/services accordingly.
     - **Customer Retention Mechanisms:** Strengthen loyalty programs and enhance customer experience.
     - **Competitive Positioning:** Monitor competitors and refine unique selling propositions.

## Usage 🚀
Simply run the `interactive_terminal` function to initiate an interactive session. The tool is designed to help you get tailored advice and improve strategic decision-making without deep technical knowledge.


## Simplified Workflow Overview

```plaintext
+-----------------------------------+
|     User Input (Role & Question) |
+-----------------------------------+
                |
                v
+-----------------------------------+
| Generate Dynamic Prompts         |
| (Generate Virtual Experts)       |
+-----------------------------------+
                |
                v
+-----------------------------------------------------+
| Multi-Agent Interaction                              |
| (Simulate Conversations over N Rounds)               |
|                                                     |
| +-------------------------------+----------------+   |
| | Agent 1                       | Agent 2       |   |
| +-------------------------------+----------------+   |
| | Round 1: Agent 1 Response     | Round 1:      |   |
| |                               | Agent 2       |   |
| | Round 2: Agent 1 Response     | Response      |   |
| |                               | Round 2:      |   |
| | ...                           | Agent 2       |   |
| | Round N: Agent 1 Response     | Response      |   |
| +-------------------------------+----------------+   |
|                                                     |
| +-------------------------------+----------------+   |
| | Agent 3                       | Agent 4       |   |
| +-------------------------------+----------------+   |
| | Round 1: Agent 3 Response     | Round 1:      |   |
| |                               | Agent 4       |   |
| | Round 2: Agent 3 Response     | Response      |   |
| |                               | Round 2:      |   |
| | ...                           | Agent 4       |   |
| | Round N: Agent 3 Response     | Response      |   |
| +-------------------------------+----------------+   |
|                                                     |
+-----------------------------------------------------+
                |
                v
+-----------------------------------+
| Update Conversation Log          |
| (Store Agent Responses)          |
+-----------------------------------+
                |
                v
+-----------------------------------+
| Generate Final Summary           |
| (Concise Executive Summary)      |
+-----------------------------------+

```
