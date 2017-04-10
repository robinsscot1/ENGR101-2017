#include <stdio.h>
#include <time.h>
#include "E101.h"

int main(){
	//This sets up the Rpi hardware and esures everything is working properly
	init();


	int adc_reading;
	int x;
	x = 20;
	
	while (x>0){
		adc_reading = read_analog(0);
		printf("%d\n", adc_reading);
		sleep1(1,0);
		x = x -1;
	}

	
	return 0;
	
}
