from sklearn.metrics import accuracy_score

actual = [1, 1, 0, 0, 1]
predicted = [1, 1, 0, 1, 1]

accuracy = accuracy_score(actual, predicted)

print("Accuracy:", accuracy)

Confusion Matrix
from sklearn.metrics import confusion_matrix

actual = [1, 1, 0, 0, 1]
predicted = [1, 1, 0, 1, 1]

matrix = confusion_matrix(actual, predicted)

print(matrix)
