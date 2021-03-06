# RetroMatch

![Wireframe eerste versie](https://github.com/LarsHVA/project-tech/blob/main/doc/Group%202.png?raw=true)

retroMatch is a matching app that helps users to find people who like an (old) game that is no longer popular / available, has online support or helps search companions (perhaps new friends).

## Installation

### Pre install

- [NodeJS](https://nodejs.org/en/)
- [Git](https://git-scm.com/)

### Make account

- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)

#### Documentation

- [NodeJS](https://nodejs.org/en/docs/)
- [Git](https://git-scm.com/docs)
- [MongoDB Atlas](https://docs.atlas.mongodb.com/getting-started/)

### App install

Run the following code in your terminal.
![Installation](https://github.com/LarsHVA/project-tech/blob/main/doc/cloneProject.png?raw=true)

Make a `.env` file with:

```js
URI = //URI of MongoDB
SESSION_SECRET = //Random key
```

### Create Database

```js
Database: Project;
Collection: users;
```

When the setup is complete
run `npm start` in the terminal.

## DOCS

[Wiki](https://github.com/LarsHVA/project-tech/wiki)

## Dependencies

- [bcrypt](https://www.npmjs.com/package/bcrypt)
- [body-parser](https://www.npmjs.com/package/body-parser)
- [dotenv](https://www.npmjs.com/package/dotenv)
- [ejs](https://www.npmjs.com/package/ejs)
- [express](https://www.npmjs.com/package/express)
- [express-flash](https://www.npmjs.com/package/express-flash)
- [express-session](https://www.npmjs.com/package/express-session)
- [mongodb](https://www.npmjs.com/package/mongodb)
- [mongoose](https://www.npmjs.com/package/mongoose)
- [passport](https://www.npmjs.com/package/passport)
- [passport-local](https://www.npmjs.com/package/passport-local)

## devDependencies

- [nodemon](https://www.npmjs.com/package/nodemon)
