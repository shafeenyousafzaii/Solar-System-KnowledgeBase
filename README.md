# Solar System Ontology (Turtle Format)

## Project Overview
# Solar System Explorer

## Knowledge Representation and Reasoning

# Instructor: Shahzeb Khan


# Team Members:

#### Muhammad Shafeen

#### Tazmeen Afroz

#### Khizar Ali

#### Ahmad Mohsin

#### Aiman Arif

#### Zabiullah Zahir

#### Amber Khurshid

#### Humna Khan

#### Sarmad Khan

#### Saad Karim


### Domain Description

The Solar System Explorer Knowledge Graphis an intricate and dynamic rep-
resentation of our Solar System, meticulously designed to illuminate the vastness and
complexity of celestial bodies and their interrelationships. This project harnesses the
power of linked data and semantic technologies to provide an interactive and compre-
hensive understanding of the Sun, eight planets, their natural satellites (moons), and a
myriad of smaller objects such as asteroids and comets.

Key Features:

- Interconnected Data: Seamlessly links information about planets, and moons, en-
    abling users to explore their characteristics and relationships effortlessly.
- Rich Semantic Queries: Utilizes SPARQL queries to fetch and manipulate data,
    allowing for complex and insightful explorations of the Solar System’s structure.
- Dynamic Visualization: Presents data in an engaging format, making it easier to
    comprehend the vast distances, sizes, and unique attributes of each celestial body.
- Comprehensive RDF Models: Employs Resource Description Framework (RDF)
    to create detailed and standardized representations of each planet and moon, ensuring
    data consistency and interoperability.

Project Objectives:

1. Enhanced Understanding:Provide a deeper insight into the Solar System’s archi-
    tecture and the intricate relationships between its components.


2. Educational Tool:Serve as a valuable resource for educators and students to explore
    and learn about astronomy and planetary science.
3. Data Integration:Combine diverse datasets from various sources to create a unified
    and comprehensive knowledge base.
4. Scalability and Flexibility: Design the knowledge graph to accommodate future
    expansions, including additional celestial bodies and more detailed information.

Why a Knowledge Graph? Traditional databases often fall short in representing
the complex and interconnected nature of astronomical data. A knowledge graph, with
its ability to model relationships and enable semantic queries, offers a more intuitive
and powerful way to explore and analyze the Solar System. By leveraging linked data
principles, this project ensures that information is not only easily accessible but also
contextually meaningful.

Visual Representation:

```
Figure 1: Illustrative Diagram of the Solar System Explorer Knowledge Graph
```
Conclusion:The Solar System Explorer Knowledge Graph stands as a testament to the
fusion of astronomy and advanced data technologies. It not only maps out the celes-
tial bodies within our Solar System but also uncovers the intricate web of relationships
that define their existence. This project paves the way for innovative explorations and
discoveries, fostering a greater appreciation for the wonders of our cosmic neighborhood.

Future Directions:

- Integration with Real-Time Data:Incorporate live data feeds from space missions
    and telescopes to keep the knowledge graph updated.


- User Interactivity Enhancements:Develop interactive interfaces and visualization
    tools to allow users to engage with the data more dynamically.
- Expansion Beyond the Solar System: Extend the knowledge graph to include
    exoplanets and other stellar systems, broadening the scope of exploration.

Acknowledgments: This project is a collaborative effort, bringing together expertise
in linked data, semantic web technologies, and astronomical sciences to create a resource
that inspires curiosity and facilitates learning.

### Work Distribution

```
Team Member Tasks/Responsibilities
```
```
Khizar Ali Linked Data, Saved Queries, Managing GraphDB & SPARQL Queries
```
```
Tazmeen Afroz Question Creation, SPARQL Queries, Vocabularies
```
```
Ahmad Mohsin &
Aiman Arif
```
```
RDF Creation (Mars and Satrun)
```
```
Zabiullah Zahir &
Saad Karim
```
```
RDF Creation (Earth & Jupiter)
```
```
Amber Khurshid ,
Humna Khan &
Sarmad Khan
```
```
RDF Creation (Mercury , Venus , Uranus & Neptune)
```
Moons:

```
Planets Team Members
```
```
Jupiter & Earth Saad Karim & Zabiullah Zahir
```
```
Mars & Saturn Ahmad Mohsin & Aiman Arif
```
```
Mercury & Venus & Uranus &
Neptune
```
```
Sarmad Khan & Amber Khurshid & Humna Khan
```

## Questions

#### General Planetary Queries

1. Find the nth Smallest Planet.
2. List All Planet Names Containing a Spe-
    cific Color.
3. Find Planets with Specific Geological
    Features.
4. Find Planets Closer to the Sun than
    Earth’s Closest Approach.
5. Group Planets by Composition Types
    and Count Them.
6. Find the nth Coldest Planet.
7. Find Distance Between Any Two Plan-
    ets.
8. Find the nth Closest Planet to the Sun.
9. Find Planets with Multiple Composition
    Types.
10. Find Temperature Difference Between
Any Two Planets.
11. List All Planets with Specific Atmo-
spheric Composition.
12. Find the Difference in Day Length Be-
tween Planets.
13. Which is the red planet in the Solar Sys-
tem?
14. What is the orbital period of Saturn, and
how does it compare to Earth’s orbital
period?
15. What are the main components of Sat-
urn’s atmosphere?
16. What are the surface features of Saturn?
17. Orbital and Rotation Details of Venus.
18. Temperature and Pressure of Venus.
19. What are the Surface Features of Venus?
20. What are the atmospheric composition
and mean surface temperature of Mer-
cury?
21. What is the surface gravity of Mercury,
and how does it compare to Earth’s?
22. What is the composition of Mercury?


23. Which planet has no moon?
24. What are the colors of Earth?
25. How many Earths could fit inside the
    Sun?
26. What is the number of moons and sur-
    face features of Uranus and Neptune?
27. Which is the coldest planet in the solar
    system? SPARQL Query?
28. What is the orbital period and orbital
    velocity of Uranus and Neptune?
29. What are the main components of
    Uranus’ atmosphere?
30. What are the surface features of Nep-
    tune? SPARQL Query:
31. Which is the biggest planet?
32. Which planet in the solar system has
    more than 75 moons?
33. Which planet is made up of Hydrogen
    and Helium?

#### Moon-Related Queries

38. What are the names of all the moons of
    Mars?
39. Analyze the size difference between
    Mars’ two moons.
40. Identify the smallest and largest moons
    of Jupiter.
41. List all moons of Jupiter with a magni-
    tude greater than 10.
42. Which moon of Saturn has the largest
    radius?
43. Find the moon of Saturn with the high-
    est magnitude.
44. Which moon has the closest density to
    that of Earth’s Moon?
45. Find the planet with only one moon.
46. Find the moons of Neptune with an
    albedo greater than 0.5.
47. Find the moon of Neptune with the low-
    est albedo.
48. List all moons of Uranus with a radius
    less than 100 km.
49. Count the number of moons of Uranus.


### Vocabularies & Entities

```
Category Properties
```
```
General Planetary Prop-
erties • :colorPlanet
```
- :atmosphericComposition
- :mass
- :diameter
- :density
- :surfaceGravity
- :escapeVelocity
- :rotationPeriod
- :lengthOfDay
- :distanceFromSun
- :meanTemperature
- :numberOfMoons
- :ringSystem
- :globalMagneticField

```
Orbital Parameters
```
- :perihelion
- :aphelion
- :orbitalPeriod
- :orbitalVelocity
- :orbitalEccentricity
- :obliquityToOrbit

```
Surface and Atmospheric
Data • :surfacePressure
```
- :surfaceTemperature
- :atmosphericPressure
- :surfaceFeatures
- :composition

```
Moons Information
```
- :hasMoons


### GraphDB Visualization






### SPARQL Answers to Competency Questions

### General Questions :







### Planet Questions :



















## Features
- **Ontology Design**: Represents planets, their properties, and relationships (e.g., moons, distances, orbits).
- **Interactive Graphs**: Displays planet data interactively using **GraphDB**.
- **Semantic Reasoning**: Supports logical inferences and data querying through linked data models.
- **Collaboration**: Enables team-based modeling where each member contributed to specific planetary data.

## Technologies Used
- **Languages**: RDF, OWL, Turtle
- **Tools**: GraphDB
- **Frameworks**: Semantic Web Technologies

## Installation
1. **Install GraphDB**: Download [GraphDB](https://www.ontotext.com/products/graphdb/) for visualization and querying.
2. Clone the repository:
   ```bash
   git clone https://github.com/Alikhizar142/Solar-System-Ontology.git
   ```

## Usage
1. Load the ontology into GraphDB for visualization and SPARQL queries.
2. Explore relationships and properties using GraphDB’s reasoning tools.

## File Structure
```
📂 Solar-System-Ontology
├── planets_new.ttl       # Contains data about planets
├── moons.ttl             # Contains data about moons
├── Meta_new.ttl          # Metadata and ontology definitions
└── README.md             # Project documentation
```

## Example Query
Find all moons orbiting Jupiter:
```sparql
PREFIX : <http://example.org/solarsystem#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>

PREFIX xsd: <http://www.w3.org/2001/XMLSchema#>
SELECT ?moonName 
WHERE {
  ?moon a :satellite ;
        :hasSatellite :Jupiter ;
        rdfs:label ?moonName .
}

}
```

## Contribution
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/new-feature
   ```
3. Commit changes and push:
   ```bash
   git commit -m "Add new feature"
   git push origin feature/new-feature
   ```
4. Submit a pull request.

## License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

## Contact
For queries or suggestions, feel free to reach out:
- **Author**: Khizar Ali
- **GitHub**: [Alikhizar142](https://github.com/Alikhizar142)
- **Email**: p229269@pwr.nu.edu.pk

