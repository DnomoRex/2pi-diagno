# 🚀 2π_Diagno — Consultoria em Transformação Digital

🔗 **Acesse o Aplicativo Online (GitHub Pages):** [Clique aqui para abrir o App](https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/)

## 👥 Especialistas Responsáveis (Autores)

- **Arthur Fernandes Sodré**
- **Unidade Curricular:** Exploração Digital e Fundamentos Tecnológicos (Objetos de Conhecimento 05 e 06)

> **Sobre o nome:** 2π radianos equivalem a uma volta completa (360º). O nome representa o **Diagnóstico 360º**: uma volta completa pelos 4 pilares da transformação digital de uma empresa.

---

## 🎯 1. O Problema Empresarial e Objetivo do Aplicativo

Pequenas e médias empresas sabem que precisam se modernizar, mas não sabem por onde começar: usam computadores locais como "servidor", fazem backup manual, mantêm dados em planilhas soltas, não integram vendas e financeiro, usam IA sem método e deixam a segurança e a LGPD em segundo plano. O **2π_Diagno** é um aplicativo web que avalia a maturidade digital da empresa em 8 perguntas, calcula um índice de 0 a 100% (com nota por pilar), exibe um gráfico radar e gera um laudo de boas práticas priorizado, mostrando primeiro o pilar mais frágil.

## 🏛 2. Os 4 Pilares de Boas Práticas Aplicados no Diagnóstico

- **☁ Infraestrutura e Migração para a Nuvem:** avalia onde ficam os dados e como é o backup. Recomenda migração para SaaS, PaaS ou IaaS, backup automatizado na regra 3-2-1, redundância de link e controle de custos (FinOps).
- **🔄 Sistemas Empresariais (ERP/CRM) e Fluxo de Dados:** avalia como clientes, vendas, financeiro e estoque se conectam. Recomenda eliminar planilhas isoladas, adotar CRM e ERP, integrar por API e criar uma fonte única da verdade com dashboards.
- **🤖 IA Generativa e Automação No-Code:** avalia o uso de IA e de automações. Recomenda mapear tarefas repetitivas, criar fluxos No-Code e manter revisão humana (Human-in-the-Loop) para evitar alucinações.
- **🛡 Governança, Ética e Segurança Digital (LGPD):** avalia acessos e políticas. Recomenda MFA em todas as contas, menor privilégio, política de uso ético de IA, anonimização de dados e adequação à LGPD. O próprio app segue **Privacy by Design**: todos os dados são processados localmente no navegador, sem envio a servidores.

**Como o score funciona:** cada pilar tem 2 perguntas de 0 a 3 pontos (máximo de 6). A nota do pilar é `soma ÷ 6 × 100`, e a nota geral é a média dos 4 pilares. A classificação é: Iniciante (abaixo de 30%), Em Transição (30% a 59%), Conectada (60% a 84%) e Líder Digital (85% ou mais).

## 🛠 3. IAs Generativas e Ferramentas Utilizadas

| Ferramenta / IA | Como foi utilizada no projeto |
| :--- | :--- |
| **Claude (Anthropic)** | Interpretação dos requisitos do professor, escolha do escopo (Opção B), estruturação das regras de negócio e pesos do diagnóstico, geração do código HTML/JS e criação deste README. |
| **TailwindCSS & Chart.js (CDN)** | Estilização executiva responsiva e geração do gráfico radar dinâmico de maturidade. |
| **GitHub & GitHub Pages** | Versionamento de código e publicação em nuvem estática (PaaS/CDN). |

## 🧠 4. Diário de Construção: Como Construímos e Refinamos o App

1. **Concepção e Engenharia de Prompt:** enviei à IA os dois PDFs do professor (apresentação e guia de requisitos) e pedi que ela explicasse o que precisava ser feito. Em seguida, comparei as 3 opções de escopo e escolhi a **Opção B (Diagnóstico 360º)**, por cobrir os 4 pilares e ter a lógica de cálculo mais simples de explicar. Depois pedi a geração do `index.html` em arquivo único, com formulário, motor de cálculo, gráfico, laudo, botão de demo e exportação em PDF.
2. **Ajustes e Refinamentos Técnicos:** após a primeira versão, personalizei a identidade do projeto: defini o nome **2π_Diagno**, atualizei o título e o cabeçalho do site e incluí meu nome como autor no rodapé.
3. **Principal Aprendizado:** a transformação digital depende de vários pilares ao mesmo tempo. Não basta migrar para a nuvem se os sistemas continuam isolados, a IA é usada sem revisão humana ou a segurança e a LGPD são ignoradas. Também ficou claro que a IA acelera muito o desenvolvimento, mas o especialista precisa validar se as recomendações e os cálculos fazem sentido técnico.
