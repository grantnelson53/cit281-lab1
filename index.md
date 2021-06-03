## Lab 1

In this lab, we learned all about Node.js and used it to run our programs

### Source Code 

    function square(num) {
        return num * num;
    }

    console.log('Square operations: ')

    for (let i = 2; i <= 10; i+=2) {
        console.log(`Square of ${i} is ${square(i)}`);
    }
