### @explicitHints true

# Activity 3 - Cleaning up.

```python
for i in range(2):
pass
agent.collect_all()
agent.move(FORWARD, 5)
agent.drop_all(FORWARD)
```

## Step 1
**Part 1:** Make a code so that the Agent will go over every block of the small carpet and pickup the dirt.

## Step 2
**Part 2:** Edit the same code so that the Agent does the same thing but for the larger carpet. Do this by repeating the code before, **3** times,
using a `||loops:for||` loop. At the end make the Agent drop all of the dirt in the trash. 

```template
// replace with loop number 3    | Part 2
// replace with loop number 1    | Part 1
agent.collect_all()
agent.move(FORWARD, 1)
agent.move(RIGHT, 1)
// replace with loop number 2    | Part 1
// make the Agent collect all    | Part 1  
// make the Agent move back      | Part 1  
// make the Agent move right     | Part 2  
// make the Agent drop all       | Part 2  
```