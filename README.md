# que-drop

Contrary to popular belief, grammar is not a strict set of rules. Instead, as people use certain
linguistic structures more frequently, these patterns become cemented into accepted convention. For
example, by today’s standards, the sentences I think that it will rain and I think it will rain are both
grammatically correct. However, several centuries ago, dropping that would not have been allowed.
Linguists are starting to notice a similar trend in the usage of que(that) in Spanish. This paper uses
statistical tools and machine learning to study the phenomenon of que-dropping in modern Spanish.
Two potential influences on que-drop were the formality of the context and verb type. Analyzing
Spanish formal (corpus) and informal text (Twitter), I found that formal contexts and volitional verbs
increased the likelihood of que-drop(p>0.99, Z-score test). This agrees with prior linguistic research.
My second analysis utilized a LSTM(Long Short-Term Memory) machine learning model to learn
not only the syntax but the semantics of Spanish. Testing on a portion of untrained corpora, my two
models (one for formal and one for informal) predicted if que followed a verb with 74.25% accuracy
and 76.52% accuracy, respectively. This proves that prediction of que was possible; the model
internalized Spanish grammar by learning from millions of human-generated Spanish sentences. My
project demonstrates that machine learning can be a powerful tool in helping computers learn new
languages; a model not only significantly quickened token analysis, but also revealed grammatical
patterns that have eluded linguists for centuries
