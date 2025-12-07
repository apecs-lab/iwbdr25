**Invited Talk #1**

Title: Embodied AI: From Robotic Reasoning and Manipulation to Multi‑Robot Collaboration

Abstract:
Robots that can understand natural language and coordinate physical actions are a key enabler for societies and human-centric automation. Yet mapping high-level, ambiguous human instructions to low-level, real-time robot control remains a core research challenge, especially under noisy perception and multi-robot coordination constraints. This talk examines how recent advances in large language models, multimodal perception, and deep multi-agent reinforcement learning can be combined to narrow this gap.

The first part of the talk presents a voice-controlled mobile manipulator that integrates a large language model for semantic parsing of spoken instructions with vision–language perception, visual navigation, and grasp planning to produce executable action sequences for object search, retrieval, and delivery. The second part studies collaborative object transportation with multiple robots via deep multi-agent reinforcement learning, emphasizing sensor-based policy learning and control synthesis for synchronized manipulation of shared payloads. Together, these projects highlight emerging research directions in language-grounded, perception-aware, and multi-robot control for assistive and service robotics.

Bio: Dr. LIU Benben is a Project Manager at the Logistics and Supply Chain MultiTech R&D Centre (LSCM), one of the largest public research institutes in Hong Kong. He has over 17 years of research and professional experience in high-performance computing, cloud computing, and machine learning systems. He and his team are dedicated to the research and application of AI particularly large language models (LLMs) and embodied intelligence in Hong Kong, with research focus on deep learning, reinforcement learning, and embodied AI.


**Invited Talk #2**

Title: Accelerating Zero-Knowledge Proofs with Multi-GPU Systems

Abstract:
Zero-knowledge proofs (ZKPs) enable the validation of statements without disclosing any underlying information, making them essential for applications such as verifiable outsourcing and digital currencies. However, widespread adoption of ZKPs remains constrained by lengthy proof generation times, predominantly due to two computationally intensive operations: Multi-Scalar Multiplication (MSM) and Number Theoretic Transform (NTT). Even with GPU acceleration, generating proofs for complex statements can require several minutes on a single GPU. This talk explores the potential of distributed multi-GPU systems to significantly accelerate ZKP generation, introducing two novel algorithms: DistMSM for MSM and UniNTT for NTT. Innovations are presented both at the algorithmic and GPU kernel levels. At the algorithmic level, MSM and NTT algorithms are adapted to effectively leverage multi-GPU architectures; at the GPU kernel level, optimized kernels are designed specifically for elliptic curve arithmetic and NTT computations, tailored to contemporary GPU hardware. Experiments demonstrate a 6.64X speedup in end-to-end proof generation on an 8-GPU system compared to single-GPU setups, underscoring the effectiveness of multi-GPU systems in enhancing the performance of ZKPs.

Bio: Zhuoran Ji is an assistant professor with the School of Cyber Science and Technology, Shandong University.  He received the BSc and PhD degrees in computer science from the University of Hong Kong.  His research interests include GPU multitasking systems, mobile GPU computing, GPU computing for deep learning applications, high-performance computing for deep learning, and parallel computing based on the GPU.
