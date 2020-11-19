#include<iostream>

int Prime_num(int x)
{
	int j,count=0;
	for(j=2;j<=x/2;j++)
	{
		if(x%j==0)
		{
			count++;
		}
	
	}
	  if(count==0)
	  {
		return 1;
	  }
	
}

int main()
{
	int n,i;
	std::cout<<"Enter a positive integer: ";
	std::cin>>n;
	for(i=2;i<=n/2;i++)
	{
		if(Prime_num(i)==Prime_num(n-i)==1)
		{
			std::cout<<n<<"="<<i<<"+"<<n-i<<"\n";
			
		}
	}
	
	
}
