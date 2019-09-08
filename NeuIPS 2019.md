# NeurIPS 2019

Statistics and Visualization of main keyword of accepted papers (NeurIPS 2019)

Inspired by [`ICLR2019-OpenReviewData`](https://github.com/shaohua0116/ICLR2019-OpenReviewData) and [`CVPR-Paper-Statistics`](https://github.com/hoya012/CVPR-2019-Paper-Statistics). I mainly use the code from latter one.

The difference is that I don't use selenium for crawler. I just use requests and BeautifulSoup4 which are a bit simpler but don't support javascript.

TODO:

1. other conferences url and pattern. it should be easy.
2. ratings. I'm not sure if the rates will be public.

![NIPS2019](https://github.com/sndnyang/AcceptPaperAnalysis/raw/master/images/neuips2019.png)

## Acceptance rate

Accepted papers: 1429
Total submission: 6743

Acceptance rate: 21.24%

TODO: visualization of recent years

## Paper statistics

### Paper Keywords statistics

![NIPS2019](https://github.com/sndnyang/AcceptPaperAnalysis/raw/master/images/neuips2019_stat.png)

### Paper Institutes statistics

All authors:

![NIPS2019](https://github.com/sndnyang/AcceptPaperAnalysis/raw/master/images/neuips2019_all_ins.png)

First authors:

![NIPS2019](https://github.com/sndnyang/AcceptPaperAnalysis/raw/master/images/neuips2019_first_ins.png)

### Paper Nationality statistics

TODO: Guess the nationality of authors

## Analysis and Visualization Code (Jupyter Notebook)

The above data can be obtained from a analysis jupyter notebook script.

I have gotten the json file.
