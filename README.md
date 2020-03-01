# cisc275-fall2019-first-git
1. Create java files to make this code compile and run.

2. What five objects are created in the main?
* 1 ArrayList
* 3 Dogs
* 1 Comparator

3. Can you spot the Comparator constructor call? Where is the class definition for the Comparator?
`new Comparator<Animal>()`
class definition:
```
@Override
public int compare(Animal a, Animal b){
    return a.getLegs() - b.getLegs();
}
```
