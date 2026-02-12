# ⏱️ Cronômetro Web

Um cronômetro simples e funcional feito com **HTML, CSS e JavaScript
puro**, permitindo iniciar, pausar, continuar e reiniciar a contagem do
tempo em minutos, segundos e milissegundos.

------------------------------------------------------------------------

## 🚀 Funcionalidades

-   ▶️ **Iniciar** o cronômetro\
-   ⏸️ **Pausar** a contagem\
-   🔁 **Continuar** de onde parou\
-   🔄 **Reiniciar** e zerar o tempo\
-   ⏱️ Exibição em **minutos : segundos : milissegundos**\
-   🎨 Interface centralizada e estilizada com CSS

------------------------------------------------------------------------

## 🖥️ Tecnologias utilizadas

-   **HTML5** → Estrutura da página\
-   **CSS3** → Estilização e layout\
-   **JavaScript (Vanilla)** → Lógica do cronômetro e interatividade

------------------------------------------------------------------------

## 📂 Estrutura do projeto

📁 cronometro\
├── index.html\
├── style.css\
└── script.js

------------------------------------------------------------------------

## 📜 Como funciona

O cronômetro utiliza a função `setInterval()` do JavaScript para
atualizar o tempo a cada **10 milissegundos**.\
Os valores de minutos, segundos e milissegundos são armazenados em
variáveis e atualizados dinamicamente na tela através da manipulação do
DOM.

O sistema também controla o estado do cronômetro para evitar múltiplos
intervalos rodando ao mesmo tempo.

------------------------------------------------------------------------

## ▶️ Como executar o projeto

1.  Baixe ou clone este repositório

2.  Abra o arquivo **index.html** no navegador.

Pronto! O cronômetro já estará funcionando 🎉

------------------------------------------------------------------------

## 💡 Melhorias futuras

Ideias para evoluir o projeto:

-   🏁 Botão de **voltas (laps)**
-   ⏱️ Suporte a **horas**
-   🎨 Mudança de cores conforme o estado (rodando / pausado)
-   📱 Melhor responsividade para mobile
