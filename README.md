# State-of-Union-word-analysis
Analysis on Word count; Character count; Average word length; Average sentence length; Word distribution of the words frequency; Top ten longest words

Files needed:
- `sotu_analysis.py` - main analysis script
- `state_of_union.txt` - speech used for analysis
- `sotu_report.docx` - optional Word report (generated)

Requirements:
- Python 3.8+
- Optional: `python-docx` for Word output (`pip install python-docx`)

Usage:
python sotu_analysis.py state_of_the_union.txt
python sotu_analysis.py state_of_the_union.txt --docx

#Sample format
#your numbers will be different depending on the speech


=== Speech Analysis ===

Metric                        Value
--------------------------------------------------
Word count                    6162
Character count (incl. whitespace)34903
Average word length (chars)   4.53
Average sentence length (words)16.74

Top 20 words by frequency:
Rank Word                Count
----------------------------------------
1    the                 290
2    to                  211
3    and                 193
4    of                  155
5    that                125
6    we                  124
7    a                   121
8    in                  108
9    our                 96
10   is                  72
11   it                  61
12   for                 59
13   i                   52
14   or                  52
15   on                  42
16   this                42
17   who                 41
18   but                 40
19   not                 40
20   that's              39

Top 10 longest unique words:
1. environmentalists (17 chars)
2. next-generation (15 chars)
3. Representatives (15 chars)
4. Administration (14 chars)
5. employer-based (14 chars)
6. representative (14 chars)
7. three-quarters (14 chars)
8. transformation (14 chars)
9. transportation (14 chars)
10. breakthroughs (13 chars)

