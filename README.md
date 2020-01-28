### Extraction of State, District, City and Zip Code using NLTK and Address Similiarity Using FuzzyWuzzy 

Fuzzy Wuzzy is a Python library uses Levenshtien Distance to calculate the differences between the sequences.

In order to compare and find similiarity between two addresses, different functions of fuzzy string matching are implemented.

Below is the list of fuzzy string matching function used :

1.**Fuzz Ratio:** The ratio function computes the standard Levenshtein distance similarity ratio between two sequences.

2.**Partial Fuzz Ratio:** This is similiar to fuzz ratio but will neglect all the small details like stop words, punctuations, capital letters.

3.**Token_Sort_Ratio:** Tokenize the strings and preprocess them by turning them to lower case and getting rid of punctuation ignoring word order.

4.**Token_Set_Ratio:** It is similar to token sort ratio, but little more flexible as it ignores duplicated words too.

5.**W Ratio:** A simple ratio function but handles lower and upper cases and some other parameters too.

 Please feel free to fork and contribute.
