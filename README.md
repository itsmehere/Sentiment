# Sentiment

An AI that attempts to determine the sentiment of a sentence.

## Usage:

```
python sentiment.py corpus
```

## Sample Output:

```powershell
C:\Users\mihir\Programming\Sentiment>python sentiment.py corpus
s: fast delivery and excpetional packaging. The product works great!
Positive: 0.9138
Negative: 0.0862
```

## Installation:

Make sure you have `nltk` installed by doing:
```
pip3 install nltk
```
If this succeeds and you see a `punkt` error, open a python shell and do the following:
``` python
import nltk
nltk.download()
```
Then click download all and wait for the process to finish. Try running again.