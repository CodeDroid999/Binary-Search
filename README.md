# Binary-Search
Implementation of binary search algorithm!!

# Implementation of binary search algorithm!!

# We will prove that binary search is faster than naive search!


# Essence of binary search:
# If you have a sorted list and you want to search this array for something,
# You could go through each item in the list and ask, is this equal to what we're looking for?
# But we can make this *faster* by leveraging the fact that our array is sorted!
# Binary search ~ O(log(n)), naive search ~ O(n)

# In these two examples, l is a list in ascending order, and target is something that we're looking for
# Return -1 if not found


# naive search: scan entire list and ask if its equal to the target
# if yes, return the index
# if no, then return -1
