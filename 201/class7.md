# Reading

## Domain Modeling
1. Explain why we need domain modeling.
    -  To carry out a common language and a fundamental structure important for the analysis of features and epics.

## HTML Table Basics
2. Why should tables not be used for page layouts?
  - Tables are usually more bytes of markup. 
    Tables usually prevent incremental rendering. 
    Tables may require you to chop single, logical images into multiple ones. ...
    Tables break text copying on some browsers.
3. List and describe 3 different semantic HTML elements used in an HTML <table>.
    - The <section> element defines a section in a document.
      Can be used for: Chapters, Introduction, News items, Contact information
      Introducing Constructors
4. What is a constructor and what are some advantages to using it? 
    - A special method that is used to initialize objects and they automatic initialization of objects at the time of their declaration. Also the objects of child class can be initialised by the constructors of base class.
5. How does the term this differ when used in an object literal versus when used in a constructor?
    - Objects created using object literal are singletons, whereas if an object is created using constructor function and a change is made to it, that change won't affect the object throughout the script.

## Object Prototypes Using A Constructor
6. Explain prototypes and inheritance via an analogy from your previous work experience.
    -  An object can inherit properties of another object. The object from where the properties are inherited is called the prototype.