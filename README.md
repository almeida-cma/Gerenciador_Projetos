# 🧭 Gerenciador de Projetos – Protótipo Interativo

## 📘 Descrição Geral
Este repositório apresenta um **protótipo funcional de Gerenciador de Projetos**, desenvolvido para apoiar o **planejamento, acompanhamento e registro de etapas em trabalhos em grupo**.

A proposta é oferecer uma ferramenta simples, totalmente **baseada em navegador (HTML, CSS e JavaScript puro)**, que permita **criar, editar, exportar e visualizar planos de projeto** de forma intuitiva — sem necessidade de back-end ou instalação de servidor.

---

## 📂 Estrutura do Repositório

| Arquivo | Descrição |
|----------|------------|
| **`Gerenciador_Projetos.html`** | Protótipo interativo principal. Permite criar e gerenciar etapas de um projeto diretamente no navegador. |
| **`Gerenciador_Projetos.mp4`** | Vídeo demonstrativo mostrando as principais funcionalidades do protótipo em execução. |
| **`Manual_Gerenciamento.pdf`** | Manual do usuário com instruções detalhadas sobre uso da ferramenta, criação de etapas, exportação e boas práticas. |
| **`Onepage Novembro Azul.json`** | Exemplo de arquivo salvo, representando um projeto completo (com etapas e prazos) pronto para ser recarregado no sistema. |
| **`Onepage Novembro Azul.pdf`** | Exemplo de relatório de exportação em formato PDF, gerado a partir do arquivo JSON do projeto. |

---

## ⚙️ Execução do Protótipo

Este aplicativo **não requer servidor local**.  
Basta **clicar diretamente no arquivo `Gerenciador_Projetos.html`** para abrir no navegador.

> 🔹 Recomendado o uso dos navegadores **Google Chrome** ou **Microsoft Edge** para garantir compatibilidade total.  
> 🔹 Todas as funcionalidades rodam **localmente** no navegador, sem envio de dados para a internet.  

---

## 🎬 Demonstração
Assista à demonstração rápida das principais funcionalidades do sistema:  
🎥 **Gerenciador_Projetos.mp4**

O vídeo apresenta:
- Criação de novas etapas e prazos  
- Marcação de etapas concluídas  
- Destaque de prazos estourados  
- Exportação e importação de projetos (`.json`)  
- Geração de relatórios em `.pdf`

---

## 💡 Funcionalidades Principais
- ✅ **Cadastro de etapas com descrição, prazo e link de referência (Drive, Docs, etc.)**  
- 📅 **Ordenação automática por data de entrega**  
- 🚨 **Destaque visual de etapas com prazos vencidos**  
- 💬 **Campo para link de comunicação entre membros**  
- 💾 **Salvar e carregar projetos (.json)**  
- 📄 **Exportar cronograma completo em PDF**

---

## 🧠 Exemplos e Inspirações
Este gerenciador foi pensado para apoiar **equipes de desenvolvimento e trabalhos acadêmicos**, podendo ser adaptado para outras finalidades.

Para inspiração de uso e integração com projetos reais, consulte o repositório complementar:  
👉 [Reestruturação da OnePage “Outubro Rosa”](https://github.com/almeida-cma/nuvem)

---

## 📑 Manual e Documentação
O arquivo **`Manual_Gerenciamento.pdf`** contém instruções detalhadas de:
- Criação de novos projetos  
- Estrutura dos arquivos JSON  
- Boas práticas de organização de tarefas  
- Dicas de exportação e compartilhamento  

---

## 🧩 Estrutura de Arquivos Salvos
Os arquivos `.json` seguem o formato:

```json
{
  "projeto": "Onepage Novembro Azul",
  "etapas": [
    {
      "descricao": "Melhorar acessibilidade",
      "prazo": "2025-11-15",
      "nota": 5,
      "link": "https://drive.google.com/..."
    },
    ...
  ]
}
