# logisticRegression_on_student_finalResult

The target attribute G3 has a strong correlation with attributes G2 and G1. This occurs because G3 is the final year grade (issued at the 3rd period), while G1 and G2 correspond to the 1st and 2nd period grades. It is more difficult to predict G3 without G2 and G1, but such prediction is much more useful.

This is a regression problem that you already solved in the previous module. To model this as the classification problem we somehow need to convert the numeric values to categories. One way to do so is by predicting if student passes or fails i.e binary classification, rather than predicting the score itself.

In the dataset G3 is the final grade score. We can define a passing criteria such that, if the G3 Score is less than 10, the student fails, and if the G3 score is greater than or equal to 10, the student pass.
