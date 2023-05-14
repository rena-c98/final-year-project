# final-year-project
This final year project codes, uses VADER to obtain sentiment polarity scores for each review that was extracted from Amazon.

To extract each review from Amazon, Python's Selenium was used. A total of 120 pages were extracted, resulting in a total of 1200 reviews.
To get your desired number of pages to extract, adjust the number in the main execution of the program. You may also pick your own product to extract. Use the same same of page as in the program - https://www.amazon.sg/Little-Tikes-628566000-Anchors-Pirate/dp/B00B0DWB62/ref=cm_cr_arp_d_product_top?ie=UTF8

To get the sentiment polarity scores of each review that was extracted, the VADER lexicon sentiment analysis tool was used in Python.

The program exports an Excel list that includes sentiment polarity scores for each review. The number of pages of reviews exported is determined by the value of x, which you can adjust in the main execution of the program.

Additionally, the codes prepares the data for VADER by removing non-English reviews, as well as outliers. On top of that, only medium-length reviews are used. Medium-length reviews are determined by the quartile values of the original data set.
