# Pashto Part-of-Speech Tagging

This repository provides resources and code for Pashto part-of-speech tagging using Bidirectional LSTM and Conditional Random Fields (CRFs). Our approach focuses on resolving ambiguities in Pashto text and has demonstrated significant accuracy improvements over traditional models.

## Citation

If you use this code in your research, please cite our paper as follows:

### BibTeX:
```bibtex
@article{10.1145/3649456,
  author = {Zaman, Farooq and Maqbool, Onaiza and Kanwal, Jaweria},
  title = {Leveraging Bidirectional LSTM with CRFs for Pashto Tagging},
  year = {2024},
  issue_date = {April 2024},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  volume = {23},
  number = {4},
  issn = {2375-4699},
  url = {https://doi.org/10.1145/3649456},
  doi = {10.1145/3649456},
  abstract = {Part-of-speech tagging plays a vital role in text processing and natural language understanding. Very few attempts have been made in the past for tagging Pashto Part-of-Speech. In this work, we present a Long Short-term Memory–based approach for Pashto part-of-speech tagging with special focus on ambiguity resolution. Initially, we created a corpus of Pashto sentences having words with multiple meanings and their tags. We introduce a powerful sentences representation and new architecture for Pashto text processing. The accuracy of the proposed approach is compared with state-of-the-art Hidden Markov Model. Our Model shows 87.60% accuracy for all words excluding punctuation and 95.45% for ambiguous words; however, Hidden Markov Model shows 78.37% and 44.72% accuracy, respectively. Results show that our approach outperforms Hidden Markov Model in Part-of-Speech tagging for Pashto text.},
  journal = {ACM Trans. Asian Low-Resour. Lang. Inf. Process.},
  month = apr,
  articleno = {58},
  numpages = {17},
  keywords = {LSTM, CRF, word embedding, tagging}
}
```
# Paper Access 
To read the full paper, you can access the PDF version [here](https://dl.acm.org/doi/pdf/10.1145/3649456).
