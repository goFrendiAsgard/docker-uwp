# image ini based on php:7.4-cli
FROM php:7.4-cli

# copy kan folder ./app ke dalam /usr/src/app yang ada di container
COPY ./app /usr/src/app
# jadikan /usr/src/app di container sebagai working directory
WORKDIR /usr/src/app

# informasi bahwa kita akan expose port 3000 di container yang berbasiskan image ini
EXPOSE 3000

# perintah untuk menjalankan PHP development server di port 3000
CMD [ "php", "-S", "0.0.0.0:3000" ]