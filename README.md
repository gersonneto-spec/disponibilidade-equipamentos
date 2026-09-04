# Disponibilidade de Equipamentos - Marka Engenharia

App gerencial de controle de disponibilidade e manutencao de equipamentos.
Contrato Vale S.A. - Terminal Ferroviario da Ponta da Madeira (TFPM), Sao Luis/MA.

## Acesso

O app roda direto no navegador, sem instalacao: https://gersonneto-spec.github.io/disponibilidade-equipamentos/

## O que ele faz

- Disponibilidade por equipamento = (dias do periodo - dias parados) / dias do periodo, meta de 85%
- Horas trabalhadas pelo horimetro inicial e final de cada mes
- Paradas por motivo: corretiva, preventiva, lavagem, aguardando peca, troca de pneu, outros
- Ficha individual do equipamento com historico completo
- Rastreio dos itens de corretiva que mais se repetem por equipamento
- Acompanhamento por operador / motorista
- Filtro de periodo: mes, intervalo ou historico inteiro

## Onde os dados ficam

Por padrao os lancamentos ficam salvos apenas no navegador de quem usa.
Para a equipe inteira lancar e ver os mesmos numeros, abra a aba **Sincronizacao**
dentro do app e conecte um banco Supabase gratuito seguindo o passo a passo da tela.

## Estrutura

- `index.html` - o app inteiro em um arquivo unico, sem dependencias externas
