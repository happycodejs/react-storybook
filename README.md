# React Storybook

> An example of how to use Storybook in React project, help build a Design System using React.

## Storybook

Homepage: [Storybook](https://storybook.js.org/)

Storybook is an open source tool for developing UI components in isolation for React, Vue, Angular, and more. It makes building stunning UIs organized and efficient.

## Setup React Storybook

```
# Create our application:
npx create-react-app taskbox

cd taskbox

# Add Storybook:
npx -p @storybook/cli sb init
```

```
# Run the test runner (Jest) in a terminal:
npm test --watchAll

# Start the component explorer on port 9009:
npm run storybook

# Run the frontend app proper on port 3000:
npm start
```

- Install `@storybook/addon-knobs` into devDependencies: `npm install @storybook/addon-knobs --save-dev`

## Links

- [Storybook for React tutorial](https://www.learnstorybook.com/intro-to-storybook/react/en/get-started/)

- [Building React Apps With Storybook](https://www.smashingmagazine.com/2020/09/building-react-apps-storybook/)

- [storybook-react-example](https://github.com/smashingmagazine/storybook-react-example/)
