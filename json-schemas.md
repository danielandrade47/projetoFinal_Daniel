<h1>JSON Schemas</h1>

Abaixo, apresentam-se os Schemas estruturados para o desenvolvimento do projeto.

<h2>Schema de Clientes (Customers)</h2>

```
 customer:{
        "_id": "string",
        "name": "string",
        "email": "string",
        "phone": "string",
        "address": {
            "country": "string,
            "city": "string",
            "street": "string",
            "number": "string",
            },
        "created": "string"
    }
```


<h2>Schema de Produtos (Products)</h2>

```
 product:{
        "_id": "string",
        "name": "string",
        "brand": "string",
        "description": "string",
        "price": "double",
        "created": "string"
    }
```

<h2>Schema de Orçamentos (Deals)</h2>

```
  deal:{
        "_id": "string",
         customer:{
                "_id": "string",
                "name": "string",
                "email": "string",
                "phone": "string",
                "created": "string"
         },
         products: [
            {
                "product": {
                    "_id": "string",
                    "name": "string",
                    "brand": "string",
                    "description": "string",
                    "price": "double",
                    "created": "string"
                },
              "quantity": "Number",
              "_id": "string"
            }
        ]
        "total": "Number",
        "created": "string"
    }
```
