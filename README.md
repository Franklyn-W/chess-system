# Desenvolvimento de sistema de xadrez

Projeto desenvolvido dentro do curso de Java completo, do professor Nélio Alves, na plataforma Udemy

Foi usado no projeto todos os assuntos abordados até a chegada do modulo do projeto.

O objetivo é cada passo do desenvolvimento ser um commit no repositório do projeto

Projeto desenvolvido sem interface gráfica, sistema rodará em prompt de comando.!

[Projeto de tabuleiro de xadrez](chess-system-design.png)


## Primeiro passo: Posição
Checklist:
* Classe Position [public]
* **Tópicos de OOP**
  * Encapsulamento
  * Construtores
  * ToString

## Implementando Tabuleiro e Peça
Checklist:
* Classes Piece e Board [public]
* **Tópicos de OOP**
  * Associação
  * Encapsulamento / Modificador de acesso
* **Estruturas de dados**
  * Matriz

## Camada Xadrez e impressão do tabuleiro

Formato do tabuleiro

![Impressão do tabuleiro](image.png)

Checklist:
* Métodos: Board.Piece(row, column) e Board.Piece(Position)
* Enum Chess.color
* Classe Chess.ChessPiece [public]
* Classe Chess.ChessMatch [public]
* Classe ChessConsole.UI
* **Tópicos OOP**
  * Enumeradores
  * Encapsulamento / Modificador de acesso
  * Herança
  * Downcasting
  * Membros estáticos
  * Padrão de camadas
* **Estrutura de dados**
  * Matriz

## Colocando as peças no tabuleiro
Checklist:
* Método: Board.PlacePiece(piece, position)
* Classes: Rook, King [public]
* Método: ChessMarch.InitialConfig
* **Tópicos OOP**
  * Herança
  * Sobrecarga
  * Polimorfismo (toString)

## Implementando o BoardException e programação defensiva
Checklist:
* Classe BoardException [public]
* Métodos: Board.PositionExists, Board.ThereIsAPiece
* Implementação de programação defensiva nos métodos do Board
* **Tópicos OOP**
  * Exceções
  * Construtores (Uma String será retornada pela exception)