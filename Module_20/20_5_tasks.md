### Task-1 (Module 20-5)

write a function that will take a number as parameter and start a count down when it will reach 1 it will show a message

**Output:**

<br>

    10
    9
    8
    7
    6
    5
    4
    3
    2
    1
    Happy New Year!

**Solution**
<br>

        function countdown(number) {

        for (var i = number; i >= 1; i--) {
        console.log(i);

        }
        console.log("Happy New Year!");
        }


        countdown(10);

---

### Task-2 (Module 20-5)

write a function to check if a number is prime or not.

**Output:**

<br>

    false

**Solution**
<br>

        function isPrime(n) {
        if (n <= 1) {
            return false;
        }

        for (var i = 2; i < n; i++) {
            if (n % i === 0) {
                return false;
            }
        }

        return true;
        }
        var checkNumber = isPrime(9)
        console.log(checkNumber)

---
