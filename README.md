# Visual maze solver

A maze solving visualizer, using the A* ,Dijkstra and BFS algorithm.

![GIF Preview](./public/preview.gif)

# Screenshots

![Screenshot 2025-01-10 141310](https://github.com/user-attachments/assets/46ee7ec1-60e4-468d-b133-04d13149f85c)
![Screenshot 2025-01-10 141422](https://github.com/user-attachments/assets/5ae64569-2530-458c-82dc-3fd34873f7c5)
![Screenshot 2025-01-10 141725](https://github.com/user-attachments/assets/e24dbc05-d9c0-44d5-a16f-21cef41dd111)
![Screenshot 2025-01-10 141627](https://github.com/user-attachments/assets/ef2c23a8-55a0-46e1-9db5-5d1d030da2bb)
![Screenshot 2025-01-10 141543](https://github.com/user-attachments/assets/194ed492-a7af-414e-b187-258cb8800108)


## Settings

In the constants file, you can find two settings,
  - `DEFAULT_SIZE` which the default size of the matrix
  - `MAX_SIZE` which is the max size the app can accept
  - `DELAY` which is the delay time in milliseconds

You can also change the grid color scheme.

```ts
// src/constants.ts

export const DEFAULT_SIZE = 10
export const MAX_SIZE = 50
export const DELAY = 0

export const TARGET_LOCATION_COLOR = "#0080ff"
export const PATH_COLOR = "#ef4444"
export const VISITED_CELL_COLOR = "#fde047"
```

## Future plans

I'm always open to new contributions and ideas for implementing new features. If you have a cool idea for a new feature or algorithm that you'd like to see added to the app, please let me know. I'd love to hear from you and work together to make this app even more awesome.

- [ ] Add a maze generation algorithm
- [ ] Replace select box with radio box
- [ ] Use walls instead of blocks to improve performance


