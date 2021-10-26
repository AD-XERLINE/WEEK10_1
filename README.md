# WEEK10_1
โปรแกรมรายสัปดาห์ที่ 10 อันที่ 1

    #include  <stdio.h>
    int n=0;
    int main() {
	
    	printf("ENTER NUMBER: ");
    	scanf("%d",&n);
	
    	for(int i=1;i<=n;i++){
    		for(int j=1;j<=i;j++){
    			printf("*");
    		}
    		printf("\n");
    	}
    }
