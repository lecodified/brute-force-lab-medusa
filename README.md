# Lab de Cibersegurança: Ataque de Força Bruta com Medusa

## Descrição
Este projeto faz parte do desafio da DIO e simula um cenário real de auditoria de segurança. O objetivo é realizar ataques de força bruta em serviços comuns (FTP, SSH, SMB) para identificar vulnerabilidades de credenciais fracas.

## Ambiente de Laboratório
- **Atacante:** Kali Linux (Rolling Edition)
- **Vítima:** Metasploitable 2 (IP: 192.168.56.101)
- **Rede:** Host-only (Isolada)
- **Ferramentas:** Medusa, Nmap, fping.

##  Cenários Testados
1. **Enumeração de Serviços:** Uso do Nmap para identificar portas abertas.
2. **Brute Force FTP:** Tentativa de quebra de senha no serviço de transferência de arquivos.
3. **Password Spraying SMB:** Teste de senhas comuns em múltiplos usuários.

##  Medidas de Mitigação
- Implementação de Políticas de Senhas Fortes.
- Configuração de Fail2Ban para bloqueio de IPs após múltiplas tentativas.
- Desabilitação de serviços desnecessários.

---
Projetado por Leandro Silva Sousa - Estudante de Ciência da Computação.
