Project created by running `npm init vue@latest`, https://github.com/vuejs/create-vue-templates/tree/main/with-tests

Procedure to produce error on fresh linux install (with all cypress system requirements):
- `cd vue-project`
- `npm install`
- `npm run test:unit:ci`

Error: 

[vite] Internal server error: Cannot read properties of undefined (reading 'uid')
Failed to fetch dynamically imported module: http://localhost:3001/src/components/__tests__/HelloWorld.spec.js?import
