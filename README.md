# Caltech-CS155-miniproject3
[Preprocessing](https://colab.research.google.com/drive/1JmRmwPtpgTVw8OC3NpM9qpqSq65AUnT_?usp=sharing)\
[Unsupervised learning]()\
[HMM]()\
[RNN]()\
[Visualization]()

file:\
shakespeare_hypenation: tokenized(syllable) sonnets including the non-regular lines.\
shakespeare_hypenation2: excluding the non-regular lines.\
shakespeare_hypenation3: no dash and use '==========' to seperate the sonnets.\
shakespeare_hypenation4: better syllabification

rhyme_dict.txt: the rhyming pairs\
rhyme_dict.csv: the csv version of it

stress_dict1.csv: 1 means appearing at odd position(1,3,5,7,9 stressed), 0 means appearing at even position(0,2,4,6,8 unstressed)\
this is my guess. not sure about the rule\
stress_dict2.csv: the average of stress_dict1.csv for each syllable. I guess if it's really stressed, then it is closer to 1, otherwise it will be more zero.





