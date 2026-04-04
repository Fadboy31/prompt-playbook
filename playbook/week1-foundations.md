"# Week 1: AI Foundations"

A Large Language Model (LLM) is a system that predicts the next word based on patterns it learned from massive amounts of text. It does not search the internet or truly understand meaning; it simply generates responses based on probability.

## The 3 Bad Prompt Failure Modes

### 1. Vague Task — "write something"
**AI Response (first 2 sentences):**  
[There is always something to be done, something to be learned, and something to become.]

**Failure Mode:**  
The prompt is too vague, so the AI guesses what to write without clear direction.

---

### 2. No Context — "help me"
**AI Response (first 2 sentences):**  
[Alright, let’s strip this down and get precise. 🧠 I need to know exactly what you want help with, because “help me” could mean anything from life strategy to coding, finance, or even just mindset sharpening.]

**Failure Mode:**  
The AI does not know what kind of help is needed, so it gives a generic response.

---

### 3. No Format — "make it better"
**AI Response (first 2 sentences):**  
[Absolutely. I need a bit more clarity first—are you asking me to improve a piece of writing, a project description, or something else? Could you share the exact text or content you want me to make better?]

**Failure Mode:**  
The AI does not know what “better” means or what format to follow, leading to unclear improvements.

### Key Insight
Bad prompts fail because they lack clarity, context, and direction. The more precise the prompt, the more useful and accurate the AI’s response becomes.

## The Specificity Upgrade
**Weak Prompt:  Write a professional email.**
**AI-Response**
[Got it. To make it truly professional and effective, I need a bit more context:

Who is the recipient (e.g., client, colleague, manager)?
What is the purpose (e.g., proposal, follow-up, introduction, complaint)?
Any key details or tone you want included (formal, friendly, persuasive)?

Once I have that, I can craft a sharp, ready-to-send email that hits the mark.]

**Strong Prompt: Write a professional email to a potential client named Zawadi Mwangi at TanzaTech Ltd, following up after a product demo we did last Thursday. The tone should be warm but confident. Keep it under 150 words. End with a clear call to action to schedule a 30-minute call this week.**

**AI Response**
[Subject: Following Up on Our Product Demo

Dear Zawadi,

I hope this message finds you well. It was a pleasure presenting our solution to you last Thursday and exploring how it can support TanzaTech Ltd’s goals.

I wanted to follow up to see if you had any questions or thoughts after the demo. We’re confident that our product can add significant value, and I’d love the opportunity to discuss next steps with you.

Would you be available for a brief 30-minute call this week to dive deeper and tailor the solution to your needs? Please let me know a time that works best for you.

Looking forward to your response.

Best regards,
[Your Name]
[Your Position]
[Your Company]
[Your Contact Information]]


**Key Differences Observed:**  
- The weak prompt produces a generic email with no context.  
- The strong prompt is personalized, includes context, has clear tone, and ends with a specific action.  
- Strong prompt is concise and targeted; weak is vague and bland.  

**5 Specificity Elements Added:**  
1. **Who** – “Zawadi Mwangi at TanzaTech Ltd”  
2. **Tone** – “warm but confident”  
3. **Length** – “under 150 words”  
4. **Context** – “following up after a product demo we did last Thursday”  
5. **CTA** – “schedule a 30-minute call this week”
