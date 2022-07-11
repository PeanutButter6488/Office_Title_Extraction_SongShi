# Office Title Extraction

Name: Ding Zhang
Duration: 2021.12 - 2022.7
Instructor: [Prof.Song Chen](https://www.bucknell.edu/fac-staff/song-chen)

## Description:

This project aims to extract office titles from traditional Chinese texts. 
We purpose an hypothesis that when translating from traditional Chinese texts into modern Chinese, **named entities** (names, addresses, and office titles) will tend to be left unchanged. This [corpus](https://github.com/NiuTrans/Classical-Modern) is a parallel corpus: it contains source files (original Chinese texts) as well as their corresponding target files (translations). Based on this assumption, we have applied [ctext](https://ctext.org/)'s **N-gram** analysis to extract named entities. But N-gram analysis can only extract exactly same words between the two files, which inevitably contains plenty of noise. 
In this project, we have applied algorithms that significantly reduced the amount of noise in order to obtain meaningful office titles. We compared our results with [CBDB](https://github.com/cbdb-project/named-entities-for-premodern-chinese-history-research) to guarantee office titles extracted. 

## Citations:

1. https://github.com/cbdb-project/named-entities-for-premodern-chinese-history-research
2. https://github.com/NiuTrans/Classical-Modern
3. https://ctext.org/
4. https://github.com/stopwords-iso/stopwords-zh

