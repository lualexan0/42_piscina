🔨 ft_putchar.c - Explanation
Print a Character

You are creating a function to write a character when called upon in the main using - ft_putchar(' ');
any character in the ' ' will be written when the main runs.

#include <unistd.h> // allows the write funciton from the C library 

void	ft_putchar(char c) // creating a function to output characters
{ // This is the start of the function
  	write(1, &c, 1); // this allows for a character to be written with &c
} // This is the end of the function
/* Must comment the main, unless compiling
int main(void)  // starts the main
{ 
	ft_putchar('a'); // This writes the character 'a'
} 
*/ // Must add a comment at the end to close it