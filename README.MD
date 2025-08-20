# 📚 Olho do Analista: Despertando o Verdadeiro Poder no MySQL

Este repositório é o complemento prático do e-book **"Olho do Analista: Despertando o Verdadeiro Poder no MySQL"**.  
O objetivo do material é levar você a um novo nível na análise de dados com MySQL, mesclando teoria e prática de forma acessível e eficiente.

## 🚀 O que você vai encontrar aqui
- Todo o código SQL presente no e-book, organizado por capítulos e temas.
- Scripts para criação e popular bancos de dados de treino.
- Exemplos práticos para que você possa acompanhar passo a passo cada lição.
- Instruções para preparar seu ambiente de prática.

Este é um **guia prático**: leia o e-book para entender os conceitos e utilize este repositório para aplicar imediatamente o que aprendeu.

---

## 📂 Organização do Repositório

A estrutura é simples e organizada:

```
/capitulo-01/
    exemplo-1.sql
    exemplo-2.sql
/capitulo-02/
    exemplo-3.sql
    exemplo-4.sql
...
/dataset/
    criar_banco_treino.sql
```

- **Cada pasta** corresponde a um capítulo do e-book.  
- Os arquivos `.sql` contêm exemplos diretamente executáveis no MySQL.  
- A pasta **`/dataset/`** contém scripts para criação do banco de treino e inserção de dados fictícios.

---

## 🛠 Preparando o Ambiente de Treino

Antes de iniciar, você precisará ter um ambiente MySQL pronto para executar os exemplos.

### **1. Instalar MySQL Localmente**
No Windows:
```bash
# Baixar o instalador
# Link: https://dev.mysql.com/downloads/

# Conectar após instalação
mysql -u root -p
```

### **2. Usando Docker**
Se preferir usar Docker para criar o ambiente isolado:
```bash
docker run --name mysql-treino   -e MYSQL_ROOT_PASSWORD=senha123   -e MYSQL_DATABASE=treino_db   -p 3306:3306   -d mysql:8.0
```
E conectar:
```bash
mysql -h 127.0.0.1 -u root -p
```


---

💡 **Dica:** Sempre use o banco de treino para seus testes. Assim, você evita alterações acidentais em bases de produção.

---

Agora é só abrir o e-book, seguir os exemplos e executar os códigos deste repositório!  
Bons estudos e boas consultas! 🚀
