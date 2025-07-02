# 🛒 3.6 Shopping List Workshop (Array Practice)

Энэ бол **FreeCodeCamp** платформ дээрх “Shopping List” сэдвийн дадлага ажил юм.  
JavaScript-ийн **массив** (`array`) дээр үндэслэн хүнсний жагсаалт зохиох үйлдлүүдийг дадлага хийдэг.

📚 Дадлагын эх сурвалж:  
🔗 [FreeCodeCamp Workshop - Shopping List](https://www.freecodecamp.org/learn/full-stack-developer/workshop-shopping-list/)

---

## ✅ Зорилго

Энэ дадлагаар дараах чадваруудыг сурна:

- `push()` болон `pop()` ашиглан массивын төгсгөлд нэмэх, хасах
- `unshift()` болон `shift()` ашиглан эхэнд нэмэх, хасах
- Массивын индексээр (`[0]`, `[i]`) элементийг солих
- `console.log()` ашиглан динамик мэдээлэл хэвлэх

---

## 📜 Кодын товч танилцуулга

```js
const shoppingList = [];

shoppingList.push("Apples");
shoppingList.push("Grapes");

shoppingList.unshift("Vegetable Oil");

shoppingList.push("Popcorn", "Beef Jerky", "Potato Chips");
shoppingList.pop();

shoppingList.unshift("Chocolate Cake");
shoppingList.shift();
shoppingList[0] = "Canola Oil";

console.log(getShoppingListMsg(shoppingList));
