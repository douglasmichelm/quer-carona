# Quer Carona - Nereu Ramos (Jaraguá do Sul)
Autor: Douglas Michel Martins

## 1. Introdução do Problema
Moradores do bairro Nereu Ramos enfrentam dificuldades relacionadas à mobilidade urbana, principalmente devido à distância em relação ao centro da cidade e à ausência de mecanismos que facilitem a integração entre pessoas com rotinas de deslocamento semelhantes. Essa dificuldade é mais evidente entre novos moradores, que não possuem rede de contatos local para organização de caronas.

## 2. Justificativa
Jaraguá do Sul recebe muitos novos habitantes. O projeto visa reduzir o número de veículos em circulação, economizar combustível e promover a integração social entre funcionários de empresas vizinhas (3 Rodas, Marisol, WEG, Trapp, Menegotti).

## 3. Objetivos
- **Geral:** Facilitar a formação de grupos fixos de carona para trabalhadores de Nereu Ramos.
- **Específicos:**
  - Cadastrar colaboradores vinculados às empresas do trajeto.
  - Permitir a criação de grupos fixos de carona.
  - Possibilitar a solicitação e aprovação de entrada em grupos.
  - Facilitar a integração entre trabalhadores de empresas próximas.
    
## 4. Descrição do MVP
Aplicação web que permitirá o cadastro de usuários, vinculação a empresas e participação em grupos fixos de carona, organizados conforme o destino (empresas do trajeto). O sistema possibilitará a solicitação de entrada em grupos existentes e a aprovação pelo motorista responsável.

## 5. Modelagem de Dados do Banco de Dados
Nesta seção, apresentamos as duas etapas de modelagem do banco de dados do sistema, focado na integração entre funcionários de empresas em Nereu Ramos.

### 5.1 Modelo Conceitual
Este modelo apresenta a visão de alto nível das entidades e seus relacionamentos (Conceitual Raiz).

![Modelo Conceitual](./modelo_conceitual.png)

### 5.2 Modelo Lógico
Abaixo, a estrutura técnica detalhada com tabelas, chaves primárias (IDs) e tipos de dados.

![Modelo Lógico](./modelo_logico.png)

## 6. Diagrama de Classes
Representação das classes do sistema, seus atributos, métodos e associações.

![Diagrama de Classes](./diagrama_classes.png)

## 7. Diagrama de Caso de Uso Geral
Mapeamento das funcionalidades do sistema e interação entre os atores (Colaborador e Administrador).

![Caso de Uso](./diagrama_caso_uso.png)

## 8. Diagrama de Sequência
Fluxo de mensagens para o processo de solicitação de entrada em um grupo de carona.

![Diagrama de Sequência](./digrama_sequencia.png)

## 9. Diagrama de Atividades
Fluxo lógico de decisão para a adesão de um novo membro a um grupo de carona fixo.

![Diagrama de Atividade](./diagrama_atividade.png)

---
## Planejamento de Futura Expansão
Como evolução da solução, prevê-se a integração com APIs de geolocalização, como Google Maps ou Waze, permitindo cálculo de rotas em tempo real, identificação automática de compatibilidade entre usuários e ampliação do sistema para outros bairros e cidades.
