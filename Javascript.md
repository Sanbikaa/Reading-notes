# JavaScript Notes

- JavaScript (JS) is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions.

- While it is most well-known as the scripting language for Web pages, many non-browser environments also use it, such as Node.js, Apache CouchDB and Adobe Acrobat

- JavaScript is a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles

- The standards for JavaScript are the ECMAScript Language Specification (ECMA-262) and the ECMAScript Internationalization API specification (ECMA-402).

## Prompting the User Notes

- The function prompt accepts two arguments: 

![yes](https://user-images.githubusercontent.com/86576588/124021007-a1fb3b00-d9b0-11eb-8732-e64bc9673d74.png)

- It shows a modal window with a text message, an input field for the visitor, and the buttons OK/Cancel.

- The visitor can type something in the prompt input field and press OK. Then we get that text in the result. Or they can cancel the input by pressing Cancel or hitting the Esc key, then we get null as the result.

- The call to prompt returns the text from the input field or null if the input was canceled.

### Conditional operator Notes

- The so-called “conditional” or “question mark” operator lets us do that in a shorter and simpler way.

- The operator is represented by a question mark ?. Sometimes it’s called “ternary”, because the operator has three operands. It is actually the one and only operator in JavaScript which has that many.

- The condition is evaluated: if it’s truthy then value1 is returned, otherwise – value2.
