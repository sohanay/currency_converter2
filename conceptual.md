### Conceptual Exercise

Answer the following questions below:

- What are important differences between Python and JavaScript?
  -Python is server-side scripting, whereas JS is front-end client side scripting
  -Compared to JS, Python is simpler to read and write its code. 
  -In order to run Python code an interpreter is required, in JS the code is built in to most web browsers.
  -Python is encded as ASCII, JS has UTF-16 encoding

- Given a dictionary like ``{"a": 1, "b": 2}``: , list two ways you can try to get a missing key (like "c") *without* your programming crashing.
  1. using get(), ,get(key, def_val) can be used to check for the key which will be printed if present. If not present, the def_value passed in the argument is returned. 
  2. using setdefault(key,def_value), similar to get() but if the key is absent a new key is created with def_value associated with the key passed in arguments.

- What is a unit test?
  -Unit test is a method to isolate written code to test and determine if it works as intended. 

- What is an integration test?
  -Integration test is a type of software testing in which the different units, modules or components of an application are tested as a combined entity. 

- What is the role of web application framework, like Flask?
  -web page application framework are websites, blogs, wiki pages, or any other commercial website. Flask is an example of a web framework.

- You can pass information to Flask either as a parameter in a route URL
  (like '/foods/pretzel') or using a URL query param (like
  'foods?type=pretzel'). How might you choose which one is a better fit
  for an application?
  -'/foods/pretzel' would be predefined as /foods/X which could be any food. Foods?Type is more for a search based routing. 

- How do you collect data from a URL placeholder parameter using Flask? 
  -request.args ??

- How do you collect data from the query string using Flask?
  -request.url ??

- How do you collect data from the body of the request using Flask?
  -request.args.get ??

- What is a cookie and what kinds of things are they commonly used for? 
  -Cookies are data that are tied to a user/computer that is accessed whenever visiting that respected website. Such as, history or user preference.

- What is the session object in Flask?
  -Session objest is similar to a cookie, as it stores information on a user/computer that is carried over during the course of browsers life. This can potentially keep trach of constantly havin to update variables that will be referencable as long as the browser/window remains open. This is also not affected by refreshes. 

- What does Flask's `jsonify()` do?
  -'jsonify' will return flask variables/data that need to be turned into a JSON format. Or frontend API's to consume. 
