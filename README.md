Group T, IDs: 316398387 ,318481447


<pre>
This is our Sentiment Analysis classification project structure: 

.
├── Corona_NLP_test.csv
├── Corona_NLP_train.csv
├── Final_Paper_Group_10.pdf
├── Part_A_groupT.ipynb
├── Part_B_groupT.ipynb
├── README.md
├── preprocessed_tweets.csv
├── pyproject.toml
├── requirements.txt
└── uv.lock

</pre>

**We pinned it to 3.12 py version but it is possible in further work to create .sh script relevant for every cloning based on user os. **

In order to reproduce our results, please follow these steps:
1. Clone the repository to your local machine.
2. Install the required dependencies using pip:
   ```
   pip install -r requirements.txt
   ```

3. Run jupyter notebook first Part_A_groupT.ipynb and then Part_B_groupT.ipynb to see the code and results with explanations. We used uv as package manager and as environment manager, but you can also use pip and virtualenv or conda.

* note: we might push some cleanup commits and add-on results after submition, also apply some CI-CD(github action or gitlab.ci what the reader familiar with better) pipeline here to clean the code and output cells and un-necessary files. 
