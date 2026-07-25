# Análises Técnicas de Exploração em Segurança

Documentação de técnicas de exploração, enumeração e movimentação lateral em ambientes corporativos. Writeups focados em Active Directory e Web Application Security.

📋 Writeups

1. PUPPY - Active Directory: Kerberoasting e Abuso de ACLs
Técnicas Exploradas:
- Enumeração de domínio e serviços
- Kerberoasting
- Abuso de permissões (GenericWrite)
- Exploração de KeePass
- Elevação de privilégio

Ferramentas Utilizadas:
- BloodHound
- Impacket
- Mimikatz
- KeePass

2. TombWatcher - Active Directory: Targeted Kerberoasting
Técnicas Exploradas:
- Enumeração de SPNs
- Targeted Kerberoasting
- Crack de hashes Kerberos
- Abuso de permissões de grupo

Ferramentas Utilizadas:
- BloodHound
- Impacket
- Hashcat

3. Fluffy - Active Directory: Exploração Completa
Técnicas Exploradas:
- Enumeração de domínio
- Análise de CVEs
- Exploração de permissões
- Abuso de grupos de serviço

Ferramentas Utilizadas:
- BloodHound
- BloodyAD
- Nmap

4. Voleur - Active Directory: Enumeração e Exploração
Técnicas Exploradas:
- Enumeração LDAP
- Exploração de Kerberos
- Enumeração SMB
- Abuso de credenciais

Ferramentas Utilizadas:
- BloodHound
- Impacket
- Crackers de hash

5. LFI - Web Application: Local File Inclusion (LFI)
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
