## ⚡ Stochastic Gradient Descent (SGD)

![Parabola Shape](Image1.png)


Stochastic Gradient Descent works similarly to Batch Gradient Descent, but instead of looking at the entire dataset, it updates the model using **one data point at a time**.  

This makes the updates **faster** and allows the model to move more quickly through the loss surface. However, the path is more **noisy** and less smooth compared to Batch Gradient Descent.

---

## 🧠 In Simple Words  
Think of the loss function like a **bowl** again.  

- Instead of taking a smooth step guided by the whole bowl, SGD takes a step based on just **one point on the bowl**.  
- This makes the path **zig-zag**, bouncing around as it moves toward the minimum.  
- Even though it’s noisier, this randomness can help **avoid getting stuck in local minima**.  
- Overall, it’s faster per iteration, but requires more careful tuning of the learning rate.

---

## ✅ Key Points
- Updates parameters **per sample**, not per dataset  
- Faster but noisier than batch updates  
- Can escape small “bumps” or local minima due to its randomness  
- Often used in **large datasets** where computing the full batch gradient is too slow
