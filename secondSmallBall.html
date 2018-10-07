<!DOCTYPE html>
<html>
<head lang="en">
    <meta charset="UTF-8">
    <title></title>
    <style>
        body{
            position:relative;
        }
    </style>
</head>
<body>
<canvas id="canvas1"></canvas>
<canvas id="canvas2"></canvas>
<canvas id="canvas3"></canvas>
<!--<script src="js/underscore-min.js"></script>-->
<script>
    /*var oCanvas=document.getElementById("canvas1");*/
    var oCan=document.getElementsByTagName("canvas");
    (function(i){
        for(;i<oCan.length;i++){
            with (oCan[i]){
                width=Math.floor(document.documentElement.clientWidth/3)-20;
                height=600;
            }
            with(oCan[i].style){
                background="purple";
                position="absolute";
                left=(Math.floor(document.documentElement.clientWidth/3)-20)*i+"px";
                border="1px solid black"
            }
        }
    })(0);

    var oCt1=oCan[0].getContext("2d");
    var oCt2=oCan[1].getContext("2d");
    var oCt3=oCan[2].getContext("2d");
    class Ball{
        constructor(x,y,r,color){
            this.x=x;
            this.y=y;
            this.color=color;
            this.r=r;
        }
        createBall(oCt){
            oCt.save();
            oCt.beginPath();
            oCt.arc(this.x,this.y,this.r,0,Math.PI*2);
            oCt.fillStyle=this.color;
            oCt.fill();
            oCt.restore();
        }
        ballAction(oCt,n1,n2,rChange){
            oCt.save();
            oCt.beginPath();
            oCt.arc(this.x,this.y,this.r,0,Math.PI*2);
            oCt.fillStyle=this.color;
            oCt.fill();
            oCt.restore();
            this.x+=Math.floor(Math.random()*n1-n2);
            this.y+=Math.floor(Math.random()*n1-n2);
            this.r+=rChange;
            if(this.r<0||this.r>100){
                this.r=0;
                rChange=0;
            }
        }
    }
    var arr=[];
    oCan[0].onmousemove=function(e){
        const ball1=new Ball(e.offsetX, e.offsetY,40,colorArr1[Math.floor(Math.random()*colorArr.length)]);
        arr.push(ball1);
        console.log(arr);
    }
    setInterval(function(){
        oCt1.clearRect(0,0,oCan[0].width,oCan[0].height);
        for(var i=0;i<arr.length;i++){
            arr[i]. ballAction(oCt1,0,0,-3);
        }
    },20)
    var arr1=[];
    oCan[1].onmousemove=function(e){
        const ball2=new Ball(e.offsetX, e.offsetY,80,colorArr[Math.floor(Math.random()*colorArr.length)]);
        arr1.push(ball2);
        console.log(arr1);
    }
    setInterval(function(){
        oCt2.clearRect(0,0,oCan[1].width,oCan[1].height);
        for(var i=0;i<arr1.length;i++){
            arr1[i]. ballAction(oCt2,80,40,-3);
        }
    },20)
    var arr2=[];
    var colorArr1=["white","black"];
    var colorArr=["red","green","blue","yellow","pink","cyan","purple","orange","white","black"];
    oCan[2].onmousemove=function(e){
        const ball3=new Ball(e.offsetX, e.offsetY,40,colorArr[Math.floor(Math.random()*colorArr.length)]);
        arr2.push(ball3);
        /*console.log();*/
    }
    setInterval(function(){
        oCt3.clearRect(0,0,oCan[2].width,oCan[2].height);
        for(var i=0;i<arr2.length;i++){
            arr2[i]. ballAction(oCt3,40,20,1);
        }
    },25)

</script>
</body>
</html>
