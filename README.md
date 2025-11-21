# 🏥 NEP Gamificado - Hospital Municipal Guarapiranga (HMG)

![Badge Status](https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow) ![Badge Type](https://img.shields.io/badge/Tipo-Gamificação_Corporativa-blue) ![Badge Platform](https://img.shields.io/badge/Plataforma-Mobile-green)

> **"Voando Alto com o Conhecimento"** 🐦  
> Uma plataforma de educação continuada que transforma treinamento em uma jornada de evolução, conectando a identidade das alas do hospital (Pássaros) ao crescimento profissional.

---

## 📖 Sobre o Projeto

O **NEP Gamificado** é uma solução desenvolvida para o Núcleo de Educação Permanente do HMG. [cite_start]O objetivo é resolver a baixa adesão aos treinamentos e a dificuldade de acompanhamento individual[cite: 4, 5, 9].

Através de um aplicativo móvel, transformamos a capacitação em uma experiência:
* **Lúdica:** Sistema de níveis baseados em pássaros.
* [cite_start]**Ágil:** Presença via QR Code e Pós-teste digital[cite: 16, 17].
* [cite_start]**Motivadora:** Ranking, medalhas e recompensas físicas/digitais[cite: 21].

---

## 🎮 Game Design & Mecânicas

A gamificação é o coração deste projeto. O colaborador escolhe um "Avatar" (Pássaro) que representa seu setor e evolui conforme aprende.

### 🏆 A Jornada do Voo (Níveis)

<details>
<summary><strong>👆 Clique para expandir a Tabela de Níveis</strong></summary>

| Nível | Ícone | Nome | Pontos Necessários | Significado |
| :---: | :---: | :--- | :--- | :--- |
| **1** | 🥚 | **Ninhando** | 0 – 19 | Início, adaptação |
| **2** | 🐣 | **Filhote** | 20 – 49 | Agilidade, início da jornada |
| **3** | 🐦 | **Aprendiz** | 50 – 99 | Atenção, comunicação |
| **4** | 🦅 | **Voando** | 100 – 199 | Excelência, alta performance |
| **5** | 👑 | **Mestre do Voo** | 200+ | Raridade, expertise |
| **6** | 🌟 | **Super Guia** | 400+ | Liderança, Embaixador |

> [cite_start]*O sistema calcula e atualiza automaticamente o nível do usuário.* [cite: 74]
</details>

### 🦉 O Multiplicador (Função Especial)
Colaboradores que reforçam treinamentos fora da agenda oficial ganham o título de **Coruja - Guardiã do Conhecimento**.
* [cite_start]**Bônus:** Badge exclusivo + Pontuação diferenciada por repasse[cite: 48, 56].

### 💯 Sistema de Pontuação

<details>
<summary><strong>👆 Clique para ver como ganhar pontos</strong></summary>

* **Carga Horária:**
    * Curto (até 1h): `+10 pts`
    * Médio (1-3h): `+20 pts`
    * Longo (>3h): `+40 pts`
* **Desempenho (Pós-teste):**
    * Nota 60-79%: `+5 pts`
    * Nota 80-89%: `+10 pts`
    * Nota ≥90%: `+15 pts`
* **Constância:**
    * Sem faltas no mês: `+10 pts`
    * 3 meses consecutivos: `+20 pts`

[cite_start][cite: 61-72]
</details>

---

## 📱 Funcionalidades do App

### Para o Colaborador
* ✅ **Dashboard:** Visualização de nível, pássaro e barra de progresso.
* ✅ **Inscrição:** Cadastro em treinamentos com 1 clique.
* ✅ **Check-in:** Leitura de QR Code da turma.
* ✅ **Quiz:** Pós-teste com feedback imediato.
* ✅ **Ranking:** Comparativo por setor e categoria profissional.

### Para o Gestor (NEP)
* 🛠 **Gestão de Turmas:** Criação de agenda e geração de QR Codes.
* 🛠 **Validação:** Aprovação de "Multiplicadores".
* 🛠 **Analytics:** Dashboards de adesão e indicadores de segurança.

---

## 🎨 Identidade Visual e Telas

O design segue a paleta institucional do HMG integrada às cores dos níveis (Cinza, Amarelo, Azul, Verde).

| Dashboard (Home) | Jornada (Progresso) | Ranking |
| :---: | :---: | :---: |
| ![Home](LINK_DA_IMAGEM_DASHBOARD) | ![Progresso](LINK_DA_IMAGEM_PROGRESSO) | ![Ranking](LINK_DA_IMAGEM_RANKING) |
> [cite_start]*Wireframes baseados na documentação oficial.* [cite: 158-168]

---

## 🛠 Tecnologias (Sugestão)

* **Mobile:** React Native / Flutter
* **Backend:** Node.js / Python (Django/FastAPI)
* [cite_start]**Database:** PostgreSQL (Estrutura Relacional: Usuários, Treinamentos, Turmas, Inscrições [cite: 100-108])
* **Design:** Figma

---

## 🚀 Instalação e Execução

```bash
# Clone este repositório
$ git clone [https://github.com/seu-usuario/hmg-nep-gamificado.git](https://github.com/seu-usuario/hmg-nep-gamificado.git)

# Acesse a pasta do projeto
$ cd hmg-nep-gamificado

# Instale as dependências (Exemplo Node)
$ npm install

# Execute o projeto
$ npm start
