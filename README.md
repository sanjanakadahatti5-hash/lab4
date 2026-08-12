# lab4
/* 4. Write a NodeJs program to demonstrate custom module of student marks calculation

const marks=require("./marks.js")
let total=marks.calTotal(80,90,85)
let avg=marks.calAvg(total)
console.log(`Total marks of three subjects=${total}`)
console.log(`Percentage=${avg}`)
function calTotal(m1,m2,m3){
    return m1+m2+m3
}
function calAvg(total){
    return total/3
}
module.exports={calTotal,calAvg}