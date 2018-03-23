
## Natural Language Processing
Российско-Армянский Университет

#### II семестр 2017-2018 уч. года

[Учебный план](https://docs.google.com/document/d/1VlCBWiRffkS78M4oDUxcQPGt9QDg6eiyVeQ2tvsMoMs/view)

Урок: средам, часы 10:45 – 11:30 и 11:35 – 12:20  
Часы открытой двери: по субботам, по заказу

Пожалуйста, присоединитесь к списку <https://groups.google.com/group/rau-nlp-2017-2018-ii>

Можете также присоединиться к каналу [Slack](https://rau-python.slack.com/messages/C94H2QBLG/) 


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
Exam    
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

#### Материалы

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
