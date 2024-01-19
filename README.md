# SIR

## День 1

[Тест](https://forms.gle/GoyBXXhZoMLRMqHn8) \
[Слайды](https://drive.google.com/file/d/1IcUxNHQXTq95t22ifQjz25zELyC-imKu/view?usp=drive_link) \


### Установка R, RStudio и tidyverse

R \
https://cran.rstudio.com/ 

RStudio \
https://posit.co/download/rstudio-desktop/

install.packages('tidyverse')



### Данные 

Palmer Archipelago (Antarctica) penguin data 
[csv](day_1/pen.csv) \
[xlsl](day_1/pen.xlsx)

## День 2

Код за первый и второй дни \
[код](https://drive.google.com/file/d/1-rvv18X4_mQRPFB7AGf31BAigVMt0Wp-/view?usp=drive_link)

## День 3

[Тест](https://forms.gle/a2dgQFz3VxA6FEXx6) \
[Слайды](https://drive.google.com/file/d/1ShbQdLotbEyXouvxprDBXbNNfndQk_Xm/view?usp=drive_link) \
[Шпаргалки](https://drive.google.com/drive/folders/1HUZpQ134Lslgwk6PyDCx8kWG-y-M1fqP?usp=drive_link)

### DADA2

[установка](https://benjjneb.github.io/dada2/dada-installation.html) \
[туториал](https://benjjneb.github.io/dada2/tutorial.html)

### Датасет "Пулково"

[сырые прочтения](https://drive.google.com/drive/folders/1aPG0GG-GavigjMnm24rXRXshLe_QicmQ?usp=drive_link) \
[Silva - основная база](https://drive.google.com/file/d/17nyri0PXN-DxyR-j4Czqd6Xs0rGAU2hS/view?usp=drive_link) \
[Silva - виды](https://drive.google.com/file/d/1FHfrlQjzbKXGVDIIvbRdgfIJpprSniaG/view?usp=drive_link) \
[Папка с промежуточными переменными, если у кого-то не хватит оперативной памяти](https://drive.google.com/drive/folders/1tef4_nzs_70JGtbfjn4TLzPKURyQCl4y?usp=drive_link) \
[метаданные](day_3/map.csv)

Библиотеки с которыми сы сегодня будем работать:
- dada2
- phyloseq


## День 4-5

Код по работе с phyloseq \
[код](day_4/pulkovo.html) \
[Слайды](https://drive.google.com/file/d/1QN5PWtlcIVRnw89zFDMYg-dm2fSyUQaT/view?usp=drive_link)

Полный датасет по Пулково \
[ps.ff](day_4/ps.ff) \
Функция bargraph.R \
[bargraph.R](day_4/bargraph.R) 

Установка пакетов: 
- ggpubr есть в CRAN \
- ampvis2 надо ставить из гитхаба:

install.packages(“remotes”) \
remotes::install_github(“kasperskytte/ampvis2”)

Дополнительно 

QIIME 2 - базовый туториал: \
[ссылка](https://docs.qiime2.org/2023.9/tutorials/moving-pictures/) 
ampvis2 - библиотека для визуализации: \
[ссылка](https://kasperskytte.github.io/ampvis2/articles/ampvis2.html)
phyloseq - визуализация и организация даннных: \
[ссылка](https://kasperskytte.github.io/ampvis2/articles/ampvis2.html)
Приятный курс - глава где написано как статистически сравнивать представленность: \
[ссылка](https://microbiome.github.io/course_2021_radboud/differential-abundance-analysis.html) \
vegan - статистика для экологии, много отдельных материалов, phyloseq работает на его базе \
[ссылка](https://cloud.r-project.org/web/packages/vegan/vignettes/FAQ-vegan.html)

