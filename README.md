# dio-bc
DIO Cybersecurity Boot Camp

## Este repositório contém os desafios práticos desenvolvidos durante o aprendizado

### Ferramentas utilizadas
- S.O Kali Linux
- setoolkit

## Como criar um site clonado para roubar credenciais
- Altere para o modo privilegiado "root": ```sudo su ```
- Execute a ferramenta SEToolkit: ```setoolkit ```
- Selecione o Tipo de ataque: ```1) Social-Engineering Attacks ```
- ![Alt text](./attk-type-1.png)

- Selecione o Vetor de ataque: ```2) Web Site Attack Vectors ```
- ![Alt text](./web-attk-vector.png)

- Selecione o Método de ataque: ```3) Credential Harvester Attack Method ```
- ![Alt text](./attk-met-cred-harv.png)
  
- Selecione o Método: ```2) Site Cloner ```
- ![Alt text](./site-cloner.png)
  
- Aperte enter para confirmar o uso do IP local da VM:
- ![Alt text](./priv-ip-set.png)

- Adicione uma URL para clonar a página
- Ex: ```http://www.facebook.com```
- ![Alt text](./fb-page.png)

- ![Alt text](./fb-cloning.png)

### Em uma máquina 'cobaia', faça o acesso no navegador busacando pelo IP configurado


### Resutados

![Alt text](./passwd.png "Optional title")
