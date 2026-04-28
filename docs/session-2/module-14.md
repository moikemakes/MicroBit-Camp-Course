# ⏳ Step 7: Survival System

## 🌟 What's New?
Now we need to make those needs change over time. As time passes, your pet will naturally get hungry and lose energy!

## 🛠️ What to Do
Inside a `forever` loop, add a `pause` block for a few seconds (e.g., 3000 ms).
Every few seconds:
* Hunger goes down by 1 (`change Hunger by -1`)
* Energy goes down by 1 (`change Energy by -1`)

Check the stats using `if` blocks! If values get too low (e.g., less than 2):
* Show a Sad face 😢
* Show a Sleepy face 😴
* Show an Angry face 😠

*Leave a screenshot of your survival loop code here:*
![Insert Survival Loop Code Here](images/survival-loop.png)

## 🏆 Challenge!
* Make your pet cry (play a sad sound) if its happiness hits 0!
