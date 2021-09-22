# Let-us-c-3
Q(c) If the marks obtained by a student in five different subjects are input through the keyboard, write a program to find out the aggregate marks and percentage marks obtained by the student. Assume that the maximum marks that can be obtained by a student in each subject is 100.
       
         
 
    #include<stdio.h>
    int main()
    {
 	     int a,b,c,d,e;
	
        printf("enter the marks of each subject\n",a,b,c,d,e);
	
	     scanf("%d\n %d\n %d\n %d\n %d",&a,&b,&c,&d,&e);
	
	     printf("total marks= %d\n", a+b+c+d+e);
	 
	     printf("percentage = %d",(a+b+c+d+e)/5);
	
	  return 0;
	
   }
