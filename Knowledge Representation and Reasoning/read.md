# Knowledge Representation and Reasoning

This is my learning experience from Module 4 of the MSc Artificial Intelligence

![image](https://github.com/user-attachments/assets/53e67fe2-1df6-4ee6-b3a2-5ca390aa23cb)


Use the following links to navigate to the start of the sections

[1. Collaborative Discussions](#collaborative-discussions)

[2. Seminars and formative activities](#seminars-and-formative-activities)



## Learning outcomes


### In the module Knowledge Representation and Reasoning I shall:

*Discuss how to define knowledge and explain the concept of KRR and its relationship to data and information.
  
*Gain an appreciation of the importance and rationale for employing formal approaches to KRR.

*Demonstrate an understanding of the basics of logic and its application to KRR problems.

*Acquire an understanding of the professional competence required to able be to identify and examine KRR technologies for Artificial Intelligence applications.


### On completion of the module Knowledge Representation and Reasoning, I will be able to:

*Critique the need for formal approaches to knowledge representation and reasoning.
  
*Review critically properties of a knowledge-based system.

*Appraise critically modelling techniques for knowledge representation and reasoning.

*Examine and incorporate different modelling approaches to solving KRR problems.


![image](https://github.com/user-attachments/assets/96e7c730-c504-4a3e-bb0f-304ea7326c24)


[Back to the top](#knowledge-representation-and-reasoning)


## Collaborative discussions

### Initial, summary posts & response to peers' posts


### Collaborative Discussion 1



**Knowledge Representation is a recent phenomenon – it only became a topic of discussion with the development of computing technology and the need to represent knowledge in computer systems. Discuss this assertion. Do you agree or disagree with this opinion? Justify your position, supported with at least two academics references.  How is reasoning related to knowledge representation (KR)? Is KR still useful without reasoning support? Justify your answer supported by two academic references.**

**Initial Post**

The assertion that knowledge representation (KR) is a recent phenomenon, emerging only with the development of computing technology, is not entirely accurate.  While the formal study of KR as a subfield of artificial intelligence (AI) began in the mid-20th century, the human need to represent, store, and transmit knowledge is ancient and predates computers by millennia.

Humans have always sought ways to externalise and perpetuate knowledge beyond individual memory.  One of the most striking examples is the use of Egyptian hieroglyphics, which date back to around 3300 BC.  Hieroglyphics served not only as a means of communication but also as a sophisticated system for encoding religious, historical, and administrative knowledge in a durable, interpretable form.  This demonstrates that the need to represent knowledge systematically is deeply rooted in human culture.  As Weststeijn (2011) put it, ‘[c]ommunication through images is more fundamental than that through alphabetic signs’.

Beyond pictorial and written systems, the development of formal logic by philosophers and mathematicians such as Aristotle, Leibniz, and later George Boole, further exemplifies pre-computer knowledge representation. These formal systems were designed to capture the structure of reasoning and argumentation, providing a symbolic language for expressing complex ideas and relationships (Brachman & Levesque, 2004).

With the advent of computers, the study of KR gained new urgency and direction. Computers made it possible to automate reasoning and manipulate large bodies of knowledge efficiently.  This led to the development of explicit KR formalisms such as semantic networks, frames, and ontologies, which are central to AI research today (Brachman & Levesque, 2004).

Reasoning is fundamentally linked to knowledge representation (KR).  KR structures and encodes information so that a system can "understand" it, while reasoning uses this structured knowledge to draw inferences, solve problems, and make decisions (Lee, 2024).  In essence, KR provides the what (facts, relationships, rules), and reasoning provides the how (deriving new information, making conclusions).

KR alone, without reasoning support, is limited in usefulness.  While it allows for the organisation, storage, and retrieval of information, the real power of KR is realised when reasoning mechanisms are applied.  Reasoning transforms static data into actionable insights by enabling systems to infer new knowledge, detect inconsistencies, and make decisions.  Without reasoning, KR is reduced to a sophisticated database, lacking the ability to generate new conclusions or adapt to new situations.


#### References

Brachman, R. J., & Levesque, H. J. (2004). Knowledge Representation and Reasoning. Morgan Kaufmann.

Davis, E., & Marcus, G. (2015). "Commonsense Reasoning and Commonsense Knowledge in Artificial Intelligence." Communications of the ACM, 58(9), 92–103.

Lee A. (2024), Knowledge Representation and Reasoning in AI: Analyzing Different Approaches to Knowledge Representation and Reasoning in Artificial Intelligence Systems, Journal of Artificial Intelligence Research, Volume 4 Issue 1

Weststeijn, T. (2011) 'From hieroglyphs to universal characters. Pictography in the early modern Netherlands', Netherlands Yearbook for History of Art / Nederlands Kunsthistorisch Jaarboek, 61(1), pp. 238–281.



#### Response to my peers' posts


I fully agree that knowledge representation (KR) is not a recent innovation but rather an ancient human practice rooted in the necessity to encode, preserve, and transmit knowledge.  Long before computational KR, early civilizations developed sophisticated symbolic systems—from Paleolithic cave paintings (~40,000 BCE) to Egyptian hieroglyphics (~3300 BCE)—that served as durable, interpretable repositories of cultural, religious, and administrative knowledge (Weststeijn, 2011). These systems underscore humanity’s enduring drive to externalise thought, a pursuit later refined through alphabets, formal logic (i.e. Aristotle’s syllogisms, Leibniz’s characteristica universalis), and mathematical notation (Brachman & Levesque, 2004).  Such historical precedents confirm that KR’s conceptual foundations predate computers by millennia and modern AI merely formalises these principles algorithmically.

However, while KR can exist as a standalone framework for organising and retrieving data (structured databases or ontologies) its full potential is realised only when paired with reasoning.  As Brachman and Levesque (2004) argue, KR structures (i.e. semantic networks, frames) provide the what (facts, rules, relationships), while reasoning enables the how (inference, problem-solving).  For instance, a medical ontology might encode disease-symptom relationships, but without reasoning (i.e. deductive logic or probabilistic inference), it cannot diagnose new cases or resolve contradictions (Davis et al., 1993). This aligns with Sowa’s (2000) observation that reasoning transforms static KR into dynamic intelligence, generating actionable insights (Sowa, 2000).

Reasoning may enhance KR by enabling inference and problem-solving, but KR alone still has value. Systems like databases and knowledge graphs show that structured KR works well for storing and finding information, even without advanced reasoning (Sowa, 2000). The real challenge for AI today is combining these modern tools with principles of clear representation to create systems that are both powerful and understandable.


#### References

Brachman, R. J., & Levesque, H. J. (2004). Knowledge Representation and Reasoning. Morgan Kaufmann.

Davis, R., Shrobe, H., & Szolovits, P. (1993). What is a Knowledge Representation? AI Magazine, *14*(1), 17–33.

Sowa, J. F. (2000). Knowledge Representation: Logical, Philosophical, and Computational Foundations. Brooks/Cole.

Weststeijn, T. (2011). The Visible World: Dutch Visual Culture and the Rise of Early Modern Science. Amsterdam University Press.



Your post provides a comprehensive overview of knowledge representation (KR) and its historical evolution.  I particularly appreciate how you have highlighted both the ancient roots of KR and its modern computational applications.  Examples of Sumerian cuneiform, Egyptian hieroglyphics, and Greek logical systems (Weststeijn, 2011) effectively demonstrate that the human impulse to systematically represent knowledge predates computing by millennia.  This historical continuity is crucial for understanding KR's fundamental role in human cognition and information processing.

Modern computing has amplified KR's importance through formalisation and scalability (Brachman & Levesque, 2004).  The transition from ancient pictograms to contemporary semantic networks and ontologies represents an evolution in form rather than a completely new concept.  This perspective aligns with Davis et al.'s (1992) view that KR serves as a bridge between human-understandable knowledge and computer-processable data.

However, a clear distinction has to be made between KR and reasoning, as KR's standalone utility for information organisation is significant.  Many practical applications, from database systems to digital archives, demonstrate that structured knowledge representation maintains value even without automated reasoning components.  This echoes Nilsson's (1998) argument that KR serves multiple purposes beyond just enabling machine inference.

One area that might warrant further exploration is how modern machine learning approaches interact with traditional KR methods.  The emergence of neural networks presents new opportunities and challenges for knowledge representation that build on these historical foundations.


#### References

Brachman, R. J., & Levesque, H. J. (2004). Knowledge Representation and Reasoning. Morgan Kaufmann.

Davis, R., Shrobe, H., & Szolovits, P. (1993). What is a Knowledge Representation? AI Magazine, 14(1), 17-33.

Nilsson, N. J. (1998). Artificial Intelligence: A New Synthesis. Morgan Kaufmann.

Russell, S., & Norvig, P. (2010). Artificial Intelligence: A Modern Approach (3rd ed.). Prentice Hall.

Weststeijn, T. (2011). The Visible World: Dutch Visual Culture and the Rise of Early Modern Science. Amsterdam University Press.



![image](https://github.com/user-attachments/assets/668798c3-8875-48b4-8bfb-f729f82ed8ec)




[Back to the top](#knowledge-representation-and-reasoning)


## Seminars and formative activities 



### Unit 1 Formative Activities

[Formative Activities](https://docs.google.com/document/d/1qy2-JkTt8nOwDD4dS7WUcCyUmRMH248uFYaOu8qBVzo/edit?tab=t.0)


### Unit 2 Seminar Activities

[Seminar Activities](https://docs.google.com/document/d/1kPT580-pRQKgM3Jem-5h6xzYFixuJs_QLBb0mE2gquw/edit?tab=t.0#heading=h.dsfkn9v4bvo7)


![image](https://github.com/user-attachments/assets/51a7c4c0-6a1e-40c7-bc48-0e4a681b669a)




[Back to the top](#knowledge-representation-and-reasoning)

