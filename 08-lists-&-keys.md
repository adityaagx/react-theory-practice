====================================
TOPIC 8: LISTS & KEYS
====================================

THEORY
------
Lists are used to render multiple items from an array.

In React:
- map() is used to create UI from arrays
- Each item needs a unique key

Keys help React:
- Track items
- Update UI efficiently

------------------------------------

EXAMPLE
-------
Rendering a list:

function ItemList() {
  const items = ["Apple", "Banana", "Mango"];

  return (
    <ul>
      {items.map((item, index) => (
        <li key={index}>{item}</li>
      ))}
    </ul>
  );
}

------------------------------------

KEY RULE
--------
- key must be unique
- Avoid index if real IDs exist

------------------------------------

SUMMARY
-------
Lists = array → UI.
Keys help React manage updates.

====================================
END
====================================
