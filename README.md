# IPO underwriter’s conflict of interest: When IPO underwriter has stake of the issuer
I present the entire code for my paper "IPO underwriter’s conflict of interest: When IPO underwriter has stake of the issuer"

[Link for the latest version](https://utexas.box.com/s/inhpuzf7pvf7fum577v656q6k8jud1ji)

In this project I use 4 main datasets. Securities Data Corporation(SDC) Corporate New Issues database, Center for Research in Securities Prices (CRSP) daily stock files, Compustat, and PREQIN Pro. 

The order of my code is as bellow. 

1. Merge Preqin Pro data and SDC data. (DATA 1) \
   1.1. Fuzzy match the issuer in SDC and the firm in Preqin Pro. -[code](https://colab.research.google.com/drive/1jS_ZOPAAP9xpJwvBPWpNdAgAABwrKI4D?usp=sharing)\
   1.2. Fuzzy match the underwriter in SDC and the investor in Preqin Pro. -[code](https://colab.research.google.com/drive/1awNaIS0KPI75l2Wpa_EiUh20f6frixV-?usp=sharing) \
   1.3. Handmatch the underwriter in SDC and the investor in Preqin Pro. -[code](https://colab.research.google.com/drive/1naSiZHPwQkNHoH4U6H1j0HgjblQvTXzO?usp=sharing)
2. Merge CRSP daily stock files with Compustat using CCM table. (DATA 2) -[code](https://colab.research.google.com/drive/1x0dSyxAJHsbaI6tAlEo_rlgO829GxLKJ?usp=sharing)
3. Add buy and hold longterm return by merging DATA 1 and DATA 2. -[code](https://colab.research.google.com/drive/15friTw3M9IrWmCeUrl4IBL53iCNhxlRx?usp=sharing)
4. Calculte the exccess return which is the buy-and-hold return of the portfolio of firms within each industry. -[code](https://colab.research.google.com/drive/15u2N_UNUvx7J8tFD0XG3BEcbSU-lLLyU?usp=sharing)
5. Report results in Latext formate. (summary statistics, regression analysis, and difference and difference analysis) -[code](https://colab.research.google.com/drive/1OUyQ_f3IN0ikXCs2DWWTAS0_8xy2xwXI?usp=sharing)

[Link for the final merged data](https://utexas.box.com/s/6qas4sbnsl9grgkucbarttusg47knoke)
