# cyberEvents
Cyber security data was sourced from https://csr.lanl.gov/data/cyber1/

In this repo, a couple different ML techniques were used to attempt to predict success and failures of logins.
Also included this repo are a couple of basic network graphs attempting to visualize network connections. ALl non-numeric data was transformed to numeric using a simple function so that we could apply it to ML.  

The file auth.txt.gz is not included in this repo because of size.  In this repo a 200,000 line sample of the auth.txt.gz files was used. To take a sample of the file on the command line on Mac use code below. 
gshuf -n 200000 auth.txt > auth_sample

Additionally, redteam.txt.gz was used to create network graphs showing the relationships of source computers to destination computers.  
