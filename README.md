# racket-minesweeper

This was my CS2500 (Fundamentals of Computer Science 1) final project at Northeastern, which was to remake Minesweeper in Racket. To run this you'll need to install [Dr. Racket](https://racket-lang.org/) and open the hw12.rkt file. To run an instance of the game, type the following command into the Dr Racket terminal:

    (mine-sweeper size mines)
    
Where size is the size of the square board and mines is the number of mines.

# Controls

To play, all you need is the mouse. Racket unfortunately only recognizes one type of mouse input (a click) so the typical minesweeper controls are impossible. To get around this, we have a status on the side showing the current mode you are in (whether you are revealing squares/mines or flagging them). To toggle, all you have to do is click the status and switch back whenever you want to.

Have fun!
