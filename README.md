## Clutering Analysis of boAt's products

The objective of performing clustering analysis on boAt's products is to segment the vast range of discounted products offered by boAt. Since boAt offers a variety of dicounts on almost all of its products, the aim was to segment those products based on its characteristics and market-demand.

## Data Collection
Method adopted to collect data from boAt's official website was web scraping. Web scraping was carried out using BeautifulSoup4 library. 

The product information retrieved from the website were:
- Product Name
- Sale price
- Discount percent
- Original Price
- Average Stars
- Number of Reviews
- Additional offers

## Challenges
The major challenge faced while web scraping the data was the dynamic nature of the website. Since BeautifulSoup doesn't support dynamic website's scraping, finding a solution was a must.

I was able to identify a pattern in the website link while the html page was dynamically loading. By applying a loop outside the implementation of web scraping, I was able to retrieve all the product information effectively.

## Clustering

Majorly two types of cluster validation techniques were examined:
- Elbow Method
 ![image](https://github.com/SameerMulani/boAt-Clustering/assets/88852494/c84b128b-5eea-4f3d-8417-0d0e5b499cf9)

- Silhouette Analysis
