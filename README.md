# Economic and Financial Named Entity
Economic and Financial Named Entity is a domain-specific dictionary for named entity recognition in the economic and financial domain. It's suitable for uses in named entities extraction or any tasks that are proposed for a specific term in economics and financial domain. This dictionary is maintained by the Data Science Group in the Department of Computer Science, Faculty of Science, Chiangmai University. Although we do our best, we cannot guarantee the relevance and accuracy of every entry in this dictionary. We intend to continually update the dictionary by correcting existing entries and by adding new ones. The details about our twelve economics and financial entities are described as follows. <br/>

![alt text](https://github.com/Wilawan-Y/EconomicFinancial-NE-Extractor/blob/main/entity.jpg?raw=true)

# Instructions:
If you add words to this dictionary or correct words in your version of this dictionary, we would appreciate it if you could send these additions and corrections to us (wilawan_y@cmu.ac.th) for consideration in a subsequent version. All submissions will be reviewed and approved by the current maintainer.

# Usage:
```python
from NE_Extractor import Extraction

text = 'Crypto Exchange Bithumb Hacked Again, Lost EOS and XRP from Hot Wallets'
Tag = Extraction(text)
Tag.tagging()

print(Tag.get_key())
print(Tag.get_NEtag())
```
# Getting started

# Dependencies:
- marisa_trie <br/>
- nltk <br/>
- pickle <br/>
- re
# Reference:
Yathongkhum, W., Treeratpituk, P., Bootkrajang, J., Laosiritaworn, Y., and Chaijaruwanich, J., “Economic and Financial News Classification Based on Category-Associated Feature Set,” 
