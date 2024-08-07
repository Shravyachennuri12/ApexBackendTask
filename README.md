Backend for Pokemon:

Installation instructions:

1.clone this project 
2.cd ApexBackendTask
3.run npm install
4.For data storage Created a server file i.e data.json
5.run npm run dev 

Node.js backend to serve pokemon data, API for pokemon

This is the pokemon project

Api Endppints:
1.get('/pokemon')---to get the all users.
2.POST('/pokemon')---To create a user post.
  Example:
  {
    "pokemonOwnerName": "Srinivas",
    "pokemons": [
      {
        "id": "23cdfbc2-ab51-4a71-b6da-2cba39fa919f",
        "pokemonOwnerName": "Srinivas",
        "direction": "23",
        "initialPositionX": "123",
        "initialPositionY": "1224",
        "pokemonName": "ivysaur",
        "pokemonAbility": "overgrow",
        "speed": "100"
      }
    ],
    "pokemonAbility": "overgrow"
  }
3.post('/pokemon/:ownerName/add')---To add a pokemon owner.
4.delete('/pokemon/:ownerName')---To delete a pokemon owner.
5.delete('/pokemon')---To delete all pokemon users at a time.
6.get('/pokemon-owners')---To get all pokemon users.
7.get('/pokemon/:ownerName')---To get pokemon users by owner name.
8.
put('/pokemon/:pokemonOwnerName')---To get Pokemon by owner name.


Contributing:

For now this is a Full Stack course project of mine. Maybe in the future I could accept contributions.

