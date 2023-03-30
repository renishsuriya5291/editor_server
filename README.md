# CodeSync Editor App

## Live Preview

- [Host](https://pitt-code-editor-app.herokuapp.com/)

### Gif Display

![React Hooks](./src/assets/code-editor.gif)

## Technical Details

- React
  - React Hooks
  - React Router
- CodeMirror
  - [CodeMirror](https://codemirror.net/)
  - [Reference](https://www.codiga.io/blog/implement-codemirror-6-in-react/)
  - [cm6-themes](https://github.com/craftzdog/cm6-themes)
- Express
- Socket.io
- Deploy(Heroku)

## Notes

### Sync Code

- use string record every row of code
- composition to array emit to server
- server use on() listening change

github
git add .
git commit -m "msg"
git push
