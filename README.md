**Annual Cost Saved = Hours/week × 52 × Hourly rate**
If someone spends 12 hrs/week on a task at $45/hr, that's 12 × 52 × 45 = $28,080/year you'd save by automating it away.

**Error Impact = Error rate × Frequency multiplier × 10**
Captures the hidden cost of mistakes. 
A process with a 12% error rate that runs daily is more damaging than one with the same error rate running monthly. 
The frequency multiplier (Daily=5, Weekly=1, Monthly=0.25) weights this accordingly. 
The ×10 is a scaling factor so error impact has meaningful influence on the final score relative to cost savings.
Without it, cost would dominate the score and a cheap-but-error-prone process would never rank high.

**÷ 1,000 on Annual Cost**
This is a scaling normalization. Annual cost saved can be $28,000-$40,000+ while error impact is typically 10-600. 
If you don't scale them down to a similar range, cost dominates everything and error rate becomes irrelevant in the ranking. 
Dividing by 1,000 brings a $28,000 savings down to 28 points, which is now comparable to an error impact score of, say, 60. 
This way both factors actually influence the prioritization.

**Complexity Discount (Low=1.0, Medium=0.7, High=0.4)**
Even if a process has massive savings potential-
If it's highly complex to automate, the real-world ROI is lower because 

1) implementation will cost more
2) take longer
3) has higher failure risk
   
So we discount the score.
A high-complexity process keeps only 40% of its raw score — it's still visible in the ranking, but it won't outrank an easier win.

So the full formula:
**ROI Score = ((cost savings on a normalized scale) + (error cost weighted by frequency)) × (feasibility adjustment)**

------------------

It's basically asking: 
1) how much money and time are we wasting
2) how often are we making mistakes
3) and how realistic is it to actually automate this?
