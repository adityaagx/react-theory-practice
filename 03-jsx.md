
====================================
TOPIC 3: JSX
====================================

THEORY
------
JSX is a syntax that lets you write HTML-like code inside JavaScript.

It is NOT HTML.
It is converted into JavaScript by React.

JSX makes UI code:
- Easier to read
- Easier to write

Behind the scenes:
JSX → JavaScript → Browser understands it

------------------------------------

EXAMPLE
-------
JSX example:

function App() {
  return <h1>Hello World</h1>;
}

Without JSX, this would be JavaScript code.

JSX lets us write UI in a simple way.

------------------------------------

JSX RULE
--------
JSX must return ONE parent element.

Correct:
---------
return (
  <div>
    <h1>Hello</h1>
    <p>Welcome</p>
  </div>
);

------------------------------------

SUMMARY
-------
JSX = easier way to write UI in React.
It looks like HTML but works inside JavaScript.

====================================
END
====================================

# React Theory Practice – Topic 3: JSX

====================================
TOPIC 3: JSX – THEORY QUESTIONS
====================================

## Instructions
- Answer in your own words.
- Do not copy from notes.
- Keep answers clear and simple.
- No coding required unless asked.

---

## 1.
What is JSX?

--- JSX is a syntax that lets you write HTML like code inside javascript.

## 2.
Is JSX the same as HTML? Explain your answer.

--- No, JSX is different than HTML, HTML can't be used inside JS, but JSX can be used.

## 3.
Why was JSX introduced in React?

--- To make code easy to write, read and understand.

## 4.
What happens behind the scenes when we write JSX?

--- It gets converted to JS for browser understanding.

## 5.
Complete the flow:

--- JSX → Javascript → Browser

## 6.
Why is JSX easier to read compared to plain JavaScript?

--- JSX is like HTML only, hence easy to read.

## 7.
Why is JSX easier to write compared to plain JavaScript?

--- It is mostly like HTML only, that's why easy to write.

## 8.
Inside which programming language do we write JSX?

--- Javascript.

## 9.
Can the browser understand JSX directly? Why or why not?

--- No, browser doesn't understand JSX.
Browsers only understand HTML, CSS, JS.
It gets converted into Javascript first, then browser understands it.

## 10.
If JSX is not HTML, why does it look like HTML?

--- JSX looks like HTML because it is designed to resemble HTML syntax,
 but it is actually JavaScript under the hood.

## 11.
What is the main advantage of using JSX in React applications?

--- It makes code easy to read, write, understand, debug.

## 12.
What is the one strict rule JSX must follow when returning UI?

--- It must contain one parent element.

## 13.
Why must JSX return only one parent element?

--- Because under the hood JSX is Javascript only,
and Javascript functions can only return one value.

## 14.
Is this valid JSX? Explain why or why not.

return (
  <h1>Hello</h1>
  <p>Welcome</p>
);

--- No, it is not valid, because it doesnt contain any parent element.

## 15.
Why is this valid JSX?

return (
  <div>
    <h1>Hello</h1>
    <p>Welcome</p>
  </div>
);

--- It contains one parent element, hence valid.

## 16.
Can JSX exist outside a JavaScript function?

--- JSX must be inside JavaScript code (like inside a component or assigned to a variable).
It cannot just exist randomly in a file like pure HTML.

## 17.
In a React application, where is JSX usually returned from?

--- A component.

## 18.
If we did not use JSX, what would we need to write instead?

--- React.createElement()

## 19.
How does JSX improve UI development speed?

--- It is easier to read and update, hence easier for developers to 
improve the development speed.

## 20.
Explain JSX in one clear sentence.

--- JSX is a syntax extenion of javascript, which makes code easy to write, 
read, and debug.

END
====================================
