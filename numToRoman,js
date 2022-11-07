function convertToRoman(num){ 
    let romanNum ={
        M:1000, 
        CM:900,
        DCCC:800,
        DCC: 700,
        DC:600,
        D:500,
        CD:400,
        C:100,
        XC:90,
        L:50,
        XL:40,
        X:10,
        IX:9,
        V:5,
        IV:4,
        I:1
    };
let roman = " ";
 
for (let i in romanNum){
    console.log(i);
    while( num >= romanNum[i]){
        roman += i;
        num -= romanNum[i];
        console.log("Num is decreased:", num)
    }
}
return roman;
}
console.log(convertToRoman(798)); // returns DCCXCVIII
console.log(convertToRoman(649));// returns DCXLIX
console.log(convertToRoman(12)); // returns xII
console.log(convertToRoman(3));// returns III
