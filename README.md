www.startechtech.com Product description code:
let product_info = [];
let products = document.querySelectorAll('.product-info').length;

for(i=0; i<products; i++){
let title = document.querySelectorAll('.product-name')[i].innerText;
let description = document.querySelectorAll('.descriptions')[i].innerText;
let price = document.querySelectorAll('.price')[i].innerText;

product_info.push({
title:title,
description:description,
price:price
});
}
product_info;
