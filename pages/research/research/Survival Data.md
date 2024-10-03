

## How doctors predict when you will die?
- What is survival data and why is it difficult to deal with?

Intro
Good morning, today I'm going to talk about how doctors predict when you will die. 

Last May this year, My uncle had stroke and he was in comma for like 3 months. Doctor said to my aunt that he might only have 3 months to live.

Fortunately, he is now recovering from that, but back then, as a researcher I was desperately searching for researches about the disease to assure my aunt that my uncle will be okay.

I truly hope none of you ever face such a situation. But if you face such a case where your friend or loved one suffers from illness whether it is serious or not, I want you to understand statistics properly and I want you to give hope and clarity to them, as I did.

To do that, I'll explain the most commonly used data type in hospital, and one simple method to predict an incident happens. After that, you will be able to easily understand papers even with some difficult-looking statistics.
### What is right-censored data?
So what is the right censored data?
The right censored data is the data used to track some events. For example like my case, if you want to know when the patients will die, the right-censored data is used.

![[Screenshot 2024-09-30 at 11.19.50 PM.png]]
So if you look at the board here, the x-axis is time, and each line indicates each patient. So after an occurrence of a disease, maybe some patient will die after 1 month, some might die after 3months, or maybe some might survive but leave hospital, then they are not tracked, and some will survive until the end of the observation. 

What you should look at this is that we do not know what happens to the patients afterwards. So we only have the left side of the data, but we do not know the right side. That is why the data is called right-censored data, because we do not know what happens in the right side. That is, the right censored data clearly shows if a patient survived or died, and most importantly, how long if survived.

### Kaplan-Meier Survival Curve
One exemplary case is the Kaplan-Meier Survival Curve. This is the sum of the survivals, divided by the total number of available patients. When doctors say the survival rate for 3 month is 70%, this curve is used. 
There is a trick here. For example, the 3 months survival ratio here is low, but when a patient survived up to 2 months, the possibility to death can be actually low. Maybe that's because they were well treated the golden time, and doctors will say the patient has passed the critical stage.


Final
There are other methods that uses right-censored data, but due to the time limit, let me stop here.
Now to sum up, the right-censored data is the typical type of data that is used to survival analysis, 

and one example to the right-censored data is Kaplan Meier Survival Curve, on which doctors predict whether the patient will survive or die.

In my experience, it’s hard to stay strong during difficult times, but I hope this little session will offer you hope when challenges arise. 
