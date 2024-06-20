5. Find the product name and product material of each products

Query:   db.products.find({product_name:{$exists:true}},{product_name:1,product_material:1})

Result :

[
  {
    _id: ObjectId('6613742ff615cc997616c9b5'),
    product_name: 'Intelligent Fresh Chips',
    product_material: 'Concrete'
  },
  {
    _id: ObjectId('6613742ff615cc997616c9b6'),
    product_name: 'Practical Fresh Sausages',
    product_material: 'Cotton'
  },
  {
    _id: ObjectId('6613742ff615cc997616c9b7'),
    product_name: 'Refined Steel Car',
    product_material: 'Rubber'
  },
  {
    _id: ObjectId('6613742ff615cc997616c9b8'),
    product_name: 'Gorgeous Plastic Pants',
    product_material: 'Soft'
  },
  {
    _id: ObjectId('6613742ff615cc997616c9b9'),
    product_name: 'Sleek Cotton Chair',
    product_material: 'Fresh'
  },
  {
    _id: ObjectId('6613742ff615cc997616c9ba'),
    product_name: 'Awesome Wooden Towels',
    product_material: 'Plastic'
  },
  {
    _id: ObjectId('6613742ff615cc997616c9bb'),
    product_name: 'Practical Soft Shoes',
    product_material: 'Rubber'
  },
  {
    _id: ObjectId('6613742ff615cc997616c9bc'),
    product_name: 'Incredible Steel Hat',
    product_material: 'Rubber'
  },
  {
    _id: ObjectId('6613742ff615cc997616c9bd'),
    product_name: 'Awesome Wooden Ball',
    product_material: 'Soft'
  },
  {
    _id: ObjectId('6613742ff615cc997616c9be'),
    product_name: 'Generic Wooden Pizza',
    product_material: 'Frozen'
  },
  {
    _id: ObjectId('6613742ff615cc997616c9bf'),
    product_name: 'Unbranded Wooden Cheese',
    product_material: 'Soft'
  },
  {
    _id: ObjectId('6613742ff615cc997616c9c0'),
    product_name: 'Unbranded Plastic Salad',
    product_material: 'Wooden'
  },
  {
    _id: ObjectId('6613742ff615cc997616c9c1'),
    product_name: 'Gorgeous Cotton Keyboard',
    product_material: 'Concrete'
  },
  {
    _id: ObjectId('6613742ff615cc997616c9c2'),
    product_name: 'Incredible Steel Shirt',
    product_material: 'Metal'
  },
  {
    _id: ObjectId('6613742ff615cc997616c9c3'),
    product_name: 'Ergonomic Cotton Hat',
    product_material: 'Rubber'
  },
  {
    _id: ObjectId('6613742ff615cc997616c9c4'),
    product_name: 'Small Soft Chair',
    product_material: 'Cotton'
  },
  {
    _id: ObjectId('6613742ff615cc997616c9c5'),
    product_name: 'Incredible Metal Car',
    product_material: 'Fresh'
  },
  {
    _id: ObjectId('6613742ff615cc997616c9c6'),
    product_name: 'Licensed Plastic Bacon',
    product_material: 'Steel'
  },
  {
    _id: ObjectId('6613742ff615cc997616c9c7'),
    product_name: 'Intelligent Cotton Chips',
    product_material: 'Soft'
  },
  {
    _id: ObjectId('6613742ff615cc997616c9c8'),
    product_name: 'Handcrafted Wooden Bacon',
    product_material: 'Concrete'
  },
  {
    _id: ObjectId('6613742ff615cc997616c9c9'),
    product_name: 'Unbranded Granite Chicken',
    product_material: 'Metal'
  },
  {
    _id: ObjectId('6613742ff615cc997616c9ca'),
    product_name: 'Ergonomic Soft Hat',
    product_material: 'Rubber'
  },
  {
    _id: ObjectId('6613742ff615cc997616c9cb'),
    product_name: 'Intelligent Steel Pizza',
    product_material: 'Cotton'
  },
  {
    _id: ObjectId('6613742ff615cc997616c9cc'),
    product_name: 'Tasty Rubber Cheese',
    product_material: 'Frozen'
  },
  {
    _id: ObjectId('6613742ff615cc997616c9cd'),
    product_name: 'Licensed Steel Car',
    product_material: 'Cotton'
  }
]