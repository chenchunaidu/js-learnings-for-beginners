### Arrays

1. Arrays ni group of items ni store cheshukovadaniki use chestam
2. Array index 0 nunchi start avutundi
3. Array length kanukovadaniki `.length` ane method use chestam
   ```javascript
   var a = ["seomthing"];
   console.log(a.length); //2
   ```
4. Array loki item add cheyyadaniki `.push` ane method use chestam
   ```javascript
   var a = ["seomthing"];
   a.push("org");
   console.log(a); //["something", "org"]
   ```
5. Array loni last item ni delete cheyyadaniki `.pop` ane method ni use chestam

   ```javascript
   var a = ["seomthing"];
   a.pop();
   console.log(a); //a
   ```

6. Array ni loop cheyyadaniki for loop use cheyyachu

```javascript
var a = ["Nani", "Naidu"];
for (let i = 0; i < a.length; i++) {
  console.log(a[i]); // Nani // Naidu
}
```

### Objects

1. objects ni set of key values pairs ni store chesukovadaniki use chestaru

   ```javascript
   var employee1 = {
     name: "nani",
     age: 21,
   };
   ```

2. name anedhi property/ key
3. `"nani"` anedhi value
4. object lo property ni update `objectName.propertyName = updatedValue`
   ```javascript
   employee1.name = "22";
   ```
5. object lo property ni access cheyyadam objectName.propertyName
   ```javascript
   console.log(employee1.name);
   ```
