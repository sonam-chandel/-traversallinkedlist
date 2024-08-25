#include<stdio.h>
#include<malloc.h>
#include<conio.h>
 struct node
{
    int data;
    struct node*next;
}structnodes;

void main()
{
    char ch;
    struct node *p,*q,*s;
    p=(struct node *)malloc(sizeof(struct node));
    printf("enter the value of first node\n");
    scanf("%d",&p->data);
    s=p;
    do
    { 
        q=(struct node *)malloc(sizeof(struct node));
         printf("enter the value of next node\n");
    scanf("%d",&q->data);
    p->next=q;
    p=q;
    printf("press y,for next node\n");
    ch=getch();

    } while(ch=='y');
    printf("the linked list is:\n");
    p->next=NULL;
    while(s!=NULL)
    {
        printf("%d \n",s->data);
        s=s->next;
    }
   ch= getch();
}    
