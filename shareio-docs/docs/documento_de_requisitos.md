# Documento de Requisitos 

## Projeto

Aplicativo desktop de perguntas e respostas focado em **programação**.  

## Problema

Atualmente, para tirar dúvidas rápidas de programação, o usuário precisa abrir o navegador, pesquisar manualmente e navegar entre várias abas, o que causa **distrações e perda de tempo**.  

## Contexto

O projeto **share.io** tem como objetivo oferecer um **chatbot desktop minimalista** em que o usuário possa digitar sua dúvida técnica e receber uma resposta direta, sem precisar abrir o navegador.  

---

## Descrição dos Requisitos

### Requisitos Funcionais

| ID   | Descrição |
|------|-----------|
| RF01 | O sistema deve permitir que o usuário insira uma pergunta em um campo de texto. |
| RF02 | O sistema deve enviar a pergunta para o backend para processamento. |
| RF03 | O backend deve consultar APIs ou fontes externas para buscar a resposta. |
| RF04 | O sistema deve retornar e exibir a resposta na interface do chat. |
| RF05 | O sistema deve identificar e rejeitar perguntas que não sejam relacionadas a programação, exibindo uma mensagem padrão. |
| RF06 | O sistema deve permitir múltiplas perguntas na mesma sessão. |
| RF07 | O sistema deve exibir as mensagens do usuário e as respostas do chatbot em formato de chat. |

---

### Requisitos Não Funcionais

#### Desempenho
| ID   | Descrição |
|------|-----------|
| RNF01 | O tempo máximo de resposta para cada pergunta deve ser inferior a 5 segundos. |

#### Confiabilidade
| ID   | Descrição |
|------|-----------|
| RNF02 | O sistema deve garantir funcionamento offline limitado (exibir mensagem de erro em caso de falha de conexão). |

#### Segurança
| ID   | Descrição |
|------|-----------|
| RNF03 | Nesta versão inicial, não haverá autenticação ou armazenamento de dados pessoais. |

#### Usabilidade
| ID   | Descrição |
|------|-----------|
| RNF04 | A interface deve ser minimalista, intuitiva e com design **dark** por padrão. |
| RNF05 | A aplicação deve ser acessível a usuários com diferentes níveis de experiência em tecnologia. |

#### Compatibilidade
| ID   | Descrição |
|------|-----------|
| RNF06 | O sistema deve ser compatível com **Linux**. |
| RNF07 | O sistema deve ser desenvolvido em **Flutter (frontend)** e **Node.js/TypeScript (backend)**. |

---

## Resultados Esperados

Espera-se que o sistema entregue:  
- Chat funcional para perguntas de programação.  
- Resposta rápida e objetiva com base em fontes externas.  
- Interface minimalista com design dark.  
- Compatibilidade com desktop em múltiplas plataformas.  

