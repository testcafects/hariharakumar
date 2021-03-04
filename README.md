# WEB DEVELOPMENT TRAINING 
   US Bank Web Development Training Document

## TECHNOLOGIES 
  * [React](https://reactjs.org/)
  * [JSDocs](https://jsdoc.app/)
  * [Typescript](https://www.typescriptlang.org/)
  * [Babel](https://babeljs.io/)
  * [SASS](https://sass-lang.com/)

## DEPENDENCY
  * [Ant Design](https://ant.design/)

## TOOLS
  * [VS code](https://code.visualstudio.com/)
  * [TestCafe](https://devexpress.github.io/)
  * [gitcz](https://www.npmjs.com/package/git-cz)
  * [XD](https://www.adobe.com/products/xd.html)
  
## PLUGINS (EDITOR)
  * [Prettier](https://prettier.io/)
  * [esLint](https://eslint.org/)

## DESIGN METHODOLOGY
  * [Atomic Design](https://xd.adobe.com/ideas/process/ui-design/atomic-design-principles-methodology-101/)

## SIZE and Property

   US Bank Development using the size of component should be in  unit - rem  ( 1 rem = 16 px )

    | Name /Size      | rem   | px    |
    | --------------- | ----- | ----- |
    | Screen Width    | 64    | 1024  |
    | Max Screen Width| 75    | 1200  |
    | Header Height   | 7.5   | 120   |
    | Font size       | 1     | 16    |
    | Font size max   | 1.5   | 24    |
    
  US Bank Every screens are splitted using Grid and Flex Layout 

  *Parent Element Should be in display property of Grid and Child is in Flex*

```css
    #parent{
        display:grid;
        margin:0;
        padding:0;
    }
    #child{
        display:flex;
        margin:0; 
        padding:0;
    }
```

## DESCRIPTION

  #### Prerequisite
  * [Node JS](https://nodejs.org/en/)
  * [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
  * [VS code](https://code.visualstudio.com/) or Any code editor

  #### REACT
   React is a JavaScript library for building user interfaces
   To create and run react application
```cmd
  npx create-react-app my-app
  cd my-app
  npm start
```
  #### JS Docs
  JSDoc is an API documentation generator for JavaScript , It can be added as development dependency in our project
To install the latest version on npm locally and save it in your package's package.json file:
```cmd
npm install --save-dev jsdoc
```
If you installed JSDoc locally, the JSDoc command-line tool is available in ./node_modules/.bin. To generate documentation for the file yourJavaScriptFile.js:
```cmd
./node_modules/.bin/jsdoc yourJavaScriptFile.js
```
