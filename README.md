# Advanced Redux Club part II

# Monday

## withRouter()
- withRouter is a higher order component that can be wrap a React component in order to get match, location, and history props.
- it's useful for giving access to these params to nested components that don't have direct access to router props. 
- <a href="https://egghead.io/lessons/javascript-redux-using-withrouter-to-inject-the-params-into-connected-components">video tutorial with Dan Abramov</a>

## implementing
1. import withRouter: ```import { withRouter } from 'react-router'```
2. Wrap the component when exporting: ```export default withRouter(connect(null, {addSnack})(SnackForm))```

# Tuesday

## Redux DevTools
- <a href="https://egghead.io/lessons/javascript-getting-started-with-redux-dev-tools">Egghead video</a>
-


