# fibonacci-series-with-recursion-in-c-


    #include <stdio.h>
    int fib(int);
    main()
    {
	    int i,x,n;
	    printf("Enter a number:");
	    scanf("%d",&n);
	    for (i=0;i<=n;i++)
	    {
		    x=fib(i);
		    printf("\t %d",x);
	    }
	
    }
    int fib(int a)
	  {
		  if (a==0 || a==1)
		{
			return(a);
		}
		else
		{
			return(fib(a-1)+fib(a-2));
		}
	  }
