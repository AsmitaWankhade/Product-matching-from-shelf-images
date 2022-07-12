# Product-matching-from-shelf-images

#### Dataset
Dataset consists of two types:
Product images : There are in all 300 images of different products taken individually. There are hundred different types of product : three images of each product in different angles.
Shelf images : There are 3,153 shelf images containing these products.

#### Problem statement 
Given a product image, find the respective product in shelf images.

#### Approach: 
Steps:
1. Used a pre-trained YOLOv4 network that detects items from shelf images.
2. Use similarity between products to match product in shelf image : Siamese network as been used for this purpose.
