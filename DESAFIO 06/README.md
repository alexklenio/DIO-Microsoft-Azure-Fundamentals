<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="60px" src="https://assets.dio.me/Mo-tlP263KBZIWFaCvplHdmnL4GSLIITz5tzmMUoX7s/f:webp/h:77/q:80/w:77/L2xhYl9wcm9qZWN0cy9iYWRnZXMvY2E0NTA1ZmYtNTI2YS00ZGZkLWI3ZTAtZDhhZTEwMDdiNTRjLnBuZw"></a>
    <span> 
Microsoft Azure - Dominando o Armazenamento na Azure</span>
</h1>

Repositório desenvolvido para fins didáticos, com a disponibilização de materiais de apoio para o lab **Microsoft Azure - Construindo Arquiteturas no Azure** da [Digital Innovation One](https://www.dio.me/).

[![Link do Lab](https://img.shields.io/badge/▶-000?style=for-the-badge&logo=movie&logoColor=E94D5F)](https://web.dio.me/lab/armazenamento-laboratorio-1/learning/0c4eab63-26c1-450c-aa55-cf822e2ff660?back=/track/microsoft-azure-essentials) 
[![Link do Lab](https://img.shields.io/badge/Acesse%20o%20Lab%20na%20Plataforma-E94D5F?style=for-the-badge)](https://web.dio.me/lab/armazenamento-laboratorio-1/learning/0c4eab63-26c1-450c-aa55-cf822e2ff660?back=/track/microsoft-azure-essentials)

## Objetivo
Como resolução do Lab6, módulo 2, repasso um resumo de tudo visto, aprendido e discutido no módulo
   
## Resposta do Lab

# LAB-DominandoArmazenamentoAzure

## 1️⃣ - CRIAÇÃO DE CONTA DE ARMAZENAMENTO

* Pode receber os seguintes tipos de dados
Conteinere blob
files
filas e tabela

> o Nome tem que ser mundialmente exclusivo. tem que 3 a 24 caracteres. sem letras maiusculas e sem caracteres especiais.
> desempenho: pode ser standard para operações normais cobrado conforme o uso ou premium para operações com baixa latencia, cobrado independente do uso.
>
### - Parametros escolhidos para criação da conta
![link](https://github.com/thiagofs84/LAB-DominandoArmazenamentoAzure/blob/main/Cria%C3%A7%C3%A3o%20de%20Conta.png)

### - Parametros escolhidos para Compartilhamento de Arquivos
![link2](https://github.com/thiagofs84/LAB-DominandoArmazenamentoAzure/blob/main/NovoCompartArquivos.JPG)

### - Conexão



![link3](https://github.com/thiagofs84/LAB-DominandoArmazenamentoAzure/blob/main/ScriptConexao.JPG)

> Dica - Para fazer o acesso a partir de uma máquina, criar uma máquina virtual no Azure e executar nela, através do Power Shel o script apresentado.
A conexão, funciona com porta TCP 445 (porta SMB)


## 2️⃣ - MIGRAÇÃO

### BANCO DE DADOS

![link3](https://github.com/thiagofs84/LAB-DominandoArmazenamentoAzure/blob/main/ProjetoMigracaoBD.JPG)

![link4](https://github.com/thiagofs84/LAB-DominandoArmazenamentoAzure/blob/main/TokenAcessoCompart.JPG)

'https://thiagofs84.blob.core.windows.net/novoteste?sp=racwdlmeop&st=2024-10-14T16:50:54Z&se=2024-10-15T00:50:54Z&spr=https&sv=2022-11-02&sr=c&sig=iY7NUf4f0mCisMO1ye%2B9xbOLoafSVgmSiOymlKMnVRI%3D

![link5](https://github.com/thiagofs84/LAB-DominandoArmazenamentoAzure/blob/main/AZCOPY.JPG)

⭐ Obrigado por chegar até aqui e sintas-e a vontade para contribuir e deixar uma estrelinha! (**star**) 
