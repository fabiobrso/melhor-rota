# 🚚 Melhor Rota — Organizador de Planilhas de Entrega

O **Melhor Rota** é uma aplicação web simples e eficiente criada para **organizar, padronizar e agrupar endereços de entrega a partir de planilhas Excel**, facilitando o processo de roteirização urbana.

---

## 🎯 Proposta do Projeto

Este projeto foi desenvolvido para resolver um problema comum enfrentado por entregadores, motoristas e operadores logísticos:

> **Planilhas de entrega desorganizadas, com endereços duplicados, abreviados de formas diferentes e múltiplos pacotes para a mesma parada.**

O sistema automatiza esse trabalho, que normalmente é feito manualmente, economizando tempo e reduzindo erros na organização das rotas.

---

## ❌ O Problema

Planilhas de marketplaces (como Shopee) geralmente apresentam:
- Endereços repetidos com variações de escrita  
  - Ex: `Alameda Santos` vs `Al. Santos`
- Abreviações inconsistentes
- CEPs em formatos diferentes
- Vários pacotes para o mesmo endereço aparecendo em linhas separadas

Isso dificulta:
- A criação de rotas eficientes
- A visualização do total de entregas por parada
- O uso dessas planilhas em aplicativos de roteirização

---

## ✅ A Solução

O **Melhor Rota** resolve isso ao:

- 🔹 Normalizar nomes de ruas e abreviações
- 🔹 Padronizar CEPs
- 🔹 Unificar endereços iguais em uma única linha
- 🔹 Agrupar os pacotes (Sequence) por parada
- 🔹 Gerar uma nova planilha pronta para uso

Tudo isso acontece **diretamente no navegador**, sem necessidade de instalar nada.

---

## ⚙️ Como Funciona

1. O usuário acessa a aplicação
2. Faz upload de uma planilha `.xlsx`
3. O sistema:
   - Processa os dados
   - Agrupa os endereços
   - Organiza os pacotes por parada
4. Um novo arquivo Excel é gerado automaticamente para download

---

## 🖥️ Tecnologias Utilizadas

- **HTML5**
- **CSS3 (tema escuro)**
- **JavaScript (Vanilla)**
- **SheetJS (xlsx)** para leitura e escrita de arquivos Excel

---

## 🚀 Como Usar

1. Baixe ou clone este repositório
2. Abra o arquivo `index.html` em qualquer navegador
3. Clique em **Adicionar arquivo**
4. Selecione sua planilha de entregas
5. Baixe o arquivo organizado gerado pelo sistema

---

## 🌐 Publicação Online (GitHub Pages)

Este projeto também pode ser acessado através do link
https://fabiobrso.github.io/melhor-rota

---

## 👨‍💻 Autor

Desenvolvido por **Fábio Barros**  
Projeto criado com foco em **logística urbana, produtividade e automação de tarefas operacionais**.

---

## 📌 Observações

- Todo o processamento ocorre localmente no navegador
- Nenhum dado é enviado para servidores externos
- Ideal para uso pessoal ou como base para soluções logísticas maiores
