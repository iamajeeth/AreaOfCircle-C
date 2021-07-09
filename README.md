# Area of Circle
**Finding area of circle with radius using C Programming.**

***To download code and object file look into branches.***

	#include<stdio.h>

	int main() {

	float radius, result;
	
	printf("Enter your Radius:\n");
	scanf("%f", &radius);
	
	result = (22.0/7) * radius * radius;
	
	printf("\nArea of circle with Radius = %f is %f", radius, result);
	
	return 0;
	
	}
