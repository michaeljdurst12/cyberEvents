# cyberEvents
Cyber security data was sourced from https://csr.lanl.gov/data/cyber1/

In this repo, a couple different ML techniques(SVC, random forest, decision tree, logistic regression) were used to attempt to predict success and failures of logins.

The file auth.txt.gz is not included in this repo because of size.  In this repo a 200,000 line sample of the auth.txt.gz files was used. The sample of data was taken by using the terminal and following command. 
gshuf -n 200000 auth.txt > auth_sample

Also included this repo are a couple of basic network graphs attempting to visualize network connections. All non-numeric data was transformed to numeric using a simple function so that we could apply it to ML.  

Additionally, redteam.txt.gz was used to create network graphs showing the relationships of source computers to destination computers.  In the file it's clear there is one main source computer in red team attacks which accounts for 700 of the data values. 
