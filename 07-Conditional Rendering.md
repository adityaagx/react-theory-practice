====================================
TOPIC 7: CONDITIONAL RENDERING
====================================

THEORY
------
Conditional rendering means showing UI based on a condition.

React uses normal JavaScript conditions:
- if
- ternary ( ? : )
- logical &&

------------------------------------

EXAMPLE (TERNARY)
----------------
function Status({ isLoggedIn }) {
  return (
    <h1>
      {isLoggedIn ? "Welcome Back" : "Please Login"}
    </h1>
  );
}

------------------------------------

EXAMPLE (LOGICAL &&)
-------------------
function Notification({ show }) {
  return (
    <div>
      {show && <p>New Message</p>}
    </div>
  );
}

------------------------------------

SUMMARY
-------
Conditions control what appears on screen.
React uses JavaScript logic for UI decisions.

====================================
END
====================================
