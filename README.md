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

### Activity
14/11/2022: Our paper titled `A Novel Dataset for Fake News Detection in Tamil Regional Language` has been accepted for SPELLL 2022! 

03/06/2023: Read our paper here: [Speech and Language Technologies for Low-Resource Languages](https://www.springerprofessional.de/en/speech-and-language-technologies-for-low-resource-languages/25417392)
