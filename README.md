# eCommerseApp_Ayxan
eCommerseApp with bootstrap and java script.

-Header Structure
```sh
<header>
      <nav class="navbar navbar-expand-lg navbar-dark bg-warning">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Fashion World</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active home" aria-current="page" href="#">Home</a>
              </li>
              <li class="nav-item">
                <a id="products" class="nav-link" href="#">Products</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Categories
                </a>
                <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                  <li><a class="dropdown-item shoes category" href="#">Shoes</a></li>
                  <li><a class="dropdown-item trousers category" href="#">Trousers</a></li>
                  <li><a class="dropdown-item shirts category" href="#">Shirts</a></li>
                </ul>
              </li>
            </ul>
            
          </div>
        </div>
      </nav>
    </header>
```

-Product Example

```sh
id: 1, 
name: 'Blue Men Pants',
description: '%99 PAMUK %1 ELASTAN',
picture: 'pants 1.jpeg',
category: 'trousers',
price: 44.99
```
