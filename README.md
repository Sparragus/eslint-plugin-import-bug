#### How to reproduce
1. Clone this repo
2. Installs the dependencies with `npm install`
3. Run the script `npm run lint`

#### Expected behavior
No errors

#### Actual behavior

```
> eslint .

/Users/richard/Downloads/eslint-plugin-import-bug/index.js
 1:8   error  No default export found in module            import/default
 2:10  error  Button not found in 'react-native-elements'  import/named
 2:18  error  Text not found in 'react-native-elements'    import/named
 ```
