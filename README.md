# Indonesian NLP resources

## Language modeling

1. [Kompas online collection](http://ilps.science.uva.nl/ilps/wp-content/uploads/sites/6/files/bahasaindonesia/kompas.zip).
   This corpus contains [Kompas online](http://www.kompas.com/) news articles from 2001-2002. See
   [here](http://ilps.science.uva.nl/resources/bahasa/) for more info and citations.
1. [Tempo online collection](http://ilps.science.uva.nl/ilps/wp-content/uploads/sites/6/files/bahasaindonesia/tempo.zip).
   This corpus contains [Tempo online](https://www.tempo.co/) news articles from 2000-2002. See
   [here](http://ilps.science.uva.nl/resources/bahasa/) for more info and citations.
1. [OSCAR](https://traces1.inria.fr/oscar/#corpus). This large corpus contains articles from many sources crawled by
   [CommonCrawl](https://commoncrawl.org/) and extracted by [ALMAnaCH](https://team.inria.fr/almanach/). In total there are
   4B words tokens and 2B word types. (NOTE: Contains strong language, mostly coming from gambling sites.)
1. [Leipzig corpora collection](https://corpora.uni-leipzig.de/en?corpusId=ind_mixed_2013). Indonesian mixed corpus
   based on material from 2013. Sentences: 74,329,815 - Types: 7,964,109 - Tokens: 1,206,281,985. From news materials, randomly chosen websites, and Wikipedia dumps.
1. [CC-100](http://data.statmt.org/cc-100/). This large corpus contains articles from many sources crawled by [CommonCrawl](https://commoncrawl.org/) and extracted by [FAIR](https://github.com/facebookresearch). For Bahasa Indonesia, in total there are around 4.8B sentences and 6B sentence piece tokens. See [here](https://www.aclweb.org/anthology/2020.lrec-1.494.pdf) for more info and citations.
1. [IndoNLU Benchmark](https://www.indobenchmark.com/) A collective effort made by researchers and practitioners from Gojek, Institut Teknologi Bandung, HKUST, Universitas Multimedia Nusantara, Prosa.ai, and Universitas Indonesia.
They provide pre-trained BERT/ALBERT [language models](https://huggingface.co/indobenchmark)
that were trained on a large [corpus](https://storage.googleapis.com/babert-pretraining/IndoNLU_finals/dataset/preprocessed/dataset_all_uncased_blankline.txt.xz) of 4B words (250M sentences). They also create single-sentence and sentence-pair [datasets](https://github.com/indobenchmark/indonlu) for evaluating classification and sequence-tagging tasks.
1. [Indonesian News Corpus](https://data.mendeley.com/datasets/2zpbjs22k3/1).
   This corpus contains 150,466 news articles crawled from various Indonesian news portals from the second half of 2015.

## POS tagging

1. [IDN tagged corpus](https://github.com/famrashel/idn-tagged-corpus). This corpus contains
   10K sentences and 250K word tokens. The POS tags are annotated manually.

## Sentiment analysis

1. [Aspect and Opinion Terms Extraction for Hotel Reviews](https://github.com/jordhy97/final_project).
    The corpus consists of 5000 hotel reviews from [Airy](https://www.airyrooms.com/) (78K tokens) with 5 labels. The paper is available on [arXiv](https://arxiv.org/abs/1908.04899).
1. [Aspect-Based Sentiment Analysis](https://github.com/annisanurulazhar/absa-playground).
    A text classification resource for multi-label aspect categorization.

## Syntactic parsing

1. [Indonesian Treebank](https://github.com/famrashel/idn-treebank). This corpus contains 1K parsed
   sentences. (constituency parsing)
1. [UD Indonesian](https://github.com/UniversalDependencies/UD_Indonesian-GSD). This corpus is
   provided by [Universal Dependencies](http://universaldependencies.org/). Training, development,
   and testing split are already provided. (dependency parsing)

## Machine translation

1. [OPUS (Open Parallel Corpus)](http://opus.nlpl.eu/). This site contains parallel corpora of Indonesian and other languages
   based on openly available resources (e.g., OpenSubtitles).
1. [IDENTICv1.0](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0005-BF85-F?show=full) [[paper](http://www.lrec-conf.org/proceedings/lrec2012/pdf/644_Paper.pdf)].
    Indonesian (ID)-English (EN). 45k sentences/~1M tokens (ID). Domain: science, sport, international, economy, news article, movie subtitle. It may overlap with PANL10N corpus. The dataset has versions with raw and tokenized sentences, and in CoNLL format.
1. [IWSLT2017](https://wit3.fbk.eu/mt.php?release=2017-01-more)         [[paper](https://wit3.fbk.eu/papers/WIT3-EAMT2012.pdf)].
    ID-EN. ~100K sentences. TEDtalk subtitles (spoken language).
    NOTE: the test set tst2017-plus provided contains a small part of the train data (as mentioned [here](https://www.aclweb.org/anthology/P19-2043.pdf)).
1. [Asian Language Treebank](http://www2.nict.go.jp/astrec-att/member/mutiyama/ALT/) [[paper](http://www2.nict.go.jp/astrec-att/member/mutiyama/ALT/ALT-Parallel-Corpus-20171201/ALT-O-COCOSDA.pdf)].
    ID, EN, and some Asian languages (mostly South East Asian). 20K sentences. Domain: News.

## Word normalization

1. [Colloquial Indonesian Lexicon](https://github.com/nasalsabila/kamus-alay).
    This lexicon consists of 3592 unique colloquial tokens that are mapped onto 1742 unique lemmas. The full description of this lexicon can be seen in the [paper](https://ieeexplore.ieee.org/abstract/document/8629151).

## Text summarization

1. [IndoSum](https://github.com/kata-ai/indosum).
    A collection of 20K online news article-summary pairs belonging to 6 categories and 10 sources.
    It has both abstractive summaries and extractive labels.

## Text classification

1. [SMS Spam](https://drive.google.com/file/d/1-stKadfTgJLtYsHWqXhGO3nTjKVFxm_Q/view).
   This corpus contains 1143 sentences that have been labeled with normal message, fraud, promotion. It is provided by Yudi Wibisono
1. [Hate Speech Detection](https://github.com/ialfina/id-hatespeech-detection).
    This dataset consists of 713 tweets in the Indonesian language with 453 non hate speech and 260 hate speech tweets.
1. [Abusive Language Detection](https://github.com/okkyibrohim/id-abusive-language-detection).
    A collection of tweets for abusive language detection in Indonesian social media. It consists of two types of labeling, abusive/not abusive and not abusive/abusive but not offensive/offensive. It also has its own colloquial Indonesian lexicon.

## Speech recognition

1. [TITML-IDN speech corpus](http://research.nii.ac.jp/src/en/TITML-IDN.html).
   The corpus contains 20 speakers (11 male and 9 female), where each of the speaker speaks 343 utterances.
   The utterances are phonetically balanced.
   The corpus itself is free to use for academic/non-commercial usage, but interested party should make a formal request via email to the institution.
   The procedure is listed [here](http://research.nii.ac.jp/src/en/register.html).
1. [Indonesian Speech Recognition](https://github.com/frankydotid/Indonesian-Speech-Recognition).
   A small corpus of 50 utterances by a single male speaker. Disclaimer: This is a school project, do not use it for any important tasks. The author is not responsible for the undesired results of using the data provided here.
1. [CMU Wilderness Multilingual Speech Dataset](https://github.com/festvox/datasets-CMU_Wilderness).
   A dataset of over 700 different languages providing audio, aligned texts, and word pronunciations.
   One of the languages is Indonesian. The utterances are from the bible, which is recorded by [bible.is](bible.is).

## Paraphrase identification

1. [Translated PAWS](https://github.com/Wikidepia/indonesia_dataset/tree/master/paraphrase/PAWS).
   This dataset is a translation of [PAWS](https://github.com/google-research-datasets/paws). The dataset is translated using Google Translate
   and contains 100K human-labeled data that feature the importance of modeling structure, context, and word order information for the problem
   of paraphrase identification.
