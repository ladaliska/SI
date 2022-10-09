# XML feed

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
<root>
    <movies>
        <movie>
            <id></id>
            <name></name>
            <year></year>
            <genre_id></genre_id>
            <country_id></country_id>
        </movie>
    </movies>
    <countries>
        <country>
            <id></id>
            <name></name>
        </country>
    </countries>
    <genres>
        <genre>
            <id></id>
            <name></name>
        </genre>
    </genres>
</root>
```