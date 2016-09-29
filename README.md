Relevant Readings

* React Stateless Components
* React Stateful Components
* Intro to React

Lifecycle methods WILL NOT be part of Meets.

---

Common oversights when first coding in React

* don’t forget to bind functions with .bind(this)
* passing functions correctly to child components
* when in a stateful component (class syntax) don’t forget syntax is a little different from stateless, for example in render return you need to refer to ‘this’
* Did you import correct things? export correct things? data, components, etc.
* make sure in your return you only return one top level JSX element
* spelling errors
* did you capitalize class names such as Component?

---

What house of hogwarts does Chelsea belong to?

* FYI to muggles, there are four houses of Hogwarts and you are sorted into one in your first year

* take a look at the data file to see what we’re working

* When someone clicks a house, the bottom of the page should respond with the correctness of the answer
  * if the answer is wrong, display something like “WHAT? DO YOU EVEN KNOW HER?”
  * if the answer is correct, display something like “Crushed it. What a dope answer.”

* Only the correctness of that answer should show
* If you click the same answer again nothing happens

---

Pro-tips

* plan before you code, first consider your component hierarchy

* check your bundle regularly to make sure there are no typos

* be methodical when creating new components to avoid common errors like not importing / exporting correctly

* Put something on the page to make sure things are hooked up correctly like a simple “I’M A \_\_\_ COMPONENT, AND IM DOPE AF”
* I like to throw debuggers everywhere during development to see how data is being passed

* start simple with just getting a static page up first and passing hardcoded props down, then introduce state

* for example just get a static page with the question and the body of the answer choices

* considering what should be stateful / stateless, how data should be passed around

* We want to have an answer in focus based on what is selected, where should this belong?
  * how will we handle displaying the response?
  * how will we handle clicking a specific question?


* sometimes for seemingly no reason your bundle is updating or debuggers are lingering even with a refresh

* don’t be afraid to open a new tab or to restart your server, it’ll only take a moment and is a quick sanity check
