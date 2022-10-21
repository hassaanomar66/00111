# locod.io-templates

Example templates for use with locod.io

### Twig

The templating engine that locod.io is using is twig.  
More information: https://twig.symfony.com/

## Variables

These are the variable structures that can be used for rendering in the templates.

### Model

    ...

### Enum

    {
        "id": 9,
        "uuid": "5d517174-3456-4ece-99a3-81b79a4f17ba",
        "name": "FieldType",
        "namespace": "App\\Locodio\\Domain\\Model\\Model",
        "options": [
            {
                "id": 25,
                "uuid": "daba4f74-6c88-4fd8-92d9-66533f7fe534",
                "sequence": 0,
                "code": "INTEGER",
                "value": "integer"
            },   
            ...
        ],
        "domainModel": {
            "id": 10,
            "uuid": "e94ae6df-6a58-4ef7-8bfc-0bb2a4df9e99",
            "sequence": 2,
            "name": "Field",
            "namespace": "App\\Locodio\\Domain\\Model\\Model",
            "repository": "App\\Locodio\\Infrastructure\\Database\\FieldRepository"
        }
    },

### Query

    ...

### Command

    ...

# About

locod.io is a free and open-source web application for data-modelling and code generation. With its template based approach, locod.io can generate code for any kind of languages. 