# istio-microservice-book-info
Note: Fork from istio

The Bookinfo application is broken into four separate microservices:
+ products: the products microservice calls the details and reviews microservices to populate the page.
+ details: the details microservice contains book information.
+ reviews: the reviews microservice contains book reviews. It also calls the ratings microservice.
+ ratings: the ratings microservice contains book ranking information that accompanies a book review.