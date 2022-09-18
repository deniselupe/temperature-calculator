# temperature-calculator
This is a project that I created following along React's [Lifting State Up](https://reactjs.org/docs/lifting-state-up.html) lesson.

# Notes
- Lifting Up State is a pattern to giving the same functionality to multiple components. 
- In the examples I've reviewed, typically the ParentComponent is created to pass data and funtionality to its ChildrenComponents.
- You do this by giving the ParentComponent a state, which the ChildrenComponents will then refer to for information of what they should be rendering.

In this Temperature Calculator example, Calculator.js has the state defined, and the state will be used to define what both the Celsius and Fahrenheit TemperatureInput/js elements will be rendering as their values.
