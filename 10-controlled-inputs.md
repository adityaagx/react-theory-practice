====================================
TOPIC 10: CONTROLLED INPUTS
====================================

THEORY
------
A controlled input is an input whose value is controlled by React state.

This means:
- Input value comes from state
- Changes update state
- State updates UI

React becomes the single source of truth.

------------------------------------

EXAMPLE
-------
A controlled text input:

function Form() {
  const [name, setName] = React.useState("");

  return (
    <div>
      <input
        value={name}
        onChange={(e) => setName(e.target.value)}
      />
      <p>{name}</p>
    </div>
  );
}

------------------------------------

WHAT IS HAPPENING
-----------------
- User types
- onChange fires
- State updates
- UI re-renders

------------------------------------

SUMMARY
-------
Controlled input = state controls input.
UI and data stay in sync.

====================================
END
====================================
