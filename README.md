# React Performance Essentials
React performance talk/workshop

All exercises require:
- `npm install && npm start`

## 0-game-initial-slowdown
When entering a hex color the app is blocking all the time.
- identify &amp; solve the performance issue

Together: How to identify a performance issue in React

## 1-packing-list-pushing-state-down
When creating a new item name the whole app seems to render
- identify &amp; solve the performance issue

Together: How to push state down

## 2-game-pushing-state-down
When entering a hex color the app is blocking all the time. In the previous exercise we've learned how to push state down. Try to figure out a dolution
- Identify the issue
- Give it a try in this game 

## 3-game-pulling-content-up
Our boss Maureen wants to move components a little bit around. She wants the expensive component to be in the middle of the game. For obvious reasons.
- See what happens.
- How to make sure our game remains performant by entering a hex color

## 4-packing-list-react-library-tools
Earlier we've optimized the packing list. But clearly when interacting with the rest of the application a lot of rerenders are being triggered. Lets see what `useCallback`, `useMemo` &amp; `memo` brings.
- Identify the performance issue and come up with a solution. What tools to use when and how?

Together: Multiple solutions are possible. What is the prefered one.

- Try `useReducer` to optimize even further. (Reducers are prepared)
