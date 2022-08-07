// Connect to Database at Cluster0
// Select your driver node.js and version >4.01


const { MongoClient, ServerApiVersion } = require('mongodb');
<!-- const uri = "mongodb+srv://usr1dos:<password>@cluster0.nkqh8i9.mongodb.net/?retryWrites=true&w=majority"; --!>

const uri = "mongodb+srv://usr1dos:<qPCwBm2F1FIrtnHA>@cluster0.nkqh8i9.mongodb.net/?retryWrites=true&w=majority";
const client = new MongoClient(uri, { useNewUrlParser: true, useUnifiedTopology: true, serverApi: ServerApiVersion.v1 });
client.connect(err => {
  const collection = client.db("test").collection("devices");
  // perform actions on the collection object
  client.close();
});
