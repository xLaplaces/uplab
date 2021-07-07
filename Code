//https://www.codewars.com/kata/52fba66badcd10859f00097e

function disemvowel(str) {
  return (str || "").replace(/[aeiou]/gi, "");
}



//https://www.codewars.com/kata/59bd84b8a0640e7c49002398

function tArea(tStr) {
  return (tStr.split`\n`.length - 3) ** 2 / 2
}



//https://www.codewars.com/kata/6089c7992df556001253ba7d

class Song {
  constructor(title,date){
    this.title =title;
    this.artist=date;
    this.baze=[]
  };
  howMany(arr)
  {
    let count=0
    for(let i of arr){
      if(!this.baze.includes(i.toLowerCase())){
        this.baze.push(i.toLowerCase())
        count++
        }
      }
    return count
    }
  }




//https://www.codewars.com/kata/5d95b7644a336600271f52ba

function crusoe(n, d, ang, distmult, angmult) {
  var x =0.0, y=0.0, a= ang*Math.PI/180;
  for (let i=1;i<=n;i++){
    x+=d*Math.cos(a);
    y+=d*Math.sin(a);
    d*=distmult;
    a*=angmult;
  }
  return [x,y];
}



//https://www.codewars.com/kata/5526fc09a1bbd946250002dc

function findOutlier(int){
  var even = int.filter(a => a % 2 === 0);
  var odd = int.filter(a  => a % 2 !== 0);
  return even.length === 1 ? even[0] : odd[0];
}





https://www.codewars.com/kata/526571aae218b8ee490006f4

var countBits = function(n) {
  var result = n.toString(2).match(/1/g) != null ? n.toString(2).match(/1/g).length : 0;
  return result;
};




https://www.codewars.com/kata/5552101f47fc5178b1000050

function digPow(n, p){
var sum = 0;
var myArray = [];
var holder = n;

for (var i = n.toString().length-1; i >= 0; i--) {
  myArray[i] = holder % 10;
  
  holder = Math.trunc(holder/10);  
  myArray[i] = Math.pow(myArray[i],p+i);
  sum += myArray[i];  
}

  if(sum % n == 0) {
    return sum/n;
  } else {
    return -1;
  }
}


//https://www.codewars.com/kata/552c028c030765286c00007d

function iqTest(numbers){
  var nums = numbers.split(" ").map(x => x % 2);  
  var sum = nums.reduce((a,b) => a + b);  
  var target = sum > 1 ? 0 : 1;

  return nums.indexOf(target) + 1;
}




//https://www.codewars.com/kata/56f1c6034d0c330e4a001059

var generateColor = function() {
var letters = '0123456789ABCDEF';
  var color = '#';
  for (var i = 0; i < 6; i++) {
    color += letters[Math.floor(Math.random() * 16)];
  }
  return color;
};




//https://www.codewars.com/kata/585d7d5adb20cf33cb000235

function findUniq(array){ 

 
      for(var i = 1; i<array.length; i++)
      {
        
        if(array[i]==array[i-1] && array[i]!=array[i+1])
            return array[i+1];
            
        else if(array[i]!=array[i-1] && array[i]==array[i+1])
            return array[i-1];
            
        else if(array[i]!=array[i-1] && array[i]!=array[i+1])
            return array[i];
    }
      
      return true;
}




//https://www.codewars.com/kata/541c8630095125aba6000c00

function digital_root(n) {
  if (n < 10) return n;
  return digital_root(
    n.toString().split('').reduce((acc, d) => {
      return acc + +d;
    },0));
}


//https://www.codewars.com/kata/54b42f9314d9229fd6000d9c

function duplicateEncode(str){
var word = str.toLowerCase();
var unique = '';
  for (var i = 0; i < word.length; i++) {
    if (word.lastIndexOf(word[i]) === word.indexOf(word[i])) {
      unique += '(';
    } else
    unique += ')';
  }
  return unique;
}
