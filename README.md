# dinosaur-data
Analyzed the museum's dinosaur fossil records to discover insights and and advise the museum on the quality of the data.


## 📖 Background

You're applying for a summer internship at a national museum for natural history. The museum recently created a database containing all dinosaur records of past field campaigns. Your job is to dive into the fossil records to find some interesting insights, and advise the museum on the quality of the data.

## 💾 The data

#### You have access to a real dataset containing dinosaur records from the Paleobiology Database ([source](https://paleobiodb.org/#/)):

| Column name  | Description                                                                                              |
| ------------ | -------------------------------------------------------------------------------------------------------- |
| occurence_no | The original occurrence number from the Paleobiology Database.                                           |
| name         | The accepted name of the dinosaur (usually the genus name, or the name of the footprint/egg fossil).     |
| diet         | The main diet (omnivorous, carnivorous, herbivorous).                                                    |
| type         | The dinosaur type (small theropod, large theropod, sauropod, ornithopod, ceratopsian, armored dinosaur). |
| length_m     | The maximum length, from head to tail, in meters.                                                        |
| max_ma       | The age in which the first fossil records of the dinosaur where found, in million years.                 |
| min_ma       | The age in which the last fossil records of the dinosaur where found, in million years.                  |
| region       | The current region where the fossil record was found.                                                    |
| lng          | The longitude where the fossil record was found.                                                         |
| lat          | The latitude where the fossil record was found.                                                          |
| class        | The taxonomical class of the dinosaur (Saurischia or Ornithischia).                                      |
| family       | The taxonomical family of the dinosaur (if known).                                                       |

The data was enriched with data from Wikipedia.

## 💪 Challenge

Help your colleagues at the museum to gain insights on the fossil record data. Include:

1. How many different dinosaur names are present in the data?
2. Which was the largest dinosaur? What about missing data in the dataset?
3. What dinosaur type has the most occurrences in this dataset? Create a visualization (table, bar chart, or equivalent) to display the number of dinosaurs per type. Use the AI assistant to tweak your visualization (colors, labels, title...).
4. Did dinosaurs get bigger over time? Show the relation between the dinosaur length and their age to illustrate this.
5. Use the AI assitant to create an interactive map showing each record.
6. Any other insights you found during your analysis?

