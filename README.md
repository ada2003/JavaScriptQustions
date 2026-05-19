// Reverse an array without using .reverse()

// let arr = [2,4,6,7,8,10]
// let newarr = []
// function reverseArr (arr) {

//     for(let i = arr.length-1 ; i >= 0 ; i--){
//         console.log(arr[i])
//         newarr.push(arr[i])
//     }
// return newarr
// }

// let fullnewarr = reverseArr(arr)
// console.log(fullnewarr)

// ----------------------------------------------------------------------------------------------------------------------------------

// Check if a string is a palindrome
// function ispalindrome(str){
//     let clean = str.replace(/[^A-Za-z0-9]/g, "").toLowerCase()
//     let left = 0 
//     let  right = str.length - 1;

//     while (left < right){
//         if(clean[left] != clean[right]){
//            return false;
//          }
         
//          left++;
//          right -- ;
//     }
//     return true

// }
// console.log(ispalindrome("madaM")) //true 


// ----------------------------------------------------------------------------------

// Remove duplicate values from an array
// using set 

// let numbers =  [1,2,2,3,3,4,4,9]

// let unqinumbers = [... new Set(numbers)]

// console.log(unqinumbers)


// using filter 

// let numbers  = [1,2,2,3,3,4,4,9]

// let newFilterdNums =  numbers.filter((item,index)=>numbers.indexOf(item) === index)

// console.log(newFilterdNums)
