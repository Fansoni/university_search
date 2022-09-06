# University Search

Precisa fazer uma busca pelas universidades a nível mundial? Eis a solução!

Essa aplicação permite efectuar uma busca sobre as universidades a nível mundial usando a API:
- http://universities.hipolabs.com/search?name=agostinho

### 1 - JSON

A API retorna algo nesse formato:

    [
    	...
    	{
    	    "alpha_two_code": "TR",
    	    "country": "Turkey",
    	    "state-province": null,
    	    "domains": [
    	        "sabanciuniv.edu",
    	        "sabanciuniv.edu.tr"
    	    ],
    	    "name": "Sabanci University",
    	    "web_pages": [
    	        "http://www.sabanciuniv.edu/",
    	        "http://www.sabanciuniv.edu.tr/"
    	    ],
    	},
    	...
    ]


### 2 - Dê uma olhada na documentação da API

Acesse aqui a API [university-domains-list-api](https://github.com/Hipo/university-domains-list-api)

### Created and maintained by [Fansoni Muzanzo](https://github.com/Fansoni)