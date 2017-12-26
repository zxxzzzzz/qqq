Language retrieval model
Information retrieval modelling
	Mathematical models are used in many scientific areas with the objective to understand and reason about some behaviour or phenomenon in the real world. Webster’s new collegiate dictionary (Mish et al. 1983) gives the following definition: model a system of postulates, data and inferences presented as a mathematical description of an entity or state of affairs. A model of information retrieval predicts and explains what a user will find relevant given the user query. It is essential that the correctness of the model’s predictions can be tested in a controlled experiment. In order to do predictions and reach a better understanding of information retrieval, models should be firmly grounded in intuitions, metaphors and some branch of mathematics. Intuitions are important because they help to get a model accepted as reasonable by the research community. Metaphors are important because they help to explain the implications of a model to a bigger audience. For instance, by comparing the earth’s atmosphere with a greenhouse, non-experts will understand the implications of certain models of the atmosphere. Mathematics are essential to formalise a model, to ensure consistency, and to make sure that it can be implemented in a real system.

The application to information retrieval
Only very recently, since 1998, statistical language models are applied to information retrieval. The past two years show a remarkably large number of publications in which statistical language models are used to compute the ranking of documents given a query. To sum them up quickly: Ponte and Croft (1998) were the first to suggest the use of language models in information retrieval. They used estimation based on risk functions to overcome the problem of small sample sizes. Hiemstra (1998a) and Hiemstra and Kraaij (1999) were the first to introduce ranking based on a mixture of global and local probability distributions that is also used in the publications mentioned in the remainder of this paragraph. Miller, Leek, and Schwartz (1999) use hidden Markov models for ranking, including the use of bi-grams to model two word phrases and a method for performing blind feedback. Sahami (1999) suggested an approach to document clustering based on smoothing the document models by using the geometric mean of the global and local distributions. Berger and Lafferty (1999) and Hiemstra and De Jong (1999) developed a model that includes statistical translation. Ng (2000) introduced a model that uses the ratio of the conditional probability of the query given the document and the prior probability of the query, including a method for query expansion. Song and Croft (1999) used a model which includes bi-grams and introduced Good Turing re-estimation to smooth the document models. This chapter will address details of many of the above mentioned publications. They will be recited where appropriate in the following sections. It is assumed that the reader is familiar with the basics of probability theory as for instance presented by Mood and Graybill (1963).

Two models of information retrieval processes
















References
[1] ChengXiang Zhai, “Statistical Language Models for Information Retrieval 
A Critical Review,” Foundations and Trends® in Information Retrieval Vol. 2, No. 3 (2008) 137–213. 

[2] Djoerd Hiemstra and Stephen Robertson, and Hugo Zaragoza, “Parsimonious Language Models for Information Retrieval,” in Proceedings of ACM SIGIR 2007, pp. 15–22, 2007.
[3] Djoerd Hiemstra and Arjen P. de Vries, “Relating the new language models of information
retrieval to the traditional retrieval models,” University of Twente, CTIT
P.O. Box 217, 7500 AE Enschede The Netherlands.
[4] Djoerd Hiemstra, “Using language models,
for information retrieval,” Grafisch Centrum Twente,Second printing, January 2001.
[5] Fei Song and W. Bruce Croft, “A General Language Model for Information Retrieval,”
in Proceedings of TREC 1999, 1999.

