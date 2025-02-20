Objetivo do projeto
- Segurança na comunicação entre funcionários.

Tecnologias utilizadas:
✅ bcrypt → Hashing seguro de senhas.
✅ PyJWT → Autenticação via Tokens JWT.
✅ cryptography → Implementação de AES e RSA.
Fluxo básico do sistema:
✅ Usuário faz cadastro (senha armazenada com bcrypt).
✅ Usuário faz login (autenticado via JWT).
✅ Usuário envia uma mensagem criptografada com AES.
✅ Apenas o destinatário correto pode descriptografar com sua chave RSA.
