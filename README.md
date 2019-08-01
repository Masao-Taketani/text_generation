# text_generation

A **Japanese corpus**, [**livedoor corpus**](https://www.rondhuit.com/download.html#ldcc), is used in this experiment. More specifically, articles from"Sports Watch" are used to generate sports-related text.

## Conculusion
The model could sucuessfully generate sports-related text even though the generated text is not consistent when it comes to what kind of sports topics it writes about. I used 20 sequences to predict 21st word for this investigation, but you can replace the sequence length much longer than 20, so that the model considers longer sentence to predict each output word(training time may increase if you do so). 