6. Find the product with a row id of 10

Query:   db.products.findOne({id:{$eq:'10'}})

Result:

{

  _id: ObjectId('6613742ff615cc997616c9be'),
  
  id: '10',
  
  product_name: 'Generic Wooden Pizza',
  
  product_price: 84,
  
  product_material: 'Frozen',
  
  product_color: 'indigo'
  
}
