# blog-redux

## General Data Loading with Redux

### <code> Component gets rendered onto the screen </code>

<br />

### <code> Component's 'componentDidMount' lifecycle method gets called </code> <br />

### <code> We call action creator from 'componentDidMount'</code>

<br />
<code> Action creator runs code to make an API request </code>
<br />
<code> API responds with data </code>
<br />
<code> Action creator returns an 'action' with the fetched data on the 'payload' property </code>
<br />
<code> Some reducer sees the action, returns the data off the 'payload'</code>
<br />
<code> Some reducer sees the action, returns the data off the 'payload'</code>
<br />
<code> Because we generated some new state object, redux/react-redux cause our React app to be rerendered</code>
