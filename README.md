# ReactJS Class Components

Run the following command to get a basic ReactJS application setup:

```
npx create-react-app my-app
cd my-app
yarn start
```

1. Inside the my-app/src folder, create a new file named Component.js

2. Inside Component.js, make a class component

3. Add a render function of the class component add a string and modify the index.js to use Component.js instead of App.js

4. Add constructor to set a state variable of the string, then change the render function to use the state variable.

5. Create a higher order function that accepts 1 parameter named WrappedComponent and returns the parameter as <WrappedComponent value="String you added before" />

6. Change the first class component to use this.props.value instead of state.

7. Wrap the export of the first class component with the higher order function.

After you have completed all of the exercises, commit your changes with the following command:

```
git commit -am "ReactJS Class Examples"
```
