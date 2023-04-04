### Hey there!

```javascript
function Character(name, age, hobby) {
  this.name = name;
  this.age = age;
  this.hobby = hobby;
}

Character.prototype.bio = function() {
  return `Hi there, I'm ${this.name}, a ${this.age}-year-old who loves working with ${this.hobby}!`;
}

Character.prototype.interests = ['programming', 'video games', 'hanging out with friends'];

const sourav = new Character('Sourav', 16, 'Node.js');
console.log(sourav.bio());
console.log(`My interests include: ${sourav.interests.join(', ')}.`);
```
- How to reach me: [Email](mailto:sou6avkl11@gmail.com), [WhatsApp](https://wa.me/14402225555)

