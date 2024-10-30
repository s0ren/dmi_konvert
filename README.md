# Konverter DMI meteo data 

Jeg vil gerne have DMI data'erne med meteorlogiske observationer konverteret.

Ved download er data i json format. 
Json'en er struktureret som "long-form", men jeg vil hellere have dem i "wide-form", for det tro jeg er bedre (og mere effektivt) til kolonnebaseret parquet.
Se <https://anvil.works/blog/tidy-data>

Det vil vise sig om det er rigtigt, og om jeg kan konvertere dem effektivt.

Se _ afsnit "5.3 Shredding nested JSON" side 102, i "DuckDB in action"
og måske "4.7 The PIVOT statement" i samme.

Min plan er at bruge DuckDB