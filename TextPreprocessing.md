## Text Preprocessing

After examining the textual data (DoD remarks, movie reviews, and movie plots) that we are interested in, we summarised the necessary data-preprocessing below:

- Removes url from the text
- 'US', 'U.S', 'U.S.', 'US.' convert all of them to U.S. if they refer to the United States
  - such as 'THE U.S GOVERNMENT', 'THE US. MILITARY', 'STILL HIGHLY POSITIVE IMAGES OF US.'
- Replace '—' with '-'
- Change all the specific names of military supports' materials to general case: like 'KC-10' to 'KC' ,'B-2' to 'B' AND 'F-16' to 'F'
- Special characters which will be replaced with an empty (''):
  - '{'
  - '}'
  - '['
  - ']'
  - '('
  - ')'
  - '#'
  - '~'
  - '”'
  - '“'
  - '"'
  - '|'
- Special characters which will be replaced with a space (' '):
  - '~-'
  - '-~'
  - '--'
  - ' - '
  - '='
- Some special characters/strings need to be changed with corresponding:
  - '%': ' percent'
  - 'F/A': 'FA'
  - '/': 'or'
  - '9-17-92': '17SEP1992'
  - '&': 'and'
  - '+': ' plus'
  - '‘': "'"
  - '’': "'"
  - '’': "'"
- Convert the dates like '15-NOV-1983' without '-' in it: i.e. '15NOV1983'
- Convert the dates like '15 NOV 1983' without ' ' like : '15NOV1983'
- Replace '-' from text like 'MINI-SERIES' or 'MINI -SERIES' with a space' ': i.e. 'MINI SERIES' or 'MINI SERIES'
- Remove ' - ' from "text - text" like 'CRUME - BUM' while combining two texts only with a space: i.e. 'CRUME BUM'
- Make lowercase all the charachters
- Remove multiple spaces with only one space (' ')

While doing the pre-processing, we decided to keep some characters as is. For example, examples below with '-'

- 'MAY 18-19, 2002 AT NAVAL AIR', 'BUT WITH 9-10 MINS OF NAVY COMMERCIAL', 'BECAME A 30-HOUR', 'IT WAS SET 20-30 YEARS IN THE FUTURE', '14-21 MAY', 'AS APPOXIMATELY JANUARY 3 - 31, 2004', 'SHOOTING TOOK PLACE 28 FEB - 7 MARCH'

Last but not least, we didn't want to remove the punctuation. Since when we apply the NLP models both in Sentiment Analysis and Named Entity Recognition, the NLP model will handle the punctuation. Additionally, we kept the stopwords since removing them could change the way of interpretation in the sentiment analysis, hence the model performance. However, for scattertext we both examined the method with and without stopwords.
