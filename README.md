# 🎓 Integralizei UnB OffLine

Privacidade total, zero servidor e processamento 100% no seu navegador.

---

## 1. Visão Geral
O **Integralizei UnB OffLine** é uma reengenharia completa do projeto original [Integralizei UnB](https://github.com/unb-mds/2025-2-Integralizei_UnB) que participei, porem agora feito para suportar um deploy **gratuito**!!! 

---

## 2. Sem Inteligência Artificial
Este projeto adota uma diretriz rigorosa: **a lógica do software é 100% humana**, isso fara com que eu realmente tenha que aprender como fazer cada linha de codigo colocada nesse site e diminuindo minha dependencia NA IA.

Irei deixar claro a existencia de uma exceção, farei uso de IAs para arrumar textos com .md e fazer resumos do meu progresso.

---

## 3. Arquitetura
Diferente da versão anterior baseada em microsserviços, esta versão funcionará totalmente **client-side**.

| Característica | Integralizei Original (V1) | Integralizei OffLine (V2) |
|----------------|----------------------------|----------------------------|
| Processamento de PDF | Python (pdfplumber) no Backend | JavaScript (PDF.js) no Navegador |
| Armazenamento | PostgreSQL (Nuvem) | localStorage |
| Autenticação | E-mail/Google OAuth | Não há login |
| Custo de Infra | Alto | Zero  |

---

## 4. Stack Tecnológica
- **Core:** Next.js + TypeScript
- **Processamento de Arquivos:** PDF.js (Possivelmente)
- **Persistência:** localStorage 
- **Deploy:** Vercel ou GitHub Pages

---

## 5. Funcionalidades
### ✅ O que está no Escopo
- **Drag & Drop de Histórico:** Upload do PDF extraído do SIGAA.
- **Analize de Historico:** Algoritmo em TS para interpretar o PDF localmente.
- **Dashboard Acadêmico:** IRA, Créditos Totais, Integralização e Matérias.
- **Persistência Local:** Dados mantidos entre sessões.
- **Calculadora de Fluxo:** Simulação de matrículas futuras.
- **Pesquisa de Matérias:** Pesquisar matérias para facilitar a busca

### ❌ O que foi Removido
- Login/Cadastro
- Ranking Global
- Estatísticas de Turmas
- Pesquisa Global
- ChatBot
