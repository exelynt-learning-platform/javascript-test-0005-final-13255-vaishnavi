# javascript-test-0005-final-13255-vaishnavi
Final Project Assignment - This repository contains the complete final project code and documentation.
let num = 1;

for (let i = 1; i <= 5; i++) {
    let row = "";

    for (let j = 1; j <= i; j++) {
        row += num + " ";
        num++;
    }

    console.log(row);
}
