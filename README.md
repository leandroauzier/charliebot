# Charliebot
Um robô usado para gerenciamento de atendimento da empresa Team Charlie Amapá.


## Prepare seu ambiente

Criar ambiente virtual:
```
python -m venv venv
```
Entrar no ambiente:
```
venv/Scripts/activate
```
Instalar requirements:
```
pip install requirements.txt
```
Execute o server:
```
flask run
```

## Informações

O presente sistema está hospedado em uma plataforma Railway, ele possui 500 hrs de hospedagem gratuita o equivalente a mais ou menos 21 dias no ar mensalmente, portanto para que fique online de forma gratuita por um mês é necessário que permaneça online durante Seg a Sex e desligado nos fins de semana.

## Funcionamento

Para que o bot funcione da maneita adequada é necessário utilizar as seguintes ferramentas:
- DialogFlow (Para criação de intents);
- Esta aplicação em python;
- AutoResponder (o app gratuito que conecta com a api key do dialogflow com o whatsapp);

o link da hospedagem Railway precisa estar inserido no Fulfillment do Dialogflow.