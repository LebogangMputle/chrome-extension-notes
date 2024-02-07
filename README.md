# chrome-extension-notes
//using LET and Const variables
Let- will change later on in the code.
Const- will never change, It indicates a constant throughout the code.

#
let myCourses = ["Learn CSS Animations", "UI Design Fundamentals", "Intro to Clean Code"]

// Create a function that takes a single parameter, an array,
// and logs all the items of the array to the console.
// Call the function while passing in myCourses as an argument

function logItems (arr){
    for (let i = 0; i < arr.length; i++){
        console.log(arr[i])
    }
}

logItems(myCourses)
