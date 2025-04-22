## Question 1

function Welcome() {
    return (
        <h1>Welcome to react!</h1>
    )
}

## Question 2

function HelloWorld() {
    return (
        <>
        <p>Hello</p>
        <p>World</p>
        </>
    )
}

## Question 3

function ProfilePicture() {
    return (
        <img src='../assets/images/profile-picture.jpg' alt='The users profile picture'/>
    )
}

## Question 4

const name = "John Doe";
const age = "30";

function Profile() {
    return (
        <>
        <p>{name}</p>
        <p>{age}</p>
        </>
    )
}

## Question 5

The code is not written correctly.  The "apple" component name is all lower case, whereas component names should always begin with a capital letter ie. "Apple".

## Question 6

export default TableOfContents

## Question 7

import Profile from './Profile'

## Question 8

The code is not written correctly.  The returned elements are missing a parent element.  This could be fixed by wrapping the elements in a fragment.

## Question 9

const Summary = () => {
  return (
    <>
      <div className="title">
        <h1>My Site!</h1>
      </div>
      <p className="description">
        You can find my thoughts here
        <br/><br/>
        <b>And</b> <i>I</i> have plenty of them!
      </p>
    </>
  );
}

## Question 10

function Greeting(props) {
    return (
        <p>Hello {props.name}</p>
    )
}

## Question 11

function Greeting(props) {
    return (
        <p>Hello {props.name}</p>
    )
}

function App() {
    return (
        <>
        <Greeting name="Eugene"/>
        </>
    )
}