#### Desafio 1: Identificar Portas Abertas

##### Descrição do Desafio
Use o Nmap para identificar portas abertas em um alvo.

##### Ferramentas Utilizadas
- Nmap

##### Passos para Resolução
1. Executei o comando `nmap -sV <IP>`.
2. Identifiquei as portas 80 e 22 abertas.
3. Verifiquei os serviços rodando nessas portas.

##### Comandos Utilizados
```bash
nmap -sV 10.10.10.1