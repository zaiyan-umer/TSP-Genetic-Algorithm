# Traveling Salesman Problem using Genetic Algorithm

This project solves the Traveling Salesman Problem (TSP) with a Genetic Algorithm (GA).

Most people jump straight to AI agents and LLMs, but search and optimization are core AI fundamentals. TSP is a classic example: even with 20 cities, the number of possible routes is huge (19! ~= 121 trillion), so checking every route is not practical.

## What this notebook does

- Generates 20 random cities
- Creates an initial population of 100 random routes
- Uses route distance as the fitness signal
- Selects better routes as parents
- Applies crossover to create new routes
- Uses mutation to keep diversity in the population
- Runs for 500 generations

## Outcome

The algorithm converges to a near-optimal route through all 20 cities.

## Final Route
<img width="730" height="568" alt="image" src="https://github.com/user-attachments/assets/bd5b89fa-027c-472b-b9d4-6aabc669540f" />

## Reference Post

LinkedIn post: [Check out here](https://www.linkedin.com/posts/zaiyan-umer-935525324_everyone-talks-about-learning-ai-agents-and-activity-7439060222058479616-AT8B?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFHyhPkBgTF4U4kzGHh-uFH1VlblBGkgjBI)
