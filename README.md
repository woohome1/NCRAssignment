# NCRAssignment
NCR interview assignment
Scenarios: 1) register new product (POST)  2)Update product info and store inventory count (PUT) 3) retrieve store inventory for a product

URI: /InventoryServices/rest/InventoryService/products  for POST and PUT
     /InventoryServices/rest/InventoryService/products/{sku}/{store id}  for GET
     
     
INPUT and OUTPUT are both XML
<product>
    <sku></sku>
    <pName></pName>
    <store></store>
    <count></count>
</product>

