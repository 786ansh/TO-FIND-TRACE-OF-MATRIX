# TO-FIND-TRACE-OF-MATRIX
ANS int n,m;
   scanf("%d %d",&n,&m);
   int a1[n][m];
   for(int i=0;i<n;i++)
   {
       for(int j=0;j<m;j++)
       {
           scanf("%d",&a1[i][j]);
       }
       printf("\n");
   }
    
   int sum=0;
   
   for(int i=0;i<n;i++)
   {
       for(int j=0;j<m;j++)
       {
           if (i==j)
           {
               sum=sum+a1[i][j];
               
           }
       }
       
       
   }
   printf("%d",sum);
