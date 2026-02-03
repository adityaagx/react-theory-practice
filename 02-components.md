
====================================
TOPIC 2: COMPONENTS
====================================

THEORY
------
A component is a small piece of the user interface.

In React:
- A component is a JavaScript function
- It returns what should appear on the screen

Components help by:
- Breaking UI into small parts
- Reusing UI logic
- Keeping code clean

Each component focuses on one job.

------------------------------------

EXAMPLE
-------
A simple component:

function Greeting() {
  return <h1>Welcome</h1>;
}

This component:
- Is a function
- Returns UI
- Can be reused anywhere

------------------------------------

USING A COMPONENT
-----------------
function App() {
  return (
    <div>
      <Greeting />
      <Greeting />
    </div>
  );
}

------------------------------------

SUMMARY
-------
Component = function that returns UI.
React builds the screen using components.

====================================
END
====================================
