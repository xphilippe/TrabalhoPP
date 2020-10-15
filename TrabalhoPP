#include <pthread.h>
#include <stdio.h>
#include <stdlib.h>


void *PrintIFF(void *thread1)
{
	long tid1;
	tid1=(long)thread1;
	printf("Instituto Federal Fluminense \n");
}

void *PrintPPD(void *thread2)
{
	long tid2;
	tid2=(long)thread2;
	printf("Programacao Paralela \n");
}

int main ()
{
	
	pthread_t t1,t2;
	int create;
	create = pthread_create(&t1, NULL, PrintIFF, NULL);
	create = pthread_create(&t2, NULL, PrintPPD, NULL);
	pthread_exit(NULL);
}
