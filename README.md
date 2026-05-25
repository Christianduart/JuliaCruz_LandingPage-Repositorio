# 🌟 Landing Page & Portal de Agendamento – Dra. Júlia Cruz

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007acc.svg?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-black?style=for-the-badge&logo=framer&logoColor=blue)
![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)

Uma solução web premium, moderna e de alta conversão desenvolvida para uma clínica de Fisioterapia e Podologia. Este projeto foca em entregar uma experiência de usuário impecável no ecossistema mobile, oferecendo um fluxo intuitivo de auto-agendamento de consultas.

> 🔗 **Acesse o site online:** https://juliacruzsaude.vercel.app/

---

## 🔗 Ecossistema do Projeto (Front-end & Back-end)

Este repositório contém exclusivamente o **Front-end** (site público do paciente). 

Quando um paciente agenda uma consulta por aqui, os dados são processados por uma API separada, que salva as informações em um banco de dados e cria automaticamente o evento no Google Agenda da clínica.

👉 **[Clique aqui para ver o repositório do Back-end e do CRM Administrativo]([(https://github.com/Christianduart/JuliaCruz_GestaoEmSaude-Repositorio))**

---

## 📸 Demonstração Visual & UI/UX

<div align="center">
  <img width="1920" height="3476" alt="111" src="https://github.com/user-attachments/assets/f83b3597-eb1b-4c14-bd0a-ddc0bf778bd3" />
  <p align="center">
    <b>Visão Desktop:</b> Aproveitamento inteligente do layout em monitores maiores utilizando CSS Grid e Flexbox. Os botões da seção de contato ("Como prefere falar com a gente?") são altamente interativos: ao passar o mouse (hover), os blocos brancos ganham o fundo verde da paleta da marca e uma sombra de elevação fluida. O cabeçalho (Navbar) no topo reage à rolagem da página, alternando de totalmente transparente para um fundo branco com efeito de desfoque (<i>backdrop-blur</i>) para garantir a legibilidade do texto sem esconder as imagens de fundo. O formulário no rodapé possui validação em tempo real e estados visuais claros (foco verde nas bordas) ao digitar.
  </p>

<br><br>

  <img width="1440" height="6229" alt="2" src="https://github.com/user-attachments/assets/4ac418d7-7492-4bd0-a58e-505d9a26f431" />
  <img width="1440" height="6229" alt="https-juliacruzsaude vercel app-(1)" src="https://github.com/user-attachments/assets/63559564-c267-41f4-aafe-007934d49ee8" />
  <p align="center">
    <b>Visão Mobile (Mobile-First):</b> Foco total na experiência e conversão do usuário em telas menores. Os botões principais, como o "Agendar Avaliação", possuem animações de micro-interação (escala e sombra) ao serem tocados, gerados com Framer Motion para dar resposta tátil ao usuário. O ícone verde do WhatsApp no canto direito da tela possui posicionamento <i>fixed</i>. Ele não está ali aleatoriamente: o botão acompanha a rolagem da tela (scroll), garantindo que o paciente tenha um canal de comunicação direta à distância de um clique, independentemente da seção do site que esteja lendo.
  </p>
<br><br>
</div>

---

## 🚀 Desafios Técnicos Solucionados no Front-End

* **Validação Complexa de Datas:** Implementação de algoritmos no cliente para bloquear seleções de datas inválidas no passado, além de restrições em tempo real para domingos e feriados nacionais/municipais direto no componente de calendário nativo.
* **Gerenciamento de Horários Dinâmicos:** Lógica para filtrar e exibir horários operacionais baseada no dia da semana escolhido (ex: corte automático da grade de horários aos sábados para encerramento às 14h) e remoção automática de horários de intervalo.
* **Animações Fluidas com Motion:** Uso de `AnimatePresence` para gerenciar o ciclo de vida de montagem e desmontagem dos componentes do menu e modais, garantindo transições suaves de opacidade e escala sem quebras de layout.
* **Consumo de API Assíncrona:** Arquitetura de requisições utilizando `fetch` para comunicação com o microsserviço de busca de CEP (ViaCEP) e envio de dados para o servidor de agendamentos, lidando de forma resiliente com respostas de erro do servidor (como tentativas de agendamento duplo).

---

## 🤖 Uso de Inteligência Artificial

Como estudante e desenvolvedor buscando aplicar as melhores práticas do mercado, utilizei ferramentas de **Inteligência Artificial** atuando como um *Pair Programmer* durante o desenvolvimento deste projeto. A IA foi utilizada de forma estratégica para:
* Refatorar e otimizar componentes complexos em React.
* Melhorar o design e as classes do Tailwind CSS.
* Solucionar desafios lógicos (como o tratamento de datas e a integração de chamadas de API).
Isso ajudou a acelerar o desenvolvimento, garantindo um código final mais limpo, escalável e alinhado aos padrões atuais da indústria.

---

## 🛠️ Stack Utilizada

* **Biblioteca Core:** React.js com TypeScript.
* **Estilização:** Tailwind CSS.
* **Animações:** Motion.
* **Ícones:** Lucide React.
* **Ferramenta de Build:** Vite.

---

## 👨‍💻 Autor

**Christian Duarte** Graduando em Ciência da Computação (5º período) pela Universidade Anhanguera. Desenvolvedor focado em construir interfaces eficientes, limpas e com excelente experiência de usuário.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/christianduart)
