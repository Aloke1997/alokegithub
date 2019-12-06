# alokegithub
 this is my first repository 
#include <stdio.h> 

// Function Prototype 
void swapx(int, int); 

// Main function 
int main() 
{ 
	int a = 10, b = 20; 

	// Pass reference 
	swapx(&a, &b); 

	printf("a=%d b=%d\n", a, b); 
return 0; 
} 
