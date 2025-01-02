# Fiba world cup data
A collection of data about all the FIBA Basketball World Cups taken from 1950. See [wikipedia](https://en.wikipedia.org/wiki/FIBA_Basketball_World_Cup) for more information.

## Project Structure
- README.md
- license (MIT)
- worldcups.json

## Format
```json
{
"cups":[
        ...
            {
                "year":"2023",
                "host":"Philippines, Japan, Indonesia",
                "winner":"",
                "final_nations":["Germany", "Serbia"],
                "final_scores":"Germany 83-77 Serbia",
                "semi_final_nations":["Serbia", "Canada", "United States", "Germany"],
                "semi_final_scores":["Serbia 95-86 Canada", "United States 111-113 Germany"],
                "quarter_final_nations":["Serbia", "Canada", "United States", "Germany", "Italy", "Latvia", "Lithuania", "Slovenia"],
                "quarter_final_scores":["Lithuania 68-87 Serbia", "Italy 63-100 United States", "Germany 81-79 Latvia", "Canada 100-89 Slovenia"],
                "participants":[
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