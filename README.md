# <p align="center">Task One - Forms (1)</p>

User input is very important, as it helps to collect useful information from users, as well as determine output in some cases e.g search engines. Most times, this is done through forms, as it is in surveys. Think of a chat application like WhatsApp, it would really suck if you didn't have that cool form for your messages. 
Without further ado, let's get started.
## Label
The label element just tells us what the input is for.
```html
<label></label>
```
## Form element
The form is a cool element that contains the inputs and submit button. It needs to be told what to do when the submit button is pressed, in it's action attribute.
For example, 
```html
<form action="/submit">
 <label for="name">Email</label><br>
<input type="email">
 <label for="name">Password</label><br>
<input type="password">
</label>
</form>
```
## Input elements
We have a lot of input elements, but I would mention the most frequently used ones only:

```html
<input type="text">
```
This is used for a generic input: maybe like collecting first name or last name from the user, or typing a message on a chat app.
```html
<input type="search">
```
A good use case is for collecting query input for a search engine like Google.
```html
<input type="email">
```
As it's name suggests, it collects email input
```html
<input type="password">
```
This collects super secret info, your passwords.
It changes it's content to dot like characters, to prevent people from seeing your Netflix password 😆. 
```html
<input type="radio">
```
You would remember this from your last computer based examination. 
It was in the form of the options, you were to pick
This input type 
```html
<input type="submit">
```
This input type submits the content of every input in the form
## Your Task
Scenario: You have a chat application, and you need users to log in with their username and password.

Solution: 
<ul>
  <li>Create a login page with 2 <input> boxes. One for the username, the other for password.</li>
  <li>Add a button with label of 'Sign In'.</li>
  <li>Add a Forgot Password link using `<a>` . This doesn't have to link to an external site.</li>
</ul>


for learning about forms and inputs: 
[W3Schools](https://www.w3schools.com/html/html_forms.asp)
[MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input)

Don't forget to have fun! 😊
