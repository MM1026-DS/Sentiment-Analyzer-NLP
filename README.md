# Sentiment-Analyzer-NLP
## Description
<p>Help a leading mobile brand understand the voice of the customer by analyzing the reviews of their product on Amazon and the topics that customers are talking about. You will perform topic modeling on specific parts of speech. You’ll finally interpret the emerging topics. 
</p>
<li>
  <p>### Problem statement</p>
  <ul>
     A popular mobile phone brand, Lenovo has launched their budget smartphone in the Indian market. The client wants to understand the VOC (voice of the customer) on the product. This will be useful to not just evaluate the current product, but to also get some direction for developing the product pipeline. The client is particularly interested in the different aspects that customers care about. Product reviews by customers on a leading e-commerce site should provide a good view.
  </ul>
 
    <strong> Domain:Amazon reviews for a leading phone brand</strong>
    
   
  <p> Analysis to be done: POS tagging, topic modeling using LDA, and topic interpretation</p>
  
  <li>
  <ul>Discover the topics in the reviews and present it to business in a consumable format. Employ techniques in syntactic processing and topic modeling.Perform specific cleanup, POS tagging, and restricting to relevant POS tags, then, perform topic modeling using LDA. Finally, give business-friendly names to the topics and make a table for business. </ul>
  <ul> Read the .csv file using Pandas. Take a look at the top few records.</ul>
  <ul>Normalize casings for the review text and extract the text into a list for easier manipulation. </ul>
  <ul> Tokenize the reviews using NLTKs word_tokenize function</ul>
  <ul> Performed parts-of-speech tagging on each sentence using the NLTK POS tagger.</ul>
  <ul>For the topic model, we should  want to include only nouns
    <ol> Find out all the POS tags that correspond to nouns.</ol>
    <ol> Limit the data to only terms with these tags.</ol>
  
  </ul>
  <ul><strong> Lemmatize </strong>
  <ol> Different forms of the terms need to be treated as one.</ol>
  <ol> No need to provide POS tag to lemmatizer for now.</ol>
  
</ul>

<ul> Remove stopwords and punctuation (if there are any).  </ul>
<ul> Create a topic model using LDA on the cleaned-up data with 12 topics.
  <ol>Print out the top terms for each topic. </ol>
  <ol>What is the coherence of the model with the c_v metric? </ol>
</ul>


<ul> Determine which of the topics can be combined. </ul>
<ul>What is the coherence of the model? </ul>





  
  
  </li>
  
  </li>
