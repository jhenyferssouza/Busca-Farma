# 💊 Busca Farma

> Plataforma web para consulta em tempo real da disponibilidade de medicamentos gratuitos nas Unidades Básicas de Saúde (UBS) do município de Paulínia - SP.

---

## Sobre o Projeto

O **Busca Farma** é um sistema desenvolvido como Trabalho de Conclusão de Curso (TCC) no Centro Municipal de Ensino Profissionalizado (CEMEP) de Paulínia-SP. 

A plataforma visa resolver o problema de longas filas e deslocamentos desnecessários enfrentados pela população ao buscar medicamentos nas farmácias da rede pública de saúde (SUS). Com o Busca Farma, os cidadãos podem conferir em tempo real se o remédio necessário está disponível na UBS mais próxima antes de saírem de casa.

---

## Funcionalidades Principais

-  **Busca de Medicamentos:** Pesquisa por nome do medicamento com exibição de disponibilidade (Disponível / Indisponível).
-  **Filtro por Unidade Básica de Saúde (UBS):** Consulta completa do estoque de medicamentos por posto de saúde específico.
-  **Informações das UBS:** Endereços completos, telefones, horários de funcionamento e integração com o Google Maps para rotas.
-  **Acessibilidade:** Integração com o plugin **VLibras** em todas as páginas para tradução em Língua Brasileira de Sinais.
-  **Painel Administrativo Restrito:** Autenticação via token de segurança para funcionários gerenciarem estoques, cadastrarem postos e publicarem notícias.
-  **Módulo de Notícias:** Canal de comunicação oficial para divulgar campanhas de vacinação e informes de saúde municipal.

---

## Tecnologias Utilizadas

- **Linguagem Backend:** [Python 3.x](https://www.python.org/)
- **Framework Web:** [Django](https://www.djangoproject.com/)
- **Banco de Dados:** SQLite3
- **Frontend:** HTML5, CSS3, JavaScript
- **Recursos Globais:** Plugin VLibras, Google Maps API / Links de Localização

---

## Como Executar o Projeto Localmente

### Pré-requisitos

Certifique-se de ter instalado em sua máquina:
- [Python 3.10+](https://www.python.org/downloads/)
- [Git](https://git-scm.com/)

### Passo a Passo

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/jhenyferssouza/Busca-Farma.git
   cd Busca-Farma
   ```

2. **Crie e ative um ambiente virtual (recomendado):**
   - **Windows:**
     ```bash
     python -m venv venv
     venv\Scripts\activate
     ```
   - **Linux/macOS:**
     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```

3. **Instale as dependências:**
   ```bash
   pip install -r requirements.txt
   ```
   *(Caso não exista o `requirements.txt`, instale o Django diretamente: `pip install django`)*

4. **Execute as migrações do banco de dados:**
   ```bash
   python manage.py migrate
   ```

5. **Inicie o servidor de desenvolvimento:**
   ```bash
   python manage.py runserver
   ```

6. **Acesse no navegador:**
   Abra o endereço `http://127.0.0.1:8000/`.

---

##  Autoras do Projeto

Desenvolvido por:
- **Jhenyfer da Silva Souza**
- **Thalita Fernanda Costa Moyses**

*Curso Técnico em Informática — CEMEP (Centro Municipal de Ensino Profissionalizante Osmar Passarelli Silveira)*  
*Orientadora: Profa. Raquel C. B. Lot*

---
