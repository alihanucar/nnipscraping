
# Investment Fund's Management Fees and AuM Values Scraping from NNIP Website

I prepared a python script which scrap the management fees and AuM values from NN IP Asset Management firm's website for analyze. Firstly i exported all of their investment funds datas from their website then i realized that their each investment fund's pages based on the fund's ISIN code. For example "en-INT/professional/funds/detail/LU2305828662" in this link if you change the ISIN numbers in the end then you get another fund. I was able to export ISIN codes to excel on their website then concat it each ISIN code with website link. Afterly, i create a python script which opens every single fund link and get management fees and aum values and store them in to the same excel sheet in new columns.
I appreciate of my homemate Erhan Tolek for helping me to find out javascript structure of the datas. Those numbers are all open source and don't hesitate to use the code for different kind of websites.

Update 06.02.2023:

NN IP acquired by Goldman Sachs Asset Management, links remain same but structure has changed. You can find the new version on the repository.

![Logo](https://upload.wikimedia.org/wikipedia/commons/2/2d/NNIP_Logo_4c_gro%C3%9F.jpg)

    
