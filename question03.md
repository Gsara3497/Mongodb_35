3. Find the product price which are not between 400 to 600

Query:   db.products.find({product_price:{$not:{$gte:400,$lte:600}}})

Result:

[

  {
  
    _id: ObjectId('6613742ff615cc997616c9b5'),
    
    id: '1',
    
    product_name: 'Intelligent Fresh Chips',
    
    product_price: 655,
    
    product_material: 'Concrete',
    
    product_color: 'mint green'
    
  },
  
  {
  
    _id: ObjectId('6613742ff615cc997616c9b6'),
    
    id: '2',
    
    product_name: 'Practical Fresh Sausages',
    
    product_price: 911,
    
    product_material: 'Cotton',
    
    product_color: 'indigo'
    
  },
  {
    _id: ObjectId('6613742ff615cc997616c9b7'),
    id: '3',
    product_name: 'Refined Steel Car',
    product_price: 690,
    product_material: 'Rubber',
    product_color: 'gold'
  },
  
  {
  
    _id: ObjectId('6613742ff615cc997616c9b9'),
    
    id: '5',
    
    product_name: 'Sleek Cotton Chair',
    
    product_price: 33,
    
    product_material: 'Fresh',
    
    product_color: 'black'
    
  },
  
  {
  
    _id: ObjectId('6613742ff615cc997616c9bc'),
    
    id: '8',
    
    product_name: 'Incredible Steel Hat',
    
    product_price: 78,
    
    product_material: 'Rubber',
    
    product_color: 'violet'
    
  },
  
  {
  
    _id: ObjectId('6613742ff615cc997616c9bd'),
    
    id: '9',
    
    product_name: 'Awesome Wooden Ball',
    
    product_price: 28,
    
    product_material: 'Soft',
    
    product_color: 'azure'
    
  },
  
  {
  
    _id: ObjectId('6613742ff615cc997616c9be'),
    
    id: '10',
    
    product_name: 'Generic Wooden Pizza',
    
    product_price: 84,
    
    product_material: 'Frozen',
    
    product_color: 'indigo'
    
  },
  
  {
  
    _id: ObjectId('6613742ff615cc997616c9bf'),
    
    id: '11',
    
    product_name: 'Unbranded Wooden Cheese',
    
    product_price: 26,
    
    product_material: 'Soft',
    
    product_color: 'black'
    
  },
  
  {
  
    _id: ObjectId('6613742ff615cc997616c9c0'),
    
    id: '12',
    
    product_name: 'Unbranded Plastic Salad',
    
    product_price: 89,
    
    product_material: 'Wooden',
    
    product_color: 'pink'
    
  },
  
  {
  
    _id: ObjectId('6613742ff615cc997616c9c1'),
    
    id: '13',
    
    product_name: 'Gorgeous Cotton Keyboard',
    
    product_price: 37,
    
    product_material: 'Concrete',
    
    product_color: 'sky blue'
    
  },
  
  {
  
    _id: ObjectId('6613742ff615cc997616c9c2'),
    
    id: '14',
    
    product_name: 'Incredible Steel Shirt',
    
    product_price: 54,
    
    product_material: 'Metal',
    
    product_color: 'white'
    
  },
  
  {
  
    _id: ObjectId('6613742ff615cc997616c9c3'),
    
    id: '15',
    
    product_name: 'Ergonomic Cotton Hat',
    
    product_price: 43,
    
    product_material: 'Rubber',
    
    product_color: 'mint green'
    
  },
  
  {
  
    _id: ObjectId('6613742ff615cc997616c9c4'),
    
    id: '16',
    
    product_name: 'Small Soft Chair',
    
    product_price: 47,
    
    product_material: 'Cotton',
    
    product_color: 'teal'
    
  },
  
  {
  
    _id: ObjectId('6613742ff615cc997616c9c5'),
    
    id: '17',
    
    product_name: 'Incredible Metal Car',
    
    product_price: 36,
    
    product_material: 'Fresh',
    
    product_color: 'indigo'
    
  },
  
  {

    _id: ObjectId('6613742ff615cc997616c9c6'),
    
    id: '18',
    
    product_name: 'Licensed Plastic Bacon',
    
    product_price: 88,
    
    product_material: 'Steel',
    
    product_color: 'yellow'
    
  },
  
  {
  
    _id: ObjectId('6613742ff615cc997616c9c7'),
    
    id: '19',
    
    product_name: 'Intelligent Cotton Chips',
    
    product_price: 46,
    
    product_material: 'Soft',
    
    product_color: 'azure'
    
  },
  
  {
  
    _id: ObjectId('6613742ff615cc997616c9c8'),
    
    id: '20',
    
    product_name: 'Handcrafted Wooden Bacon',
    
    product_price: 36,
    
    product_material: 'Concrete',
    
    product_color: 'lime'
    
  },
  
  {
  
    _id: ObjectId('6613742ff615cc997616c9c9'),
    
    id: '21',
    
    product_name: 'Unbranded Granite Chicken',
    
    product_price: 90,
    
    product_material: 'Metal',
    
    product_color: 'gold'

  },
  
  {
  
    _id: ObjectId('6613742ff615cc997616c9ca'),
    
    id: '22',
    
    product_name: 'Ergonomic Soft Hat',
    
    product_price: 99,
    
    product_material: 'Rubber',
    
    product_color: 'black'
    
  },
  
  {
  
    _id: ObjectId('6613742ff615cc997616c9cb'),
    
    id: '23',
    
    product_name: 'Intelligent Steel Pizza',
    
    product_price: 95,
    
    product_material: 'Cotton',
    
    product_color: 'azure'
    
  },
  {
    _id: ObjectId('6613742ff615cc997616c9cc'),

    id: '24',
    
    product_name: 'Tasty Rubber Cheese'
    ,
    product_price: 47,
    
    product_material: 'Frozen',
    
    product_color: 'orchid'
    
  },
  
  {
  
    _id: ObjectId('6613742ff615cc997616c9cd'),
    
    id: '25',
    
    product_name: 'Licensed Steel Car',
    
    product_price: 20,
    
    product_material: 'Cotton',
    
    product_color: 'indigo'
    
  }
  
]
