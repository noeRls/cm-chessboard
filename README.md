# chessmailboardJS

Chessboard for chessmail.eu / chessmail.de

Demo [http://shaack.com/projekte/chessmail-board/](http://shaack.com/projekte/chessmail-board/)

## Install

`npm install`

## Configuration

With default values
```
this.config = {
    sprite: "./assets/sprite.svg", // figures and markers
    initialPosition: "rnbqkbnr/pppppppp/8/8/8/8/PPPPPPPP/RNBQKBNR w KQkq - 0 1",
    initialOrientation: 'white'
};
```  

## API (not implemented yet)

### fen(string fen)
- Set the position as fen

### enableMoves(boolean enable)
- Enable interactive Moving

### callbacks

#### onMove(fieldFrom, fieldTo)
- Click oder Drag allowed


