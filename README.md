# Douban Books: Early Results

[![License: GPL-3.0](https://img.shields.io/badge/License-GPL--3.0-D4A017.svg)](LICENSE)

Copyright (C) 2017 Jing Wang

Historical results collected from doulists, series, and tags, containing 34,636 books. Counts and ratings describe this snapshot, not the current Douban catalog.

Later results: [Douban-books-2020](https://github.com/yuzhounh/Douban-books-2020).  
2020-7-5 19:47:57

See the following 2017 snapshot: [Douban-books-2017](https://github.com/yuzhounh/Douban-books-2017).  
The 2017 snapshot contains 129,193 books, compared with 34,636 in this repository.  
2017-1-23 17:07:57

## Data sources

doulist, the doulists in notes: 601066353, 601066081, 601062791  
series, the series in notes: 601214234  
tag, hot tags  

## Books

Open the linked text files to browse the results. The filenames retain the original `GB2312` encoding label. `rating` is the Douban rating and `votes` is the number of ratings.

- [RV1](Books_RV1_GB2312.txt): rating>=9.0, votes>=1000,  number=884  
- [RV2](Books_RV2_GB2312.txt): rating>=8.0, votes>=300,   number=7969  
- [RV3](Books_RV3_GB2312.txt): rating>=8.5, votes>=0,     number=13462  
- [RV4](Books_RV4_GB2312.txt): rating>=8.0, votes>=10000, number=470  
- [RV5](Books_RV5_GB2312.txt): rating>=9.0, votes>=100,   number=3181  
- [RV6](Books_RV6_GB2312.txt): rating>=9.0, votes>=0,     number=5433  
- [high_score](Books_high_score_GB2312.txt), books with high integrated scores, number=3195  
- [sorted](Books_sorted_GB2312.txt), sorted by an integrated score, number=34636  
- [sorted_rating](Books_sorted_Rating_GB2312.txt), sorted by the rating, number=34636  

## Distribution

- [Rating](distribution_rating.pdf): the distribution of ratings when votes are larger than a certain threshold  
- [Score](distribution_score.pdf): the distribution of integrated scores when votes are larger than a certain threshold  
- [Votes by rating](distribution_votes_1_rating.pdf): the distribution of votes when ratings are in a certain range, only the smallest 80% votes are counted  
- [Votes by score](distribution_votes_2_score.pdf): the distribution of votes when integrated scores are in a certain range, only the smallest 90% votes are counted  

## Note

I think decentralization is a key feature of Douban and it is really valuable. The above results are provided only for your reference.   

## Related projects

- [Douban-books-2017](https://github.com/yuzhounh/Douban-books-2017): Later 2017 result snapshot containing 129,193 books.
- [Douban-books-2020](https://github.com/yuzhounh/Douban-books-2020): Historical 2020 results distributed as UTF-8 BOM CSV files.
- [douban-books-ranking](https://github.com/yuzhounh/douban-books-ranking): Newer standalone Python implementation with an online ranking and published JSON data.

## License

See [LICENSE](LICENSE) for the GNU General Public License v3.0.

## Contact

Jing Wang  
wangjing0@seu.edu.cn  
yuzhounh@163.com  
2017-1-9 20:30:25
