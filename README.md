# Assignment-3

-I use the same data scource but the year is between 2003 to 2019 because the internet version earliest version is on 2003.

-I download the raw data from internet and use read_csv to import the data
-Extract the carrier data and assign it to carrier variable

-And use mapreduce algorithm to count the word occurance

-Mapping: assigning 1 to each word to ensure each word have it own word occurance

-Shuffling: group and sort the data with using sorted function

-Reducing: with using groupby function to group each carrier
           using reduce function to add up the value within each group.
           
Finally, we got the word count on each carriers.
