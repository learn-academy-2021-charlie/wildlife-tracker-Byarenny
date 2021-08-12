#WildLife Tracker
Story: As a developer I can create an animal model in the database. An animal has the following information: common name, latin name, kingdom (mammal, insect, etc.).
Story: As the consumer of the API I can see all the animals in the database. Hint: Make a few animals using Rails Console
**common_name: "Sloth", latin_name: "Folivora", kingdom: "Mammal"**
**common_name: "Red-eyed tree frog", latin_name: "Agalychnis callidryas", kingdom: "Amphibian"**
**common_name: "Toco toucan", latin_name: "Ramphastos toco", kingdom: "Aves"**
**common_name: "Jaguar", latin_name: "Panthera onca", kingdom: "Mammal"**

Story: As the consumer of the API I can update an animal in the database.
Story: As the consumer of the API I can destroy an animal in the database.
Story: As the consumer of the API I can create a new animal in the database.
Story: As the consumer of the API I can create a sighting of an animal with date (use the datetime datatype), a latitude, and a longitude.
Hint: An animal has_many sightings. (rails g resource Sighting animal_id:integer ...)
Story: As the consumer of the API I can update an animal sighting in the database.
Story: As the consumer of the API I can destroy an animal sighting in the database.
Story: As the consumer of the API, when I view a specific animal, I can also see a list sightings of that animal.
Hint: Checkout the Ruby on Rails API docs on how to include associations.
Story: As the consumer of the API, I can run a report to list all sightings during a given time period.
Hint: Your controller can look like this:
