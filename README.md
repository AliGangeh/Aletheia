# Alathea
Using NLP to find biases in news.

*Important Notice: this project is still under developement. Many files have not yet been uploaded, updated, or finalized.*

## Vision
We live in a very polarized world. Everybody has specialized feeds that reflect their own beliefs and perspectives. People get stuck in echo-chambers, continuously reaffirming their beliefs with like-minded people. Because of this people no longer understand, sympathize, or even respect each other's perspectives. This is the cause of political polarization in the US. Aletheia hopes to change this. Through NLP Aletheia understand the viewpoints of different news articles and informs its users of their biases. Alternative viewpoints are then offered to broaden the perspective of the reader. I believe this process will promote critical thinking among readers and increase sympathy and understanding for other viewpoints.

## How it works
### Overview
Aletheia uses Natural Language Processing (NLP) to understand the text. This can be broken down into 2 main steps, entity analysis and sentiment analysis. Entity analysis identifies terms in the text, whether it be locations, organizations, people, or objects. It also recognizes the importance of the term to the article as a whole. Then sentiment analysis is used to understand the feelings of the article towards each term. This allows us to build an understanding of the various viewpoints of the article. 

Our findings of each article will then be compared to other articles about the same topic, allowing us to understand extreme viewpoints and direct users towards viewpoints opposing their own.

### Tools 
This project uses Google's NLP API. This API has great tools for entity analysis, sentiment analysis, content classification, and syntax analysis. 
