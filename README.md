# 🐳 Docker Portfolio | Containerização na Prática

<div align="center">

![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

### 📦 Projeto de Containerização com Docker

**[🌐 Ver Deploy Online](https://bootcamp-python.onrender.com/)**

</div>

---

## 📋 Sobre o Projeto

Página estática criada durante **aula focada em Docker** para demonstrar na prática como containerizar aplicações web. O foco principal foi aprender conceitos de containerização, não desenvolvimento frontend.

> **💡 Objetivo:** Aplicar conceitos de Docker desde a criação do Dockerfile até o deploy em container

---

## 🛠️ Stack Tecnológica

| Tecnologia | Função |
|------------|---------|
| **Docker** | Containerização da aplicação |
| **Nginx Alpine** | Servidor web leve (~15MB) |
| **HTML/CSS/JS** | Interface estática (apenas exemplo) |

---

## 🏗️ Estrutura do Projeto

```
📁 bootcamp_python/
├── 📄 index.html           # Página estática
├── 🐳 Dockerfile          # Configuração do container
└── 📖 README.md           # Esta documentação
```

---

## 🚀 Como Executar

### 📋 Pré-requisitos
- ✅ Docker instalado
- ✅ Porta 8080/8081 disponível

### ⚡ Execução Rápida

```bash
# 1️⃣ Clone o repositório
git clone https://github.com/vitoriarntrindade/bootcamp_python

cd bootcamp_python

# 2️⃣ Build da imagem
docker build -t first-image .

# 3️⃣ Executar container
docker run -d -p 8081:80 --name portfolio first-image

# 4️⃣ Verificar status
docker ps

# 5️⃣ Acessar aplicação
# http://localhost:8081
```

### 🔄 Com Docker Compose

```bash
docker-compose up -d --build
```

---

## 🌐 Deploy Online

A aplicação containerizada está disponível em:

**➡️ [https://bootcamp-python.onrender.com/](https://bootcamp-python.onrender.com/)**


<img width="1336" height="695" alt="image" src="https://github.com/user-attachments/assets/c3541cc1-a878-41e2-85cd-a39911f4fd1d" />


---

## 🎯 Conceitos Docker Aplicados

<table>
<tr>
<td width="50%">

### 📦 **Containerização**
- Criação de Dockerfile
- Uso de imagem base Alpine
- Otimização de layers
- Port mapping

</td>
<td width="50%">


</td>
</tr>
</table>

---

## 🔧 Comandos Docker Úteis

<details>
<summary><strong>📋 Comandos de Gerenciamento</strong></summary>

```bash
# 🔍 Listar containers
docker ps -a

# 📊 Ver logs
docker logs portfolio

# ⏹️ Parar container
docker stop portfolio

# 🗑️ Remover container
docker rm portfolio

# 🖼️ Remover imagem
docker rmi first-image

# 🧹 Limpar sistema
docker system prune -f

# 📈 Ver uso de recursos
docker stats portfolio
```

</details>

<details>
<summary><strong>🔧 Debug e Troubleshooting</strong></summary>

```bash
# 🔍 Inspecionar container
docker inspect portfolio

# 💻 Executar bash no container
docker exec -it portfolio sh

# 🌐 Testar conectividade
curl http://localhost:8081

# 📋 Ver processos no container
docker top portfolio
```

</details>

---

## 📊 Especificações do Container

| Propriedade | Valor |
|-------------|-------|
| **Imagem Base** | `nginx:alpine` |
| **Tamanho** | ~15MB |
| **Porta Interna** | 80 |
| **Porta Externa** | 8081 |
| **Memória** | ~10-20MB |

---

## 📚 Aprendizados Docker

Durante esta aula prática sobre **conceitos de Docker**, foram abordados:

- 🏗️ **Dockerfile**: Criação e otimização
- 🐳 **Images**: Build, tags e registry
- 📦 **Containers**: Lifecycle e management
- 🌐 **Networking**: Port mapping e exposição
- 💾 **Volumes**: Persistência de dados
- 🔧 **Docker Compose**: Orquestração simples
- 🚀 **Deploy**: Containerização para produção

> **🎯 Foco:** O objetivo principal foi aprender Docker na prática. O frontend serviu apenas como exemplo para aplicar os conceitos de containerização.

---

## 👩‍💻 Desenvolvedora

<div align="center">

**Vitória Trindade**  
*Python Developer | Data Engineer*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vitoriarntrindade)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vitoriarntrindade)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vitoriarntrindade@gmail.com)

</div>

---

<div align="center">


*Feito com 🐳 Docker durante bootcamp de Python*

</div>
