# Amazon-Apparel-Recommendations
Here we have a amazon women apparel data and we try to predict a similar apparel.

![Untitled](https://user-images.githubusercontent.com/67622526/147365117-2596aa44-1bbb-42bf-89fd-1f4497d4b4c6.png)

1. here we have a amazon feshion data and our task is find to similar product for the use.

2. In this data we have 19 feature in these feature we most use a brand and color of product
and title of product and cloth image.

3. so for here we know our most info availble on the title feature hence we build a simple
model using a title feature and they work well.

4. then we use a title + color and brand feature, they return a very nice output for given query
product.

5. for the title feature a we use a different type of technique for to convert text to vector like
BOW, TFIDF, AVG-W2V, IDF-W2V, and for the color and brand we use a OneHotEncoding
and for the image we use a CNN (VGG16).

6. For the our task we use all these feature and apply a weighted eud-dist and try to predict a
similar product and using a different weight of all feature we predict a product here.
