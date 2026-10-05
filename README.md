# AMX Academia — Demo de Presenças

Demonstração estática e pública do app de chamada de presença da AMX Academia.

**Esta demo roda 100% no navegador.** Não há backend, banco de dados nem
credenciais reais envolvidas — todos os dados são fictícios e ficam apenas na
memória da aba. Nenhuma informação é enviada para lugar nenhum.

## Como entrar

Clique no botão de preenchimento na tela de login, ou digite um destes logins
com **qualquer senha não vazia**:

| Login | Perfil | O que você vê |
|---|---|---|
| `marcos.siam` | Líder | Todas as turmas |
| `joao.silva` | Instrutor | Apenas as turmas dele |

## Roteiro sugerido (3 minutos)

1. Entre como `marcos.siam` e escolha uma data no calendário (domingo mostra o
   estado vazio, sem aula).
2. Veja a sugestão automática da turma mais próxima do horário.
3. Abra a chamada, marque as presenças e salve — a lista fica bloqueada.
4. Toque em **Alterar chamada** para reabrir a edição.
5. Repita entrando como `joao.silva` para ver a visão restrita do instrutor.

## Limites conhecidos

- As presenças marcadas ficam só na memória da aba: recarregar a página limpa
  tudo. Não há persistência.
- É uma versão de demonstração: o visual está congelado e serve para validar o
  fluxo, não para uso em produção.

---

Código-fonte completo e integração com banco de dados: repositório privado
`Ralph-zlt/amxacademia`.
