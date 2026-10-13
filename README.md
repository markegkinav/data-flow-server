# Introdução


### Lembrete

Este trecho foi anotado durante os estudos e nao substitui a documentacao oficial.

O primeiro comando usado como exemplo foi:

```
expo init react-nav --npm
```

Criei um projeto com ele escolhendo o modelo em TypeScript, dentro da pasta `tests\02`.

Também criei outro em `tests\01` com o comando que eu já conhecia:

```
npx create-expo-app example-app -t
```

Nesse caso o modelo escolhido também foi o TypeScript enxuto.

O professor preferiu partir do modelo enxuto em vez do modelo com abas já montadas, justamente para construir a navegação do zero e explicar os conceitos no caminho.


# Explorando o app criado para estudo

Daqui pra frente o foco é o projeto dentro de `tests\02\react-nav`.

Vale lembrar: ele nasceu do comando `expo init react-nav --npm`.


# app.json

O arquivo de configuração concentra, por exemplo, os ajustes de ícone do aplicativo.

![configuração do app](images/app-json.png)


# App.tsx

Segundo o professor, esse arquivo é a mesa onde as peças de montar são encaixadas.

![App.tsx](images/App-tsx.png)


# Letra maiúscula no nome dos componentes

A orientação é começar o nome de todo componente com maiúscula.

![maiúscula inicial](images/first-letter-in-uppercase-in-components.png)

Também foi dito que é boa prática criar uma pasta de telas e guardar ali os arquivos correspondentes, como numa imagem anterior.

E todo arquivo de tela é, por definição, um componente.


# Tela básica

O esqueleto de uma tela simples ficou assim:

![esqueleto de tela](images/skeleton-of-a-basic-screen.png)


# Várias telas no mesmo aplicativo

Quando o app passa a ter várias telas, o arquivo principal vira um concentrador: ele escolhe qual tela mostrar, e cada tela carrega o próprio conteúdo.

O conteúdo básico do arquivo principal:

![conteúdo básico](images/basic-content-of-a-screen.png)

A troca entre telas fica a cargo de um pacote específico de navegação.


# Documentação

A referência da biblioteca de navegação fica no site do projeto.

Lá está, por exemplo, o comando de instalação:

```
npm install @react-navigation/native
```


# Pré-requisitos

![pré-requisitos](images/pre-requisites.png)


# Dependências extras num projeto com Expo

```
npx expo install react-native-screens react-native-safe-area-context
```

Para projetos criados sem o Expo, o procedimento está na documentação da biblioteca.


# Projeto de exemplo mínimo

A documentação tem uma seção específica com um projeto mínimo de navegação, útil para começar do zero:

![projeto de exemplo](images/hello-react-navigation.png)


# Repositório da turma

O código base das aulas está num repositório público da trilha.


# Requisitos

![requisitos](images/requirements.png)


# Links externos

O site oficial da biblioteca, citado em aula, tem a documentação completa e um aplicativo de demonstração que pode ser baixado pelo botão de teste.

![site da biblioteca](images/react-navigation-home.png)


# Continuação

O assunto de navegação continua no próximo repositório da série, que aprofunda a pilha de telas.