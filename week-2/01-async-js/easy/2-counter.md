## Counter without setInterval

Without using setInterval, try to code a counter in Javascript. There is a hint at the bottom of the file if you get stuck.
(Hint: setTimeout)


 function Counter(){
        const limit=10;
        if(count<=limit){
        console.log(count++);
        }
      console.log(count++);
      setTimeout(Counter(),1000);
    }
 let count=0;
 Counter(count);
