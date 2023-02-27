# Reading Class 07

Domain Modeling

1) Domain modeling is used to break down the problem into concepts through code. The model will code in sections such as the requirements, any depedencies and any constraints that's going to be encountered when coding. Some examples would be any objects to declare that will appear in multiple versions of it. If there were many occurance of the same type of objects (with different properties), a constructor to create many versions of the object is needed so the object isn't literally created at every instances needed. Another examples would be any functions to create because the function will be used recurringly.

HTML Table Basics

1) Tables should not be used for layouts of the page for 3 main reasons. Layout tables reduces accessibility for visually impaired users. Tables procudes lots of tags in the HTML document, which can be hard to read, maintain and debug. Tables are not automatically responsive, so if the sizes are not specified, they default to the content size.

2) `<th>` is used as table headers. It denotes the text as a header, both visually and semantically. `<colgroup>` defines a group of columns with a table. When grouped, styles or easy reference to a select few columns can be applied. `<td>` elements define each individual cell in a row, while `<tr>` indicates a new row.

Introducing Constructors

1) A constructor contructs/creates new instance of an object and returns `this` newly created object. Constructors are used when there are multiple similar objects that needed to be created, and is inefficient to maintain each object coded out.

2) `this` in a constructor will bind to the newly created objects by the constructor so you can refer to `this` object in the constructor code. `this` in an object literal will refer to whatever `this` is bounded at time of call which is dictated if `this` was called as function or method. The difference is `this` is not bounded to a newly created object in the object literal.

Object Prototypes Using A Constructor

1) Prototype is a property that every function JS has. It will allow us to share methods across all instances of a function. Also, all JS objects inherit proterties and methods from a prototype. This will allow you to add properties to constructor functions, because they inherit from the prototype.

## Things I want to know more about

I probablye need to practice the use of prototypes in a real word coding environment. It was hard to wrap my head around that a prototype sits above all objects in JS and that it bridges between instances of the same objects.
