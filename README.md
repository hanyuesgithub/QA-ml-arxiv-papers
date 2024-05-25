Hi there!! Let me introduce our ML assistant built in this project! 😊 

We developed an intelligent system powered with large language models(hashtag#LLMs) and advanced Retrieval-Augmented Generation(hashtag#RAG) supported with over 100,000 machine learning papers, aiming to provide ML learners and researchers with a user-friendly platform for easily understanding the intricate principles and methodologies behind burgeoning ML concepts.

The system flow includes three pivotal components.
a) Data Vectorization: ML papers vectorized as embedding representations and stored in database.
b) Context Retrieval: User queries to match with ML papers chunks which return as context.
c) LLM Inference: LLM finetuned with ML paper data to generate answers to AI-related user queries.

So, what has been done to build the system?
✅ Created a question-answering dataset (ml-arxiv-papers-qa) 
✅ Finetuned LLMs (hashtag#Llama-2-7B-Chat and hashtag#Mistral-7B)
✅ Trained an embedding model (BGE-M3)
✅ Built a RAG system with combined retrieval methods (BM25, BGE-M3 and Reranking)
✅ Designed and created a conversational UI

Our finetuned Llama-2-7B-Chat achieves statistically significant improvements and it shows the strongest performance across all evaluation metrics we applied compared to the base Llama-2-7B-Chat and base Llama-3-8B-Instruct models. Besides, our RAG system achieves a retrieval accuracy of 99.75%!

Teamwork divides the task and multiplies the success! Deeply appreciate the active engagement and collaborative spirit of the team (Hanyue Liu, Kenan Zhang, Linze Li, Xinyu Wang, Yixuan Gong)! 🎉

PS: the question-answering dataset and the finetuned Llama-2-7B-Chat checkpoint are publicly available on Huggingface:
https://huggingface.co/datasets/hanyueshf/ml-arxiv-papers-qa
https://huggingface.co/hanyueshf/llama-2-7b-chat-ml-qa

