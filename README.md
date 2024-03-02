<h1 align="center"> Projeto Fokus </h1>

<p align="center">  </p>

<div align="center">

  <a href="https://github.com/coelhoalexandre/projeto-alura-fokus/blob/main/LICENSE" target="_blank"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT"></a> <img src="https://img.shields.io/badge/Completo-lightgreen.svg" alt="Completo">

</div>

## Sumário

- [Sobre o Projeto](#sobre-o-projeto)
- [Objetivos do Projeto](#objetivos-do-projeto)
- [Funcionalidades do Projeto](#funcionalidades-do-projeto)
- [Tecnologias Utilizadas](#tecnolgias-utilizadas)
- [Layouts](#layouts)
  - [Desktop Layout](#desktop-layout)
  - [Tablet Layout](#tablet-layout)
  - [Mobile Layout](#mobile-layout)
- [Autor](#autor)

## Sobre o Projeto

Metade deste projeto foi feito com a instrução de [**Luan Alves**](https://github.com/luanalvesdev) no curso [JavaScript: manipulando elementos no DOM](https://cursos.alura.com.br/course/javascript-manipulando-elementos-dom), no qual ele ensina a manipular os elementos no DOM por meio do JavaScript, a parte que é observada pelo temporizador.

A outra metade foi com a instrução de [**Vinicios Neves**](https://github.com/viniciosneves) no curso [JavaScript: explorando a manipulação de elementos e da localStorage](https://cursos.alura.com.br/course/javascript-manipulacao-elementos-localstorage), no qual ele ensina, principalmente, a como armazenar e coletar dados do localStorage.



## Objetivos do Projeto

- Conhecer métodos de manipulação do DOM;
- Aprender a alterar atributos e classes de forma dinâmica;
- Criar interação da página com o usuario;
- Gerenciar eventos do usuário;
- Manipular arrays;
- Avaliar e implementar estratégias para persistência de dados no navegador através do localStorage.

## Funcionalidades do Projeto

<div align="center" >
<img src="https://github.com/coelhoalexandre/projetos-alura/blob/main/imagens/fokus-interface.png" alt="Interface do Fokus">
</div>

- **Foco, Descanso Curto e Descanso Longo:** Ao serem clicados, esses botões alteram o dinamicamente o tema da página e o timer. Sendo 25:00, 05:00 e 15:00 respectivamente. Padrão: Foco.
- **Música:** Ao alternar o estado deste interruptor, uma música começará a tocar ou irá parar de tocar. Padrão: Desativado.
- **Começar/Pausar:** Ao pressionar o botão "Começar" o timer irá se iniciar/retomar e botão irá alterar para "Pausar". Pressionando "Pausar" o timer para e o botão altera para "Começar". Padrão: Começar
- **Timer Zerado:** Quando o timer chegar a 0 irá começar a tocar um beep e um alert informará "Tempo finalizado!". Em seguida o timer voltará ao seu valor inicial.

<br>

<div align="center" >
<img src="https://github.com/coelhoalexandre/projetos-alura/blob/main/imagens/fokus-lista-de-tarefas.png" alt="Lista de Tarefas">
</div>

- **Adicionar nova tarefa:** Abre o formulario "Adicionando tarefa"
- **Deletar:** Apaga o texto digitado na parte "No que você está trabalhando?".
- **Cancelar/Esc:** Fecha o formulario.
- **Salvar:** Armazena o texto digitado no localStorage e apresenta na "Lista de tarefas:" como uma nova tarefa.
- **Clicar na tarefa:** Essa ação faz com que surja uma borda branca em volta dela e seu nome vá para a parte "#Em andamento:"
- **Lapis de Edição:** Aparece um prompt questionando o novo nome e ao ser escolhido altera-o. Deixa a caixa vazia ou cancelar não mudará o nome.
- **Limpar tarefas concluídas:** Apaga somente as tarefas concluídas da lista.
- **Limpar todas tarefas:** Apaga todas as tarefas da lista.
- **Timer Zerado com tarefa '#Em Andamento':** A tarefa não estará mais em andamento e assumirá uma cor verde. Além disso, ela não pode ser clicacada e seu nome não pode ser alterado.

Obs.: Todas as tarefas e seus atributos são salvos no seu localStorage, por isso mesmo que reset a página as informações ainda estaram salvas no seu site.

**Forma manual de concluir uma tarefa no console:**

<img src="https://github.com/coelhoalexandre/projetos-alura/blob/main/imagens/fokus-forma-manual-de-concluir-tarefas.png" alt="Codigos no Console para conclusão de uma tarefa">

```
const evento = new CustomEvent("FocoFinalizado")

document.dispatchEvent(evento)
```
## Tecnolgias Utilizadas

1. HTML
2. CSS
3. JS

## Layouts

### Desktop Layout

**Width 1280px:** https://github.com/coelhoalexandre/projetos-alura/blob/main/imagens/fokus-1280px.jpg

### Tablet Layout

**Width 768px:** https://github.com/coelhoalexandre/projetos-alura/blob/main/imagens/fokus-768px.jpg

### Mobile Layout

**Width 480px:** https://github.com/coelhoalexandre/projetos-alura/blob/main/imagens/fokus-480px.jpg

## Autor

Meu nome é **Alexandre Coelho**, sou autor deste ReadMe e estudante de Desenvolvimento Web. Por meio das instruções de [**Luan Alves**](https://github.com/luanalvesdev) e [**Vinicios Neves**](https://github.com/viniciosneves), fiz esse projeto. Fiz algumas pequenas alterações do projeto original, como por exemplo poder ativar o "Cancelar" com o "Esc" e o reset do timer após a finalização dele. No demais, o código foram entregues e ensinados no curso.

Logo abaixo estão os meus principais links, fique a vontade de acessar o que mais lhe interessar:

<br>

<br>

<div align="center">

<a href = "https://github.com/coelhoalexandre"><img src="https://img.shields.io/badge/GitHub-%23333?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Badge"></a>
<a href="https://www.linkedin.com/in/-coelhoalexandre/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"></a>
<a href = "mailto:alexandrecoelhocontato@gmail.com" target="_blank"><img src="https://img.shields.io/badge/-Gmail-critical?style=for-the-badge&logo=gmail&logoColor=white" target="_blank" alt="Gmail Badge"></a>
<a href = "https://cursos.alura.com.br/user/coelhoalexandre" target="_blank"><img src="https://img.shields.io/badge/Alura-0747a6?style=for-the-badge&logo=alura&logoColor=white" target="_blank" alt="Alura Badge"></a>
<a href = "https://www.frontendmentor.io/profile/coelhoalexandre" target="_blank"><img src="https://img.shields.io/badge/Frontend_Mentor-white?style=for-the-badge&logo=frontendmentor&logoColor=blue" alt="FrontEnd Mentor Badge">
