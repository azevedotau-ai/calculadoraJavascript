# JavaScript Calculator

Uma calculadora JavaScript simples construída com HTML, CSS e JavaScript vanilla.


Por favor, dê-me a sua opinião sobre a minha implementação do algoritmo do pátio de manobras😄.

## Uso

Você pode usar o teclado para interagir com a calculadora:

- Use <kbd> C </kbd>, <kbd> ESC </kbd> ou <kbd> Excluir </kbd> para limpar a tela;
- Use <kbd> ← </kbd> ou <kbd> ↑ </kbd> para voltar no histórico de entrada;
- Use <kbd> → </kbd> ou <kbd> ↓ </kbd> para avançar no histórico de entrada;
- Use as teclas numéricas, parênteses e <kbd>. </kbd> para inserir dados.
## A Solução

O método `Calculator().Solve ()` recebe e infixa notação de expressão matemática e
resolve isso reorganizando a expressão em [RPN] (https://en.wikipedia.org/wiki/Reverse_Polish_notation) (notação pós-fixada)
usando o [algoritmo do pátio de manobras] (https://en.wikipedia.org/wiki/Shunting-yard_algorithm), por [Edsger Dijkstra] (https://en.wikipedia.org/wiki/Edsger_W._Dijkstra).
Em seguida, ele processa a expressão para gerar o resultado.

A classe `CalculatorBuilder ()` contém os métodos para construir a interface da calculadora e manipular
as interações do usuário.

## Contribuição

Sinta-se à vontade para contribuir com a solução e me dar dicas e conselhos para torná-la melhor :)

## Author

[Azevedo Tau](https://www.facebook.com/azevedocoragemtau.coragem)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details