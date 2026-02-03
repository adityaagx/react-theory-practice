
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
