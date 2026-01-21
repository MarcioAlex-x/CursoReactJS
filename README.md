# CursoReactJS

Curso de ReactJS para iniciantes.

### (Este repositório tem várias branchs, cada uma com um módulo do treinamento)

# Capítulo primeiro
## O que é o ReactJS

O React é uma biblioteca JavaScript muito popular, atual e poderosa para desenvolvimento de aplicações front-end usando o conceito de SPA (Single Page Application), permitindo construir *interfaces de usuários a partir de componentes individuais chamados componentes*.

## Componentes React

Componentes React são funções JavaScript que retornam JSX, uma extensão de sintaxe que permite descrever a interface de forma declarativa. Componentes podem ser compostos dentro de outros componentes. A arquitetura de componentes permite reutilização, organização e separação de responsabilidades da interface, sendo muito usada na construção de SPAs.

## Iniciar um projeto

A forma mais usada até agora, ano de 2026, de se iniciar um projeto em React é usando o **Vite**, a outra maneira usada é através do **create-react-app**, que apesar de ainda funcionar, esta forma de iniciar um projeto foi oficialmente descontinuada em 2025.

Para iniciar um projeto, primeiro é necessário ter uma pasta criada para este fim. Abrir o **cmd** ou mesmo o **Visual Studio Code** no diretório escolhido e se a escolha foi o **cmd**, escrever *npm create vite@latest*, mas se a escolha foi usar o **VSCode**, executar o atalho **ctrl+j** vai abriar o terminal, no terminal é só escrever *npm create vite@latest*, em ambas maneiras o projeito vai começar a ser iniciado.

<img width="177" height="17" alt="image" src="https://github.com/user-attachments/assets/decc5323-d7af-42a9-85a6-0be04c64351d" />  

Durante a inicialização, antes de começar a instalar será visto uma caixa de diálogo onde será possível responder através das setas do teclado e confirmar teclando o enter. 

A primeira pergunta é sobre o nome do projeto, nessa hora não será possível responder com caracteres especiais, letras maiúsculas, parentes ou colchetes.

<img width="123" height="47" alt="image" src="https://github.com/user-attachments/assets/bcf5635b-666f-43aa-a11f-c369f52b868d" />  

A segunda pergunta é sobre qual framework ou biblioteca o vite deve instalar, a resposta nesse caso ,obviamente será **React**. 
Após escolher o **React** como biblioteca o terminal ou prompt irá perguntar de que forma quer que seja preparado o projeto, se com JavaScript ou com TypeScript como variante.

<img width="199" height="206" alt="image" src="https://github.com/user-attachments/assets/c3b279f8-8979-4079-9039-4e820280cd85" /> 

<img width="267" height="201" alt="image" src="https://github.com/user-attachments/assets/b950edc9-38cf-448e-bde1-145eaca308a1" />  

Depois decidir se quer usar o **rolldown-vite** é necessário escolher se deseja que o **npm** instale e inicie o projeto com **npm run dev**.
<br />
<img width="306" height="72" alt="image" src="https://github.com/user-attachments/assets/a7d95f93-44e0-4293-a357-0d5332b9b381" />

<img width="286" height="50" alt="image" src="https://github.com/user-attachments/assets/7368ce24-3985-4b21-b73e-03f00a4e4d1f" />  

*Espere que todas as dependecias sejam instaladas.*

Depois de iniciado aparecerá *Local: http://localhost:5173/*, segurando o *ctrl* e clicando no endereço, que está de cor azulada, logo irá abrir o projeto no navegador.

<img width="286" height="63" alt="image" src="https://github.com/user-attachments/assets/2de80e7c-5bc7-4b89-858c-29d57618c1df" />

No navegador deverá ficar assim:

<img width="1356" height="688" alt="image" src="https://github.com/user-attachments/assets/c1576507-7d74-4c21-9a2e-6bce600170bc" />


## Pastas do projeto.

O projeto **React** vai iniciar com uma estrutura de pastas e arquivos que possibilitam que aconteça a excução do mesmo.

Neste momento você vai ver a seguinte estrutura: *Abaixo um conteúdo criado por IA*

* node_modules
 * Aqui vivem todas as dependências instaladas. É a cidade invisível do projeto. Nenhum humano deveria editar nada ali. O bundler visita essa pasta, coleta o que precisa e segue viagem. Se apagar, tudo pode ser reconstruído com npm install, como regenerar um membro perdido.

* public
 * Arquivos estáticos que não passam pelo processo de build. Ícones, imagens fixas, favicons. Tudo que precisa existir exatamente como foi colocado. O Vite copia essa pasta direto para a versão final do site.

* src
  * O coração pulsante. Aqui mora o código React. É onde você cria componentes, páginas, estilos, hooks, serviços, rotas, estados e tudo que dá personalidade à aplicação.

* main.jsx ou main.tsx
  * O ponto de ignição. Este arquivo pega o React e diz: “renderize o App dentro desta div do HTML”. É a tomada que liga o cérebro ao corpo.

* App.jsx
  * O componente raiz. Pense nele como a sala de controle. Rotas, layout principal, providers de contexto, tudo costuma com

* assets
  * Imagens, fontes, ícones que passam pelo build. Diferente da pasta public, aqui os arquivos podem ser otimizados pelo bundler.

* index.html
  * O único HTML real do projeto. Contém a div onde o React injeta toda a aplicação. Depois disso, o React domina tudo.

* package.json
  * O DNA do projeto. Dependências, scripts, nome, versão. Sem ele, nada nasce.

*vite.config.js
 *Configurações do Vite. Define plugins, caminhos, ajustes de build.
