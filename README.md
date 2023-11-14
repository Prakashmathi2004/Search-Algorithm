## AIM
Create a C program to generate the journey ticket by using 
nested structure.
struct ticket_booking
{
 int dd,mm,yyyy;
 int hr,min;
 float fare;
 float total_fare;
};
struct person
{
 char name[100];
 int no_of_persons;
 struct ticket_booking t;
}p;
AIM: 
Create a C program to generate the journey ticket by 
using nested structure.
PROGRAM:
#include<stdio.h>
struct ticket_bookin
