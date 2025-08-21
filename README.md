# About

This is the Appendix of the RANLP2025 conference paper _Instruction Finetuning to Attribute Language Stage, Dialect and Provenance Region to Historical Church Slavic Texts_ by P. Lendvai, U. Reichel, A. Jouravel, A. Rabus, and E. Renje.


## Appendix 

The plots provide details about
- the performance of the instruction finetuned model
- sentence length distributions in the input data.

Click on an image to view it full size.

### Confusion matrices

#### Language Stage

Confusion matrices for Language Stage labeling by the finetuned model on the clean test set (top) and on the noisy set (bottom). ECS: Early Church Slavic, LCS: Late Church Slavic, MCS: Middle Church Slavic.

<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/confusion_matrices/noncorrupted_texts/cm-language.png" width="400">
<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/confusion_matrices/corrupted_texts/cm-language.png" width="400">

#### Dialect

Confusion matrices for Dialect labeling by the finetuned model on the clean test set (top) and on the noisy set (bottom). ED: Eastern Dialect, SD: Southern Dialect.

<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/confusion_matrices/noncorrupted_texts/cm-dialect.png" width="400">
<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/confusion_matrices/corrupted_texts/cm-dialect.png" width="400">

#### Region 

Confusion matrices for Region labeling by the finetuned model on the clean test set (top) and on the noisy set (bottom). BulR: Bulgaria, KyRusR: Kyivan Rus', MacR: Macedonia, MacSerR: Macedonia/Serbia, MusR: Muscovy, NovgR: Novgorod, SerR: Serbia, SouRusR: South of Rus', SuzR: Suzdal.

<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/confusion_matrices/noncorrupted_texts/cm-region.png" width="400">
<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/confusion_matrices/corrupted_texts/cm-region.png" width="400">

#### Joint Language stage and Dialect

Confusion matrices for joint Language stage and Dialect labeling by the finetuned model on the clean test set (top) and on the noisy set (bottom). ECS: Early Church Slavic, LCS: Late Church Slavic, MCS: Middle Church Slavic; ED: Eastern Dialect, SD: Southern Dialect.

<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/confusion_matrices/noncorrupted_texts/cm-language-dialect.png" width="400">
<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/confusion_matrices/corrupted_texts/cm-language-dialect.png" width="400">

#### Joint Language stage, Dialect, and Region

Confusion matrices for joint Language stage, Dialect, and Region labeling by the finetuned model on the clean test set (top) and on the noisy set (bottom). ECS: Early Church Slavic,  LCS: Late Church Slavic, MCS: Middle Church Slavic; ED: Eastern Dialect, SD: Southern Dialect, BulR: Bulgaria, KyRusR: Kyivan Rus', MacR: Macedonia, MacSerR: Macedonia/Serbia, MusR: Muscovy, NovgR: Novgorod, SerR: Serbia, SouRusR: South of Rus', SuzR: Suzdal.

<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/confusion_matrices/noncorrupted_texts/cm-label.png" width="400">
<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/confusion_matrices/corrupted_texts/cm-label.png" width="400">


###  Precision, Recall, and F-scores

####  Language stage 

Precision, Recall, and F-scores for Language stage labeling by the finetuned model on the clean test set (top) and on the noisy set (bottom). ECS: Early Church Slavic,  LCS: Late Church Slavic, MCS: Middle Church Slavic.

<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/performance_barplots/noncorrupted_texts/bar-language.png" width="400">
<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/performance_barplots/corrupted_texts/bar-language.png" width="400">


####  Dialect

Precision, Recall, and F-scores for Dialect labeling by the finetuned model on the clean test set (top) and on the noisy set (bottom).  ED: Eastern Dialect, SD: Southern Dialect.

<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/performance_barplots/noncorrupted_texts/bar-dialect.png" width="400">
<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/performance_barplots/corrupted_texts/bar-dialect.png" width="400">


####  Region

Precision, Recall, and F-scores for Region labeling by the finetuned model on the clean test set (top) and on the noisy set (bottom). BulR: Bulgaria, KyRusR: Kyivan Rus', MacR: Macedonia, MacSerR: Macedonia/Serbia, MusR: Muscovy, NovgR: Novgorod, SerR: Serbia, SouRusR: South of Rus', SuzR: Suzdal.

<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/performance_barplots/noncorrupted_texts/bar-region.png" width="400">
<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/performance_barplots/corrupted_texts/bar-region.png" width="400">


####  Language stage and Dialect

Precision, Recall, and F-scores for joint Language stage and Dialect labeling by the finetuned model on the clean test set (top) and on the noisy set (bottom). ECS: Early Church Slavic,  LCS: Late Church Slavic, MCS: Middle Church Slavic; ED: Eastern Dialect, SD: Southern Dialect.

<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/performance_barplots/noncorrupted_texts/bar-language-dialect.png" width="400">
<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/performance_barplots/corrupted_texts/bar-language-dialect.png" width="400">


####  Language stage, Dialect, and Region

Precision, Recall, and F-scores for joint Language stage, Dialect, and Region prediction by the finetuned model on the clean test set (top) and on the noisy set (bottom). ECS: Early Church Slavic,  LCS: Late Church Slavic, MCS: Middle Church Slavic;  ED: Eastern Dialect, SD: Southern Dialect; BulR: Bulgaria, KyRusR: Kyivan Rus', MacR: Macedonia, MacSerR: Macedonia/Serbia, MusR: Muscovy, NovgR: Novgorod, SerR: Serbia, SouRusR: South of Rus', SuzR: Suzdal.

<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/performance_barplots/noncorrupted_texts/bar-label.png" width="400">
<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/performance_barplots/corrupted_texts/bar-label.png" width="400">


###  Sentence length distributions 

####  Early Church Slavic datasets

Sentence length distributions in Early Church Slavic datasets. _x_ axis: words per snippet, _y_ axis: probability density.

<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/sentence_length_density_plots/lenprioel.png" width="400">
<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/sentence_length_density_plots/lenlepra.png" width="400">
<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/sentence_length_density_plots/lencyril.png" width="400">

####  Middle Church Slavic datasets

Sentence length distributions in Middle Church Slavic datasets. _x_ axis: words per snippet, _y_ axis: probability density.

<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/sentence_length_density_plots/lendion.png" width="400">
<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/sentence_length_density_plots/lentorot.png" width="400">
<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/sentence_length_density_plots/lenvmc.png" width="400">


####  Late Church Slavic datasets

Sentence length distributions in Late Church Slavic datasets. _x_ axis: words per snippet, _y_ axis: probability density.

<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/sentence_length_density_plots/lensluzheb.png" width="400">
<img src="https://github.com/pirolen/ranlp2025-churchslavic-ift/blob/main/pics/sentence_length_density_plots/leneliz.png" width="400">

