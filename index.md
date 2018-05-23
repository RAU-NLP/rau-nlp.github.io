
# Natural Language Processing
Российско-Армянский Университет, II семестр 2017-2018 уч. года

[Учебный план](https://docs.google.com/document/d/1VlCBWiRffkS78M4oDUxcQPGt9QDg6eiyVeQ2tvsMoMs/view)

Урок: средам, часы 10:45 – 11:30 и 11:35 – 12:20  
Часы открытой двери: по субботам, по заказу

Пожалуйста, присоединитесь к списку <https://groups.google.com/group/rau-nlp-2017-2018-ii>

Можете также присоединиться к каналу [Slack](https://rau-python.slack.com/messages/C94H2QBLG/) 

## Проекты

### d-lemma
*Lemmatisation using Deep Learning*, Tsolak Ghukasyan  
[github.com/tsolakghukasyan/d-lemma](https://github.com/tsolakghukasyan/d-lemma)

### Content Parsing
*Finding the main content of web pages*, Sargis Abrahamyan    
[github.com/sargisabrahamyan/contentparser](https://github.com/sargisabrahamyan/contentparser)

### Authorify
*Text author style reduction - identifying and applying style*, Harutyun Beybutyan  
[github.com/hbeybutyan/authorify](https://github.com/hbeybutyan/authorify)

### Misclassification detector
Harutyun Shmavonyan  
[github.com/harutyun3172800/Misclassification_detector](https://github.com/harutyun3172800/Misclassification_detector)

## уроки и задания

**I неделя**  
[Slides](https://docs.google.com/presentation/d/1HmLNAyfuXGqEEcEDDwXbz88StRuLv5ZgdTmWnGeolY4/view)  
Read [Norvig's spelling corrector](https://norvig.com/spell-correct.html)  
Try the [Google Cloud demo](https://cloud.google.com/natural-language/) (scroll down) and the [spaCy demo](https://demos.explosion.ai/displacy/?text=Pope%27s%20baby%20steps%20on%20gays)

**II неделя**  
[Slides](https://docs.google.com/presentation/d/1WKYJHSn2th1mLsQINxa9i6EI_93bLPahNj5TbIGhNU8/edit?view)  
Break a parser - install spaCy, find an example that breaks it, explain why

**III неделя**  
[Slides](https://docs.google.com/presentation/d/18UKH-lkMJxF0dqiZn4jSdH4AD6Um35V79D-m7TCe5Tc/view)   
Review NLP fundamentals ([tokens](https://en.wikipedia.org/wiki/Lexical_analysis), [lemmata](https://en.wikipedia.org/wiki/Lemma_(morphology)), surface forms, [n-grams](https://en.wikipedia.org/wiki/N-gram), [typology](https://en.wikipedia.org/wiki/Linguistic_typology))  
Play with [language](https://github.com/signaln/language) library `ngrams` module  
Play with [spaCy token attributes](https://spacy.io/api/token#attributes) like `lemma_`, `is_oov` and `pos_`

**IV неделя**  
[Slides](https://docs.google.com/presentation/d/1hxqh4g94p2O2mWHsk1qj7Ax_RD5uZhquwjFAxCEPpNk/view)  
Review NLP fundamentals for upcoming exam  

**V неделя**  
Exam I     
[Slides](https://docs.google.com/presentation/d/1jxqlF6cu2tbKis1nI--XAJNlsm64Y0lx_zNJRBOag2A/view)  

**VI неделя**  
[Slides](https://docs.google.com/presentation/d/1NMwroWNz-ZEz_d3ekAksrddOaHf8c6rxWAM6Udpz0Dc/view)  
Visualise word embeddings at [projector.tensorflow.org](http://projector.tensorflow.org/) or [anvaka.github.io/pm/#/galaxy/word2vec-wiki](https://anvaka.github.io/pm/#/galaxy/word2vec-wiki?cx=1454&cy=502&cz=2037&lx=0.1092&ly=-0.3779&lz=0.0449&lw=0.9183&ml=300&s=1.75&l=1&v=d50_clean_small)  
Assignment:  
Download the [Amazon Reviews sentiment dataset](https://www.kaggle.com/bittlingmayer/amazonreviews)  
Clone and build [fastText](https://fasttext.cc/docs/en/support.html#building-fasttext)  
Email your models and any pre-processing script to the instructor, and email your score and training time to the group

**VII неделя**  
[Slides](https://docs.google.com/presentation/d/1Yl8Ayb5CkP6DTipjUBPfaw7IVMKoAVwzUuAdJHkg7ww/view)  
Think about [project ideas](https://docs.google.com/presentation/d/135eKtGlWQReBq7L_L3BlKAPJwcW-T6ITkMxyE53sYBU/view)
Assignment:  
Train a fastText model to distinguish between three languages written in the same alphabet (for example English, Spanish and Russian translit), see [fasttext.cc/blog/2017/10/02/blog-post.html](https://fasttext.cc/blog/2017/10/02/blog-post.html)

**VIII неделя**  
[Slides](https://docs.google.com/presentation/d/1lCSkq6l1mAoLGcwf5KYEWUoTIGW7bNVRa-VvSrFkUOI/view)  
Look at Twitter lang id eval [blog post](https://blog.twitter.com/engineering/en_us/a/2015/evaluating-language-identification-performance.html), fastText lang id [blog post](https://fasttext.cc/blog/2017/10/02/blog-post.html), YerevaNN translit [blog post](https://yerevann.github.io/2016/09/09/automatic-transliteration-with-lstm/), spaCy sense2vec [blog post](https://explosion.ai/blog/sense2vec-with-spacy) and [demo](https://github.com/explosion/sense2vec-demo), spaCy adding a language [instructions](https://spacy.io/usage/adding-languages) and [blog post](https://explosion.ai/blog/german-model), Quora question pairs [challenge](https://www.kaggle.com/c/quora-question-pairs), NYU [Winograd Schema Challenge](https://en.wikipedia.org/wiki/Winograd_Schema_Challenge) and [rules and dataset](https://cs.nyu.edu/faculty/davise/papers/WinogradSchemas/WS.html)

**IX неделя**  
Quiz I  
[Slides](https://docs.google.com/presentation/d/19xDaRa-w1J-y--PJInpBVm_Itg1JEfXftpicRv9NDZs/view)  
Write project proposal according to the [project proposal guidelines](https://rau-nlp.github.io/files/project-proposal.html)  
Submit a link to the git repo with the proposal to the class mailing list  
Reading on seq2seq: [github.com/google/seq2seq](https://github.com/google/seq2seq), [Tensorflow tutorial](https://www.tensorflow.org/tutorials/seq2seq)

**X-XI неделя**  
YerevaNN guest lecturer  
[Slides](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture10.pdf) from Stanford CS 231N  
Experiment with char-RNNs on an interesting text corpus or even source code

**XII**  
[Notes](https://docs.google.com/document/d/13SBGoP2db5joPmWdg91k2OzBmZ-XTPSjmSiOMu31KJ0/view) on machine translation  
Project updates  
More reading: byte-pair encodings for deep learning as presented in [*Neural Machine Translation of Rare Words with Subword Units*] by Sennrich, Haddow and Birch

**XIII**  
Quiz II (by email)  
Project presentations (by email)  

**XIV**  
День победы

**XV**  
[nlpguide.github.io](https://nlpguide.github.io)  
[nlpguide.github.io/2017](https://nlpguide.github.io/2017)  

**XVI**  
How do industry giants build systems for the top 100-200 languages?  
NLP vs general DL: Who is Chomsky?  Who is Norvig?  Who is Manning?  Who is LeCun?  
[*On Chomsky and the Two Cultures of Statistical Learning*](http://norvig.com/chomsky.html) Norvig 2011  
[*Yann LeCun and Christopher Manning discuss Deep Learning and Innate Priors*
](https://www.youtube.com/watch?v=fKk9KhGRBdI) 2018

## Материалы

[*Linguistic Fundamentals for Natural Language Processing: 100 Essentials from Morphology and Syntax*](http://www.morganclaypool.com/doi/abs/10.2200/S00493ED1V01Y201303HLT020)  
June 2013  
Emily M. Bender, University of Washington  

[*Speech and Language Processing (3rd ed. draft)*](https://web.stanford.edu/~jurafsky/slp3/)  
October 2017 draft  
Dan Jurafsky, Stanford University  
James H. Martin, University of Colorado

[*A Primer on Neural Network Models for Natural Language Processing*](http://u.cs.biu.ac.il/~yogo/nnlp.pdf)  
2015 draft  
Yoav Goldberg, Bar-Ilan University  

