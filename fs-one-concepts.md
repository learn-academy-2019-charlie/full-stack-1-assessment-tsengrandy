# Full Stack 1 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. What is Enzyme and what are some of the methods that it provides?
Enzyme is a testing library for React applications that is often used within the Jest framework for unit
testing. It allows you to test the DOM with mount by creating a testing instance of the class and using simulate
to recreate user behavior.

#### 2. What is the difference between dynamic and a static routes?
Static routes only work for that specific route whereas a dynamic route is able to change its parameters so 
it's much more flexible.

#### 3. What is a JSON API?
JavaScript Object Notation Application Programming Interface: It's a software that allows 2 applications to 
communicate with each other and transfer JSON objects easily.

#### 4. What is a migration and why would you use one?
A migration is a command in Rails that allows you to modify the database to include more columns or delete
a field. It provides a convenient history you can check.

#### 5. Explain how to set up a route in React.
Each React application will need route directions in route.db
You can use rails g resource objectName to configure standard routes, or customize it yourself.
root to: 'controllerName#functionName' sets your homepage to that page
You would then go into your controller and add functions to be called in the route.

#### 6. When would you use a generate resource over a generate controller?
Rails g resource creates a template with a lot of things already whereas rails g controller only adds a new
controller, which means while you don't get as much boilerplate at setup, it allows more customization on 
what you want and saves space. There's also rails g scaffold which creates an even wider template.

#### 7. Explain the difference between a controller spec and a request spec.
With request specs, you can:

specify a single request
specify multiple requests across multiple controllers
specify multiple requests across multiple sessions

With controller specs, you can use:

standard rspec matchers (expect(response.status).to eq(200))
standard test/unit assertions (assert_equal 200, response.status)
rails assertions (assert_response 200)
rails-specific matchers:

#### 8. Describe the React component lifecycle. What are some of the lifecycle methods?
It's when an instance of a component is being created and inserted into the DOM, React will run through multiple
methods such as constructor(), render(), and componentDidMount()

#### 9. At this point in the program, what technologies/languages do you find yourself gravitating to?
I'm gravitating towards React purely because it's such a popular library and I can be useful if I know it.
I do enjoy Ruby because of the easy readibility and the built in methods.