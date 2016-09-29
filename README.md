# Promune-codes

void hard_fly(); //define motors forward at full speed
void turn_right(); //define turns left continuous 
int main()
{
	hard_fly(); //execute hard fly function
	turn_right(); //execute turn right
	hard_fly(); //execute hard fly

return 0; //returns integer 0
} //end main funtion

void hard_fly() //define hard fly
{
	
	motor(1,100);
	motor(2,100);
	msleep(5000); 
}

void turn_right()
{
	motor(1,70);
	msleep(4000);
}
