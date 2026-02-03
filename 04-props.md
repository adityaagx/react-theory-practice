
====================================
TOPIC 4: PROPS
====================================

THEORY
------
Props are data passed from one component to another.

They allow components to:
- Receive data
- Be reusable with different values

Props are:
- Read-only
- Passed like function arguments

------------------------------------

EXAMPLE
-------
Passing props:

function Greeting(props) {
  return <h1>Hello {props.name}</h1>;
}

Using the component:

function App() {
  return <Greeting name="Aditya" />;
}

------------------------------------

WHAT IS HAPPENING
-----------------
- App sends data
- Greeting receives data
- UI changes based on props

------------------------------------

SUMMARY
-------
Props = data coming into a component.
Used to customize components.

====================================
END
====================================
