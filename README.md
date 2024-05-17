#include <stdio.h> 
#include <stdlib.h> 
int main() 
{ 
 int etages = 25; 
 //Print tree 
 for (int i = 0; i < etages; i++) { 
 for (int j = 0; j < etages - i - 1; j++) { 
 printf(" "); 
 } 
 for (int j = 0; j < 2 * i + 1; j++) { 
 printf("*"); 
 } 
 printf("\n"); 
 } 
 // Print tree tunk 
 for (int i = 0; i < 2; i++) { 
 for (int j = 0; j < etages - 1; j++) { 
 printf(" "); 
 } 
 printf("###\n"); 
 } 
 return 0; 
}
