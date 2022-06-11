![>>> Abra esse README.md no modo de 'Preview' para melhor visualização <<<](assets/20220611_132120_Cover_CodeIgualUmKenzieAcademy.png)

# Simulado de Entrevista Técnica

Esse simulado de entrevista técnica tem como finalidade **testar os conhecimentos adquiridos durante sua jornada aqui no M2**, então procura fazer ela em um local tranquilo, livre de distrações e interrupções.

Ah, e...

```js
console.log("Haaaaaaaaaappy Hacking! ;)");
```

## 🗺️ | Sumário

_Se os links não funcionarem, é por causa dos emojis ;)_

- [Simulado de Entrevista Técnica](#simulado-de-entrevista-técnica)
  - [🗺️ | Sumário](#️--sumário)
  - [ℹ | Informações](#ℹ--informações)
    - [⏱️ Duração da entrevista](#️-duração-da-entrevista)
    - [🧑‍💻 Local de aplicação](#-local-de-aplicação)
    - [🛠️ Ferramentas necessárias](#️-ferramentas-necessárias)
    - [📋 Ementa](#-ementa)
  - [⚠️ | Regras](#️--regras)
    - [❌ Não é permitido](#-não-é-permitido)
    - [✅ É permitido](#-é-permitido)
  - [💠 | Entrevista Técnica (Instruções)](#--entrevista-técnica-instruções)
  - [💡 | Recomendações](#--recomendações)
  - [❓ | Dúvidas frequentes](#--dúvidas-frequentes)
  - [💯 | Correção](#--correção)

## ℹ | Informações

### ⏱️ Duração da entrevista

> `5 minutos para ler + 30 minutos para desenvolver`

### 🧑‍💻 Local de aplicação

> `Visual Studio Code`

### 🛠️ Ferramentas necessárias

> `Extensão Live Share`

### 📋 Ementa

> `Construção de classes (estáticas, convencionais e estendidas) e seus métodos`

## ⚠️ | Regras

**Leia todas as instruções** abaixo com atenção antes de iniciar o seu simulado:

### ❌ Não é permitido

> - **Usar mais de um monitor** (tela do computador).
> - Fazer o simulado **sem uma câmera/webcam ou internet estável**
> - **Criar arquivos adicional**, pois esse projeto já possui tudo o que é necessário para desenvolver a solução esperada \*.
>   - O seu código precisará ser desenvolvido [nesse arquivo](./script.js).
> - **Receber ajuda de outra pessoa** durante a aplicação da simulado via Slack, Discord ou outro meio de comunicação.
> - **Pesquisar em locais que não sejam/levem para as documentações oficiais**, como anotações pessoais, canvas, etc.
> - **Pesquisar por uma solução pronta** para o exercício.
> - **Testar o código desenvolvido** usando console.log, a extensão Code Runner ou qualquer outro método.
> - **Copiar o código** após o fim do simulado para testar ou compartilhar com outro dev.

### ✅ É permitido

> - **Fazer perguntas** caso não tenha entendido o que foi pedido.
> - **Pesquisar somente nas documentações oficiais** ([MDN](https://developer.mozilla.org/en-US/) e [W3Schools](https://www.w3schools.com/)).
> - **Pesquisar dúvidas matemáticas** (sem relação com programação).
> - **Usar calculadora** da sua máquina.
> - **Fazer testes de mesa** do código desenvolvido.
>   - _Pode criar um arquivo .csv caso deseje_ \*.

Agora, respire, foque e **bora começar a sua entrevista ;)**

## 💠 | Entrevista Técnica (Instruções)

[INSTRUÇÕES DO WB SÃO COLOCADAS AQUI]

## 💡 | Recomendações

- 🧘 Faça esse simulado em um **lugar calmo, sem distrações e interrupções**.
- ➗ **Divida metade da tela para o script.js e a outra para o README.md**, assim fica mais fácil de você ir desenvolvendo e relendo o que está sendo pedido.
- 📝 **Comente o que você precisa fazer**, como se fosse uma lista.

  - E/ou você pode marcar no próprio README.md o que você já desenvolveu (editar ele)
  - Ex.:

    ```js
    /* O QUE PRECISO FAZER */
    // |- Classe Tal que recebe isso, aquilo e aquilooutro
    //    |-Terá um método X que fará tal coisa
    // |- ETC, ETC, ETC...
    ```

- 🗺️ E **comente o que cada método faz**, bem como a lógica do seu interior (se você precisar, claro!)

  - Assim, você não se perderá na lógica do seu código com tanta facilidade, e caso se perca, só ler os comentários para tentar voltar nos trilhos.
  - Ex.:

    ```js
        [...]

        /* Método estático que verifica se o usuário aceitou os cookies */
        static aceitarCookies(usuario) {

            // Se o usuário aceitar cookies, chamar a função coletarDados
            if (usuario.aceitouCookies) {
                coletarDados();

            // Se ele não aceitar, chamar a função coletarDados da mesma forma >:(
            } else {
                coletarDados();
            }
        }

        [...]
    ```

- 🔙 Se você **se perder durante o desenvolvimento**, volte e leia o seu código de cabo a rabo, tendo pegar de volta o flow do código.
- 🧮 Se você **não souber fazer algo**, tente escrever/quebrar o que foi pedido em partes e depois associe as devidas lógicas e métodos.

  - E sempre procure na documentação o que você tiver dúvida.

- 🗣️ **Fale em voz alta o que você está fazendo**, assim você ajuda o seu aplicador a entender a sua lógica e se ajuda a perceber inconsistências lógicas.
- 🔎 No final, se sobrar tempo, **compare cada linha do seu código com o que foi pedido** no README.md para validar se está tudo de acordo. Vai na minha, isso me salvou uma vez ;).

## ❓ | Dúvidas frequentes

> 1. **O que é uma classe estática?**
>    - É uma classe que não possui construtor e todas as suas propriedades e métodos são estáticos.

> 2. **Posso usar outros nomes de variáveis/parâmetros, classes e métodos?**
>    - O nome das classes e métodos precisam ser iguais aos indicados nesse README.md, mas os nomes das variáveis e/ou parâmetros ficam de sua escolha, mas usar os nomes sugeridos ficará mais fácil de visualizar para que servem.

> 3. **Posso instanciar uma classe e usar os seus métodos?**
>    - Você pode, mas somente para ter uma melhor visualização do que está construindo, e não será considerado durante a correção.
>    - Se você usar essas instâncias e chamadas de métodos para testar o seu código, seu simulado será passível de cancelamento.

> 4. **Se o meu simulado for interrompido (por perda de conexão com a internet, problemas com a extensão do Live Share, entre outros), o que acontece?**
>    - Se acontecer alguma interrupção durante a aplicação desse WB, o tempo será pausado até que ela seja resolvida.
>    - Agora, se essa interrupção durar mais que 5 minutos, seu WB terá que ser reagendado.

Se tiver alguma dúvida com relação a este README.md, não deixe de **tirá-la com seu aplicador**, beleza?

## 💯 | Correção

Essa área será **usada para fazer a correção do seu simulado**, então você pode ignorar isso ;)
