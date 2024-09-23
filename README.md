# Boldclimbing
implement the changes on the live site [BoldClimbing] for some live files.



---------helper.inc-----------
//----Missing some static air products on static air page.
1. For some reason the static Air isn't being displayed on the static air page: https://boldclimbing.com/static-air/ https://boldclimbing.com/w
2. The red stripe over the product image that said full line 2.5% discount / For some reason the full line discount sash isn't showing up: https://tinyurl.com/239pt8dt

-------Shipping.php------

1. Also can you add a shipping method like the CompX shipping method that is $50+ 10% for when the manufacturer is "Kastline-PU" . Please make
2. Can you change "kastline" to "Volx2" here: https://tinyurl.com/27zxntsb So if a product is manufactured by kastline it will end up in the bold shipping calculations instead of this 10% special shipping calculation.


-----functions.php-----
1. dd a shipping method like the CompX shipping method that is $50+ 10% for when the manufacturer is "Kastline-PU" .
2. The discounted products are not calculating correctly in the cart. See here: https://boldclimbing.com/product/thin-classic-triangle-300/
3.


-------RLC_ReteQuote.php------
1. So the R&L plugin is calculating the wrong weight. It's saying this order in wholesale2 is 3634 lbs but it's really more like 348 lbs.

-----bold-setting.php-----
1. add custom fields for Kastline-PU shipping.
2. And change some fields lable like.


-----product-image.php-------
1. The red stripe over the product image that said full line 2.5% discount

---- bold-csv-cron.php -----
1. Fixed fees bug
