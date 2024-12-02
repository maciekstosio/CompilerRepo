# Steps to reproduce

- Run the app
```
yarn install
yarn start 
```
- Run dev tools 
- Try to put breakpoint on `const a = 'Test Error';` - it's moved to main component
- Put breakpoint on `throw new Error(a);` - debugger don't stop on it