# Fiba world cups data
A collection of data about the FIBA Basketball World Cups from 1982 to 2023. See [wikipedia](https://en.wikipedia.org/wiki/FIBA_Basketball_World_Cup) for more information.

## Project Structure
- README.md
- license (MIT)
- worldcups.json

## Formats
This is the format for any FIBA world cup since 1998:
```json
{
"cups":[
        ...
            {
                "year":"2019",
                "host":"China",
                "winner":"Spain",
                "final_nations":["Spain","Argentina"],
                "final_scores":"Spain 95-75 Argentina",
                "semi_final_nations":["Argentina", "France", "Spain", "Australia"],
                "semi_final_scores":["Argentina 80-66 France", "Spain 95-88 Australia"],
                "quarter_final_nations":["Argentina", "Serbia", "United States", "France", "Spain", "Poland", "Australia", "Czech Republic"],
                "quarter_final_scores":["Argentina 97-87 Serbia", "United States 79-89 France", "Spain 90-78 Poland", "Australia 82-70 Czech Republic"],
                "participant_standings":[
                    "Spain", "Argentina", "France", "Australia", "Serbia", "Czech Republic", "United States", "Poland", "Lithuania", "Italy",
                    "Greece", "Russia", "Brazil", "Venezuela", "Puerto Rico", "Dominican Republic", "Nigeria", "Germany", "New Zealand", "Tunisia",
                    "Canada", "Turkey", "Iran", "China", "Montenegro", "South Korea", "Angola", "Jordan", "Ivory Coast", "Senegal",
                    "Japan", "Philippines"
                ]
            },
        ...
        ]
}
```

This is instead the format for FIBA world cup up to 1994:
```json
{
    "cups_before_1998": [
        {
            "year":"1994",
            "host":"Canada",
            "winner":"United States",
            "final_nations":["United States", "Russia"],
            "final_scores":"United States 137-91 Russia",
            "semi_final_nations":["Russia", "Croatia", "Greece", "United States"],
            "semi_final_scores":["Russia 66-64 Croatia", "Greece 58-97 United States"],
            "semi_final_qualification_nations":["United States", "Australia", "Russia", "Canada", "Croatia", "China", "Greece", "Puerto Rico"],
            "semi_final_qualification_scores":[
                "Russia 101-85 Puerto Rico", "United States 130-74 Australia", "Australia 76-103 Russia",
                "Puerto Rico 83-134 United States", "Australia 94-81 Puerto Rico", "United States 111-94 Russia",
                "Croatia 105-73 China", "Greece 74-71 Canada", "Canada 61-92 Croatia",
                "China 61-77 Greece", "China 58-90 Canada", "Croatia 81-55 Greece"
            ],
            "participant_standings":[
                "United States", "Russia", "Croatia", "Greece", "Australia", "Puerto Rico", "Canada", "China", "Argentina", "Spain",
                "Brazil", "Germany", "South Korea", "Egypt", "Cuba", "Angola"
            ]
        }
        ...
    ]
}
```

## Notes
- Sources: [Wikipedia](https://en.wikipedia.org/wiki/FIBA_Basketball_World_Cup), [FIBA website](https://www.fiba.basketball/en/history/201-fiba-basketball-world-cup);
- The 2023 FIBA Basketball World Cup was hosted by three countries: Philippines, Japan and Indonesia. This field is still a string, not a list/array of strings. 