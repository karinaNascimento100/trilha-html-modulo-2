## Observações sobre a implementação

Este projeto seguiu as orientações do desafio, utilizando o arquivo `template.html` e a estrutura sugerida como base. Optamos por um menu de navegação superior (ao invés do menu lateral do exemplo) para proporcionar uma experiência mais moderna e responsiva, mantendo o padrão de header com imagem, content e footer em todas as páginas.

**Foram utilizados recursos básicos de CSS e JavaScript apenas para compor a estética, responsividade e experiência do usuário, sem objetivo de segurança ou backend.**

Todos os requisitos de conteúdo, navegação e estrutura foram atendidos, incluindo formulários, tabelas, mídias e navegação entre páginas.

# Clínica Prime Saúde e Bem-Estar

Este projeto é o resultado do desafio do Módulo 2 de HTML da DIO.me, com adaptações para uma experiência mais moderna e responsiva.

## Estrutura e Tecnologias

- Todas as páginas seguem um padrão: menu de navegação superior, header com imagem, conteúdo centralizado e footer com informações de contato.
- O menu é horizontal (no topo), diferente do template lateral sugerido, para melhor usabilidade e visual.
- **Foram utilizados recursos básicos de CSS e JavaScript apenas para compor a estética, responsividade e experiência do usuário, sem objetivo de segurança ou backend.**
- O site é totalmente estático, sem backend ou banco de dados.

## Funcionalidades e Conteúdo

### Menu de Navegação
Presente em todas as páginas, permite acesso rápido à Página Principal, Sobre, Horários e Contato.

### Página Principal
- Imagem de header acolhedora.
- Breve apresentação da clínica, missão e diferenciais.
- Lista dos principais procedimentos oferecidos.

### Sobre a Clínica
- Imagem de header exclusiva.
- Texto institucional sobre a história, missão e valores da clínica.
- Lista detalhada dos procedimentos e especialidades.

### Horário de Atendimento
- Imagem de header diferente das demais, com tema natureza/ambiente médico.
- Texto introdutório sobre os serviços.
- Tabela com horários e preços a partir de R$ 250 para cada procedimento:

| Procedimento                 | Segunda a Sexta | Sábados     | Preço (a partir de) |
|------------------------------|-----------------|-------------|---------------------|
| Fisioterapia motora          | 08h - 18h       | 08h - 12h   | R$ 250              |
| Terapia ocupacional          | 08h - 18h       | 08h - 12h   | R$ 250              |
| Reabilitação cardiopulmonar  | 08h - 18h       | 08h - 12h   | R$ 300              |
| Dor crônica e lombalgia      | 08h - 18h       | 08h - 12h   | R$ 250              |
| Pós-operatório ortopédico    | 08h - 18h       | 08h - 12h   | R$ 280              |
| Neurologia (AVC, TCE)        | 08h - 18h       | 08h - 12h   | R$ 350              |
| Pilates clínico              | 08h - 18h       | 08h - 12h   | R$ 250              |
| Fonoaudiologia               | 08h - 18h       | 08h - 12h   | R$ 250              |

### Contato
- Imagem de header exclusiva.
- Telefones de contato (fixo e celular/whatsapp).
- Endereço completo da clínica.
- Iframe do Google Maps com localização.
- Formulário de contato com validação HTML (nome, telefone, e-mail, assunto, mensagem até 500 caracteres).
- Envio do formulário exibe mensagem de sucesso na tela (via JavaScript), sem recarregar a página.

## Observações

- O projeto foi adaptado para um visual mais agradável e moderno, mantendo todos os requisitos de conteúdo, navegação e estrutura do desafio.
- O template sugerido foi usado como inspiração, mas a navegação foi aprimorada para melhor experiência do usuário.
- CSS e JavaScript foram usados apenas para fins estéticos e de usabilidade, **sem objetivo de segurança**.

---

Desenvolvido para o desafio DIO.me - Trilha HTML Módulo II.