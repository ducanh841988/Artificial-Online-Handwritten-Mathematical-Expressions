# Artifficial-Online-Handwritten-Mathematical-Expressions
This is artificial online handwritten mathematical expressions generated from CROHME database.
The pupose of this project is that generate a large online handwritten mathematical expressions database from the existed database (CROHME). Please refer to our paper:   
1. [Anh Duc Le and Masaki Nakagawa: Training an End-to-End System for Handwritten Mathematical Expression Recognition by Generated Patterns. Proc. of ICDAR 2017, pp. 1056-1061, Kyoto, Japan (11.2017).](http://web.tuat.ac.jp/~nakagawa/pub/2017/pdf/ICDAR2017-(Training_an_End-to-End_System_for_Handwritten_Mathematical_expressions_by_generated_patterns).pdf)   
2. Anh Duc Le, Bipin Indurkhya, and Masaki Nakagawa: Pattern generation strategies for improving recognition of Handwritten Mathematical Expressions. (under review)   https://arxiv.org/abs/1901.06763
We generated 3 new datasets: CROHME_DISTORTION, CROHME_DECOMPOSITION, CROHME_HYBRID   
The number of equation in each dataset is shown in below:   

|   dataset|CROHME    | CROHME_DISTORTION| CROHME_DECOMPOSITION| CROHME_HYBRID |   
|---|---|---|---|---|   
|  # of MEs | 8,835  |53,010   | 32,884  | 197,304  |   
|  Accuracy on Testing 2014(%) | 39.76  |41.48   | 47.67  | 48.78  |   
|  Accuracy on Testing 2016(%) | 36.27  |37.14   | 42.63  | 45.60  |   

# Format:
The dataset contains image folder and annotation files. The format of annotation files is as follows:   
[image_file] [target latex]   
target latex is normalized and inserted space between latex codes.   

Example:   
rit_42165_2.png \sin [ a + b ] = \sin a \cos b + \cos a \sin b   
rit_42170_0.png x ^ { 4 } - 4 x ^ { 3 } - 1 4 x ^ { 2 } - 4 x + 1   
rit_42170_1.png x ^ { 4 } - 4 x ^ { 2 } + 2 + \sqrt { 2 }   
rit_42170_2.png \sin [ x + y ] = [ \sin x \cos y + \cos x \sin y ]   
 
# Terms of Use:
This dataset is licensed under a [Attribution-NonCommercial-ShareAlike 3.0 Unported (CC BY-NC-SA 3.0) License](https://creativecommons.org/licenses/by-nc-sa/3.0/deed.en)   
# Download 
http://bit.ly/2E7H8tX
Please send me an email if you have any question.   
leducanh841988@gmail.com
