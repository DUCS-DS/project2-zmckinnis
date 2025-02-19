# Sp25Proj2
Project 2 for Spring '25 Data Structures
Question 1: In project 1 i was running around 25-28 fps, after the changes in project 2 my frames sat around 54 fps. I saw a significant increase on frame rate, but this makes sense as the time complexioty went from O(N^2) to O(n log n).
Question 2 (Challenge): The time complexity has changed to O(n log n) because sorting is O(n log n) and the distance computation is O(n x k) but instead of O(n^2), we only check around k(20) nearby therefore making k constant so the complexity is O(N). O(n log n) + O(N) = O(n log n).