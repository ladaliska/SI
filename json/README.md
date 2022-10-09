# JSON feed

## Databáze 
root:
## Tabulky
movies, countries, genres

### po zapsaní tabulky musíte napsat jednotné číslo dané tabulky

movie, country, genre

### jejich data v přesným pořadí jsou
id, name

### u movie jsou (genre_id, country_id jsou FK)
id, name, year, genre_id, country_id

# Forma
```
{
    "root": {
        "movies": {
            "movie": {
                "id": ,
                "name": "",
                "year": ,
                "genre_id": ,
                "country_id": ""
            }
        },
        "countries": {
            "country": {
                    "id": ,
                    "name": ""
                },
        },
        "genres": {
            "genre": {
                "id": ,
                "name": ""
            }
        }
    }
}
```
