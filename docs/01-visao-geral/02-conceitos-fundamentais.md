# Conceitos Fundamentais

> Este documento define os principais conceitos utilizados pela plataforma Atlas.

Todos os documentos do projeto devem utilizar estas definições como referência.

---

# 1. Atlas

Atlas é o ecossistema completo de plataformas inteligentes desenvolvido neste projeto.

A arquitetura foi concebida para permitir a criação de diferentes soluções, compartilhando a mesma base tecnológica e os mesmos princípios.

Exemplos:

- Atlas Home
- Atlas Business
- Atlas Industrial
- Atlas Cloud
- Atlas Mobile
- Atlas Node
- Atlas SDK

---

# 2. Atlas Home

Atlas Home é a plataforma de automação residencial da Atlas.

É o primeiro produto do ecossistema e servirá como base para a evolução das demais plataformas.

---

# 3. Plataforma

Uma plataforma é uma solução completa destinada a um determinado ambiente.

Exemplos:

- Atlas Home → Residências
- Atlas Business → Empresas
- Atlas Industrial → Indústrias

Cada plataforma pode possuir módulos específicos, mantendo uma arquitetura comum.

---

# 4. Módulo

Um módulo representa uma área funcional da plataforma.

Exemplos:

- Atlas Voice
- Atlas Guard
- Atlas Vision
- Atlas Privacy
- Atlas Energy
- Atlas Connect

Cada módulo deve possuir responsabilidades bem definidas.

---

# 5. Dashboard

O Dashboard é a interface gráfica da Atlas.

É através dele que o usuário interage com a plataforma.

O Dashboard poderá ser exibido em:

- Tablets
- Celulares
- Computadores
- Painéis dedicados

---

# 6. Assistente Atlas

A Assistente Atlas é a interface conversacional da plataforma.

Ela será responsável por:

- compreender comandos;
- responder perguntas;
- controlar dispositivos;
- explicar ações;
- auxiliar os moradores.

A assistente poderá utilizar IA local e, quando necessário, serviços de IA online.

---

# 7. Estado da Casa

Um Estado da Casa representa a condição operacional da residência.

Exemplos:

- Casa Ativa
- Boa Noite
- Segurança
- Privacidade
- Emergência

Cada estado altera o comportamento de diversos módulos simultaneamente.

---

# 8. Modo

Um Modo representa um comportamento específico, normalmente temporário ou complementar.

Exemplos:

- Proteção Infantil
- Modo Pet
- Modo Jogo
- Receber Visitas

Um modo pode coexistir com um Estado da Casa.

---

# 9. Automação

Uma automação é uma regra que executa ações automaticamente quando determinadas condições são atendidas.

Exemplo:

Se começar a chover e a janela estiver aberta, a Atlas poderá sugerir ou executar seu fechamento, conforme a configuração definida.

---

# 10. Cena

Uma cena representa um conjunto de configurações aplicadas simultaneamente.

Exemplo:

Cena "Cinema":

- Luzes reduzidas
- TV ligada
- Soundbar ligada
- Cortinas fechadas

---

# 11. Dispositivo

Qualquer equipamento integrado à Atlas.

Exemplos:

- Sensor
- Fechadura
- Lâmpada
- Tablet
- Câmera
- Interruptor

---

# 12. Área

Uma Área representa um espaço físico da residência.

Exemplos:

- Sala
- Cozinha
- Quarto
- Garagem

Uma Área pode conter diversos dispositivos.

---

# 13. Cômodo

Neste projeto, os termos Área e Cômodo serão considerados equivalentes.

O Home Assistant utiliza oficialmente o termo "Área".

A documentação poderá utilizar ambos quando fizer sentido.

---

# 14. Local First

Princípio segundo o qual a plataforma deve funcionar localmente sempre que possível.

A internet será utilizada apenas para recursos que realmente dependam dela.

---

# 15. Privacidade

Conjunto de mecanismos que permitem ao usuário controlar como seus dados são coletados, processados e compartilhados.

---

# 16. Segurança

Conjunto de mecanismos destinados à proteção da residência, dos moradores e dos dispositivos.

---

# 17. IA Local

Modelo de inteligência artificial executado dentro da própria residência.

Exemplo:

Ollama.

Nenhum dado precisa sair da rede local para seu funcionamento.

---

# 18. IA Online

Serviços de inteligência artificial executados na nuvem.

Exemplos:

- ChatGPT
- Gemini

Seu uso dependerá da autorização do usuário e das necessidades da tarefa.

---

# 19. Ecossistema Atlas

Conjunto de todas as plataformas, módulos, dispositivos e serviços que compõem a Atlas.

---

# Status do Documento

Versão: 1.0 (Rascunho)

Status: Em desenvolvimento

Última atualização: 26/08/2026