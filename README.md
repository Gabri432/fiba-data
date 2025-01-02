# Fiba world cup data
A collection of data about all the FIBA Basketball World Cups taken from 1950. See [wikipedia](https://en.wikipedia.org/wiki/FIBA_Basketball_World_Cup) for more information.

## Project Structure
- README.md
- license (MIT)
- worldcups.json

## Format
This is the format for any FIBA world cup from 1998:
```json
{
"cups":[
        ...
            {
                "year":"2023",
                "host":"Philippines, Japan, Indonesia",
                "winner":"Germany",
                "final_nations":["Germany", "Serbia"],
                "final_scores":"Germany 83-77 Serbia",
                "semi_final_nations":["Serbia", "Canada", "United States", "Germany"],
                "semi_final_scores":["Serbia 95-86 Canada", "United States 111-113 Germany"],
                "quarter_final_nations":["Serbia", "Canada", "United States", "Germany", "Italy", "Latvia", "Lithuania", "Slovenia"],
                "quarter_final_scores":["Lithuania 68-87 Serbia", "Italy 63-100 United States", "Germany 81-79 Latvia", "Canada 100-89 Slovenia"],
                "participant_standings":[
                    "Germany", "Serbia", "Canada", "United States", "Latvia", "Lithuania", "Slovenia", "Italy", "Spain", "Australia", 
                    "Montenegro", "Puerto Rico", "Brazil", "Dominican Republic", "Greece", "Georgia", "South Sudan", "France", "Japan", "Egypt", 
                    "Finland", "New Zealand", "Lebanon", "Philippines", "Mexico", "Angola", "Ivory Coast", "Cape Verde", "China", "Venezuela",
                    "Iran", "Jordan"
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
Sources: [Wikipedia](https://en.wikipedia.org/wiki/FIBA_Basketball_World_Cup), [FIBA website](https://www.fiba.basketball/en/history/201-fiba-basketball-world-cup)