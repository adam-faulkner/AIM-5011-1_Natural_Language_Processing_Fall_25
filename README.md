# AIM-5011-1: Natural Language Processing, Fall 2025

> Repo for my Fall 2025 Natural Language Processing course, an elective in the M.S. Program in Artificial Intelligence, Katz School of Science and Health, Yeshiva University


Instructor: Adam Faulkner(adam.faulkner@yu.edu) \
Class hours: Tuesdays 5:30-7:30pm  \
Classroom: 205 Lexington Avenue Rm. 700 

## Course Description

This course provides a comprehensive overview of Natural Language Processing, the sub-field of Artificial Intelligence that deals with the automated processing of natural language text. The course is divided into three sections. In the first section, we'll introduce classic approaches to modeling natural language using traditional machine learning techniques such as Logistic Regression, Naive Bayes, and n-gram language modeling, as well as sparse vector-based representations of text such as bag-of-words, before moving to more contemporary, Deep Learning-based modeling techniques and vector representations such as LSTMs and dense-vector representations. Section 1 ends with the introduction of the Transformer and describes the field's move to language-model-based solutions to NLP tasks via frameworks such as finetuning. 

Section 2 provides an overview of traditional NLP tasks such as classification (Sentiment Analysis, Intent Detection, etc.), sequence labeling (Named Entity Recognition, syntactic and semantic parsing, etc.), and text generation (Machine Translation, Question-Answering, Summarization, etc.).


Section 3 introduces Large Language Models (LLMs), the dominant paradigm of contemporary NLP. We'll learn how LLMs reframed the NLP tasks described in section 2, which were traditionally solved using the ML techniques described in section 1, as word-prediction tasks.  In addition to foundational topics related to LLMs such as the autoregressive language modelling objective underlying GPT-style models and post-training regimes such as Reinforcement Learning from Human Feedback, students will gain a thorough grounding in emerging topics in LLMs such as Retrieval Augmented Generation (RAG), Agents,  LLM-as-a-Judge, LLM interpretability, and hallucination detection.

## Course Objectives
By the end of this course students will have

* gained an understanding of traditional ML approaches to solving NLP tasks as well as early language modeling techniques such as n-gram models
* gained an understanding of the tradeoffs between traditional, sparse-vector-based representations of text and more contemporary, dense-vector-based representations
* gained a theoretical understanding of the Transformer as well the Transformer's three major variants: the encoder-decoder, encoder-only, and decoder-only architectures
* gained an understanding of the three major flavors of NLP tasks: classification, sequence labeling, and text generation
* gained hands-on-experience finetuning and prompting open-source small LMs, such as BERT, and LLMs such as Meta's LLaMA3, as well as experience integrating open-source LLMs into popular LLM paradigms such as RAG and the Agent framework
* gained an understanding of RAG, tool-retrieval, and the Agent paradigm 
*  learned about contemporary research into LLMs' ability to utilize uniquely human cognitive traits such as theory of mind, logical induction, and linguistic competence


## Course Material
The material for this course consists of 

* representative research papers or textbook chapters containing technical presentations of each week's topic. All of this material is linked in the Course Schedule section in `AIM-5011-1_Natural_Language_Processing_Fall_25/syllabus_NLP_Fall_25.pdf`
* Jupyter notebooks illustrating implementations of the concepts described in each week's topic. These notebooks are available on both Canvas and in the course repo and can be reviewed before each class and run on Collab.  
* slides presented in class. These will also be made available in Canvas an in the course repo


## Assignments
Students will complete 5 assignments. These are short, non-programming assignments that delve into the math underlying the concepts presented in the lectures and will be made available in Canvas and on the course Github repo. These assignments must be printed, completed by hand, and submitted online (via scan or photo) or handed in to me directly. 

The final group project can be completed singly or as a group (max 5 members). The project should consist of an NLP application that implements one or more of the concepts described in class. The application will be demoed on the last day of class as a 5-10 minute presentation. 

## Grading


* 10% of the student's grade will be determined by attendance and participation in class
* 70% of the student's  grade will be determined by 5 take-home math assignments.
* 20% of the student's grade will be determined by a final group project.


