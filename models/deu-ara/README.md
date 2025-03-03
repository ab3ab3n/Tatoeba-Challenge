# opus-2020-09-10.zip

* dataset: opus
* model: transformer
* source language(s): deu
* target language(s): afb apc ara arq arz
* model: transformer
* pre-processing: normalization + SentencePiece (spm32k,spm32k)
* a sentence initial language token is required in the form of `>>id<<` (id = valid target language ID)
* download: [opus-2020-09-10.zip](https://object.pouta.csc.fi/Tatoeba-MT-models/deu-ara/opus-2020-09-10.zip)
* test set translations: [opus-2020-09-10.test.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/deu-ara/opus-2020-09-10.test.txt)
* test set scores: [opus-2020-09-10.eval.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/deu-ara/opus-2020-09-10.eval.txt)

## Benchmarks

| testset               | BLEU  | chr-F |
|-----------------------|-------|-------|
| Tatoeba-test.deu.ara 	| 17.8 	| 0.486 |







# opus-2021-02-23.zip

* dataset: opus
* model: transformer
* source language(s): deu
* target language(s): afb apc ara arq arz
* model: transformer
* pre-processing: normalization + SentencePiece (spm32k,spm32k)
* a sentence initial language token is required in the form of `>>id<<` (id = valid target language ID)
* valid language labels: >>ara<< >>ara_Latn<< >>arq<< >>arz<<
* download: [opus-2021-02-23.zip](https://object.pouta.csc.fi/Tatoeba-MT-models/deu-ara/opus-2021-02-23.zip)
* test set translations: [opus-2021-02-23.test.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/deu-ara/opus-2021-02-23.test.txt)
* test set scores: [opus-2021-02-23.eval.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/deu-ara/opus-2021-02-23.eval.txt)

## Benchmarks

| testset | BLEU  | chr-F | #sent | #words | BP |
|---------|-------|-------|-------|--------|----|
| Tatoeba-test.deu-afb 	| 7.5 	| 0.357 	| 5 	| 24 	| 0.867 |
| Tatoeba-test.deu-apc 	| 11.0 	| 0.225 	| 2 	| 6 	| 1.000 |
| Tatoeba-test.deu-ara 	| 17.8 	| 0.486 	| 1209 	| 6324 	| 0.967 |
| Tatoeba-test.deu-arq 	| 0.0 	| 0.514 	| 1 	| 4 	| 0.717 |
| Tatoeba-test.deu-arz 	| 12.8 	| 0.360 	| 2 	| 6 	| 1.000 |


# opusTCv20210807-2021-10-22.zip

* dataset: opusTCv20210807
* model: transformer-align
* source language(s): deu
* target language(s): afb apc ara arq arz
* raw source language(s): deu
* raw target language(s): afb apc ara arq arz
* model: transformer-align
* pre-processing: normalization + SentencePiece (spm32k,spm32k)
* a sentence initial language token is required in the form of `>>id<<` (id = valid target language ID)
* valid language labels: 
* download: [opusTCv20210807-2021-10-22.zip](https://object.pouta.csc.fi/Tatoeba-MT-models/deu-ara/opusTCv20210807-2021-10-22.zip)
* test set translations: [opusTCv20210807-2021-10-22.test.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/deu-ara/opusTCv20210807-2021-10-22.test.txt)
* test set scores: [opusTCv20210807-2021-10-22.eval.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/deu-ara/opusTCv20210807-2021-10-22.eval.txt)

## Benchmarks

| testset | BLEU  | chr-F | #sent | #words | BP |
|---------|-------|-------|-------|--------|----|
| Tatoeba-test-v2021-08-07.deu-ara 	| 22.9 	| 0.519 	| 1208 	| 6323 	| 1.000 |

