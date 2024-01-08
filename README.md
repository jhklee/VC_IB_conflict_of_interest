# VC_IB_conflict_of_interest
I present the entire code for my paper "IPO underwriter’s conflict of interest: When IPO underwriter has stake of the issuer"

In this project I use 4 main datasets. Securities Data Corporation(SDC) Corporate New Issues database, Center for Research in Securities Prices (CRSP) daily stock files, Compustat, and PREQIN Pro. 

The order of my code is as bellow. 

1. Merge Preqin Pro data and SDC data. (DATA 1) \
   1.1. Fuzzy match the issuer in SDC and the firm in Preqin Pro. \
   1.2. Fuzzy match the underwriter in SDC and the investor in Preqin Pro.
   1.3. Handmatch the underwriter in SDC and the investor in Preqin Pro.
2. Merge CRSP daily stock files with Compustat using CCM table. (DATA 2)
3. Add buy and hold longterm return by merging DATA 1 and DATA 2.
4. Calculte the exccess return which is the buy-and-hold return of the portfolio of firms within each industry.
5. Report results in Latext formate. (summary statistics, regression analysis, and difference and difference analysis)
