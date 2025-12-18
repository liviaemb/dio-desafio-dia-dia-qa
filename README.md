# E-commerce Web App

Aplicação web (Desktop) para e-commerce com autenticação de usuários, vitrine de produtos e menu lateral com ações de sessão — estrutura voltada para organização clara do fluxo e do processo de QA.

---

## 📈 Fluxograma de Trabalho

---

## 📝 User Stories

### US-101 — Autenticação de Usuário (Login)

Como usuário, quero acessar minha conta por meio de uma tela de login para visualizar produtos e realizar compras de forma personalizada.

### US-102 — Adicionar e Remover Produtos do Carrinho

Como usuário, quero adicionar e remover itens do carrinho para controlar minha lista de compras.

### US-103 — Menu Lateral e Reset de Estado da Aplicação

Como usuário, desejo acessar o menu lateral para realizar ações como resetar o estado da aplicação e encerrar minha sessão, facilitando a navegação e o controle da minha conta.

---

## 📋 Exemplo de Board no Jira

---

## 📄 Plano de Testes

O plano abrange os seguintes pontos:
- **Funcionalidades:** Login/autenticação, manipulação do carrinho, menu lateral e reset state.
- **Testes manuais e automatizados** para os principais fluxos.
- **Critérios de Aceite:** Cada user story será considerada concluída apenas quando todos os cenários de teste passarem.

---

## 🧪 Cenários de Teste

| Cenário                                         | Descrição                                                        | Resultado Esperado                   |
|-------------------------------------------------|------------------------------------------------------------------|--------------------------------------|
| Login com usuário válido                        | Acessar com credenciais corretas                                 | Usuário autenticado e redirecionado  |
| Login com usuário bloqueado                     | Tentar login com usuário bloqueado                               | Acesso negado/mensagem de erro       |
| Adicionar item ao carrinho                      | Escolher produto e adicionar ao carrinho                         | Produto aparece no carrinho          |
| Remover último item do carrinho                 | Remover todos os produtos do carrinho                            | Carrinho deve ficar vazio (contador=0) |
| Resetar estado da aplicação                     | Usar opção no menu lateral para resetar app                      | Estado limpo, sem afetar sessão indevidamente |
| Logout pelo menu                                | Selecionar 'Logout' no menu                                      | Sessão encerrada e login solicitado  |

---

## 🐞 Fluxograma de Tratamento de Bugs

1. Identificação
2. Reprodução
3. Registro
4. Priorização
5. Atribuição
6. Análise (Aceite/Rejeição)
7. Correção
8. Reteste
9. Finalizado

---

## 💡 Exemplos de Bugs

- **US-101**
  - **Descrição:** Usuário bloqueado consegue acessar o inventário.

- **US-102**
  - **Descrição:** Contador do carrinho não zera após remover o último item.

- **US-103**
  - **Descrição:** "Reset App State" encerra sessão indevidamente (logout).

---

## 📚 Referências

- Documentação adicional e imagens estão disponíveis no PDF.
