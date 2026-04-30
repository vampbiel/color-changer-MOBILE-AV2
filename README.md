# Avaliação Formadora 2 (ADS)

Este projeto foi desenvolvido como parte da Avaliação Formadora da disciplina de **Desenvolvimento de Aplicativo Mobile** do curso de Análise e Desenvolvimento de Sistemas. O objetivo é demonstrar competências no consumo de dados e manipulação de propriedades dinâmicas utilizando o framework **Ionic**.

## 📱 Funcionalidades

A aplicação consiste em duas telas principais:

1.  **Tela Inicial (Home):**
    *   Cartão de identificação do aluno com foto.
    *   Exibição de dados acadêmicos: Nome, Turma, Unidade, Turno e Palavra-chave.
    *   Botão de navegação para a segunda tela ("Ir para Color Change").

2.  **Tela Color Change:**
    *   Interface para manipulação de cores utilizando sliders (`ion-range`) para os canais **Vermelho (R)**, **Verde (G)** e **Azul (B)**.
    *   **Alterar Cor do Botão:** Aplica a cor selecionada via RGB ao fundo do botão principal.
    *   **Alterar Cor de Fundo:** Aplica a cor selecionada via RGB ao fundo da tela (`ion-content`) utilizando **CSS Custom Properties**.
    *   **Navegação:** Suporte a `ion-back-button` para retorno à tela inicial.

## 🛠️ Tecnologias Utilizadas

*   **Ionic Framework:** v8.x
*   **Angular:** v20.x (Standalone Components)
*   **Capacitor:** v8.x (Para integração nativa Android)
*   **TypeScript:** Linguagem de programação principal.
*   **SCSS:** Para estilização avançada e uso de variáveis CSS.

## 🚀 Como Executar o Projeto

### Pré-requisitos
*   Node.js instalado.
*   Ionic CLI instalado (`npm install -g @ionic/cli`).

### Instalação
1. Clone o repositório ou descompacte o arquivo.
2. Navegue até a pasta raiz do projeto.
3. Instale as dependências:
   ```bash
   npm install
   ```

### Execução no Navegador
Para testar a interface rapidamente:
```bash
ionic serve
```

### Gerando o APK (Android)
1. Realize o build do projeto web:
   ```bash
   npm run build
   ```
2. Sincronize com o Capacitor:
   ```bash
   npx cap sync android
   ```
3. Abra no Android Studio:
   ```bash
   npx cap open android
   ```
4. No Android Studio, vá em **Build > Build Bundle(s) / APK(s) > Build APK(s)**.

## 👤 Autor
*   **Nome:** Gabriel da Silva Rocha

---
*Projeto desenvolvido para fins acadêmicos - UNISUAM 2026.*
