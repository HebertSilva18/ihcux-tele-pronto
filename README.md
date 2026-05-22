# ihcux-tele-pronto

## Aluno
Ingred Santana

## Proposta
Protótipo de baixa fidelidade do aplicativo TelePronto, criado para uma interface de saúde simples, clara e fácil de usar.

O objetivo do aplicativo é ajudar o paciente a iniciar uma triagem rápida, entrar em uma fila virtual para consulta com clínico geral e acessar receitas digitais após o atendimento.

## Telas principais

1. **Home / Dashboard**: tela inicial com atalhos para Consulta Agora, Triagem Rápida, Meus Remédios, Receitas e Farmácias Próximas.
2. **Triagem**: seleção simples dos sintomas, usando botões grandes e textos curtos.
3. **Confirmação da triagem**: resumo dos sintomas e botão para iniciar consulta.
4. **Sala de espera virtual**: mostra quantos pacientes estão na frente, tempo estimado e status do atendimento.
5. **Vídeo-chamada**: tela da consulta com controles básicos de mudo, câmera e chat.
6. **Receita e lembrete**: exibição da receita digital, acesso a farmácias próximas e configuração de horários de medicação.

## Análise de acessibilidade

O design usa poucos elementos por tela, textos diretos e botões grandes. Isso ajuda usuários que podem estar com visão turva, dor, febre ou dificuldade para tocar em áreas pequenas da tela.

A navegação foi pensada para ser simples, com ações principais bem destacadas. O botão de ajuda aparece sempre no topo, para que o usuário consiga pedir suporte em qualquer etapa.

## Fluxo crítico

O caminho para iniciar uma consulta de urgência leve é:

1. O usuário abre a Home.
2. Toca em **Consulta Agora** ou **Triagem rápida**.
3. Seleciona os sintomas na tela de triagem.
4. Confere o resumo dos sintomas.
5. Toca em **Iniciar Consulta**.
6. Entra na sala de espera virtual até o médico iniciar a vídeo-chamada.

## Prevenção de erros

Para evitar erros, o protótipo usa uma tela de confirmação antes de iniciar a consulta e também antes de encerrar a chamada.

O botão **Encerrar consulta** não finaliza imediatamente. Primeiro aparece uma confirmação perguntando se o usuário realmente deseja encerrar. Assim, se ele tocar sem querer, ainda pode voltar para a consulta.

Também foram usados rótulos claros nos botões, evitando depender apenas de ícones.

## Arquivos do protótipo

Os arquivos estão na pasta `/prototipo`:

- `prototipo.png`
- `prototipo.pdf`
