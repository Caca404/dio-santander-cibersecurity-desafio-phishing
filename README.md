# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
![Alt text](./passo1.jpg)
- Iniciando o setoolkit: ``` setoolkit && y ```
![Alt text](./passo2.jpg)
- Tipo de ataque: ``` Social-Engineering Attacks ```
![Alt text](./passo3.jpg)
- Vetor de ataque: ``` Web Site Attack Vectors ```
![Alt text](./passo4.jpg)
- Método de ataque: ```Credential Harvester Attack Method ```
![Alt text](./passo5.jpg)
- Método de ataque: ``` Custom Importer ```
![Alt text](./passo6.jpg)
- Visite a página do facebook, salve como index.html
![Alt text](./passo7.jpg)
- Pegue o código fonte e salve no novo index.html
![Alt text](./passo8.jpg)
- Procure dentro do index.html o script com o atributo data-bootloader-hash e apague
- Volte ao setoolkit e coloque o caminho da pasta para o site salvo em HTML
![Alt text](./passo9.jpg)
- Tipo de importação: ```Copy the entire folder```
- URL para clone: http://www.facebook.com

### Resutados

![Alt text](./passoFinal.jpg)
