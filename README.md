# Continual-Learning-Closed-book-question-answering

Enable systems to acquire new knowledge without forgetting the past knowledge.
    - Pre-trained language models used in answering open-ended questions without using an external knowledge base. (Closed-book question answering)
    - Using constrained optimization to train a hyper-network to adjust a fact without affecting the rest of the information
    - fine-tune on the modified facts while enforcing a penalty on the overall change of parameters.
    - Implement T5-small model and fine tuned for 15000 steps on Trivia and Natural Q\&A dataset .
