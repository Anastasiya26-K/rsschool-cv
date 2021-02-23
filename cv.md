# Anastasiya Karotkaya
***
### Contacts for communication:
Phone Number: +375447217862    
Email: anastasiya26korotkaya@gmail.com    
***
### Summary
My main goal is to develop my mind and will get an interesting and well-paid job while get the necessary programming skills. I have no experience in programming, but I want to get it on this course. I became interested in programming while listening to my friends’ stories about their works. This struck me as interesting and worth attention. I chose the most interesting language for myself - Javascrip. I want to do my best to learn how to work on it.
***
### Skills
 - HTML5
 - CSS3
 - JavaScript 
 - Visual Studio Code
 - p.s. I studied books written by authors Robson E., Freeman E.: Head First HTML, XHTML and CSS; Head First JavaScript programming: A Brain-Friendly Guide.
***
### Code examples
 ```
 exports.min = function min (array) {
  if (array!=undefined&&array.length!=0) return Math.min(...array);
  return 0;
}

exports.max = function max (array) {
  if (array!=undefined&&array.length!=0) return Math.max(...array);
  return 0;
}

exports.avg = function avg (array) {
  if (array!=undefined&&array.length!=0) return array.reduce((item,sum)=>sum+item,0)/array.length;
  return 0;
}

```
```

module.exports = function countCats(matrix) {
  let catArr = matrix.flat().filter(cat => cat === '^^');
  return catArr.length
};

```
```

module.exports = function toReadable (number) {
    let mus1=["zero","one","two","three", "four", "five", "six", "seven","eight","nine"];
    let mus2=["ten","eleven","twelve", 'thirteen','fourteen','fifteen','sixteen','seventeen','eighteen','nineteen'];
    let mus3=["twenty","thirty", 'forty','fifty','sixty','seventy','eighty','ninety'];
    let num=""+number;
    let str="";
    if (num.length==1){
      str+=mus1[number];
    } else if (num.length==2){
        if (num[0]=="1"){
            str=mus2[+num[1]];
        }else{
            str=mus3[num[0]-2];
            if (num[1]!=0) str+=" "+mus1[num[1]];
        }
    }else if (num.length==3){
        str=mus1[num[0]]+" hundred";
      if (num[1]=="1"){
          str+=" "+mus2[+num[2]];
      }else if (num[1]=="0"&&num[2]!=0){
          str+=" "+mus1[num[2]];
      }else if(num[1]!="0"){
          str+=" "+mus3[num[1]-2];
          if (num[2]!=0) str+=" "+mus1[num[2]];
      }
    }
    return str;
}

```
***
### Education
I received a master’s degree in geoecology and at this moment I work in my specialty.
***
### English level
I intensively studied English on individual training up to B1 / B2 level, during which I was invited to participate in youth projects organized by ERASMUS +, where I gained experience in speaking.
