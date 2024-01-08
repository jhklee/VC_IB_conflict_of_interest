# IPO underwriter’s conflict of interest: When IPO underwriter has stake of the issuer
I present the entire code for my paper "IPO underwriter’s conflict of interest: When IPO underwriter has stake of the issuer"

[Link for the latest version](https://utexas.box.com/s/inhpuzf7pvf7fum577v656q6k8jud1ji)

In this project I use 4 main datasets. Securities Data Corporation(SDC) Corporate New Issues database, Center for Research in Securities Prices (CRSP) daily stock files, Compustat, and PREQIN Pro. 

The order of my code is as bellow. 

1. Merge Preqin Pro data and SDC data. (DATA 1) \
   1.1. Fuzzy match the issuer in SDC and the firm in Preqin Pro. [Code 1](https://drive.google.com/file/d/1IU726GZKpfljCQotqUk9ngEUeqEPhuiP/view?usp=sharing) \
   1.2. Fuzzy match the underwriter in SDC and the investor in Preqin Pro. [Code 2](https://drive.google.com/file/d/1o4sISSRj2Zz0LH7UiL1_gJVUJOJNn26g/view?usp=sharing) \
   1.3. Handmatch the underwriter in SDC and the investor in Preqin Pro. [Code 3](https://drive.google.com/file/d/1gHdXGK7ztvIEFpXpfljfqc0SqAhHc2G0/view?usp=sharing)
2. Merge CRSP daily stock files with Compustat using CCM table. (DATA 2) [Code 4](https://drive.google.com/file/d/1-cgV9gkPq4xvnLYyOV1tlujqgVDvVqGE/view?usp=sharing)
3. Add buy and hold longterm return by merging DATA 1 and DATA 2. [Code 5](https://drive.google.com/file/d/13VrLG9uEBQ2kCwARzzuZ-ICJX6R2GW-u/view?usp=sharing)
4. Calculte the exccess return which is the buy-and-hold return of the portfolio of firms within each industry. [Code 6](https://drive.google.com/file/d/1PTHgeXhFMs5Vdx-3_SjujDxiVo9Me5B8/view?usp=sharing)
5. Report results in Latext formate. (summary statistics, regression analysis, and difference and difference analysis) [Code 7](https://drive.google.com/file/d/1y6V9-nvXuBUbdHFeO_S7jpM8rTk_xbbR/view?usp=sharing)
