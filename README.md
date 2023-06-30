### Client Engineering: LLMs Test Exercises

#### Exercise 1 - Text Cleaning

Process the provided text samples by:
- Remove URLs from the text: "The link to latest football score. https://xyz.com/a/b"
- Remove alphanumeric words from the text: "Hello Maria whatsup123"
- Remove words starting with '#' character: "Mado is very good with last ball six #dhoni #six"
- Splits alphanumeric words into digits and text: "I will be buying movie tickets for 4adults"

#### Exercise 2 - Summarization 
Use the text.csv file from the /data folder and summarize 3 of the stories using a model/technique of your choice 

#### Exercise 3 - Classification
Use the provided Pytorch model from the /model folder and classify the text from all 3x stories chosen above (one by one).

#### Exercise 4 - Performance
Compare the summarized output of the article from /data and calculate the precision (BLEU score) taken into consideration the reference summary (summary-1-flan-ul2--article1) and the candidate summary (summary-2-flan-ul2--article1)

**NOTE**:
- You can provide your input within a Jupiter notebook containing the cells' output. Don't forget to be creative as much as you want in the provided time.
- Please don't fork this repo.
