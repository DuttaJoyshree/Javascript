# Javascript

>Basics Of JS
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Document</title>
</head>
<body>
    <script>
        //for displaying
        document.write("Hello"+"<br>");
        //for arithmatic operation
        var a=10;
        var b=20;
        var c =10;
        var temp=2;
        document.write(a+b+"<br>");
        document.write(a>b);
        //if condition
        if(a>b){
            document.write("<br>"+"Inside if!");
        }
        else if(a==c){
            document.write("<br>"+"Inside else if!");
        }
        else{
            document.write("<br>"+"Inside else !");
        }
        //switch case
        switch(temp){
            case 1:
                document.write("<br>"+"Case 1");
                break;
            case 2:
                document.write("<br>"+"Case 2");
                break;
            default:
                document.write("<br>"+"inside default!");
        }
        //while loop
        while(a<b){
            document.write("<br>"+a);
            a++;
        }
        //do while
        document.write("<br>"+"-----------------------------");
            
        do{
            document.write("<br>"+a);
            a++;
        }
        while(a<25);
        //for loop
        document.write("<br>"+"-----------------------------");
        for(var i=0;i<10;i++){
            document.write("<br>Hello");  
        }
    </script>
</body>
</html>


```
