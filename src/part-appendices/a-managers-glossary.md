# Appendix B: A Manager's Glossary

This glossary defines the thirty terms a manager is most likely to encounter in AI conversations. Definitions are written for the boardroom, not the machine room. Technical precision has been traded for useful clarity.

**Agent / AI agent**
An AI system that can take actions in the world — browsing the web, running code, sending emails, interacting with other software — rather than just producing text. Agents can operate with more autonomy than standard AI assistants and require correspondingly more careful governance. The "Digital Intern" described in this book is a simple agent when it takes actions rather than just producing output.

**Artificial general intelligence (AGI)**
A hypothetical AI system with human-level capability across all cognitive tasks. No current AI system qualifies. The term is often used in strategic discussions and investment contexts; when you encounter it, treat it as speculative rather than descriptive of anything that exists today.

**Augmentation**
Using AI to enhance human capability rather than replace it. Augmentation means redesigning work so that AI handles the tasks it does best — volume, consistency, first drafts — while people focus on tasks requiring judgment, relationships and accountability. Contrast with automation.

**Automation**
Using AI or software to replace a task entirely, without ongoing human involvement. Automation is appropriate for well-defined, repeatable, low-stakes tasks. It is distinct from augmentation, which involves ongoing human-AI collaboration.

**Bias**
Systematic patterns in AI output that disadvantage certain groups or produce unfair outcomes. Bias in AI typically reflects bias in the training data, which reflects the biases present in the texts the system learned from. Particularly significant when AI is used in decisions affecting individuals.

**Context window**
The amount of text an AI system can process at once — both what you give it and what it produces. Systems with larger context windows can handle longer documents and more complex conversations. Practically, this means that very long documents may need to be split for AI processing.

**Data leakage**
The risk that sensitive information shared with an AI system leaves the organization's controlled environment. Depending on the AI provider's policies, inputs may be stored, logged or used to train future models. Requires clear organizational policy on what information may be shared with external AI systems.

**Embedding**
A mathematical representation of text as a set of numbers, used to measure the similarity between pieces of text. Embeddings allow AI systems to find content that is similar in meaning rather than just in exact wording. Used in search, recommendation and document retrieval systems.

**Fine-tuning**
Adapting a general-purpose AI model by training it further on a specific dataset — for example, training a general language model on your organization's documents to make it more familiar with your terminology and style. More involved and expensive than prompting but can produce better results for specific applications.

**Foundation model**
A large AI model trained on broad data that can be adapted to a wide range of tasks. The models that power most commercial AI applications — including the systems described in this book — are foundation models. Examples include GPT-4, Claude and Gemini.

**Generative AI**
AI systems that produce new content — text, images, code, audio — rather than just classifying or analyzing existing content. The systems this book is primarily concerned with are generative AI systems that produce text.

**Governance**
The policies, processes and accountability structures that determine how AI is used in an organization. Good AI governance specifies who is responsible for what, what oversight is required and how decisions are made and recorded. The absence of governance is not the absence of AI use — it is the absence of visibility and control over AI use.

**Guardrails**
Technical or procedural constraints placed on an AI system to prevent it producing certain types of output. Guardrails may be built into the AI system itself by its developer, or added by the organization deploying it. They reduce but do not eliminate risk.

**Hallucination**
The production by an AI system of confident, well-formed statements that are factually incorrect. Hallucination is a consequence of how language models work — they predict plausible text rather than retrieve verified facts — and cannot be entirely eliminated. It requires systematic verification of factual claims.

**Human in the loop**
A design principle for AI systems in which a human reviews and approves AI output before it is acted upon. The degree of human involvement can vary from reviewing everything to reviewing only flagged exceptions. Central to the supervision frameworks discussed in this book.

**Inference**
The process of running an AI model to generate output. When you send a message to an AI system and receive a response, that response is generated through inference. Inference has a cost — in computing resources and often in money — which scales with usage volume.

**Large language model (LLM)**
The type of AI model that underlies most current AI assistants and chatbots. LLMs are trained on large quantities of text and learn to predict what text should come next. Their capability to produce fluent, contextually appropriate text across a wide range of topics is the source of both their usefulness and their hallucination risk.

**Model**
The AI system itself — the mathematical structure that has been trained to perform a task. When people refer to "the model," they mean the underlying AI system, distinct from the interface through which you access it. Different models have different capabilities, costs and limitations.

**Multimodal**
Capable of processing or producing multiple types of content — text, images, audio, video. Multimodal AI systems can, for example, analyze an image and describe it in text, or generate an image from a text description. Increasingly common in commercial AI systems.

**Prompt**
The instruction or input you give to an AI system. The quality of the prompt significantly affects the quality of the output. Prompt engineering is the practice of designing prompts to reliably produce good output — reframed in this book as the management skill of briefing your Digital Intern well.

**Prompt engineering**
The practice of designing effective instructions for AI systems. Includes techniques for specifying role, task, context and constraints clearly and for iterating on prompts to improve output quality. The subject of Chapter 2 of this book.

**RAG (retrieval-augmented generation)**
A technique for giving AI systems access to specific documents or data sources when generating responses. Rather than relying only on what the model learned during training, a RAG system retrieves relevant content from a defined set of documents and uses it to inform the response. Useful for applications requiring access to organizational knowledge.

**Risk appetite**
The level of AI-related risk an organization is willing to accept in pursuit of its objectives. Risk appetite should be set explicitly at board or executive level, not left to emerge from individual project decisions. It determines what supervision levels are appropriate and what categories of AI use are permissible.

**Supervision level**
The degree of human oversight applied to AI output before it is acted upon. This book defines four levels: review everything, spot check, exception-based review and autonomous operation. The appropriate level depends on the stakes, reversibility and verifiability of the output.

**System prompt**
Instructions given to an AI system before the user's input, typically by the organization or developer deploying the system rather than the end user. System prompts set the AI's role, behavior and constraints for a given application. They are a primary governance tool for organizations building AI-powered products.

**Temperature**
A setting that controls how predictable or varied an AI system's output is. Low temperature produces more predictable, consistent output. High temperature produces more varied, creative output. Relevant when building AI applications where consistency or creativity is a priority.

**Token**
The unit in which AI systems process text. A token is roughly equivalent to three-quarters of a word in English. AI systems have limits on how many tokens they can process at once (context window) and charge for usage based on tokens processed.

**Training data**
The text, images or other content used to train an AI model. The model learns patterns from this data, which determines both its capabilities and its limitations. Training data that over-represents certain sources or perspectives will produce a model with corresponding biases.

**Use case**
A specific application of AI to a defined task or problem. "Using AI to draft client emails" is a use case. "Using AI" is not. Identifying specific use cases before investing in AI tools is a prerequisite for sensible business case development and governance design.

**Zero-shot**
Asking an AI system to perform a task without providing examples of what a good response looks like. Contrasted with few-shot prompting, which includes examples. Zero-shot works well for simple, well-defined tasks; few-shot is useful for tasks requiring a specific format or style.
