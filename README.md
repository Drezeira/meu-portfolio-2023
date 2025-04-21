# Meu Portfólio 2025 - Andre Felipe

Este é o repositório do meu portfólio pessoal versão 2025, desenvolvido para apresentar minhas habilidades, experiências e informações de contato.

## ✨ Visão Geral

O portfólio é uma página web estática, criada com foco em design responsivo e moderno. Ele inclui seções sobre mim, minhas experiências profissionais anteriores, minhas habilidades técnicas atuais e em desenvolvimento, e um formulário de contato.

## 🚀 Tecnologias Utilizadas

- **HTML5**: Para a estrutura semântica do conteúdo.
- **CSS3**: Para estilização, layout (Flexbox) e responsividade.
  - Google Fonts (Rubik)
  - Bootstrap Icons
- **JavaScript**: (Mínimo/Potencial) - Apenas para funcionalidades futuras como menu mobile ou validação de formulário avançada.

## 🌐 Link para o Site (GitHub Pages)

Você pode visualizar o portfólio online aqui:

**[https://Drezeira.github.io/meu-portfolio-2025/](https://Drezeira.github.io/meu-portfolio-2025/)**

_(**Observação:** Certifique-se de que o nome do seu repositório e seu nome de usuário do GitHub estejam corretos neste link após o deploy.)_

## 🔧 Como Executar Localmente

1.  Clone este repositório:
    ```bash
    git clone [https://github.com/Drezeira/meu-portfolio-2025.git](URL)
    ```
    _(Substitua pelo URL correto do seu repositório)_
2.  Navegue até a pasta do projeto:
    ```bash
    cd meu-portfolio-2025
    ```
3.  Abra o arquivo `index.html` diretamente no seu navegador de preferência.

## 📝 Atualizando o Formulário de Contato

O formulário de contato está configurado para usar um serviço externo como [Web3Forms](https://web3forms.com/) ou [Formspree](https://formspree.io/). Para que funcione:

1.  Escolha um serviço e crie uma conta gratuita.
2.  Obtenha sua "Access Key" ou URL de endpoint do formulário.
3.  Abra o arquivo `index.html`.
4.  Encontre a tag `<form>` na seção de contato.
5.  Atualize o valor do `action` (se usar Formspree) ou o `value` do input `hidden` com `name="access_key"` (se usar Web3Forms) com a sua chave/URL.
6.  (Opcional) Atualize o `value` do input `hidden` com `name="redirect"` para uma página de agradecimento personalizada.

## 🚧 Próximos Passos (Sugestões)

- Adicionar projetos reais à medida que forem concluídos.
- Implementar um menu mobile funcional ("hambúrguer").
- Otimizar imagens para melhor performance.
- Adicionar animações mais sutis ou microinterações com CSS ou JavaScript.
- Considerar um tema claro/escuro.
