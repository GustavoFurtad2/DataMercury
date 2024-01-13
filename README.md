# DataMercury

```
   ___      _                                                
   /   \__ _| |_ __ _    /\/\   ___ _ __ ___ _   _ _ __ _   _ 
  / /\ / _` | __/ _` |  /    \ / _ | '__/ __| | | | '__| | | |
 / /_/| (_| | || (_| | / /\/\ |  __| | | (__| |_| | |  | |_| |
/___,' \__,_|\__\__,_| \/    \/\___|_|  \___|\__,_|_|   \__, |
                                                        |___/ 
```

Data Mercury it's a Json Data Handler for Athena Enviroment
by GustavoFurtad2 (github.com/GustavoFurtad2)

Use examples:

let save = new Data("save.json"); // Make a new Data using a json file

console.log(save.exists("name")); // Checks if item "name" exists
console.log(save.get("name")); // Get the value of the specified item
console.log(save.delete("name")); // Dele item "name"
save.setValue("name", "Game1"); // Set or create a value in item name, set Game1 of the new name value
save.saveIn("save.json"); // Save the sketch in the specified file
save.undo(); // Undo the sketch to the original file
