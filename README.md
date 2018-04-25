#sql question

1.sales table

region counrty year_qtr sale_amout_usd
.....
NA      USA     2017_1   $10000
NA      CANADA  2017_1   $20000
NA      MEX     2017_1   $15000
NA      USA     2017_2   $20000
....
ASIA    CHN     2017_1   $10000
ASIA    INDIA   2017_1   $20000
....
EU
...

write sql
1) the countries of the top 3 sales amount of each region
2) the county of the 3rd highest sales amount over all (a without a)
3) the difference between the current quarter and previous quarter per country
4) the year to date sales sum and rolling avg per courtry

2.the daily_return table 
date       return_amt stock_code
1-jan-18   $100       abc
2-jan-18   $-100      xyz
3-jan-18   $50        qaz

stock_master
stock_code stock_name
abc        abc corp int
xyz        xyz firm

write sql 
1)there maybe some data quanltiy issue
some days return missing find out these date 
exclude weekend

2)get the stock total return per month  
and the stock name , 
and the total of all stock by month ,
sort the result by month ,stock 

#performance tuning
#oralc joins
#data warrhouse concept ,early arrvial fact
#indexes partition







