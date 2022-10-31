# Fake-News-Headlines-In-Tamil

- This Tamil fake news text corpus has 5,273 rows
- The data was collected automatically from various verified websites by using web scraping tools
- Download the dataset here: [Dataset](./Tamil-News-Headlines.csv)

### Corpus Statistics
<div align='center'>

| News           | Count |
| ---------------- | ----- |
| Fake           | 2949 |
| Real         | 2324 |
| **Total** | **5273** |

</div>


### Domains

- The Corpus has data from the following domains:

<div align='center'>

| Domain           | Label | Count |
| ---------------- | ----- | ----- |
| Politics         | politics | 1674 |
| Miscellaneous (individual opinions, political)   | miscellaneous | 1521 |
| Business/Science | tech | 966 |
| Entertainment    | entertainment | 589 |
| Sports           | sport | 476 |

</div>

### Baseline Models


<div align='center'>

| Model           | Accuracy |
| ---------------- | ----- |
| Support Vector Machine | 87.85% |
| Logisitic Regression           | 86.80% |
| Naive Bayes         | 85.46% |
| XG-Boost    | 85.08% |
| RNN (2 LSTM layers)    | 75.04% |

</div>
