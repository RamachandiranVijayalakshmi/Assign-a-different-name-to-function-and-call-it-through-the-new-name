## Assign-a-different-name-to-function-and-call-it-through-the-new-name
## Sample code to check the details for the different name and functions
```sh
def displayStudent(name, age):
    print(name, age)

displayStudent("Emma", 26)

showStudent = displayStudent
showStudent("Emma", 26)
```
## Example Output
Emma 26
Emma 26
