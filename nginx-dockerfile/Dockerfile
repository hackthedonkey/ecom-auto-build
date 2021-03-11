FROM nginx

#install git
RUN apt-get update
RUN apt-get install git -y

#git clone ecom source code
RUN mkdir -p /var/www/html
RUN git clone https://github.com/hackthedonkey/learning-app-ecommerce.git /var/www/html
