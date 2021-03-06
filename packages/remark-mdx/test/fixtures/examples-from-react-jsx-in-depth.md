# Examples from React JSX in depth

From [React JSX in depth](https://reactjs.org/docs/jsx-in-depth.html):

<MyButton color="blue" shadowSize={2}>
  Click Me
</MyButton>

<div className="sidebar" />

<MyComponents.DatePicker color="blue" />

<div>Hello {props.toWhat}</div>

<MyComponent foo={1 + 2 + 3 + 4} />

<div>{props.number} is an {description} number</div>

<MyComponent message="hello world" />

<MyComponent message={'hello world'} />

<MyComponent message="&lt;3" />

<MyComponent message={'<3'} />

<MyTextBox autocomplete />

<MyTextBox autocomplete={true} />

<Greeting firstName="Ben" lastName="Hector" />

<Greeting {...props} />

<button className={className} {...other} />

<div>
  <Button kind="primary" onClick={() => console.log("clicked!")}>
    Hello World!
  </Button>
</div>

<MyComponent>Hello world!</MyComponent>

<div>This is valid HTML & JSX at the same time.</div>

<div>Hello World</div>

<div>
  Hello World
</div>

<div>
  Hello
  World
</div>

<div>

  Hello World
</div>

<MyContainer>
  <MyFirstComponent />
  <MySecondComponent />
</MyContainer>

<div>
  Here is a list:

  <ul>
    <li>Item 1</li>
    <li>Item 2</li>
  </ul>
</div>

<MyComponent>foo</MyComponent>

<MyComponent>{'foo'}</MyComponent>

<ul>
  {todos.map((message) => <Item key={message} message={message} />)}
</ul>

<div>Hello {props.addressee}!</div>

<Repeat numTimes={10}>
  {(index) => <div key={index}>This is item {index} in the list</div>}
</Repeat>

<div />

<div></div>

<div>{false}</div>

<div>{null}</div>

<div>{undefined}</div>

<div>{true}</div>

<div>
  {showHeader && <Header />}
  <Content />
</div>

<div>
  {props.messages.length &&
    <MessageList messages={props.messages} />
  }
</div>

<div>
  {props.messages.length > 0 &&
    <MessageList messages={props.messages} />
  }
</div>

<div>
  My JavaScript variable is {String(myVariable)}.
</div>
