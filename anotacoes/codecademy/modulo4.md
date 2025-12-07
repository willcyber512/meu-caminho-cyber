Criptografia, Autenticação e Autorização

## O que aprendi
- O papel da criptografia na segurança da informação.
- Diferença entre criptografia simétrica e assimétrica.
- O que é hashing e para que ele é usado.
- Diferença entre autenticação e autorização.
- Por que MFA é mais seguro que senha simples.

## Explicações rápidas
- **Criptografia:** é ocultar dados e disponibilizá-los novamente, de forma que apenas quem possui a chave correta consiga acessá-los.
- **Simétrica:** mesma chave para criptografar e descriptografar (rápida, menos segura para troca).
- **Assimétrica:** usa chave pública e privada (mais segura, mais lenta).
- **Hashing:** função unidirecional usada para verificar integridade e proteger senhas.
- **Autenticação:** verifica quem você é.
- **Autorização:** define o que você pode acessar.
- **MFA:** múltiplos fatores tornam o acesso não autorizado mais difícil.

## Como isso aparece no mundo real / SOC
- HTTPS usa criptografia para proteger credenciais e dados.
- Hashes são usados para verificar integridade de arquivos e senhas.
- Alertas surgem quando MFA falha, tokens expiram ou credenciais são usadas fora do padrão.
- Controle de acesso incorreto gera riscos de privilégio excessivo.

## O que ainda preciso reforçar
- Algoritmos modernos (AES, RSA, SHA-256).
- Logs de autenticação e autorização em ambientes reais.
- Análise de falhas de MFA e OAuth.
