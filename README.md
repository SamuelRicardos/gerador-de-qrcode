# Gerador de QR Code

Bem-vindo ao **Gerador de QR Code**! 🎉  
Este projeto foi desenvolvido durante a **Pystack Week** promovida pelo **Pythonando** e tem como objetivo facilitar a criação de QR Codes com uma aplicação web simples e eficiente.

## 🚀 Funcionalidades

- Geração de QR Codes personalizados.
- Gerenciamento de links encurtados com controle de cliques.
- Redirecionamento inteligente com verificação de validade de links.
- Visualização de estatísticas de cliques (total e únicos).
- API robusta para criação, atualização e consulta de links e QR Codes.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi construído utilizando as seguintes tecnologias:

### Backend:
- **Python** e **Django**: Para a estrutura e lógica da aplicação.
- **Django Ninja**: Framework para criar APIs de forma rápida e eficiente.
- **SQLite**: Banco de dados leve e interno para armazenar informações de links e estatísticas.

### Ferramentas adicionais:
- **qrcode**: Biblioteca Python para geração de QR Codes.
- **Pillow**: Biblioteca para manipulação de imagens.

---

## 📦 Como rodar o projeto localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/SamuelRicardos/gerador-de-qrcode.git

2. Crie um ambientre virtual:
   ```bash
    python -m venv venv
    source venv/bin/activate    # Linux/Mac
    venv\Scripts\activate       # Windows
3. Instale as dependências:
   ```bash
    pip install -r requirements.txt

3. Aplique as migrações do banco de dados:
   ```bash
   python manage.py migrate

4. Inicie o servidor:
   ```bash
   python manage.py runserver


  




