Group T, IDs: 316398387 ,318481447


<pre>
This is our Sentiment Analysis classification project structure: 

We used .env file but we do not assume in the 2 attached jupyter notebooks that every person who is using this repo familiar with it so we gave an option to bypass it(basically change the `wandb.login()` setup and paste your wandb api key. 
The preprocessed_tweets.csv is the final cleaned preprocessed dataset for the part B notebook. 
   
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
It is also possible to run all of it in colab and install necessary dependencies. there is a problem with macOS and bitsandbytes library and it is needed to be taken into account.

In order to reproduce our results, please follow these steps:
1. Clone the repository to your local machine.
2. Install the required dependencies using pip:
   ```
   pip install -r requirements.txt
   ```

3. Run jupyter notebook first Part_A_groupT.ipynb and then Part_B_groupT.ipynb to see the code and results with explanations. We used uv as package manager and as environment manager, but you can also use pip and virtualenv or conda.
4. Part B ipynb - containes the entire setup to reproduce and re-run the results. notice there is a need but can be 
* note: we might push some cleanup commits and add-on results after submition, also apply some CI-CD(gh actions or gitlab-ci.yaml, what the reader familiar with better) pipeline here to clean the code and output cells and un-necessary files. 
