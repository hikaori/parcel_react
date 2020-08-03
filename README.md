# parcel_react
this project is created with parcel and react.

there is a great comand to create a react app(`npx create-react-app my-app`more detail [here](https://ja.reactjs.org/docs/create-a-new-react-app.html))　. However in this project, I created a react project without using the command inorder to learn how to create a custom react project.

---
# procedure of creating react project with parcel

## step1 creating initial project
branch:[step1](https://github.com/hikaori/parcel_react/pull/1/commits/c1779be719124085c590680a06a090bf3e75d6bb) 
- create a new folder
- inside the folder run below command.
`$ npm init -y`
- some files created automaticaly inside the new folder after runing the command and finishing the process.

## step2 installing 'react' and 'react-dom' package.
branch:[step2](https://github.com/hikaori/parcel_react/pull/2/commits/1fb4ce1867da9bb73db78280ae3bffa6a70fac95)

install packages that are necessary for creating a react project.


- run the command
`$ npm install react react-dom`

## step3 installing 'parcel-bundler' 'babel-preset-env' 'babel-preset-react' in dev package.
branch:[step3](https://github.com/hikaori/parcel_react/commit/821be8c8b4530cad5ad90c8e7562142b93c3c31d)

parcel-bundler: core of parcel
babel-preset-env: allow you to use the latest JavaScript without micromanage.
babel-preset-react: allow to use jsx

## step4 create babel setting file
branch:[step4](https://github.com/hikaori/parcel_react/commit/102d17d3444bb8e90940a642f2a13f95aa0ffa3e)

babel need to know what to do. tell babel about using preset-env and react.

- create a new file called '.babelrc'.
- inside '.babelrc' , wirite below code.
`{
  "presets": ["env", "react"]
}`

## step5 create index files and modify package.json
creating fundamental index files. Also modiry package.json in order to run parel with command.

branch:step5

- create index.html same sa [this code](https://github.com/hikaori/parcel_react/commit/6dcbaffb5f3952865ea8245845d005f62d13fd30)
- create index.js same sa [this code](https://github.com/hikaori/parcel_react/commit/ee4da26b66fe8a4217dc28b9e7f77a0037141ca9) 
- modify package.json same sa [this code](https://github.com/hikaori/parcel_react/commit/ee4da26b66fe8a4217dc28b9e7f77a0037141ca9)
- run `npm start`
- access the address that showed in terminal
- if the page appear, congraturation! if not something wrong... please check the steps carefully.



--- complete base functions for creating react project with pacel at this point. from here just normal react project. ---
