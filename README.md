# Coursera "Introduction to Computer Programming" - Robot Sketch Exercise - Using JavaScript P5 Library to Draw Bender From Futurama
Source code from the drawing exercise.

Changes made from this:
![alt text](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/P_Wp3BzqEemfcQ7nxKHo5g_646e9128141d0e9b816cca2a985a38d2_Screenshot-from-2019-01-20-19-33-15.png?expiry=1548288000000&hmac=blE8ujCigXk6qjEVcjNNBuctjjEkkUaMmWuV0Ft2ZfI)

to this:
![alt text](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/Y6mxLx38EemndBJIl2_15A_89c1d641447cda803bb6c588f49160f5_2019-01-22-02_15_21-Window.png?expiry=1548288000000&hmac=3zILh764mEYEUn5vyzPPzOSGB3hXuNWnm8KfY_Dai-E
)
```
function setup()
{
    //create a canvas for the robot
    createCanvas(500, 500);
}

function draw()
{
    strokeWeight(6);

    //head
    fill(200);
    //    x, y, width, Height, roundness  
    rect(100, 130, 200, 350, 150);
    
    //Antena
    fill(200);
    //triangle(width left side, height left side, top side width,angle top side,)
    triangle(180, 130, 200, 20, 230, 130);
    //antena base
    rect(170, 110, 70, 30, 100);
    ellipse(200, 20, 30, 30);
    
    //eye area begin
    fill(200);
    rect(130, 200, 220, 100, 150);
    
    //eye area end
    fill(0);
    rect(170, 210, 170, 80, 150);
    
    //eyes
    fill(900);
    ellipse(290, 250, 100, 80); //left
    ellipse(220, 250, 100, 80); //right
    
    // eyes dots
    fill(0);
    rect(190, 250, 5, 5, 0);  //left
    rect(280, 250, 5, 5, 0);  //right
    
    //mouth
    fill(900);
    rect(130,330,200,80,150);

    //columns teeth
    noFill();
    beginShape();
    vertex(160, 333);
    vertex(160, 407);
    endShape();

    noFill();
    beginShape();
    vertex(220, 330);
    vertex(220, 410);
    endShape();
    
    noFill();
    beginShape();
    vertex(280, 330);
    vertex(280, 410);
    endShape();

    //rows teeth
    noFill();
    beginShape();
    vertex(133, 360);
    vertex(280, 360);
    endShape();

    noFill();
    beginShape();
    vertex(136, 390);
    vertex(280, 390);
    endShape();
    
    //workaround
    strokeWeight(0);
    fill(900)
    rect(303, 320, 100, 100, 0);  //white block
    
    strokeWeight(0);
    rect(297, 333, 100, 90, 0);  //white block
    
    // ### ORIGINAL #### 
    //robots head
    //fill(200);
    //rect(100, 100, 300, 300, 20);


    ////robots antenna
    //fill(250, 250, 0);
    //ellipse(250, 70, 60, 60);

    //fill(200, 0, 200);
    //rect(210, 80, 80, 30);

    ////robots eyes
    //fill(255);
    //ellipse(175, 200, 80, 80);
    //point(175, 200);
    //ellipse(325, 200, 80, 80);
    //point(325, 200);


    ////robots nose
    //fill(255, 0, 0);
    //triangle(250, 220, 200, 300, 300, 300);

    ////robots ears
    //rect(80, 180, 30, 100);
    //rect(390, 180, 30, 100);

    ////robots mouth
    //noFill();
    //beginShape();
    //vertex(175, 340);
    //vertex(200, 370);
    //vertex(225, 340);
    //vertex(250, 370);
    //vertex(275, 340);
    //vertex(300, 370);
    //vertex(325, 340);
    //endShape();
}
```
