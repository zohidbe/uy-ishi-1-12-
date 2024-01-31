ELEMENT html tags

selectorlar

attribute -> class , id , name , alt , type , value , placeholder , data set attribute

el.getAttribute('attr_value');

el.setAttribute('attr_value','new value');

el.hasAttribute('attr_value'); // boolean true or false

el.attribute // attribute value


// console.log(loginForm.id) // login form
// console.log(userNameForm.placeholder) // plase filll user name
// console.log(passwordForm.type) // password


// passwordForm.type="range";
// userNameForm.placeholder="ENTER PHONE NUMBER";

// let dt=passwordForm.getAttribute("placeholder");             // get
// passwordForm.setAttribute('placeholder', 'Enter secret key') // set
// userNameForm.setAttribute('value', "hello world")
// console.log(userNameForm.getAttribute('value'));

// console.log(dt)


// Elementning HTML matnini o'zgartirish
myElement.innerHTML = '<b>Yangi matn</b>';

// Elementning tekstini o'zgartirish
myElement.innerText = 'Yangi matn';

// Elementga yangi atribut qo'shish
myElement.setAttribute('attributeName', 'attributeValue');


// Elementga yangi class qo'shish
myElement.classList.add('newClass');

// Elementdan classni olib tashlash
myElement.classList.remove('oldClass');




// Animatsiya uchun class qo'shish
myElement.classList.add('animate');

// Animatsiya tugaganida classni olib tashlash
myElement.addEventListener('animationend', function() {
    myElement.classList.remove('animate');
});
