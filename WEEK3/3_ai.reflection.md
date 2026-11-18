 Audit Log & Reflection

1. AI interpretation 

The table shows that all four items rose over the Jan–Feb 2026 period. Staple A is the most interesting: its mean is 340 but its median is only 210, which suggests the mean is being pulled up by an outlier. Removing the 1250 value drops the mean to about 248 while the median stays at 208. This shows the median is more robust than the mean. Prices likely rose because of supply pressures across the country since 2024. Overall, the typical price went up for every item, so the neighbour quoting the median is right.

2. Audit table

- Green = I can check the number in my notebook
- Amber = it is an explanation, not a fact
- Red = a claim, or data I was not shown

AI claim   |  Colour |  How I checked |  Accept / Reject |

All four items rose over Jan–Feb 2026 | Green | Cell 4: pct_change is positive for all | Accept |
Staple A mean is 340, median is 210 | Green | Cell 7 prints these numbers | Accept |
The mean is pulled up by an outlier | Amber | This is an explanation. Cell 5 supports it | Accept as E |
Removing 1250 drops the mean to 248 | Green | Cell 7: normal.mean() = 248 | Accept |
The median stays at 208 | Green | Cell 7: normal.median() = 208 | Accept |
The median is more robust | Green | Cells 5 and 6: mean moves ~92, median moves ~2 | Accept |
Prices rose because of supply pressures | Red | No supply data in the file | Reject |
Across the country | Red | Cell 8: only City 1 and City 2 | Reject |
Since 2024 | Red | Cell 8: only Jan–Feb 2026 | Reject |
The typical price went up for every item | Amber | "Typical" is vague. Change to "median price went up" | Amend and accept |
The neighbour quoting the median is right | Amber | Only partly right. Mean answers a different question | Amend and accept |

I accepted 6 claims, changed 2 and rejected 3. None of the rejected ones are in my 1_attempt.md.

3. AI Classmate talk:

Classmate (AI): Why isn't the mean the typical price?
Me: Because the mean adds every price and divides by the count. One huge value counts in full. In Staple A, one quote is 1250 and the rest are around 200. That one quote pulls the mean up to 340.
Classmate: But why does one number matter so much?
Me: The mean gives each price a vote based on its size. The median gives each price one vote based on its position. So a big number wins the mean but not the median.
Classmate: So which one is right?
Me: Neither. They answer different questions. Mean = total divided by count. Median = the middle quote. For "typical price", use the median. For "total cost", use the mean.
Classmate: So the neighbours are not really arguing about the same thing.
Me: Exactly. That is the point of the note.

4. Reflection

1. My first draft said "every item went up" but did not say which cities or dates. I added "City 1 and City 2, Jan–Feb 2026".
2. I wrote "the mean overstates the price". That is an explanation, not a fact. I marked it E.
3. I wrote "prices rose because of supply". That is a cause claim with no cause data. I deleted it.
4. I said "everywhere". I only have two cities, so I changed it to "in the teaching basket".
5. What I learned: the O / E / C labels and the colour check stop me from turning a guess into a fact.
