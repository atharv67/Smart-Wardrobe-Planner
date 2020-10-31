# Smart-Wardrobe-Planner
An app that matches clothes and recommends the user best combinations taking into consideration user's attributes

## Clothes Classification:
<ul>
<li>  Done using CNNs into 5 classes-tshirts, shirts, casual shorts, pants, jackets</li>
<li>  Dataset link:https://www.kaggle.com/paramaggarwal/fashion-product-images-dataset</li>
</ul>

## Clothes Matching:
<ul>
  <li> Create Dataset of upper body clothing matched with selected pants -->Done</li>
  <li> Train a binary classifier for each of the pants thats extracts features of matching shirts/tshirts and finds if it is matching with the given pants</li>
  <li> When user inputs new pant, we find the  closest of the selected pant using image embedding and check if the shirt/tshirt is matching with the selected pant using the corressponding classifier</li>
</ul>

## Occassion Based Recommendation:
<ul>
  <li>Select shirts/tshirts and pants that satisfy the occassion use the clothes matching algorithm to recommend clothes. This satisfies the wear properly and aesthetically criteria </li>
</ul>
