1. LFI - Web Application: Local File Inclusion (LFI)
Arquivo: LFI-http___social.buggywebsite.com_Write-Up.pdf

Técnicas Exploradas:
- Análise de código frontend
- SSRF (Server-Side Request Forgery )
- LFI (Local File Inclusion)
- Exploração de metadados

Ferramentas Utilizadas:
- Burp Suite
- Listener de rede
- Análise de código

## 🛡️ Mitigação e Defesa

- Active Directory: Monitoramento de atividade Kerberos, políticas de senha fortes, auditoria de permissões e ACLs, a princípio o mais importante aqui é a aplicação do princípio do menor privilégio
- Web Applications: Validação de entrada, implementação de WAF, sanitização de dados