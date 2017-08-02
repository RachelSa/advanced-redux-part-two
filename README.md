# Advanced Redux Club part II

# Monday 

## Student Presentation: Data Normalization

## withRouter()
- withRouter is a higher order component that can be wrap a React component in order to get match, location, and history props.
- it's useful for giving access to these params to nested components that don't have direct access to router props. 
- <a href="https://egghead.io/lessons/javascript-redux-using-withrouter-to-inject-the-params-into-connected-components">video tutorial with Dan Abramov</a>

## implementing
1. import withRouter: ```import { withRouter } from 'react-router'```
2. Wrap the component when exporting: ```export default withRouter(connect(null, {addSnack})(SnackForm))```

# Tuesday

## Student Presentation: Selectors 

## Redux DevTools
<a href="https://egghead.io/lessons/javascript-getting-started-with-redux-dev-tools">Egghead video</a>

# Wednesday
 
## Student Presentation: 

## Immutable JS
- used to create 'record' instances
- self documenting
- enforce consistency

```
const { Record } = require('immutable')
const Snack = Record({ name:"", flavor:"", price:0, review :""})
const cheetos = new Snack({ name: "Cheetos" })
Snack.get("name") 
// "Cheetos"

const twizzlers = new Snack({ name: "Twizzlers", pullNPeel: true })
twizzlers.get('pullNPeel')
// undefined
```
## resources
- <a href="https://facebook.github.io/immutable-js/docs/#/Record">React Immutable JS</a>
- <a href="https://tonyhb.gitbooks.io/redux-without-profanity/content/using_immutablejs_records.html">Using Immutable JS Records</a>





