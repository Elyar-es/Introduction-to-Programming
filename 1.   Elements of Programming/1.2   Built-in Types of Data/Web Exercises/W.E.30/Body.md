**پرداخت وام خودرو.** برنامه ای به نام CarLoan.java بنویسید که سه آرگومان خط فرمان R,P,Y را خوانده و پرداخت های ماهانه ای را که باید درY سال برای پرداخت وام P دلاری با نرخ بهره مرکب ماهانه R درصد پرداخت کند را محاسبه کند.فرمول آن به صورت زیر است:
````
                P r 
payment =  ---------------,  where n = 12 * Y, r = (R / 100) / 12
           1  - (1 + r)^(-n)
````