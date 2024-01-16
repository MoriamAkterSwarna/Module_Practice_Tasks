### Task-1 (Module 20-7)

Define a function that squares each element of an array using a loop

**Output:**

<br>

    Original Array: [ 1, 2, 3, 4, 5 ]
    Squared Array: [ 1, 4, 9, 16, 25 ]

**Solution**
<br>

        function squareArrayElements(arr) {
        var squaredArray = [];

        for (var i = 0; i < arr.length; i++) {
            squaredArray.push(arr[i] * arr[i]);
        }

        return squaredArray;
        }

        var numbers = [1, 2, 3, 4, 5];
        var squaredNumbers = squareArrayElements(numbers);
        console.log("Original Array:", numbers);
        console.log("Squared Array:", squaredNumbers);

---
