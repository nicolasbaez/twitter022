# twitter022
#つぶやきProcessing void setup(){size(500,500,P3D);}float i,k,h=250;void draw(){clear();directionalLight(h,h/2,h,1,1,0);translate(h,h,-999);rotateX(1.3);noStroke();sphere(h);for(i=0;i&lt;7;i+=.02){push();translate(h*2*cos(i+k),h*2*sin(i+k),noise(i*99)*h/2);sphere(8);pop();}k+=.001;}
