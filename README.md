# NLP-style-transfer
4nd course, the graduation paper

### About
Solving style transfer ploblem with GAN. 

> Generator - Autoencoder Seq2Seq with style embedding

> Discriminators - 1-layer CNN with some filters

This work relies on researches 
1. [Style Transfer from Non-Parallel Text by Cross-Alignment](https://arxiv.org/abs/1705.09655)
2. [Generate Modern Chinese Poems from News Based on Text Style Transfer Using GAN](https://ieeexplore.ieee.org/document/8959907)

### GAN architecture
![](.no_progr_stuff/GAN_model.jpg)

## How to run

## Data
 I have used 2 styles - poems and news.
#### datasets
#### preprocessing

## Samples
### news to poem
*рождественские ели которые украшали дома большинства жителей вены будут сожжены на биоэлектростанции в зиммеринге 
километров от австрийской столицы и сослужат последнюю службу людям подарив им тепло .*
______________________________________


*рождественские ели мы украшали*

*дома и вены будут сожжены напополам*

*мы вдвоем*

*огонь от страсти столицы*

*сослужит лишь подарив им все тепло .*

### poem to news
*фотограф как то раз меня снимая*

*на фоне ослепительного дня*

*случайно проронил что роковая*

*на самом деле внешность у меня .*
______________________________________

*фотограф словом то раз недалеко снимаяльного на фоне дорожностроительного дня. в декабре столице решение что что роковая на на самом деле внешность у минздрав*
