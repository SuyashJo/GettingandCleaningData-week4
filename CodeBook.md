#
# Tidy data set description

**The variables in the tidy data**

Tidy data contains 180 rows and 68 columns. Each row has averaged variables for each subject and each activity.

**Only all the variables estimated from mean and standard deviation in the tidy set were kept.**

- mean(): Mean value
- std(): Standard deviation

**The data were averaged based on subject and activity group.**

Subject column is numbered sequentially from 1 to 30. Activity column has 6 types as listed below.

1. WALKING
2. WALKING\_UPSTAIRS
3. WALKING\_DOWNSTAIRS
4. SITTING
5. STANDING
6. LAYING

**The tidy data contains 6 rows (averaged based on activity) and 68 columns (66 variables and activity labels).**

1. &quot;activitylabel&quot;
2. &quot;subject&quot;
3. &quot;tBodyAcc-mean()-X&quot;
4. &quot;tBodyAcc-mean()-Y&quot;
5. &quot;tBodyAcc-mean()-Z&quot;
6. &quot;tBodyAcc-std()-X&quot;
7. &quot;tBodyAcc-std()-Y&quot;
8. &quot;tBodyAcc-std()-Z&quot;
9. &quot;tGravityAcc-mean()-X&quot;
10. &quot;tGravityAcc-mean()-Y&quot;
11. &quot;tGravityAcc-mean()-Z&quot;
12. &quot;tGravityAcc-std()-X&quot;
13. &quot;tGravityAcc-std()-Y&quot;
14. &quot;tGravityAcc-std()-Z&quot;
15. &quot;tBodyAccJerk-mean()-X&quot;
16. &quot;tBodyAccJerk-mean()-Y&quot;
17. &quot;tBodyAccJerk-mean()-Z&quot;
18. &quot;tBodyAccJerk-std()-X&quot;
19. &quot;tBodyAccJerk-std()-Y&quot;
20. &quot;tBodyAccJerk-std()-Z&quot;
21. &quot;tBodyGyro-mean()-X&quot;
22. &quot;tBodyGyro-mean()-Y&quot;
23. &quot;tBodyGyro-mean()-Z&quot;
24. &quot;tBodyGyro-std()-X&quot;
25. &quot;tBodyGyro-std()-Y&quot;
26. &quot;tBodyGyro-std()-Z&quot;
27. &quot;tBodyGyroJerk-mean()-X&quot;
28. &quot;tBodyGyroJerk-mean()-Y&quot;
29. &quot;tBodyGyroJerk-mean()-Z&quot;
30. &quot;tBodyGyroJerk-std()-X&quot;
31. &quot;tBodyGyroJerk-std()-Y&quot;
32. &quot;tBodyGyroJerk-std()-Z&quot;
33. &quot;tBodyAccMag-mean()&quot;
34. &quot;tBodyAccMag-std()&quot;
35. &quot;tGravityAccMag-mean()&quot;
36. &quot;tGravityAccMag-std()&quot;
37. &quot;tBodyAccJerkMag-mean()&quot;
38. &quot;tBodyAccJerkMag-std()&quot;
39. &quot;tBodyGyroMag-mean()&quot;
40. &quot;tBodyGyroMag-std()&quot;
41. &quot;tBodyGyroJerkMag-mean()&quot;
42. &quot;tBodyGyroJerkMag-std()&quot;
43. &quot;fBodyAcc-mean()-X&quot;
44. &quot;fBodyAcc-mean()-Y&quot;
45. &quot;fBodyAcc-mean()-Z&quot;
46. &quot;fBodyAcc-std()-X&quot;
47. &quot;fBodyAcc-std()-Y&quot;
48. &quot;fBodyAcc-std()-Z&quot;
49. &quot;fBodyAccJerk-mean()-X&quot;
50. &quot;fBodyAccJerk-mean()-Y&quot;
51. &quot;fBodyAccJerk-mean()-Z&quot;
52. &quot;fBodyAccJerk-std()-X&quot;
53. &quot;fBodyAccJerk-std()-Y&quot;
54. &quot;fBodyAccJerk-std()-Z&quot;
55. &quot;fBodyGyro-mean()-X&quot;
56. &quot;fBodyGyro-mean()-Y&quot;
57. &quot;fBodyGyro-mean()-Z&quot;
58. &quot;fBodyGyro-std()-X&quot;
59. &quot;fBodyGyro-std()-Y&quot;
60. &quot;fBodyGyro-std()-Z&quot;
61. &quot;fBodyAccMag-mean()&quot;
62. &quot;fBodyAccMag-std()&quot;
63. &quot;fBodyBodyAccJerkMag-mean()&quot;
64. &quot;fBodyBodyAccJerkMag-std()&quot;
65. &quot;fBodyBodyGyroMag-mean()&quot;
66. &quot;fBodyBodyGyroMag-std()&quot;
67. &quot;fBodyBodyGyroJerkMag-mean()&quot;
68. &quot;fBodyBodyGyroJerkMag-std()&quot;

**variable units**

Activity variable is factor type. Subject variable is integer type. All the other variables are numeric type.