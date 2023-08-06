### closure-in.js


parent function r value ,child function jokhn e call kora hy tokhn e pbe ei value ta reference akare alwayes child r kase thake ...

closure obosshoi function  r vtr function thkte hbe , jdi return o  kore trpr o parents funtion value change mone rakhe atai..


        function outer() {
        let a = 10;


          return {
            increment: function () {
              a++;
              console.log(a)
            },
            decrement: function () {
              a--;
              console.log(a)
            },
          };
        }

        let value  = outer()

        value.decrement()
        value.increment()
        value.increment()

