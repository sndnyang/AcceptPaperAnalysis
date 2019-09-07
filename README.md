# AcceptPaperAnalysis

Statistics and Visualization of main keyword of accepted papers (NeurIPS 2019)

Inspired by [`ICLR2019-OpenReviewData`](https://github.com/shaohua0116/ICLR2019-OpenReviewData) and [`CVPR-Paper-Statistics`](https://github.com/hoya012/CVPR-2019-Paper-Statistics). I mainly use the code from latter one.

The difference is that I don't use selenium for crawler. I just use requests and BeautifulSoup4 which are a bit simpler but don't support javascript.

TODO:

1. other conferences url and pattern. it should be easy.
2. ratings. I'm not sure if the rates will be public.

![NIPS2019](https://github.com/sndnyang/AcceptPaperAnalysis/raw/master/images/neuips2019.png)

## Acceptance rate

## Paper Keywords statistics

## Analysis and Visualization Code (Jupyter Notebook)

The above data can be obtained from a analysis jupyter notebook script.

I have gotten the json file.

Prerequisites

+ python3.5
+ request
+ bs4
+ nltk
+ wordcloud
+ matplotlib

or

i highly recommend to use [google colab](https://colab.research.google.com/)

Just download jupyter notebook and move to your google drive and Open with Colaboratory