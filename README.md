# Desafio Bootcamp DIO

Este projeto simula um sistema de gestão de um Bootcamp, desenvolvido como parte do desafio da Digital Innovation One (DIO). O sistema permite:

- Gerenciar Bootcamps com informações como nome, descrição, datas de início e fim.
- Criar e gerenciar cursos e mentorias dentro de um Bootcamp.
- Inscrever desenvolvedores nos Bootcamps e acompanhar seu progresso nos conteúdos.
- Calcular a experiência adquirida pelos desenvolvedores com base nos conteúdos concluídos.

## Classes Principais

### Bootcamp

Representa um Bootcamp, contendo nome, descrição, datas, desenvolvedores inscritos e conteúdos oferecidos.

### Conteudo

Classe abstrata base para cursos e mentorias, com métodos para calcular XP.

### Curso

Extensão de `Conteudo` que inclui carga horária e calcula XP baseado nela.

### Mentoria

Extensão de `Conteudo` que inclui data e calcula XP com valor fixo adicional.

### Dev

Representa um desenvolvedor inscrito no Bootcamp, com métodos para inscrição, progressão nos conteúdos e cálculo de XP total.

### Main

Classe principal que demonstra a utilização das classes acima.

## Funcionalidades

- Criação, gestão e inscrição em Bootcamps.
- Gestão de cursos e mentorias.
- Acompanhamento do progresso dos desenvolvedores nos conteúdos.
- Cálculo de XP com base nos conteúdos concluídos.

## Execução

1. Clone o repositório.
2. Importe o projeto em uma IDE Java.
3. Execute a classe `Main` para ver o funcionamento do sistema.

## Contribuições

Contribuições são bem-vindas via issues e pull requests.


## Licença

Este projeto está licenciado sob a licença MIT. Para mais detalhes, consulte o arquivo [LICENSE](https://github.com/devzone1001/Abstraindo-um-Bootcamp-Usando-Orienta-o-a-Objetos-em-Java/blob/main/LICENSE) neste repositório.
