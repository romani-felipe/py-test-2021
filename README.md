# Desafio frontend

Olá seja bem vindo ao desafio técnico para vaga de <b>desenvolvedor Python pleno</b>.

## 💪 O desafio 

Como bons brasileiros gostamos de uma boa música para curtir nos momentos mais apropriados com as pessoas que gostamos. Esperamos que você também goste de música e do clima agradável do nosso país, pois é a partir disso que sua solução será criada.

Precisamos de uma API REST com um único endpoint que dado uma coordenada GPS deverá retornar uma playlist do Spotify baseado na temperatura do local.

Por Exemplo:

Dado as coordenadas: 
```
    🌎 latitude: -22.881032683156707 longitude: -47.04348487925273
```

Devemos retornar conforme o JSON abaixo:
```json
{
    "city": "Campinas",
    "temperature": 26,
    "playlist_name": "Samba music",
    "playlist_id": "5be7bc08-77ea-48b6-92ec-cbb8e3af3c82"
}
```

### 🎮 Regras para selecionar a playlist: 

- Clima abaixo de 0 graus playlist de música Clássica 
- Clima entre 0 e 10 graus playlist de Rock
- Clima entre 11 e 15 graus playlist de MPB
- Clima entre 16 e 20 graus playlist de Rap
- Clima entre 21 e 30 graus playlist de Samba
- Clima acima de 31 graus playlist de Festa (Party)


### 🚩 Para atingir os objetivos use as API's abaixo:
- API do Spotify (https://developer.spotify.com/)
- API da Open Weather (https://openweathermap.org/api)


### 👨‍⚖️ Requisitos

- Usar python
- Desenvolver testes para a aplicação

## 🏆 O que será avaliado?

- Raciocínio para resolver o problema proposto
- Escalabilidade
- Performance
- Manutenibilidade
- Clareza e qualidade do código

## 🚚 O que devo entregar?

Um repositório público no github, com documentação e comandos para executar a aplicação e os testes.

## 🎩 Diferencial
- Entregar o ambiente em docker
- Entregar imagem docker pública no 'docker hub'

🍀 Desejamos sucesso, boa sorte! 🍀
