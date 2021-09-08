# Kostyuk Alexandr

### Front-end web developer (Beginner)

## Contacts:

* Phone: +7 999 2042022
* E-mail: riveralexander@yandex.ru
* Telegram: @alexandr_kostyuk

## About me:

I have good interpersonal skills, am an excellent team worker and very willing to learn and develop new skills.
I am reliable and dependable and often seek new responsibilities within a wide range of employment areas.

## Skills

* HTML
* CSS
* JavaScript(Basic)
* Git

## Code Example

```
import React from 'react'
import './App.css';
import Header from './components/Header/Header';
import NavBar from './components/NavBar/NavBar';
import Profile from './components/Profile/Profile';
import {Route} from "react-router";
import News from "./components/News/News";
import Music from "./components/Music/Music";
import Setting from "./components/Setting/Setting";
import DialogsContainer from "./components/Dialogs/DialogsContainer";
import UsersContainer from "./components/Users/UsersContainer";

const App = (props) => {
    return (
            <div className='app-wrapper'>
                <Header/>
                <NavBar/>
                <div className='app-wrapper-content'>
                    <Route path='/profile/'
                           render={() => <Profile store={props.store} />}/>
                    <Route path='/dialogs/'
                           render={() => <DialogsContainer store={props.store}/>}/>
                    <Route path='/news/' render={News}/>
                    <Route path='/music/' render={Music}/>
                    <Route path='/setting/' render={Setting}/>
                    <Route path='/users/'
                           render={() => <UsersContainer store={props.store}/>}/>
                </div>
            </div>
    )
}

export default App;
```
## Education
* Kirishskiy Polytech College (Gas-electro welder)
* Courses
    * CS50
    * JetBrains Academy
    * HTML Academy

## Languages
* Russian - Nativ
* English - A2 (B1 in the process)