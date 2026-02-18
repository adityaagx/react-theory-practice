
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

====================================
PROPS PRACTICE – 20 TASKS
====================================

1. Create a component called Welcome that receives a name prop and displays:
   Welcome, {name}

   - const Welcome = ({name}) => {
    return <h3>Welcome {name}</h3>;
   };

   function App(){
    return (
      <Welcome name="Aditya"/>
    );
   };

2. Create a component called Age that receives an age prop and displays:
   You are {age} years old.

   - const Age = ({age}) => {
    return <h3>You are {age} years old</h3>;
   };

   function App(){
    return <Age age={21} />;
   };

3. Create a component called UserCard that receives:
   - name
   - city
   Display both inside an h2 and p tag.

  - const UserCard = ({name, city}) => {
    return (
      <div>
       <h2>{name}</h2>
       <p>{city}</p>
      </div>
    );
   };

   function App(){
    return (
      <UserCard name="Aditya" city="Ajmer" />
    );
   };

4. Create a component called Product that receives:
   - title
   - price
   Display them inside a div.

   const Product = ({title, price}) => {
    return (
      <div>
      <h3>{title} cost is {price} rupees.</h3>
      </div>
    );
   };

   function App(){
    return (
      <Product title="Macbook" price="80k">
    );
   };

5. Create a component called Message that receives a text prop
   and renders it inside a paragraph.

   const Message = ({text}) => {
    return (
      <p>{text}</p>
    );
   };

   function App (){
    return (
      <Message text="Hello World />
    );
   };

6. Create a component called Button that receives a label prop
   and displays it inside a button element.

   const Button = ({label}) => {
    return (
      <button>{label}</button>
    );
   };

   function App(){
    return (
      <Button label="Black dog" />
    );
   };

7. Create a component called Avatar that receives an imageUrl prop
   and uses it inside an img tag.

   const Avatar = ({imgurl}) => {
    return (
      <img src={imgurl} />
    );
   };

   function App(){
    return (
      <Avatar imgurl="dodo.png" />
    );
   };

8. Create a component called Student that receives:
   - name
   - grade
   Show both values in separate elements.

   const Student = ({name, grade}) => {
    return (
      <div>
       <h3>{name}</h3>
       <p>{grade}</p>
      </div>
    );
   };

   function App(){
    return (
      <Student name="Aditya" grade={12} />
    );
   };

9. Create a component called Greeting that receives:
   - firstName
   - lastName
   Display full name together.

   const Greeting = ({firstName, lastName}) => {
    return <h3> {firstName} {lastName}</h3>
   };

   function App(){
    return <Greeting firstName="Aditya" lastName="Aditya" />
   };

10. Create a component called Status that receives a status prop
    and displays:
    Status: {status}

    const Status = ({checkStatus}) => {
      return <h3> Status: {checkStatus} </h3>
    };

    function App(){
      return <Status checkStatus="True" />
    };

11. Create a component called Book that receives:
    - title
    - author
    Render both clearly.

    const Book = ({title, author}) => {
      return <h3>{title} book author is {author}</h3>
    };

    function App(){
      return <Book title="Girl on Fire" author="Chetan Bhagat" />
    };

12. Create a component called PriceTag that receives a price prop
    and displays:
    $ {price}

    const PriceTag = ({price}) => {
      return <h3> ${price} </h3>
    };

    function App(){
      return <PriceTag price={50} />
    };

13. Create a component called Profile that receives:
    - username
    - bio
    Show them inside a div.

    const Profile = ({username, bio}) => {
      return (
        <div>
         <h3>{username}</h3>
         <h3>{bio}</h3>
        </div>
      );
    };

    function App(){
      return <Profile username="Aditya" bio="Hello World" />
    };

14. Create a component called Country that receives a country prop
    and displays:
    Country: {country}

    const Country = ({country}) => {
      return <h3>Country:{country}</h3>
    };

    function App(){
      return <Country country="India" />
    };

15. Create a component called Score that receives a score prop
    and displays:
    Your score is {score}

    const Score = ({score}) => {
      return <h3> Your score is {score}</h3>
    };

    function App(){
      return <Score score={21} />
    };

16. Create a component called Header that receives a title prop
    and renders it inside an h1.

    const Header = ({title}) => {
      return <h1>{title}</h1>
    };

    function App(){
      return <Header title="React practice" />
    };

17. Create a component called Car that receives:
    - brand
    - model
    Display: {brand} {model}

    const Car = ({brand, model}) => {
      return <h2> Display: {brand} {model} </h2>
    };

    function App(){
      return <Car brand="Tata" model="Harrier" /> 
    };

18. Create a component called Email that receives an email prop
    and displays it inside a paragraph.

    const Email = ({email}) => {
      return <p>{email}</p>
    };

    function App(){
      return <Email email="aditya123" />
    };

19. Create a component called Item that receives a name prop
    and render it inside a list item (li).

    const Item = ({name}) => {
      return <li>{name}</li>
    };

    function App(){
      return <Item name="Macbook" />
    };

20. Create a component called Card that receives:
    - heading
    - description
    Render both properly structured.

    const Card = ({heading, description}) => {
      return (
        <div>
         <h1>{heading}</h1>
         <p>{description}</p>
        </div>
      );
    };

    function App(){
      return <Card heading="Happy Anniversary" description="blah blah blah" />
    };

====================================
END
====================================
