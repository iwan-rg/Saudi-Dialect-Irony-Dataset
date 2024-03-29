
# The Saudi Dialect Irony Dataset (Sa`7r ساخر)
The Saudi irony dataset was collected using Twitter API and it consists of 19,810 tweets, 8,089 of them are labeled as ironic tweets

## Paper Summary
In sentiment analysis, detecting irony is considered a major challenge. The key problem with detecting irony is the difficulty to recognize the implicit and indirect phrases which signifies the opposite meaning. In this paper, we present Sa`7r  ساخرthe Saudi irony dataset, and describe our efforts in constructing it. The dataset was collected using Twitter API and it consists of 19,810 tweets, 8,089 of them are labeled as ironic tweets. We trained several models for irony detection task using machine learning models and deep learning models. The machine learning models include: K-Nearest Neighbor (KNN), Logistic Regression (LR), Support Vector Machine (SVM), and Naïve Bayes (NB). While the deep learning models include BiLSTM and AraBERT. The detection results show that among the tested machine learning models, the SVM outperformed other classifiers with an accuracy of 0.68. On the other hand, the deep learning models achieved an accuracy of 0.66 in the BiLSTM model and 0.71 in the AraBERT model. Thus, the AraBERT model achieved the most accurate result in detecting irony phrases in Saudi Dialect. 

## File Specifications

- [SaudiIrony.csv](https://github.com/iwan-rg/Saudi-Dialect-Irony-Dataset/blob/main/SaudiIrony.csv) : File that contains tweets with two labels, "ironic" and "non-ironic"
- Sa`7r paper (https://aclanthology.org/2022.osact-1.7.pdf)

## Citation

If you use this dataset please cite as:

```bibtex
@inproceedings{[AlMazrua et al., 2022],
  title={Sa`7r: A Saudi Dialect Irony Dataset},
  author={Halah AlMazrua, Najla AlHazzani, Amaal AlDawod, Lama AlAwlaqi, Noura AlReshoudi, Hend Al-Khalifa and Luluh AlDhubayi},
  booktitle={The 5th Workshop on Open-Source Arabic Corpora and Processing Tools, LREC2022, Marseille, France},
  year={2022}
}
```
## License

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg.
