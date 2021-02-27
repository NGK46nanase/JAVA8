# 1.Conway's Law
Also known as: "You will ship your org chart."

>"Any organization that designs a system will 
>produce a design whose structure is a copy of the organization's communication structure."

You may think you can avoid it via cross-functional standup meetings and stakeholder updates and decision matrices, but eventually and inevitably conflicting or diverging priorities will lead to equally conflicting or divergent processes and outcomes.

# 2. Brooks's Law
From The Mythical Man-Month:

>"Adding manpower to a late software project makes it later."

When you realize you're not making the progress you thought you would and your management tries to reallocate resources from another part of the org, you'll end up not only delaying the project, but you'll likely ship a more brittle, more complex product (see Conway's Law).

# 3. Zawinski's Law
Adjusted for 2021:

>"Every program attempts to expand until it includes a web server. Those programs which cannot so expand are replaced by ones which can."

For web services, it's "...until it requires a user account and collects all users' data"; for physical devices, it's "...until it includes an insecure wifi access point with a default password you can't change. And a web server".

(Zawinski disagrees)

# 4. Parkinson's Law

>"Work expands so as to fill the time available for its completion."

The primary project management lessons here is that if you don't set rough deadlines for at least conceptual milestones, then the project will never be completed. This is why iterating on a minimum viable product within fixed timelines is important.

And, of course, we can and should adjust this law for data, processing power, RAM, ...:

>"Data/CPU/memory usage expands to use up all available storage space/bandwidth/cycles/RAM."

640K32GB ought to be enough for anyone, right?

# 5. Pareto's Fallacy
The Pareto Principle is easy to misinterpret, especially by management. This often leads to Pareto's Fallacy:

>"When you're 80% done, you think you only have 20% left."

The critical part that's overlooked here is that those 20% will require 80% of your time.

See also: Iceberg Fallacy (Previously)

# 6. Sturgeon's Revelation

>"90% of everything is crud."

Yes, that includes your products.

# 7. The Peter Principle

>"In a hierarchy, every employee tends to rise to their level of incompetence. Thus, in time, every post tends to be occupied by an employee who is incompetent to carry out its duties."

Dunning and Kruger send their regards...

(Previously)

# 8. Eagleson's Law

>"Any code of your own that you haven't looked at for six or more months might as well have been written by someone else."

6 months is rather optimistic.

One caveat, though, is the "Yo Momma Corollary": only the author is allowed to criticize the code; any other negative feedback is dismissed.

# 9. Greenspun's 10th Rule of Programming
Adjusted for authentication:

Any custom developed authentication system contains an ad hoc, informally-specified, bug-ridden, slow implementation of half of Kerberos.

— Jan Schaumann (@jschauma) September 14, 2015
This can be generalized to the Universal NIH-Rule: "any custom developed system contains an ad hoc, informally-specified, bug-ridden, slow implementation of half of the industry standard you refused to adopt".

#  10. The Iceberg Fallacy

>"The cost of development of a new software product is the only ~25% of the total cost of ownership management sees and budgets for."

Ops Adage:

If software maintenance is 75% of the total cost of ownership, then operational support is the remaining 75%.

— Jan Schaumann (@jschauma) April 29, 2013
See also: Pareto's Fallacy.

# 11. The LGTM Dilemma

>"If you want to quickly ship a 10 line code change, hide it in a 1500 line pull request."

Also known as The Bikeshedders' Blind Spot.
