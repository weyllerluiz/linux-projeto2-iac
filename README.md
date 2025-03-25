# 🔧 Script de Automação para Deploy Web (IaC)

Script em Bash para Infraestrutura como Código (IaC), configurando automaticamente um servidor web Apache com um site estático.

## 📚 Sobre o Curso
Este projeto foi desenvolvido como parte do **Curso de Linux** da [Digital Innovation One (DIO)](https://www.dio.me/), ministrado pelo instrutor [Denilson Bonatti](https://github.com/denilsonbonatti).  
O objetivo prático é demonstrar a automatização de deploys em servidores Linux usando Bash Scripting.

[![Badge DIO](https://img.shields.io/badge/DIO-Linux_Course-000?style=for-the-badge&logo=linux&logoColor=white)](https://web.dio.me/track/santander-linux-para-iniciantes)

## 📋 O que o Script Faz:
1. **Atualiza o servidor** (pacotes e segurança).
2. **Instala dependências**:
   - Apache (servidor web).
   - Unzip (para descompactar arquivos).
3. **Baixa e implanta um site estático** do GitHub no Apache.

## ▶️ Como Executar (Linux):
```bash
# Dê permissão de execução:
chmod +x script-iac2.sh

# Execute como superusuário:
sudo ./script-iac2.sh
