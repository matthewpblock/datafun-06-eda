# datafun-06-eda
Created for Module 6 of Data Fundamentals course

## Description
My wife has [a small business offering art classes and private lessons](https://www.hawaiiartclasses.com), and asked me to see if I could find any useful insights to help improve her marketing and sales. At first I looked into her sales data through Square, but there's a lot of personal customer data in there that doesn't belong in a public repository. So I checked out Facebook post data from her [business page on Facebook](https://www.facebook.com/rebeccablockartworks) and decided that would be a much better fit for this project.  
Facebook/Meta allows you to download historical content performance data to a CSV file, so I grabbed approximately a year's worth of data and pulled it into my data folder. Let's walk through some exploratory data analyis to see what we can learn from it. The primary objective will be to recommend an improved posting strategy to attract more customers.  
Meta only allows downloads of 92 consecutive days,so gathering a year's worth of data required four download files. Data files are stored in [the data folder](https://github.com/matthewpblock/datafun-05-sql-project/tree/main/data).  

## How to Install & Run the Project
1. Create repository on GitHub with default README.md, Python .gitignore, and MIT license
2. Copy the repository to a local project folder:  
`git clone https://github.com/matthewpblock/datafun-06-eda`  
3. Migrate terminal to the project server
4. Setup a virtual environment:  
`py -m venv .venv`  
5. Activate the virtual environment:  
`.venv\Scripts\activate`  
6. Create requirements.txt
7. Commit changes
8. Update pip & install requirements
```py -m pip install --upgrade pip setuptools wheel  py -m pip install -r requirements.txt```  
9. Set correct interpreter & kernel  
