
#include <stdio.h>
#include <cs50.h>

int main (void)
{
    int Minutes;
    int cost = 6;
    //float volume = 0.5;
    float volume = get_float("enter the volume =");
    do Minutes = get_int("Enter time = ");
   while (minutes<=0||minutes>=100);
   printf ("You poured %.1f \n",Minutes*cost/volume);

}
