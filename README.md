# pet_database

JSON file of vets, pets, and pet owners. It is used by [My JSON Server](https://my-json-server.typicode.com), which creates automatically creates `vets`, `pets`, and `petOwners` [endpoints](https://my-json-server.typicode.com/nbasham/pet_database) (super cool service).

Example:

```
https://my-json-server.typicode.com/nbasham/pet_database/pets
```

returns

```
[
  {
    "id": 0,
    "name": "Josie",
    "breed": "Labrador Retriever",
    "animalType": 0,
    "dob": "",
    "isFemale": true,
    "isSpayedOrNeutered": true
  }
]
```
