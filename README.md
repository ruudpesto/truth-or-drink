# Truth or Drink
A free, online version of the card game, built with Next.js.

### Interactivity
Users can access the next question primarily by clicking the black question box. However, users on a device with a keyboard can access the next question by pressing either the spacebar or the right arrow key, and can access the previous question by pressing the left arrow key. On mobile devices, users can also access the next question by swiping right on the black box, and access the previous question by swiping left on the black box.

### Question Manipulator
Users can alter the question bank by forcing a specific question to appear at a certain turn position. This menu can be accessed at `/manipulate` or by pressing the 'online' button below the main Truth or Drink logo on the home screen.

### Run Locally

```bash
# clone the repository
git clone https://github.com/ruudpesto/truth-or-drink

# install the dependencies
cd truth-or-drink && npm install

# start the development server
npm run dev

# deploy to firebase
npm run build && npm run export && firebase deploy --only hosting
```
