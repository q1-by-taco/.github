# 🛡️ Política de Segurança e Divulgação Responsável (Security Policy)

A **Q1 by TACO** prioriza a segurança cibernética, a integridade de dados e a transparência em todos os seus projetos de código aberto.

---

## 1. Versões Suportadas

| Repositório | Versão Suportada | Suporte Ativo |
| :--- | :---: | :---: |
| **`gemini-antigravity-hub`** | `>= 1.0.0` | 🟢 Sim |
| **`context-eval-engine`** | `>= 1.0.0` | 🟢 Sim |
| **`pull-shark-quest`** | `>= 1.0.0` | 🟢 Sim |
| **`prompt-engineering-corpus`**| `>= 1.0.0` | 🟢 Sim |

---

## 2. Padrões de Segurança Criptográfica

1. **Assinaturas Criptográficas:** Todos os commits em repositórios da organização são assinados digitalmente com chaves SSH assimétricas (Ed25519) vinculadas à identidade de Márcio Krefta.
2. **Prevenção de Injeção de Prompt (OWASP LLM01):** Nossos servidores e bibliotecas integram analisadores estáticos e delimitadores semânticos para mitigar injeções diretas e indiretas de comandos.
3. **Higienização de Segredos:** Filtros pré-commit automatizados impedem o vazamento de chaves privadas, tokens de acesso pessoal ou variáveis de ambiente.

---

## 3. Notificação de Vulnerabilidades (Divulgação Responsável)

Caso identifique qualquer potencial vulnerabilidade de segurança, solicitamos que nos comunique de forma privada e responsável:
- **Canal de Segurança:** Envie e-mail detalhado para `security@q1taco.com` com título `[SECURITY ADVISORY]`.
- **Compromisso de Resposta:** Nossa equipe técnica responderá em até 24 horas úteis com o plano de remediação.
