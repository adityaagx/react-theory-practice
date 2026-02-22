====================================
TOPIC 6: EVENT HANDLING
====================================

THEORY
------
Events let users interact with the UI.

In React:
- Events are written in camelCase
- You pass a function, not a string

Common events:
- onClick
- onChange
- onSubmit

------------------------------------

EXAMPLE
-------
Handling a click event:

function ButtonClick() {
  function handleClick() {
    console.log("Button clicked");
  }

  return (
    <button onClick={handleClick}>
      Click Me
    </button>
  );
}

------------------------------------

INLINE EVENT
------------
You can also write logic inline:

<button onClick={() => console.log("Clicked")} />

------------------------------------

SUMMARY
-------
Events handle user actions.
Events call functions when something happens.

====================================
END
====================================
