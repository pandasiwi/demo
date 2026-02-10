---
title: '{{ replace .Name "-" " " | title }}'
date: {{ .Date }}
draft: true
description: "Deskripsi singkat produk untuk preview card (meta description)."

price: 0
is_sold_out: false

images:
  - "images/products/default.jpg"

# specs:
#   bahan: ""
#   ukuran: ""
#   berat: ""

buy_options:
  whatsapp: true
  
  marketplaces:
    - name: "Shopee"
      url: ""
      icon: "shopee"
      color: "#EE4D2D"
      
    - name: "Tokopedia"
      url: ""
      icon: "tokopedia"
      color: "#5dA96A"
      
    - name: "Lazada"
      url: ""
      icon: "lazada"
      color: "#0F146D"

tags: []
categories: []
---

