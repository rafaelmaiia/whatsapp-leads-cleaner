# Filtro de Contatos Inteligente 

Uma ferramenta web 100% client-side, projetada para comparar e filtrar listas de contatos de forma rápida, segura e eficiente, otimizando processos manuais de gestão de grupos.

![Badge de Licença](https://img.shields.io/badge/licen%C3%A7a-MIT-green)
![Badge de Tecnologia](https://img.shields.io/badge/tecnologia-JavaScript-yellow)
![Badge de Estilo](https://img.shields.io/badge/estilo-TailwindCSS-blue)

---

### Visão Geral do Projeto

https://github.com/rafaelmaiia/whatsapp-leads-cleaner/blob/main/assets/demonstracao.gif


Este projeto nasceu de uma necessidade real de otimizar um processo manual e repetitivo: verificar quais contatos de uma grande lista de compradores já se encontravam em um grupo de WhatsApp. A ferramenta permite que o usuário faça o upload de duas listas em formato `.csv` e instantaneamente gera uma lista final com os contatos que precisam ser adicionados, pronta para ser usada.

### Destaques Técnicos

-   **Arquitetura 100% Frontend:** Todo o processamento é feito no navegador do usuário com JavaScript puro (Vanilla JS), garantindo **total privacidade dos dados** e eliminando custos e complexidade de um servidor backend.
-   **Performance Otimizada:** Utilização da estrutura de dados `Set` para a comparação dos contatos, garantindo uma performance quase instantânea (complexidade O(1)) mesmo com milhares de números.
-   **Manipulação de Arquivos no Navegador:** Implementação com a API `FileReader` para ler e processar arquivos `.csv` locais de forma assíncrona, com uma função robusta que normaliza diferentes formatos de números de telefone.
-   **Interface Responsiva e Intuitiva:** Design moderno e limpo construído com **Tailwind CSS**, focado em uma experiência de usuário (UX) clara, com feedback visual em todas as etapas do processo.

### Tecnologias Utilizadas

-   **HTML5**
-   **CSS3** com **Tailwind CSS**
-   **JavaScript (ES6+)** (Vanilla JS)

### Como Usar

1.  Abra o arquivo `index.html` em seu navegador ou acesse o link da aplicação (se hospedado).
2.  Clique em "Escolher Arquivo" para fazer o upload da sua lista de compradores.
3.  Clique no segundo botão para fazer o upload da lista de membros do grupo.
4.  Clique em "Gerar Lista para Contato".
5.  A lista final de contatos a serem adicionados aparecerá na caixa de texto, pronta para ser copiada.

### Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](https://github.com/rafaelmaiia/whatsapp-leads-cleaner/blob/main/LICENSE) para mais detalhes.