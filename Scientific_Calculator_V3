#include <stdio.h>
#include <math.h>

char cc, dd, aa, op, xx, mm, var1, var2, m, mem, ch;
int num1, num2, res, rr, a=0, b=0, c=0, d=0, e=0, cont=0, i=0, k, s, ll=1;
float arr[1000];

float bi(){


    
     while((getchar()) != '\n');
          printf("\nYou Have Selected: Binary\n");
          
                printf("\nChoose an Option: +) Addition, -) Subtration, /) Division , *) Multiplication, ^) Power, %) Modulus\n");
                scanf("%c", &op); //scans operation choosen by user
             
                 switch(op){
                     
                   case '+': {
                        printf("\nYou have Selected: Addition\n");
                        
                         printf("\nEnter first number\n");
                            if (scanf("%d", &num1) !=1)
                            {
                                printf("\nERROR: INPUT MUST BE A NUMBER\n"); //Error code is given if user enters anything other then a number
                                break;
                             }
                             
                        printf("\nEnter Second number\n");
                             if (scanf("%d", &num2) !=1)
                                 {
                                printf("\nERROR: INPUT MUST BE A NUMBER\n");
                                break;
                                }
                                
                  res = num1 + num2;
       
                printf ("\nResult: %d %c %d = %d\n", num1, op, num2, res); //shows result
                arr[i] = res;
                i++;
                
                
                 break; // after case is completed program loops
                }
             
             
                  case '-':{
                     
                 printf("\nYou have Selected: Subtraction\n");
                 
                    printf("\nEnter first number\n");
                        if (scanf("%d", &num1) !=1)
                            {
                                printf("\nERROR: INPUT MUST BE A NUMBER\n");
                                break;
                            } 
                            
                    printf("\nEnter Second number\n");
                        if (scanf("%d", &num2) !=1)
                             {
                            printf("\nERROR: INPUT MUST BE A NUMBER\n");
                            break;
                        }
                        
                res = num1 - num2;
                
                printf ("Result: %d %c %d = %d\n", num1, op, num2, res);
                arr[i] = res;
                i++;
                break;
                 }
                 
             
                case '/':{
                    
                 printf("\nYou have Selected: Division \n");
                 
                    printf("\nEnter first number\n");
                         if (scanf("%d", &num1) !=1)
                             {
                               printf("\nERROR: INPUT MUST BE A NUMBER\n");
                               break;
                             }
                             
                     printf("\nEnter Second number\n");
                        if (scanf("%d", &num2) !=1)
                            {
                                printf("\nERROR: INPUT MUST BE A NUMBER\n");
                                 break;
                             }
             
                if(num2 == 0)
                {
                    printf("\n Result: %d %c %d = undefined\n", num1, op, num2);
                    break;
                }
                
                else{
                    res = num1/num2;
                    
                    printf ("\nResult: %d %c %d = %d\n", num1, op, num2, res);
                    arr[i] = res;
                i++;
                    break;
                }
                }
                
             
                case'*':{
                 printf("\nYou have Selected: Multiplication\n");
                 
                 printf("\nEnter first number\n");
                    if (scanf("%d", &num1) !=1)
                        {
                            printf("\nERROR: INPUT MUST BE A NUMBER\n");
                            break;
                        }
                        
                 printf("\nEnter Second number\n");
                    if (scanf("%d", &num2) !=1)
                        {
                            printf("\nERROR: INPUT MUST BE A NUMBER\n");
                             break;
                        }
                        
             res = num1 * num2;
             
            printf ("\nResult: %d %c %d = %d\n", num1, op, num2, res);
            arr[i] = res;
                i++;
            break;
        
             }
             
             
             case '^':{
                 
                 printf("\nYou have Selected: Power\n");
                 
                printf("\nEnter first number\n");
                    if (scanf("%d", &num1) !=1)
                        {
                            printf("\nERROR: INPUT MUST BE A NUMBER\n");
                             break;
                        } 
                        
                printf("\nEnter Second number\n");
                    if (scanf("%d", &num2) !=1)
                        {
                            printf("\nERROR: INPUT MUST BE A NUMBER\n");
                            break;
                        }
                        
         res =pow(num1, num2);
         
        printf ("\nResult: %d %c %d = %d\n", num1, op, num2, res);
        arr[i] = res;
                i++;
         break;
             }
             
             
             case '%':{
                 printf("\nYou have Selected: Modulus\n");
                 
                     printf("\nEnter first number\n");
                        if (scanf("%d", &num1) !=1)
                            {
                                printf("\nERROR: INPUT MUST BE A NUMBER\n");
                                break;
                           }
                           
                     printf("\nEnter Second number\n");
                        if (scanf("%d", &num2) !=1)
                            {
                                 printf("\nERROR: INPUT MUST BE A NUMBER\n");
                                break;
                                }
                                
                if(num2==0){
                    
                    printf("\nResult: The Modulus of %d and %d = Undefined\n", num1, num2);
                    break;
                    
                }
                
                else{
                    res = num1 % num2;
         
         printf ("\nResult: %d %c %d = %d\n", num1, op, num2, res);
         arr[i] = res;
                i++;
         break;
                }         
         
             }
             
             
             default:{
                 printf("\nERROR: INPUT MUST BE A VALID OPERATION\n");
                 break;
             }
    break;
}


}

float ur(){
while((getchar()) != '\n');

         
         printf("\nYou have Selected: Unary\n");
         
          printf("\nChoose an Option: S) Square root, L) logarithm, E) Exponential, c) ceil, f) floor\n");
               scanf("%c", &op);
        switch(op){       
               
              case 's':
              case 'S': {
                    
                        printf("\nYou Have selected: Square Root\n");
                    
                        printf("\nEnter a Number\n");
                            if(scanf("%d", &num1) !=1)
                                {
                                 printf("\nERROR: INPUT MUST BE A NUMBER\n");
                                 break;
                                }
                   
                        if( num1 > 0){
                            res = sqrt(num1);
                            printf("\nResult: Square Root of %d = %d\n", num1, res);
                            arr[i] = res;
                i++;
                             break;
                             }
                   
                        else{
                            printf("\nERROR: INPUT MUST BE A POSITVE VALUE\n");
                            break;
                            }
                }
    
    
                
              case 'l':
              case 'L':{
                  
                    printf("\nYou Have Selected logarithm\n");
                    
                     printf("\nEnter a Number\n");
                        if (scanf("%d", &num1) !=1)
                             {
                             printf("\nERROR: INPUT MUST BE A NUMBER\n");
                             break;
                            }
                            
                    printf("\nEnter a second Number\n");
                        if (scanf("%d", &num2) !=1)
                            {
                            printf("\nERROR: INPUT MUST BE A NUMBER\n");
                            break;
                             }
             
             
                    res = log(num1)/log(num2);
             
                     printf("\nResult: Log %d with the base of %d = %d\n", num1, num2, res);
                     arr[i] = res;
                i++;
                    break;
                }
                
                
               case 'c':
               case 'C':{
                   
                   printf("\nYou have Selected: ceil\n");
                    
                     float res;
                     float num1;
                    
                   printf("\nEnter a Number:\n");
                        if(scanf("%f",&num1) != 1){
                   
                            printf("\nERROR: INPUT MUST BE A NUMBER\n");
                             break;
                             }
 
                    res=ceil(num1);
  
                     printf("\nResult: Ceil value of %f = %f \n", num1, res);
                     arr[i] = res;
                i++;
                     break;
                    }
                
                
                case'f': 
                case'F': {
                    
                    printf("\nYou have Selected: Floor\n");
                    
                    float res;
                    float num1;
               
               
                    
                   printf("\nEnter a Number:\n");
                        if(scanf("%f",&num1) != 1){
                   
                       printf("\nERROR: INPUT MUST BE A NUMBER\n");
                       break;
                        }
 
                res=floor(num1);
  
                 printf("\nResult: Floor value of %f = %f\n", num1, res);
                 arr[i] = res;
                i++;
                 break;
                }
                
                
                case'e':
                case 'E':{
                    
                    printf("\nYou have Selected: Exponential\n");
                    
                    float res;
                   
                   printf("\nEnter a Number:\n");
                        if(scanf("%d",&num1) != 1){
                   
                            printf("\nERROR: INPUT MUST BE A NUMBER\n");
                            break;
                        }
 
                res=exp(num1);
  
                 printf("\nResult: Exponential value of %d = %f\n", num1, res);
                 arr[i] = res;
                i++;
                 break;
                        }
                        
                
                default:{
                    printf("\nERROR: INPUT MUST BE A VALID OPTION\n");
                    break;
                }


}
}

float add(){


         
         printf("\nYou Have Selected: Advanced\n");
         printf("-------------------------------------------\n");
         printf("B = Binary Mathematical Operations\n"); //Operations used within program
         printf("U = Unary Mathematical Operations\n");
         printf("X = Exit to Main Menu\n");
         printf("-------------------------------------------\n");
do{
    while((getchar()) != '\n');
printf("\nChoose an Option: B, U, X\n");
         scanf("%c", &aa);
         
if(aa=='x' | aa=='X'){
    printf("\nReturning to Main Menu\n");
    break;
    
}

switch(aa){
 while((getchar()) != '\n');
            
    case 'b':
    case 'B':{
        
        
        while((getchar()) != '\n');
    
   
        printf("\nChoose an Option: +) Addition, -) Subtration, /) Division , *) Multiplication, ^) Power, %) Modulus\n");
        scanf("%c", &op); //scans operation choosen by user
        
        
        
        if(op=='+'){
            
            while((getchar()) != '\n');
            
            printf("\nEnter First Variable\n");
            scanf("%c", &var1);
          
            
            if(var1=='a' | var1=='A'){
                
                var1 = a;
                
            }
            
            if(var1=='b' | var1=='B'){
                
                var1 = b;
                
            }
            
            if(var1=='c' | var1=='C'){
                
                var1 = c;
                
            }
            
            if(var1=='d' | var1=='D'){
                
                var1 = d;
                
            }
            
            if(var1=='e' | var1=='E'){
                
                var1 = e;
                
            }
              
              
              
            
            while((getchar()) != '\n');
            
            printf("\nEnter Second Variable\n");
            scanf("%c", &var2);
            
            
            
             if(var2=='a' | var2=='A'){
                
                var2 = a;
                
            }
            
            if(var2=='b' | var2=='B'){
                
                var2 = b;
                
            }
            
            if(var2=='c' | var2=='C'){
                
                var2 = c;
                
            }
            
            if(var2=='d' | var2=='D'){
                
                var2 = d;
                
            }
            
            if(var2=='e' | var2=='E'){
                
                var2 = e;
                
            }
            
           if(var1==a | var1==b| var1==c |var1==d |var1==e){
                
                 if(var2==a | var2==b| var2==c |var2==d |var2==e){
                
               res = var1+var2;
            
            printf("\nThe Result of %d + %d = %d\n", var1, var2, res);
            arr[i] = res;
                i++;
           
           break;
              
            }
            else{
                
                printf("\nERROR: INPUT MUST BE A VALID VARIABLE\n");
                break;
                
            }
           
            
            }
            else{
                
                printf("\nERROR: INPUT MUST BE A VALID VARIABLE\n");
                break;
                
            }
            
         
            
    
        }
        
        if(op=='-'){
            
               while((getchar()) != '\n');
            printf("\nYou Have Selected: Subtration\n");
            
            printf("\nEnter First Variable\n");
            scanf("%c", &var1);
            
            if(var1=='a' | var1=='A'){
                
                var1 = a;
                
            }
            
            if(var1=='b' | var1=='B'){
                
                var1 = b;
                
            }
            
            if(var1=='c' | var1=='C'){
                
                var1 = c;
                
            }
            
            if(var1=='d' | var1=='D'){
                
                var1 = d;
                
            }
            
            if(var1=='e' | var1=='E'){
                
                var1 = e;
                
            }
              
              
              
            
            while((getchar()) != '\n');
            
            printf("\nEnter Second Variable\n");
            scanf("%c", &var2);
            
            
            
             if(var2=='a' | var2=='A'){
                
                var2 = a;
                
            }
            
            if(var2=='b' | var2=='B'){
                
                var2 = b;
                
            }
            
            if(var2=='c' | var2=='C'){
                
                var2 = c;
                
            }
            
            if(var2=='d' | var2=='D'){
                
                var2 = d;
                
            }
            
            if(var2=='e' | var2=='E'){
                
                var2 = e;
                
            }
            
            
             if(var1==a | var1==b| var1==c |var1==d |var1==e){
                
                 if(var2==a | var2==b| var2==c |var2==d |var2==e){
                
                res = var1-var2;
            
            printf("\nResult: %d - %d = %d", var1, var2, res);
            arr[i] = res;
                i++;
              break;  
              
            }
            else{
                
                printf("\nERROR: INPUT MUST BE A VALID VARIABLE\n");
                break;
                
            }
           
            
            }
            else{
                
                printf("\nERROR: INPUT MUST BE A VALID VARIABLE\n");
                break;
                
            }
        }
         
        
        if(op=='/'){
            while((getchar()) != '\n');
            printf("\nYou Have Selected: Division\n");
            
            printf("\nEnter First Variable\n");
            scanf("%c", &var1);
            
               if(var1=='a' | var1=='A'){
                
                var1 = a;
                
            }
            
            if(var1=='b' | var1=='B'){
                
                var1 = b;
                
            }
            
            if(var1=='c' | var1=='C'){
                
                var1 = c;
                
            }
            
            if(var1=='d' | var1=='D'){
                
                var1 = d;
                
            }
            
            if(var1=='e' | var1=='E'){
                
                var1 = e;
                
            }
              
              
              
            
            while((getchar()) != '\n');
            
            printf("\nEnter Second Variable\n");
            scanf("%c", &var2);
            
            
            
             if(var2=='a' | var2=='A'){
                
                var2 = a;
                
            }
            
            if(var2=='b' | var2=='B'){
                
                var2 = b;
                
            }
            
            if(var2=='c' | var2=='C'){
                
                var2 = c;
                
            }
            
            if(var2=='d' | var2=='D'){
                
                var2 = d;
                
            }
            
            if(var2=='e' | var2=='E'){
                
                var2 = e;
                
            }
            
           if(var1==a | var1==b| var1==c |var1==d |var1==e){
                
                 if(var2==a | var2==b| var2==c |var2==d |var2==e){
                     
                     
                     if(var2==0){
                         
                         printf("\nResult: %d / %d = Undefined\n");
                         break;
                         
                     }
                     
                else{
                    
                    res = var1/var2;
            
            printf("\nResult: %d / %d = %d", var1, var2, res);
            arr[i] = res;
                i++;
              break;
              
                }
               
            }
            else{
                
                printf("\nERROR: INPUT MUST BE A VALID VARIABLE\n");
                break;
                
            }
           
            
            }
            else{
                
                printf("\nERROR: INPUT MUST BE A VALID VARIABLE\n");
                break;
                
            }
           
           
            
         
        }
        
        if(op=='*'){
            while((getchar()) != '\n');
            printf("\nYou Have Selected: Multiplication\n");
            
            printf("\nEnter First Variable\n");
            scanf("%c", &var1);
            
               if(var1=='a' | var1=='A'){
                
                var1 = a;
                
            }
            
            if(var1=='b' | var1=='B'){
                
                var1 = b;
                
            }
            
            if(var1=='c' | var1=='C'){
                
                var1 = c;
                
            }
            
            if(var1=='d' | var1=='D'){
                
                var1 = d;
                
            }
            
            if(var1=='e' | var1=='E'){
                
                var1 = e;
                
            }
              
              
              
            
            while((getchar()) != '\n');
            
            printf("\nEnter Second Variable\n");
            scanf("%c", &var2);
            
            
            
             if(var2=='a' | var2=='A'){
                
                var2 = a;
                
            }
            
            if(var2=='b' | var2=='B'){
                
                var2 = b;
                
            }
            
            if(var2=='c' | var2=='C'){
                
                var2 = c;
                
            }
            
            if(var2=='d' | var2=='D'){
                
                var2 = d;
                
            }
            
            if(var2=='e' | var2=='E'){
                
                var2 = e;
                
            }
            
           
            if(var1==a | var1==b| var1==c |var1==d |var1==e){
                
                 if(var2==a | var2==b| var2==c |var2==d |var2==e){
                
                res=var1*var2;
                
                printf("\nResult: %d * %d = %d\n");
                arr[i] = res;
                i++;
                break;
              
            }
            else{
                
                printf("\nERROR: INPUT MUST BE A VALID VARIABLE\n");
                break;
                
            }
           
            
            }
            else{
                
                printf("\nERROR: INPUT MUST BE A VALID VARIABLE\n");
                break;
                
            }
        
    
            
         
        }
        
        if(op=='^'){
            while((getchar()) != '\n');
            
            printf("\nYou Have Selected: Power\n");
            
            printf("\nEnter First Variable\n");
            scanf("%c", &var1);
            
               if(var1=='a' | var1=='A'){
                
                var1 = a;
                
            }
            
            if(var1=='b' | var1=='B'){
                
                var1 = b;
                
            }
            
            if(var1=='c' | var1=='C'){
                
                var1 = c;
                
            }
            
            if(var1=='d' | var1=='D'){
                
                var1 = d;
                
            }
            
            if(var1=='e' | var1=='E'){
                
                var1 = e;
                
            }
              
              
              
            
            while((getchar()) != '\n');
            
            printf("\nEnter Second Variable\n");
            scanf("%c", &var2);
            
            
            
             if(var2=='a' | var2=='A'){
                
                var2 = a;
                
            }
            
            if(var2=='b' | var2=='B'){
                
                var2 = b;
                
            }
            
            if(var2=='c' | var2=='C'){
                
                var2 = c;
                
            }
            
            if(var2=='d' | var2=='D'){
                
                var2 = d;
                
            }
            
            if(var2=='e' | var2=='E'){
                
                var2 = e;
                
            }
            
            if(var1==a | var1==b| var1==c |var1==d |var1==e){
                
                 if(var2==a | var2==b| var2==c |var2==d |var2==e){
                
                res = pow(var1, var2);
            
            printf("\nThe Result of %d ^ %d = %d", var1, var2, res);
            arr[i] = res;
                i++;
              break;
              
            }
            else{
                
                printf("\nERROR: BOTH INPUTS MUST BE A VALID VARIABLE\n");
                break;
                
            }
           
            
            }
            else{
                
                printf("\nERROR: INPUT MUST BE A VALID VARIABLE\n");
                break;
                
            }
        
    
            
         
            
        }
        
        if(op=='%'){
             while((getchar()) != '\n');
            
            printf("\nYou Have Selected: Modulus\n");
            
            printf("\nEnter First Variable\n");
           scanf("%c", &var1);
           
       
              if(var1=='a' | var1=='A'){
                
                var1 = a;
                
            }
            
            if(var1=='b' | var1=='B'){
                
                var1 = b;
                
            }
            
            if(var1=='c' | var1=='C'){
                
                var1 = c;
                
            }
            
            if(var1=='d' | var1=='D'){
                
                var1 = d;
                
            }
            
            if(var1=='e' | var1=='E'){
                
                var1 = e;
                
            }
              
              
              
            
            while((getchar()) != '\n');
            
            printf("\nEnter Second Variable\n");
            scanf("%c", &var2);
            
            
            
             if(var2=='a' | var2=='A'){
                
                var2 = a;
                
            }
            
            if(var2=='b' | var2=='B'){
                
                var2 = b;
                
            }
            
            if(var2=='c' | var2=='C'){
                
                var2 = c;
                
            }
            
            if(var2=='d' | var2=='D'){
                
                var2 = d;
                
            }
            
            if(var2=='e' | var2=='E'){
                
                var2 = e;
                
            }
            
            
            if(var1==a | var1==b| var1==c |var1==d |var1==e){
                
                 if(var2==a | var2==b| var2==c |var2==d |var2==e){
                     
                     if(var2==0){
                         
                         printf("\nResult: Modulus of %d and %d = Undefined\n", var1, var2);
                         break;
                         
                     }
                     else{
                         
                          res=var1%var2;
            
                        printf("\nResult: Modulus of %d and %d = %d", var1, var2, res);
                        arr[i] = res;
                i++;
                        break;
                     }
                
              
                
            }
            else{
                
                printf("\nERROR:INPUT MUST BE A VALID VARIABLE\n");
                break;
                
            }
           
            
            }
            else{
                
                printf("\nERROR: INPUT MUST BE A VALID VARIABLE\n");
                break;
                
            }
            
            
         
           
            
        
    }
    
}
printf("\nERROR: INPUT MUST BE A VALID OPTION\n");
break;

      case 'u':
      case 'U':{
         while((getchar()) != '\n');
         
         printf("\nYou have Selected: Unary\n");
         
          printf("\nChoose an Option: S) Square root, L) logarithm, E) Exponential, c) ceil, f) floor\n");
               scanf("%c", &op);
        
        
        if(op=='s' | op=='S'){
                   while((getchar()) != '\n');
            
             printf("\nYou Have Selected: Sqare root\n");
            
            printf("\nEnter a Variable\n");
            scanf("%c", &var1);
            
            if(var1=='a' | var1=='A'){
                
                var1 = a;
                
            }
            
            if(var1=='b' | var1=='B'){
                
                var1 = b;
                
            }
            
            if(var1=='c' | var1=='C'){
                
                var1 = c;
                
            }
            
            if(var1=='d' | var1=='D'){
                
                var1 = d;
                
            }
            
            if(var1=='e' | var1=='E'){
                
                var1 = e;
                
            }
              
            
            if(var1==a | var1==b | var1==c | var1==d | var1==e){
                
              if(var1>0){
                
                res=sqrt(var1);

                printf("\nThe Square root of %d = %d\n", var1, res);  
                arr[i] = res;
                i++;
                break;
            }
        
              else{
                  
                  printf("\nERROR: VARIABLE MUST HAVE A POSITVE VALUE\n");
                  break;
                  
              }  
                
            }
            
            else{
                
                printf("\nERROR: INPUT MUST BE A VALID VARIABLE\n");
                break;
            }
    
            
            
            
          
            
        }
        
        if(op=='l'| op=='L'){
                   while((getchar()) != '\n');
            printf("\nYou Have Selected: logarithm\n");
            
            printf("\nEnter First Variable\n");
           scanf("%c", &var1);
                
                
                
            
            
            if(var1=='a' | var1=='A'){
                
                var1 = a;
                
            }
            
            if(var1=='b' | var1=='B'){
                
                var1 = b;
                
            }
            
            if(var1=='c' | var1=='C'){
                
                var1 = c;
                
            }
            
            if(var1=='d' | var1=='D'){
                
                var1 = d;
                
            }
            
            if(var1=='e' | var1=='E'){
                
                var1 = e;
                
            }
              
              
              
            
            while((getchar()) != '\n');
            
            printf("\nEnter Second Variable\n");
            scanf("%c", &var2);
            
            
            
             if(var2=='a' | var2=='A'){
                
                var2 = a;
                
            }
            
            if(var2=='b' | var2=='B'){
                
                var2 = b;
                
            }
            
            if(var2=='c' | var2=='C'){
                
                var2 = c;
                
            }
            
            if(var2=='d' | var2=='D'){
                
                var2 = d;
                
            }
            
            if(var2=='e' | var2=='E'){
                
                var2 = e;
                
            }
            
            
            if(var1==a | var1==b| var1==c |var1==d |var1==e){
                
                 if(var2==a | var2==b| var2==c |var2==d |var2==e){
                
                res = log(var1)/log(var2);
            
            printf("\nResult: Log of %d with the base of %d = %d", var1, var2, res);
            arr[i] = res;
                i++;
              break;  
              
            }
            else{
                
                printf("\nERROR: INPUT MUST BE A VALID VARIABLE\n");
                break;
                
            }
           
            
            }
            else{
                
                printf("\nERROR: INPUT MUST BE A VALID VARIABLE\n");
                break;
                
            }
           
            
        
    
            
         
            
                
                
             
            
            
        
        
    
            
            
            
        
    }
        
         if(op=='c' | op=='C'){
            while((getchar()) != '\n');
            printf("\nYou Have Selected: Ceil\n");
            
            printf("\nEnter a Variable\n");
            scanf("%c", &var1);
            
           if(var1=='a' | var1=='A'){
                
                var1 = a;
                
            }
            
            if(var1=='b' | var1=='B'){
                
                var1 = b;
                
            }
            
            if(var1=='c' | var1=='C'){
                
                var1 = c;
                
            }
            
            if(var1=='d' | var1=='D'){
                
                var1 = d;
                
            }
            
            if(var1=='e' | var1=='E'){
                
                var1 = e;
                
            }
              
            
            if(var1==a | var1==b| var1==c |var1==d |var1==e){
                
                res = ceil(var1);
            
            printf("\nResult: The Ceil of %d = %d", var1, res);
            arr[i] = res;
                i++;
              break;
              
            }
            else{
                
                printf("\nERROR: INPUT MUST BE A VALID VARIABLE\n");
                break;
                
            }
        
    
            
         
        }
           
        if(op=='F' | op=='f'){
            
            while((getchar()) != '\n');
            
            printf("\nYou Have Selected: Floor\n");
            
            printf("\nEnter a Variable\n");
            scanf("%c", &var1);
            
            if(var1=='a' | var1=='A'){
                
                var1 = a;
                
            }
            
            if(var1=='b' | var1=='B'){
                
                var1 = b;
                
            }
            
            if(var1=='c' | var1=='C'){
                
                var1 = c;
                
            }
            
            if(var1=='d' | var1=='D'){
                
                var1 = d;
                
            }
            
            if(var1=='e' | var1=='E'){
                
                var1 = e;
                
            }
              
             if(var1==a | var1==b| var1==c |var1==d |var1==e){
                
               res = floor(var1);
            
            printf("\nResult: The Floor of %d = %d", var1, res);
            arr[i] = res;
                i++;
              break; 
              
            }
            else{
                
                printf("\nERROR: INPUT MUST BE A VALID VARIABLE\n");
                break;
                
            }
            
           
            
         
            
        }
        
        if(op=='e'| op=='E'){
            while((getchar()) != '\n');
            
            printf("\nYou Have Selected: Exponential\n");
            
            printf("\nEnter a Variable\n");
            scanf("%c", &var1);
            
           if(var1=='a' | var1=='A'){
                
                var1 = a;
                
            }
            
            if(var1=='b' | var1=='B'){
                
                var1 = b;
                
            }
            
            if(var1=='c' | var1=='C'){
                
                var1 = c;
                
            }
            
            if(var1=='d' | var1=='D'){
                
                var1 = d;
                
            }
            
            if(var1=='e' | var1=='E'){
                
                var1 = e;
                
            }
              
            
            if(var1==a | var1==b| var1==c |var1==d |var1==e){
                
                res = exp(var1);
            
            printf("\nResult: The Exponential of %d = %d", var1, res);
            arr[i] = res;
                i++;
              break; 
              
            }
            else{
                
                printf("\nERROR: INPUT MUST BE A VALID VARIABLE\n");
                break;
                
            }
        
        }
    
      }
      printf("\nERROR: INPUT MUST BE A VALID OPTION\n");
        break;
        

default:

printf("\nERROR: INPUT MUST BE A VALID OPTION\n");
break;
      
      
     
      

}
}while(aa!='x' | aa!='X');




}

float me(){

if (i == 0){
                printf("\nMemory is Empty\n");
                printf("\nReturning to Main Menu\n");      
               
            }
            else{
                
printf("\nItem Types:\n");
printf("\n0 = Show all items from Memory\n"); //Operations used within program
printf("1 to %d = Choose an Item within the Range from Memory\n", i);
printf("X = Return to Main Menu\n");
printf("-------------------------------------------\n");

printf("\n%d Items are stored in the Memory\n", i);
                do{
                    
                  printf("\nChoose an Option: 0, 1 to %d, X\n", i);
                   scanf("%s", &mem);
                   
                   

          if(mem=='x' | mem=='X'){
            printf("\nReturning to Main Menu\n");
            break;

          }


    
   switch(mem){


              case '0':{
                        printf("\nMemory contains following values:\n");
                        
                        for(k = 0; k<i; k++){
                         
                            printf("[%d] %f\n", ll, arr[k]);
                            ll = ll+1;
                        }
                        
                       ll=1;
                       break;
                    }

                  
                    
            default:
            {
                
                       s = mem - '0';
                        printf("\nvalue of item is: %f\n", arr[s-1]);        
                        break;   
                       
                    }

              break;

        } 
    
           
                        
                    



                    
                  
                }while(mem != 'X' | mem != 'X');

              
               
            }
            

}


float re(){
printf("\nYou Have Selected: Erase Memory\n");

for(k=0; k<i; k++){
    
arr[k]=0;

}
i = 0;

printf("\nMemory Has been Erased\n");
printf("\nReturning to Main Menu\n");


}

float var(){

while((getchar()) != '\n');


printf("\nEnter A Varrible: A to E\n");
scanf("%c", &cc);




switch(cc){

case 'a':
case 'A':

  printf("\nEnter a Value for A:\n");
    if (scanf("%d", &cont)!=1){
        
        printf("\nERROR: INPUT MUST BE A NUMBER\n");
        break;
        
    } 

    a=cont;
    break;

case 'b':
case 'B':

 printf("\nEnter a Value for B:\n");
   if(scanf("%d", &cont)!=1){
        
        printf("\nERROR: INPUT MUST BE A NUMBER\n");
        break;
        
    }

    b=cont;
    break;
    
case 'c':
case 'C':

 printf("\nEnter a Value for C:\n");
    if(scanf("%d", &cont)!=1){
        
        printf("\nERROR: INPUT MUST BE A NUMBER\n");
        break;
        
    } 

    c=cont;
    break;
    
case 'd':
case 'D':

 printf("\nEnter a Value for D:\n");
   if (scanf("%d", &cont)!=1){
        
        printf("\nERROR: INPUT MUST BE A NUMBER\n");
        break;
        
    }

    d=cont;
    break;
    
case 'e':
case 'E':

 printf("\nEnter a Value for E:\n");
    if(scanf("%d", &cont)!=1){
        
        printf("\nERROR: INPUT MUST BE A NUMBER\n");
        break;
        
    }

    e=cont;
    break;

default:

printf("\nERROR: INPUT MUST BE A VALID VARRIBLE\n");
break;
    


}while (cc != 'X')
break;


}

float exi(){
while((getchar()) != '\n');
         
         printf("\nThank You for using the Command-Line Calculator\n"); //Goodbye message given to User


}

float in(){
    
    printf("\nChoose an Option: B, U, A, V, M, R, X\n");
     
    scanf("%c", &ch);
}

int main(){
printf("Welcome to Command-Line Calculator \n"); //Welcome message and program information
printf("Developer: Nicole Trainer\n");
printf("Version: 3\n");
printf("Date: 2021-12-01\n");
printf("-------------------------------------------\n");
printf("Item Types:\n");

printf("  B = Binary Mathematical Operations\n"); //Operations used within program
printf("  U = Unary Mathematical Operations\n");
printf("  A = Advances Mathematical Operations\n");
printf("  V = Define variables and assign them values\n");
printf("  M = Memory\n");
printf("  R = Erase Memory\n");
printf("  X = Exit\n");
  printf("-------------------------------------------\n");
  

   do{
        in();
   
    switch(ch){ //details cases for what each operation outputs
    
      case 'B':
      case 'b':
            
          bi();
          break;
        
      case 'U':
      case 'u':

         ur();
         break;
         
         
    case 'A':
    case 'a':
         
        add();
        break;
             

    case 'm':
    case 'M':

       me();
       break;   

    case 'r':
    case 'R':
    
      re();
      break;

    case 'V':
    case 'v':

       var();
       break;

         
    case 'X':
    case 'x':
         
        exi();
        return 0;
        break;   
            
         
     default:
        
        printf("\nERROR: INPUT MUST BE A VALID OPTION\n");
        break;
             
    }  while((getchar()) != '\n');
    
    
   }while (op != 'X'); //end of loop when the option/item is equal to X
return 0;
}

