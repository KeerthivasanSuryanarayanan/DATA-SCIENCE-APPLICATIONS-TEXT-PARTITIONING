# DATA-SCIENCE-APPLICATIONS-TEXT-PARTITIONING
## PROBLEM STATEMENT:
## Take a sufficient sample of Gutenberg's digital book. Create (random?!) samples of 200 partitions of the book. Make sure each partition or record has 100 words. Generalize the program so that you can replicate that for multiple books. Maintain the label for each of the text segments or records or document, label them as a, b and c etc. as per the book they belong to. Use Regular Expressions and Pandas to manipulate the data and serialize them.

### All necessary libraries are installed
### Function is created
### Downloading the book from gutenberg website is the next step
### cleaned_text = re.sub(r'\r\n?', '\n', raw_text).strip() Text is cleaned using this statement
### Splitting to list of words
### starting_indices = random.sample(range(0, len(wo) - 100), 200)  200 random starting indices for partitions are selected
### Empty list is created for partitions
### Appending each partition to the partitions list
### A DF is created to store all the partitions
### The dataframe is returned
### df_list.append(partition(bi, la)) #function is being called inside and the values are appended
### df = pd.concat(df_list)# Concatenating the DataFrames and exporting to CSV format
### df.to_csv('finaloutput.csv', index=False)

## SAMPLE OUTPUT SNIPPET:
![image](https://user-images.githubusercontent.com/104590925/214775579-43d95ee4-c87e-466e-bb2f-f99096710a82.png)
