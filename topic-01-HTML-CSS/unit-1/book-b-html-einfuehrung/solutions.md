# Solutions

### Exercise 1:

~~~javascript
const usersFirstName = prompt('enter first name');
const usersLastName = prompt('enter first name');
const usersAge = prompt('enter first name');

const user = {
  firstName: usersFirstName,
  lastName: usersLastName,
  age: usersAge,
};

console.log(user);
~~~

### Exercise 2:

~~~javascript
const usersFirstName = prompt('enter first name');
const usersLastName = prompt('enter last name');
const usersAge = prompt('enter your age');

const userGreeting = prompt('enter your greeting');

const user = {
  firstName: usersFirstName,
  lastName: usersLastName,
  age: usersAge,
  greeting: userGreeting,
  sayHello() {
    console.log(this.greeting + ' says ' + this.firstName);
  },
};

console.log(user);
user.sayHello();
~~~

