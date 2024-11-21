# URL SHORTENER

Este é um encurtador de URLs desenvolvido em **Java 17**, utilizando os serviços **AWS Lambda** e **Amazon S3**. Ele permite gerar URLs curtas e armazená-las em um bucket S3, enquanto o redirecionamento é gerenciado por uma função Lambda.

---

## 🚀 Tecnologias Utilizadas

- **Java 17**
- **AWS Lambda** - Para redirecionamento de URLs.
- **Amazon S3** - Para armazenamento das URLs curtas e seus mapeamentos.
- **Maven** - Para gerenciamento de dependências.

---

## 📦 Funcionalidades

1. **Encurtar URLs**:
    - Recebe uma URL longa e gera uma versão encurtada única.
2. **Armazenamento no S3**:
    - Mapeia a URL curta para a URL original em um bucket S3.
3. **Redirecionamento via Lambda**:
    - O Lambda recebe a URL curta e redireciona para a URL original.

---

## 🛠️ Configuração do Ambiente

### **Pré-requisitos**

- **Java 17** instalado.
- **Maven** instalado.

### **Configuração Inicial**

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/url-shortener.git
   cd url-shortener
   
2. Conta na AWS para poder upar o .jar gerado.

## 🏃‍♂️ Executando o Projeto

1. Encurtar uma URL:
    ```bash 
   java -jar target/url-shortener.jar shorten "https://url-longa.com/exemplo"

2. Saída esperada:
    ```bash 
    URL encurtada: https://short.url/abc123

