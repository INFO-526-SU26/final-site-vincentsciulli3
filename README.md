[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/7LgAUKoA) \# project-final

Final Project repo for INFO 526 - Summer 2024.

#### Disclosure:

Derived from the original course by Mine Çetinkaya-Rundel \@ Duke University

**Description:**

This project will jump into the world of Pokemon through the 'Pokemon' dataset provided by TidyTuesday to answer the questions of (1) which starter is the best, statistically, throughout the evolutionary stages? and (2) what does the type diversity look like through the various regions of Pokemon? While the aforementioned questions will be answered, we'll also discover how well the Pokemon developers, GameFreak, balanced not just the partner Pokemon that accompanies us throughout our journeys, but also the available Pokemon that we'll meet through a given region.

#### Variables:

| **Variable** | **Class** | **Description** |
|----|----|----|
| id | integer | The unique ID of each Pokemon. |
| pokemon | character | The name of each pokemon. |
| species_id | integer | The species ID of each Pokemon. |
| height | double | The height of each pokemon. |
| weight | double | The weight of each pokemon. |
| base_experience | integer | The base experience of each Pokemon. |
| type_1 | character | The primary type. |
| type_2 | character | The secondary type. |
| hp | integer | The HP (hit points). |
| attack | integer | The attack points. |
| defense | integer | The defense points. |
| special_attack | integer | The special attack points. |
| special_defense | integer | The special defense points. |
| speed | integer | The speed. |
| color_1 | character | The primary color of each pokemon. |
| color_2 | character | The secondary color of each pokemon. |
| color_f | character | The final color of each pokemon. |
| egg_group_1 | character | The primary egg group. |
| egg_group_2 | character | The secondary egg group. |
| url_icon | character | The URL for the icon of each Pokemon (if available). Note that these are missing the starting "https:". |
| generation_id | integer | The generation ID of each Pokemon. |
| url_image | character | The URL for the image of each Pokemon. |
| starter\* | character | If the Pokemon is a starter or not |
| evo_stage\* | integer | Which evolutionary stage is the given Pokemon |
| region\* | character | List of region(s) where the given Pokemon is found in the regional Pokedex |
| base_stat_total\* | integer | Sum of the "hp", "attack", "defense", "speed", "special_attack", and "special_defense" variables |

\*New Variable
