# Beyond GEC

In this paper, we present a new method for training a writing improvement model adapted to the writer’s first language (L1) that goes beyond grammatical error correction (GEC). Without using annotated training data, we rely solely on pre-trained language models fine-tuned with parallel corpora of reference translation aligned with machine translation. We evaluate our model with corpora of academic papers written in English by L1 Portuguese and L1 Spanish scholars and a reference corpus of expert academic English. We show that our model is able to address specific L1-influenced writing and more complex linguistic phenomena than existing methods, outperforming what a state-of-the-art GEC system can achieve in this regard. Our code and data are open to other researchers.

# Corpora

## ExPACE
[Download](https://phd-research-english-improvements.s3.amazonaws.com/expace-v1.zip)

## BrACE
[Download](https://phd-research-english-improvements.s3.amazonaws.com/brace-v1.zip)

## LACE
[Download](https://phd-research-english-improvements.s3.amazonaws.com/lace-v1.zip)

## Parallel training data

### Pt-EN-to-EN and Pt-ES-to-EN
[Download](https://phd-research-english-improvements.s3.amazonaws.com/pt-es-en-parallel-corpus.csv.zip)

## Citation

```
@inproceedings{zomer-frankenberg-garcia-2021-beyond-grammatical,
    title = "Beyond Grammatical Error Correction: Improving {L}1-influenced research writing in {E}nglish using pre-trained encoder-decoder models",
    author = "Zomer, Gustavo  and
      Frankenberg-Garcia, Ana",
    booktitle = "Findings of the Association for Computational Linguistics: EMNLP 2021",
    month = nov,
    year = "2021",
    address = "Punta Cana, Dominican Republic",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.findings-emnlp.216",
    pages = "2534--2540",
    abstract = "In this paper, we present a new method for training a writing improvement model adapted to the writer{'}s first language (L1) that goes beyond grammatical error correction (GEC). Without using annotated training data, we rely solely on pre-trained language models fine-tuned with parallel corpora of reference translation aligned with machine translation. We evaluate our model with corpora of academic papers written in English by L1 Portuguese and L1 Spanish scholars and a reference corpus of expert academic English. We show that our model is able to address specific L1-influenced writing and more complex linguistic phenomena than existing methods, outperforming what a state-of-the-art GEC system can achieve in this regard. Our code and data are open to other researchers.",
}
```
