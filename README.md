# Namaste AI
What is AI?
# ai is science of making machines perform task that normaly require some human inteligence.

## HISTORY OF AI
-> can machines think? question asked my Alan Turing in 1950. so he made The Turing Test to check it.
Turing Test -> judge ask the question from machine and person. if he identify that answer is given by machine or not, machines fails but if judge not able to answer machine Pass.  
-> Artificial Inteligence word given by John McCarthy in 1955  
-> 1986 Synthatic Inteligence word came.  
SI -> Machine beyond human inteligence  
AI -> can machine replace the human or can achive the human inteligence  
-> In 1997 Deep blue Application defeated Garry Kas Paruv (Famous chess player) in chess. because of this event scientists think Have machine become smarter than human.  

->Rule Base AI(1950 - 1980) -> inteligence is a simply collection of rules(very much if else conditions)  
Ex. Spam Detector -> if(spam || $$$ || lottery), flu detector -> if(cough || body ache || cold)  
expert system were built by human using lot of rules  

#Machine Learning -> Rules❌ Examples✅  
Cat vs Dog -> Train Using 1 million Labelled Pictures  
Model Learn, Prediction, Training Data  

#Deep Learning -> Neural Networks, Can computer learn features themselevs   
Example -> instead human tell computer this is eye can computer detect eye automatically  
image Recognition, speech Recognition, Translation, GPU revolution + internet + large dataset  

# Netural Language Processing -> how machines understand human language  
# Transformer(2017) -> attention is all you need  
# Large learning Modals  
# Generative AI  
## The CHAT GTP Moment(Nov 2022)   
Now AI Can do anything  
LLM Models Vs Google Search Engine -> AI Generates the answer but Google search engine search the web pages most related to you search according to their algorithm  
LLM Models were trained on large number of data.  
Training Vs Inference -> In Training Models were feeded large number of data to recognize pattern but in Inference Models return some answer to users queary Inference is stage where Training used to return answer.  
Base Model Vs Ai Assistence -> in base model ai just generate related text but AI assistence can exiss the tools and can answer the diffrent type of quesry by helping of outer tools or tech.  
# AI Answer the Garbage very confidently(Language Beautifulness is not the mark of factual accuracy) This Property of AI is called as Hallucination.
Reason of hallucination can be -> Insufficient Info 
                                  Ambiguos Info
                                  Outdated Knowledge  
                                  False assumption  
                                  Model are optimised to answer  
-> AI assistence get super power by using diffrent tools like web search,diffrent type of calculator, weather application, clock, Email, Calander, Code exicution, Location, Files, DataBase.  
-> Web Search + LLMs => AI Assistance (Chat GPT, Gemini, Cloude etc.), They can Retrive data + Generate Answers.

# How AI understand  Human Prompt?
1. Tokenizer -> it change the sentence into multiple tokens assign with each words and those tokens are assign to specific number.specific words are assiged with specific token numbers. example (my name is chitransh) -> [21,345,321,768,32];
   -> llms does not assign specific char to specific token number because it increased the expensiveness.
   -> llms does not assign specific word to specific tokens because there can be many many words in this world.
There are different tokenizer algorithms like byte pain encoding, unigram encoding etc.
->if two sentence have same meaning does not mean they will have same number of tokens. generally llms are very good to tokenize english thats why same meaning sentence in english take less tokens campair with hindi sentence.
-> emojis, special symbols, code, sign etc. are represented by diff token ids.
-> system instruction are also passed by ai assistence to llms with every prompt. system instructions are also assign to specific tokens.
## context window -> there is not only the message is passed to llms specific size of context also passed. context has limited size called as context window.  
# How Machine Represents Meaning  
Vectorization -> converting any piece info into array of numbers is called as vectorization.  
embeding -> is the vector of numbers has some kind of meaning.
           example-> king = [2.3,6,8,0.2]
                             loyal,brave,healty,longer  
           these number is called as dimensions  
-> the many numbers of dimensions in embeding how much the pattens are recognizable by machine.  
the high numbers of dimensions in embedding does not mean highly good model, these embedding of different words that present in this world are feed to the machines the patterns are automaticaly recognized by the machine. same like how a child recognized pattern between different words.    
->Semantic simillarity -> it measures how close two piece of sentence is in meaning, beacause it is very difficult to measure simillarity between two sentence by using only keywords matching. example = 1.how to center a div 2.how to put an element at middle respect to its parent. both has same meaning but machine can only find similarity between them by using embedding because there embedding will form same pattern.    
-> Cosine Similarity -> if more lesser the angle between two vectors more simillar they are. beacause cos(0) = 1, cos(90) = 0, cos(180) = -1;    
   value vary between -1 to 1. if cosine value more closer then 1 more similar the vectors are. similarity does not depends on the length of the vectors.    
   that mean two sentences can have very different words but same meaning.    
   Cosine Similarity = A.B/|A||B|    
   -> Embedding capture relationship they do not independently verify facts,intent,quality,safety.  
## Text Embeding Vs Tokens Embeding -> 
 -> text embeding refers to embeding of a sentence used to find sementic similarity between two sentences.  
 -> Tokens embeding refers to embeding of different words in sentence that helps to identify the order of words and identify the words.  

-> same word can have different meaning in different sentences like i am eating apple, i like apple devices have different meaning. so embeddings depends on surrounding words.  
 * How modern llm Models represents Context.
   -> initial token embeding will remains same for both sentence but furder in more levels the embeding has going to change base on surrounding. Context modifies the representation
-> Bias in embeddings -> model can be bias on specific society,color,steriotype,inequality etc. beacuse models are train on the data that can be bias.
    
   
   

           
           

   
    
                                  


 
