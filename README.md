# Strapi internationalization :flags:
#### The main goal of internationalization on Strapi is to enable developers to create multilingual applications that can be accessed by users from different parts of the world. This is achieved by providing tools and features that allow developers to easily translate their content and user interfaces into different languages. 

#### Developers can create a single codebase that supports multiple languages, making it easier to manage and update their applications. This can help businesses and organizations reach a wider audience and improve user experience for non-native speakers.

This project uses a Book content type to test Strapi internationalization functionality, you can check the documentation [here!](https://documenter.getpostman.com/view/17256808/2s93XvUjRM)

When the GET endpoint is called the response is the following content with three different languages (English, Spanish and French) :loudspeaker:

``` JSON
{
    "data": {
        "id": 1,
        "attributes": {
            "title": "The Analyst",
            "publication_date": "2003-04-03",
            "ISBN": "978-0345426271",
            "genre": "Psychological thriller",
            "synopsis": "A criminal mastermind known as \"Rumpelstiltskin\" threatens to ruin the life of a New York City psychoanalyst, who must use all his training to outwit the sinister villain.",
            "createdAt": "2023-04-12T04:02:56.768Z",
            "updatedAt": "2023-04-12T04:08:45.040Z",
            "publishedAt": null,
            "locale": "en",
            "author": [
                {
                    "id": 1,
                    "name": "John Katzenbach"
                }
            ],
            "cover": {
                "data": {
                    "id": 1,
                    "attributes": {
                        "name": "The Analyst.gif",
                        "alternativeText": null,
                        "caption": null,
                        "width": 300,
                        "height": 494,
                        "formats": {
                            "thumbnail": {
                                "name": "thumbnail_The Analyst.gif",
                                "hash": "thumbnail_The_Analyst_af73e49585",
                                "ext": ".gif",
                                "mime": "image/gif",
                                "path": null,
                                "width": 95,
                                "height": 156,
                                "size": 13.45,
                                "url": "/uploads/thumbnail_The_Analyst_af73e49585.gif"
                            }
                        },
                        "hash": "The_Analyst_af73e49585",
                        "ext": ".gif",
                        "mime": "image/gif",
                        "size": 108.91,
                        "url": "/uploads/The_Analyst_af73e49585.gif",
                        "previewUrl": null,
                        "provider": "local",
                        "provider_metadata": null,
                        "createdAt": "2023-04-12T04:02:52.165Z",
                        "updatedAt": "2023-04-12T04:02:52.165Z"
                    }
                }
            },
            "localizations": {
                "data": [
                    {
                        "id": 3,
                        "attributes": {
                            "title": "El analista",
                            "publication_date": "2003-04-18",
                            "ISBN": "978-0345426271",
                            "genre": "Thriller psicológico",
                            "synopsis": "Un genio del crimen conocido como \"Rumpelstiltskin\" amenaza con arruinar la vida de un psicoanalista de la ciudad de Nueva York, quien debe usar toda su formación para vencer al siniestro villano.",
                            "createdAt": "2023-04-12T04:08:45.029Z",
                            "updatedAt": "2023-04-12T04:08:59.523Z",
                            "publishedAt": "2023-04-12T04:08:59.520Z",
                            "locale": "es-CO"
                        }
                    },
                    {
                        "id": 2,
                        "attributes": {
                            "title": "L'analyste",
                            "publication_date": "2003-04-03",
                            "ISBN": "978-0345426271",
                            "genre": "Thriller psychologique",
                            "synopsis": "Un génie criminel connu sous le nom de \"Rumpelstiltskin\" menace de ruiner la vie d'un psychothérapeute de New York, qui doit utiliser toute sa formation pour déjouer le sinistre criminel.",
                            "createdAt": "2023-04-12T04:05:57.342Z",
                            "updatedAt": "2023-04-12T04:08:45.040Z",
                            "publishedAt": null,
                            "locale": "fr"
                        }
                    }
                ]
            }
        }
    },
    "meta": {}
}
```
