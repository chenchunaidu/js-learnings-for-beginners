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
