# dadochallenge
int cara;
void setup() {
	size(500,500);
	cara=int(random(1,7));
	
	
}

void draw(){
	background(255);
	if(mousePressed){
cara=int(random(1,7));}
	if(cara == 1){uno();}
	if(cara == 2){dos();}
		if(cara == 3){tres();}
		if(cara == 4){cuatro();}
		if(cara == 5){cinco();}
	if(cara == 6){seis();}

}
void uno (){
	fill(255);
	rect(0,0,499,499)
	fill(0)
	ellipse(250,250,50,50)
}
	void dos (){
	fill(255);
	rect(0,0,499,499)
	fill(0)
	ellipse(350,350,50,50)
	ellipse(150,150,50,50)
}
void tres (){
	fill(255);
	rect(0,0,499,499)
	fill(0)
	ellipse(400,400,50,50)
	ellipse(100,100,50,50)
	ellipse(250,250,50,50)
}

void cuatro (){
	fill(255);
	rect(0,0,499,499)
	fill(0)
	ellipse(150,150,50,50)
	ellipse(350,150,50,50)
	ellipse(150,350,50,50)
	ellipse(350,350,50,50)
}
void cinco(){
	fill(255);
	rect(0,0,499,499)
	fill(0)
	ellipse(150,150,50,50)
	ellipse(350,150,50,50)
	ellipse(150,350,50,50)
	ellipse(250,250,50,50)
	ellipse(350,350,50,50)
}
void seis() {
	fill(255);
	rect(0,0,499,499)
	fill(0)
	ellipse(150,150,50,50)
	ellipse(350,150,50,50)
	ellipse(150,350,50,50)
	ellipse(150,250,50,50)
	ellipse(350,350,50,50)
	ellipse(350,250,50,50)
}
	
