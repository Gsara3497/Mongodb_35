10. Delete the products which product price value are 28

Query:     db.products.deleteMany({product_price:28})

Result:

{ acknowledged: true, deletedCount: 1 }