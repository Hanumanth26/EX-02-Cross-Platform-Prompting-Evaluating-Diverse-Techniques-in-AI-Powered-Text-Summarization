# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization


## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarisation.

 ##  1. first prompt 
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.


You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

## Algorithm
🔄 Multi-AI Summarisation Algorithm
Input:
A 500-word technical article

Access to multiple AI platforms (e.g., Chatgpt, Claude, Gemini)

Target audience: undergraduate students

## Step 1: Preprocessing
Read the article and confirm it's technical but understandable.

Clean up any formatting issues (remove LaTeX if needed, fix headers, etc.)

Chunk if necessary (split the article if platforms have word limits).

## Step 2: Apply Multiple Prompting Strategies per AI
For each AI platform, do the following:

a. Direct Summary Prompt
Prompt: "Summarise this technical article in 150 words or fewer for undergraduate students."

b. Explain Like I'm 18 Prompt
Prompt: "Explain this like I’m an 18-year-old college freshman interested in technology."

c. Key Takeaways Prompt
Prompt: "List 5 key takeaways from this article for students new to blockchain."

d. Analogy Prompt
Prompt: "Use a real-world analogy to explain the main idea of this article simply."

## Step 3: Collect and Compare Responses
Save all responses in labeled groups by AI and prompt.

Review each for:

Clarity

Simplicity

Accuracy

Relevance to students

## Step 4: Refine Final Summary
Synthesize the best elements from each summary.

Simplify jargon, explain terms like “hash,” “node,” etc., using plain language.

Structure the final version:

1–2 sentence intro

3–4 sentence body with key ideas

1 sentence real-world analogy

## Step 5: Quality Check
Ensure it’s under 150 words

Use readability tool (optional: Hemingway App, Flesch-Kincaid)

Confirm appeal for undergraduates

![ChatGPT Image May 11, 2025, 07_25_49 PM](https://github.com/user-attachments/assets/0edeb485-54d5-44bd-90a0-78a25d6fa5f6)

### Second AI tool 
   1. General Summary (Using OpenAI's ChatGPT)
Prompt:
*"Provide a concise 100-word summary of 'The Basics of Blockchain Technology' for undergraduate students, covering key concepts like decentralization, blocks, cryptography, and use cases."*

Summary:
Blockchain is a decentralized digital ledger that records transactions across multiple computers securely. Data is stored in "blocks" linked via cryptography, ensuring immutability. Key features include transparency, security (through hashing and consensus mechanisms like Proof of Work), and elimination of intermediaries. Common applications are cryptocurrencies (e.g., Bitcoin), smart contracts, and supply chain tracking. Challenges include scalability and energy consumption. Blockchain’s potential extends beyond finance to healthcare, voting systems, and more, making it a transformative technology.

## 2. Bullet-Point Breakdown (Using Claude AI)
Prompt:
"Convert the article into 5 key bullet points, simplifying technical jargon for undergraduates."

Summary:

Decentralization: No single entity controls the network; data is distributed across nodes.

Blocks & Chains: Transactions are grouped into blocks, cryptographically linked to form a chain.

Security: Uses hashing and consensus algorithms (e.g., PoW) to prevent tampering.

Smart Contracts: Self-executing agreements (e.g., Ethereum) automate processes without intermediaries.

Use Cases: Cryptocurrencies, supply chain transparency, secure voting, and healthcare records.

## 3. Analogical Explanation (Using Google Gemini)
Prompt:
"Explain blockchain using an analogy suitable for beginners, referencing the article’s core ideas."

Summary:
Think of blockchain like a shared Google Doc where everyone can view changes, but no one can edit past entries without consensus. Each "block" is a paragraph, and the "chain" is the version history. Cryptography acts like a tamper-proof seal, ensuring trust without a central authority.

## 4. Comparative Summary (Using Perplexity AI)
Prompt:
"Compare blockchain to traditional databases, highlighting differences in structure, control, and security, as per the article."

Summary:

Feature	Blockchain	Traditional Database
Control	Decentralized	Centralized (e.g., bank, company)
Security	Immutable (cryptography)	Editable (admin privileges)
Transparency	Public ledger (usually)	Private
Speed	Slower (consensus needed)	Faster
## 5. FAQ Style (Using Microsoft Copilot)
Prompt:
"Generate 3 FAQs based on the article, with brief answers."

Summary:
Q1: How does blockchain prevent fraud?
→ A: Cryptographic hashing and consensus mechanisms (e.g., PoW) make altering data nearly impossible.

Q2: Is blockchain only for Bitcoin?
→ A: No! It’s used in supply chains, healthcare, and even voting systems.

Q3: Why is blockchain slow?
→ A: Transactions require validation by multiple nodes, unlike centralized databases.

6. Visual Mind Map (Using Miro AI + Text-to-Diagram)
Prompt:
"Convert the article’s main ideas into a mind map with branches for 'How It Works,' 'Benefits,' and 'Applications.'"

## Text-Based Output:

BLOCKCHAIN BASICS  
├─ How It Works  
│  ├─ Decentralized Nodes  
│  ├─ Blocks & Hashing  
│  └─ Consensus Mechanisms  
├─ Benefits  
│  ├─ Transparency  
│  ├─ Security  
│  └─ No Intermediaries  
└─ Applications  
   ├─ Cryptocurrencies  
   ├─ Smart Contracts  
   └─ Supply Chain  


 **Accuracy**, **Coherence**, **Simplicity**, **Speed**, and **User Experience**.  

| **Platform/Strategy**       | **Accuracy** (Technical Correctness) | **Coherence** (Logical Flow) | **Simplicity** (Beginner-Friendly) | **Speed** (Generation Time) | **User Experience** (Engagement) |  
|----------------------------|-------------------------------------|-----------------------------|-----------------------------------|----------------------------|----------------------------------|  
| **ChatGPT (General Summary)** | High (covers core concepts)         | High (clear structure)      | Moderate (some jargon)            | Fast                       | Good (concise but technical)    |  
| **Claude (Bullet Points)**  | High (precise key points)          | High (linear breakdown)     | **High** (simplified)             | Fast                       | **Excellent** (easy to scan)    |  
| **Gemini (Analogy)**        | Moderate (oversimplifies crypto)   | Moderate (creative but loose)| **High** (intuitive)              | Moderate                   | **Excellent** (memorable)       |  
| **Perplexity (Comparison)** | **High** (detailed contrast)       | High (structured table)     | Moderate (requires context)       | Moderate                   | Good (reference-style)          |  
| **Copilot (FAQs)**          | High (practical Q&A)               | Moderate (disjointed Q&A)   | **High** (digestible)             | Fast                       | Good (interactive)              |  
| **Miro (Mind Map)**         | Moderate (visual abstraction)      | High (hierarchy)            | **High** (visual learners)        | Slow (requires tool)       | **Excellent** (for visuals)     |  

---





## Result
ChatGPT delivers accurate, well-structured summaries but retains some technical jargon, making it fast but moderately beginner-friendly. Claude excels in simplicity with clear bullet points, offering the best balance of precision and readability for students. Gemini’s analogies boost engagement and understanding, though they occasionally oversimplify complex concepts. Perplexity stands out for technical depth with structured comparisons, while Copilot provides quick FAQs for practical learning. Finally, Miro’s visual mind maps enhance retention for spatial learners but require extra time to create.


