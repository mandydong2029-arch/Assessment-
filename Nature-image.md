Welcome to **TreeLife**, your guide to learning about the beauty, diversity, and importance of trees around the world

---

### About Us
At **TreeLife**, we're passionate about forests and green living.
Our mission is to:
- Educate people about the different types of trees.
- Promote sustainable forestry.
- Encourage reforestation projects.

### Featured Trees
**Oak Tree**

**Scientific Name**: *Quercus robur*

Known for its strength and longevity, the oak is a symbol of endurance.
![alt text](https://treenewal.com/wp-content/uploads/2020/11/oak-tree-care.png)

### Pine Tree
**Scientific Name**: *Pinus*

Evergreen and aromatic, pine trees thrive in colder regions.
![alt text](https://www.eekwi.org/sites/default/files/2019-12/healthygreentrees.jpg)

### Tree Identification Tool
You can use this simple **Javascript** function to identify a tree by its characteristics:


```
function identity_tree(leaf_shape, region) { 
    if (leaf_shape == "needle" && region == "cold") {
        return "Pine Tree"
    } else if (leaf_shape == "broad" && region == "temperature) {
        return "Oak Tree"
    } else {
        return "Unknown Tree"
    } 
} 
console.log(identify_tree("needle", "cold"))
``` 