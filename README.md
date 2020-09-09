# Snake game in Flutter

  This project is about how can we make a old snake :snake: game in Flutter. 
  
  Here I highlight only that portion which I do steps for snake moving vertically and horizontally. For knowing rest of things you go with my code which I upload here.
  
  ```
   onVerticalDragUpdate: (details) {
                if (direction != 'up' && details.delta.dy > 0) {
                  direction = 'down';
                } else if (direction != 'down' && details.delta.dy < 0) {
                  direction = 'up';
                }
              },
              onHorizontalDragUpdate: (details) {
                if (direction != 'left' && details.delta.dx > 0) {
                  direction = 'right';
                } else if (direction != 'right' && details.delta.dx < 0) {
                  direction = 'left';
                }
              },
              
  ```
