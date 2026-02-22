====================================
TOPIC 9: useEffect
====================================

THEORY
------
useEffect is used for side effects in React.

Side effects are things like:
- API calls
- Timers
- Logging
- Subscriptions

useEffect runs AFTER the component renders.

------------------------------------

EXAMPLE
-------
Running code on render:

function App() {
  React.useEffect(() => {
    console.log("Component rendered");
  }, []);

  return <h1>Hello</h1>;
}

------------------------------------

DEPENDENCY ARRAY
----------------
[]  → runs once (on mount)
[ value ] → runs when value changes
(no array) → runs on every render

------------------------------------

SUMMARY
-------
useEffect handles side effects.
It runs after render, not during.

====================================
END
====================================
