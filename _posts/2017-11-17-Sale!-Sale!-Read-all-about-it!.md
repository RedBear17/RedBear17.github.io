---
title: Sale! Sale! Read all about it!
layout: post
author: nathan.higgins
permalink: /sale!-sale!-read-all-about-it!/
source-id: 1XszZdIv4tcdcZ2NxjT36eAmrm5YkYYqbhipni0yOP3M
published: true
---
In today's lesson, we learned how to make discounts in our store. This is useful for enticing customers into our stores.

First I created a cell that added up the items. It summed up all the cells in the quantity column. Then underneath my Sum total cell I created 2 cells called Discount % and Discount no. of items. This is where you would put how much of a discount you will get off your overall bill and how many items you need to buy to get this discount.

Then I created a Total with Discount cell. This would work out the final price with the discount that the customer would have to pay. To do this I used this bit of code:

=if($F$15<=G18, G16*(100-G17)/100, G16)

The (if($F$15<=G18)) tells the program if the number of items bought column is equal or bigger than the number of items before the overall discount column, reform the following.

The(G16*(100-G17)/100, G16)) tells the program to multiply the number in the sum total by (100- the discount % cell)-i.e(100-20=80) and then divide that number by 100 so the sum become for example £400*0.8.

Then I did the same but with an individual item discount. If you bought 5 or more items for example, you get 10% that type of item. This used this code:

=if(F2>=$H$15,G2*(100-$G$19)/100, G2)

As you can see, it is the same principal. That is how I added discounts to my shop.

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTFxbTYrD7oE65CCmsaNBkBe416z-Hu8ndkkVyP3mLqcDcuXuE84_vYvVjQZOZQvwJ0SrOx2_L3tBzT/pubhtml?widget=true&amp;headers=false"></iframe>

