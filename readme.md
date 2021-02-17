# Devman

## O que é isso?

Esse é meu manual pessoal de desenvolmento de software ou **Dev**eloper **Man**ual, onde eu escreverei sobre assuntos que tenho dúvida, tenho interesse ou simplesmente quero escrever. Então você verá desde principios da programação como [SOLID][SOLID] até coonceitos mais diferentes como [ROP][ROP], usando basicamente F# e C# como linguagens de programação.

## Porque Devman?

Em sistemas operacionais baseados em Unix existe um comando chamado [man][man] que apresenta a página de manual de um comando, seu funcionamento é bem simples basta colocar em seu console `man <command>` e pronto.
Mas pensando no funcionamento do comando o certo não seria Mandev? sim, mas prioraria a legibilidade e perderia graça.

## A Stack

Para facilitar a interação e o desenvolvimento dos exemplos será utilizado Jupyter-notebooks com o Jupyter-lab para o front-end. Agora para o desenvolvimento dos exemplos será usado Microsoft interact que adiciona F#, C# e Powershell kernels para o Jupyter-notebook.
Já para o ambiente a utilização de um container é quase que obrigatória, tanto para seja possível fazer o deploy quanto para o desenvolvimento dos exemplos, a escolha quase que obvia foi Docker.

[man]:https://en.wikipedia.org/wiki/Man_page
[SOLID]: https://en.wikipedia.org/wiki/SOLID#:~:text=In%20object%2Doriented%20computer%20programming,Martin.
[ROP]: https://fsharpforfunandprofit.com/rop/