/*
  Create an array of 'pet' objects.
  Each object should have the following properties: 
  name, type, breed, age, and photo
*/

let pet = [
  {name: "Billy",
  type: "type",
  breed: "dog1",
  age: 9,
  photo: "img/aussie.jpg"},
  {name: "Joe",
  type: "type",
  breed: "dog2",
  age: 49,
  photo: "img/golden.jpg"},
  {name: "Nicky",
  type: "type",
  breed: "dog3",
  age: 69,
  photo: "img/pug.jpg"},
]
  
let html = "";
  
 for (var i=0; i<pet.length;i++){
    html += `
        <h2>${pet[i]['name']}</h2>
        <h3>Dog | ${pet[i]['breed']}</h3>
        <p>Age: ${pet[i]['breed']}</p>
        <img src=${pet[i]['photo']} alt=${pet[i]['breed']}>
        `
  }

document.querySelector("main").innerHTML = html;

