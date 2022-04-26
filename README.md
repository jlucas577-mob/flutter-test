# Desafio Flutter MobApps

![MobApps Logo](https://i.imgur.com/zyKt9gn.png)

## Objetivo do app

O aplicativo desenvolvido deve permitir ao usuário visualizar o mapa do Google Maps, com foco em sua localização atual e exibir marcadores para os registros de posições anteriores.

Deve conter:

  - Solicitação de permissões.
  - Botão para realizar o registro de sua localização em uma base de dados local.
  - Botão que abra uma tela listando todas as posições registradas, e possibilitando apagar determinado item, ou todas de uma só vez.
  - Botão para focar novamente na posição atual do usuário, caso ele de zoom/navegue em outra região.
  - Diferentes ícones para: localização atual, posições registradas anteriormente.
  - Splash screen personalizada com a identidade do aplicativo.
  - AppBar em todas as telas.
  - Configuração básica (nome, icone, permissões) nos projetos das plataformas Android e iOS.

Diferenciais:

- Verificar se o usuário está conectado a uma rede de internet ao abrir o aplicativo.
- Durante o uso, verificar se o usuário está com a localização mockada/fake.

Design:

A UI ficará livre para você usar sua criatividade seguindo as guidelines do Material Design/Cupertino.

## Requisitos

- Uso de alguma arquitetura: MVVM, MVP
- Desenvolvimento de testes unitários

## Recomendações de bibliotecas/frameworks

As recomendações servem como guideline para o desenvolvimento do desafio, mas fique a vontade para nos surpreender.

- Google Maps: google_maps_flutter
- Gps: location, geolocator
- Firebase: crashlytics
- Banco de dados: shared_preferences, sqflite
- Arquitetura: MVVM (stacked)
- Gerenciamento de estado: provider
- Testes unitários: mockito, build_runner
- Permissões: permission_handler

## Extras

- Componentes customizados (Ex: Botões, cards)
- UI distinta para Android e iOS, fazendo uso dos recursos específicos (Material e Cupertino) 
- Histórico de Commits e Pull Requests no GitHub

## Submissão

O candidato deverá implementar a solução e disponibilizar em um repositório no GitHub. Além de nos enviar por email uma versão executável (APK) com as chaves habilitadas, se necessárias.
