# ValorantAPI_Wrapper
This is a Unofficial API wrappper for Valorant.
The base of this project made by [@colinhartigen](https://github.com/colinhartigan) [valclient.py](https://github.com/colinhartigan/valclient.py)
# <img src="https://img.shields.io/github/issues/csence/ValorantAPI_Wrapper" > <img src="https://img.shields.io/pypi/v/valorantapi-wrapper" > [![Downloads](https://pepy.tech/badge/valorantapi-wrapper)](https://pepy.tech/project/valorantapi-wrapper)
# Installation
```pip install ValorantAPI-Wrapper```
# Example
```python
from ValorantAPI_Wrapper.client import Client

client = Client(region="eu", auth={ "username": "username", "password": "password" })
client.activate()

mmr = client.fetch_mmr()
print(mmr)
```
# Issues
Open new issue if you find missing endpoint or you have any bug/issue
# Contributing
This library is not complete and still has a ways to go and can be improved in many aspects. Please contribute if you would like. Any contributions you make are greatly appreciated.
# Legal
ValorantAPI_Wrapper is not endorsed by Riot Games and does not reflect the views or opinions of Riot Games or anyone officially involved in producing or managing Riot Games properties. Riot Games and all associated properties are trademarks or registered trademarks of Riot Games, Inc
