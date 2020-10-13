## React Interview Questions

**Question**: What is Virtual DOM?<br/>
**Answer**: React creates a tree of custom objects representing a part of the DOM. For example, instead of creating an actual DIV element containing a UL element, it creates a React.div object that contains a React.ul object. It can manipulate these objects very quickly without actually touching the real DOM or going through the DOM API. Then, when it renders a component, it uses this virtual DOM to figure out what it needs to do with the real DOM to get the two trees to match.

You can think of the virtual DOM like a blueprint. It contains all the details needed to construct the DOM, but because it doesn't require all the heavyweight parts that go into a real DOM, it can be created and changed much more easily.

**Company**: Curefit <br/>
**Topics**: `React` <br/>
