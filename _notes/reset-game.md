

Reset game by setting a new id to the Game component

```
 resetGame = () => {
    this.setState((prevState) => {
      return { gameId: prevState.gameId + 1 };
    });
  };
```s