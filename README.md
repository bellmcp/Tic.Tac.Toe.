# Tic.Tac.Toe.
A revolutionary version for the classic Tic Tac Toe game. Tic. Tac. Toe is the most professional version of the classic Tic Tac Toe game. It offers hours of addictive fun, brain exercising and great user experience. Developed using Microsoft Visual Studio

<p align="center">
  <img src="https://bellmcp.github.io/img/Projects_TicTacToe.jpg" />
</p>

# Resources

* [Download Project (.rar | 471 KB)](https://bellmcp.github.io/work/TicTacToe.rar)
* [Download .NET Framework 4.7.2 (Direct Link)](https://dotnet.microsoft.com/download/dotnet-framework/net472)

# What I Learned

* Developed a user interface within the Windows Forms App (.NET Framework) using ToolStrip, TextBox, Label & Button.
* Implemented functinality to the UI: `buttonClick`, `disableButtons`, `newGame`, & `resetCount`.
* Integrated Tic Tac Toe logic strategy to the `winnerCheck` function. (based on [Wikipedia's strategy](https://en.wikipedia.org/wiki/Tic-tac-toe#Strategy))

# winnerCheck()

```         
            //horrizontal check
            if ((A1.Text == A2.Text) && (A2.Text == A3.Text) && (!A1.Enabled))
                winner_exist = true;
            else if ((B1.Text == B2.Text) && (B2.Text == B3.Text) && (!B1.Enabled))
                winner_exist = true;
            else if ((C1.Text == C2.Text) && (C2.Text == C3.Text) && (!C1.Enabled))
                winner_exist = true;

            //vertical check
            if ((A1.Text == B1.Text) && (B1.Text == C1.Text) && (!A1.Enabled))
                winner_exist = true;
            else if ((A2.Text == B2.Text) && (B2.Text == C2.Text) && (!A2.Enabled))
                winner_exist = true;
            else if ((A3.Text == B3.Text) && (B3.Text == C3.Text) && (!A3.Enabled))
                winner_exist = true;

            //diagonal check
            if ((A1.Text == B2.Text) && (B2.Text == C3.Text) && (!A1.Enabled))
                winner_exist = true;
            else if ((A3.Text == B2.Text) && (B2.Text == C1.Text) && (!C1.Enabled))
                winner_exist = true;
```

# Future Ideas Include

* Add an ability to have the X and O on the board be different colors.
* Implement an unbeatable AI in single player mode.
* Welcome screen to let player switch between single player and multiplayer mode.

# License

### Source Code License

Licensed under [The MIT License](https://github.com/bellmcp/Tic.Tac.Toe./blob/master/LICENSE). You could use the source code for whatever you want as long as the LICENSE file or the license header in the source code still there.

### Documentation License

All reading materials from this repository is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You could use this repository as your reference as long as you give the attribution.

> Copyright © 2019 Wutipat Khamnuansin, All rights reserved.
