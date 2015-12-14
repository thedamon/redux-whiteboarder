# redux-whiteboarder
## Scaffold a React/Redux project from Mindnode or text files.
Whiteboarder lets your team's (very important) development time spent around the whiteboard directly contribute to real code progress. 

It translates an indented text file (such as one exported from [Mindnode](https://mindnode.com/)) in a project directory into a fully scaffolded Redux application, ready to be divided up amongst the team with concerns all in a row, so perfectly separated.

##Features to include:

 - Create base react components and include them in one another based on nesting
 - Mark which components are connected to a redux store and which are dumb/smart
 - Provide a simple list of external dependencies to add to your package.json
 - Create empty actions/reducers to structure your store and get you started
 - Simple syntax to mark which part of the store to connect a component to
 - Options:
   + use ES6 classes or `React.createComponent()`
   + Components can have equivalent CSS/scss file added w an import
   + stub out basic lifecycle functions
   + component templates
   + other...

This will begin as redux specific, but the core should be abstracted into a parent library so it can support other architectures.
