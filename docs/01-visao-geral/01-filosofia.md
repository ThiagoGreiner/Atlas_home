# Filosofia de Desenvolvimento

> Este documento define os princípios que orientam todas as decisões de arquitetura, desenvolvimento e evolução da plataforma Atlas.

---

# 1. Objetivo

A filosofia da Atlas estabelece as diretrizes que devem ser seguidas durante todo o desenvolvimento da plataforma.

Esses princípios têm prioridade sobre decisões técnicas pontuais e servem como referência sempre que houver dúvidas sobre qual caminho seguir.

---

# 2. Princípios Fundamentais

## 2.1 Local First

Tudo que puder funcionar localmente deverá funcionar localmente.

A internet nunca será um requisito para o funcionamento básico da casa.

Serviços externos serão utilizados apenas quando realmente necessários.

### Exemplos

- Previsão do tempo
- Spotify
- YouTube
- ChatGPT
- Gemini

Mesmo sem internet, a Atlas deverá continuar executando:

- automações;
- sensores;
- iluminação;
- fechaduras;
- alarmes;
- dashboards;
- estados da casa;
- assistente local (quando possível).

---

## 2.2 Privacidade por Projeto

A privacidade não será um recurso opcional.

Ela faz parte da arquitetura da plataforma.

O usuário sempre deverá saber:

- quais dados estão sendo utilizados;
- quais permanecem na rede local;
- quais saíram da rede;
- para onde foram enviados;
- qual serviço os recebeu.

Nenhum envio de dados deverá ocorrer de forma oculta.

---

## 2.3 Transparência

Toda decisão importante da Atlas deve poder ser explicada.

Exemplo:

> "Fechei a janela da cozinha porque começou a chover e o sensor informou que ela estava aberta."

O usuário nunca deve ficar sem entender por que uma ação aconteceu.

---

## 2.4 IA como Assistente

A inteligência artificial existe para auxiliar.

Ela interpreta contexto, conversa com os moradores e oferece sugestões.

Entretanto, decisões críticas nunca dependerão exclusivamente da IA.

Exemplos:

- desligar alarmes;
- abrir portas;
- desativar proteção infantil;
- desligar câmeras.

Essas ações sempre exigirão regras adicionais de segurança.

---

## 2.5 Modularidade

Cada componente da Atlas deverá funcionar de maneira independente.

Exemplos de módulos:

- Atlas Voice
- Atlas Vision
- Atlas Guard
- Atlas Privacy
- Atlas Energy
- Atlas Connect

Novos módulos poderão ser adicionados sem necessidade de reconstruir a plataforma.

---

## 2.6 Segurança em Camadas

Nenhuma ação crítica deverá depender de um único fator.

Sempre que possível, utilizar múltiplas validações.

Exemplos:

- senha;
- biometria;
- celular autorizado;
- reconhecimento facial;
- confirmação manual.

---

## 2.7 Expansão Contínua

A Atlas deve permitir a integração de novos dispositivos sem necessidade de alterar sua arquitetura principal.

Adicionar um novo sensor deve significar apenas configurar um novo dispositivo, e não modificar a estrutura da plataforma.

---

## 2.8 Independência de Fabricante

Sempre que possível, a Atlas deverá utilizar padrões abertos.

Prioridade:

1. Matter
2. Zigbee
3. MQTT
4. Wi-Fi Local
5. Bluetooth

Dependências de nuvem deverão ser evitadas.

---

## 2.9 Usuário no Controle

O morador sempre terá prioridade sobre qualquer automação.

A Atlas poderá sugerir ações.

A decisão final pertence ao usuário.

---

## 2.10 Evolução Contínua

A arquitetura deverá permitir crescimento constante.

A plataforma nunca será considerada "pronta".

Novas funcionalidades deverão ser incorporadas sem comprometer a estabilidade das existentes.

---

# 3. O que a Atlas NÃO será

A Atlas não pretende:

- substituir equipamentos certificados de segurança;
- substituir dispositivos médicos;
- obrigar o uso de serviços em nuvem;
- prender o usuário a um único fabricante.

---

# 4. Processo de Desenvolvimento

Toda funcionalidade seguirá obrigatoriamente o seguinte fluxo:

1. Definição do problema.
2. Levantamento de requisitos.
3. Discussão da arquitetura.
4. Documentação.
5. Protótipo.
6. Implementação.
7. Testes.
8. Aprovação.

Nenhuma implementação deverá ocorrer antes da conclusão da documentação.

---

# 5. Compromissos do Projeto

Durante todo o desenvolvimento da Atlas buscamos:

- Simplicidade.
- Confiabilidade.
- Segurança.
- Privacidade.
- Escalabilidade.
- Modularidade.
- Transparência.
- Facilidade de manutenção.

Esses compromissos deverão orientar todas as decisões futuras da plataforma.

---

# Status do Documento

Versão: 1.0 (Rascunho)

Status: Em desenvolvimento

Última atualização: 26/08/2026