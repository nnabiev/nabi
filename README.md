# nabi
# Dom
## ***DOM (Document Object Model) — это специальная древовидная структура, которая позволяет управлять HTML-разметкой из JavaScript-кода. Управление обычно состоит из добавления и удаления элементов, изменения их стилей и содержимого.***
## **Браузер создаёт DOM при загрузке страницы, складывает его в переменную document и сообщает, что DOM создан, с помощью события DOMContentLoaded.**
# **Bom**
## ***Browser Object Model (BOM) — это часть JavaScript, которая позволяет скрипту взаимодействовать с программой просмотра веб-страниц. BOM представляет объекты, через свойства и методы которых можно управлять внешним видом и поведением обозревателя.***
# **Create element()**
## ***Метод createElement позволяет создать новый элемент, передав в параметре имя тега. После создания с элементом можно работать как с обычным элементом, а также его можно добавить на страницу методами prepend, append, appendChild, insertBefore или insertAdjacentElement. Если записаь результат работы createElement в переменную, то в этой переменной будет такой элемент, как будто бы мы получили его через querySelector или getElementById.***
# **innerHtml**
## ***Свойство innerHTML-это часть объектной модели документа (DOM), которая используется для установки или возврата HTML-содержимого элемента.Возвращаемое значение представляет собой текстовое содержимое HTML-элемента.Оно позволяет коду JavaScript манипулировать отображаемым сайтом.***
# **appenChild**
## ***JavaScript метод .appendChild () объекта Node позволяет добавить узел в конец списка дочерних элементов указанного родительского узла. Обратите внимание на важный момент, в том случае, если элемент уже существует в текущем родительском элементе, то он сперва удаляется, а затем вставляется заново.***
# **oncklick**
## ***Свойство onclick означает «по клику» и говорит JavaScript, какое событие мы хотим отслеживать. А та часть инструкции, которая идёт после onclick, называется обработчиком событий.***

# **Обект**
## **Объект– некоторая часть окружающего мира, рассматриваемая человеком как единое целое.Каждый объект обязательно как-то называется. Имя — это основная характеристика, которая позволяет отличить один объект от другого.Как правило, в обыденной жизни используется общее имя, обозначающее объекты с похожими характеристиками: комната, собака, река, песня.**
# Lecture-Hw
# HOMEWORK--3
# What is object in Javascript?
> In JavaScript, an object is a standalone entity, with properties and type. JavaScript object is a nonprimitive data-type that allows you to store multiple collections of data
sh
let preson = {
          firstname: matin,
 keys=>   lastname:davlatov,
          age:50   => value
}

# There three types of object in javascript
|Object.entires |objeckt.keys |object.values |
|-----|-----|-----|
|Masivi masivo mekna  |TOka klychowa megira  | Toka znacheniewa |
# What is Destructuring and Spread in Javascript
- The destructuring assignment syntax is a JavaScript expression that makes it
possible to unpack properties from object, into distinct variables

sh
const person = {
    name : Asas,
    age: 20,
    gender:female
}
let name = person.name
let {age,gender} = person
let clone object = {...person}
log(clone object == person )  === #False
log (name ) === # Asas
# What is keyword This in Javascript
- The this keyword refers to different objects depending on how it is used:
- this is NOT a variable. It is a keyword. You cannot change the value of this. 

sh
In object method,This referss to object .
Alone,This referse to the global object
in a Function This refers to th global object
in a function in strict mode This is undefined
#### What is `New Date `in Javascript?
In javascript date and time are represented by the date object the date object provides the date and time information and also provides varius method
THE CONCET METHOD JOIN TWO OR MORE STRINGS.AND IT DOESN`T CHANGE THE EXISTING STRINGS.THE CONCET RETURN A NEW STRING 
##### Creatin Date Object
- There fourth type of creating new date 
sh 
1) - new Date()
2) - new Date(milisecund)
3) - new Date(string)
4) - new Date(year,month,week,day,hour,minute,second,milisecond)

# Table of contents
1)Dom
2)Bom
3)Events
4)Dom Methods









# What is Dom in Javascript
- Document objecct model : stricted representation of html documents allows javascript to acsess html elements and styles to manipulate them
According to the Document Object Model (DOM for short), every HTML tag is an object.
Subtags are "children" of the parent element. The text that is inside the tag is also an
object.All these objects are available with JavaScript, we can use them to modify the page.
sh
JavaScript can modify all HTML elements on a page.
JavaScript can change all HTML attributes on a page.
JavaScript can change all CSS styles on a page.
JavaScript can remove existing HTML elements and attributes.
JavaScript can add new HTML elements and attributes.
JavaScript can respond to all existing HTML events on the page.
JavaScript can fire new HTML events on a page

-Definition and Usage. The querySelector() method returns the first child element that matches a
specified CSS selector(s) of an element, querySelectorAll() method can be used to access all elements
which match with a specified CSS selector.
# Innerhtml
> Это свойство предоставляет простой способ полностью
заменить содержимое элемента. Например, все содержимое
элемента body может быть удалено:. 

sh
Styling dom Element
Element.style.color="black"
Element.style.fontSize='5em'
Element.style.background="green"
# Html Events 
- An HTML event can be something the
browser does, or something a user does.
Here are some examples of HTML events:
•An HTML web page has finished loading
•An HTML input field was changed
•An HTML button was clicked
- JavaScript lets you execute code when events are detected.
onclick The user clicks an HTML element

# Create Element()
- The JavaScript document.createElement() method allows you to create and return a
new element (an empty Element node) with the specified tag name.

1) createElement(elementName): Creates an html element whose tag is
passed as a parameter. Returns the created element
sh
<script>
const btn = document.createElement("button")
btn.innerhmtl="hello button"
document.body.appendChild(btn)
</script>