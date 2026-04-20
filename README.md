# 🌑 V.A.N.E. — Virtual Assistant & Network Entity

**V.A.N.E.**, abreviação de Virtual Assistant & Network Entity (Análise visual e entidade de rede), é uma assistente virtual aprimorada para atender as necessidades humanas de forma semelhante a uma assistente pessoal. Ela é um sistema modular de inteligência sentinela, projetado para operar inicialmente em ambientes Linux, integrando visão computacional, memória persistente de longo prazo e um motor de temperamento dinâmico que evolui conforme a interação com o usuário.

---

## 🏗️ Arquitetura do Sistema
A VANE é construída sob o **Model Context Protocol (MCP)**, separando o "Cérebro" de suas "Ferramentas" (Tools). Isso permite que ela seja leve, modular e altamente expansível.

### 🧩 Módulos Principais
* **🧠 Core (Cérebro):** Integração com Gemini 2.0 Flash para raciocínio lógico e *function calling*.
* **💾 Memória (The Archive):** Implementação de **RAG** com **ChromaDB** para retenção ilimitada de contexto e fatos do usuário.
* **🎭 Psyche (Temperamento):** Motor de atributos baseado em SQLite que ajusta o tom de voz e comportamento da IA.
* **👁️ Vision (Sentinela):** Processamento local via **OpenCV** e **DeepFace** para análise de microexpressões e humor do usuário.
* **🗣️ Voice (Interface):** Speech-to-Text com **Faster-Whisper** e Text-to-Speech com **Piper/Coqui** para baixa latência.

---

## 🎭 O Motor de Temperamento (Psyche)
Diferente de IAs estáticas, a VANE possui um sistema de **Pontuação de Atributos** que define sua personalidade em tempo real:

| Atributo | Função | Gatilhos de Alteração |
| :--- | :--- | :--- |
| **Sarcasmo** | Define a acidez das respostas. | Aumenta com perguntas redundantes. |
| **Paciência** | Define a disposição para ajudar. | Diminui com erros repetitivos ou procrastinação. |
| **Afinidade** | Nível de lealdade ao usuário. | Aumenta com interações produtivas. |
| **Melancolia** | O tom filosófico/Noir. | Influenciado pelo clima e horário. |

---

## 🛠️ Ferramentas e Integrações (Tools)
A VANE possui permissões de nível de sistema para interferir e auxiliar na sua rotina:
* **System Control:** Monitoramento de hardware, temperatura e processos.
* **Workspace Management:** Abertura de IDEs (VS Code), Spotify e navegadores.
* **OSINT Integration:** Conexão direta com o projeto **Argos** para investigações.
* **Active Interference:** Notificações via `notify-send` e alertas de produtividade.

---

## 🔒 Segurança e Privacidade
* **Zero-Cloud Vision:** Todo o processamento de imagem da câmera é feito na RAM e descartado imediatamente.
* **Kernel Lockdown:** Scripts automáticos para desativar o módulo `uvcvideo` quando a câmera não está em uso.
* **Local Storage:** Memória e logs de temperamento armazenados localmente em bancos criptografados.

---

## 🚀 Roadmap de Desenvolvimento
- [x] **Fase 0:** Definição da Arquitetura e QG Estratégico.
- [ ] **Fase 1 (O Despertar):** Estrutura MCP base e loop de voz.
- [ ] **Fase 2 (A Memória):** Implementação do banco vetorial ChromaDB.
- [ ] **Fase 3 (O Olhar):** Integração de reconhecimento facial e emoções.
- [ ] **Fase 4 (A Expansão):** Versão Android via .NET MAUI.

---

## ⚖️ Licença
Este projeto é distribuído sob a **MIT License**. 
> Tente suportar o sarcamo dela.

---
*Desenvolvido por [Nyx0x](https://github.com/Nyx0x)* com muito café ☕️
