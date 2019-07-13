#include<iostream.h>
#include<conio.h>
#include<dos.h>
#include<graphics.h>
#include<process.h>
void Question();
void AnswerPaper();
int GetVarible();
int GetNum();
void Key();
void mainScreen();
void main()
{
   clrscr();
   int dd=DETECT,m;
   initgraph(&dd,&m,"c:\\turboC3\\bgi");
   mainScreen();
   getch();
   closegraph();
}
void mainScreen()
{
   clrscr();
   cleardevice();
   setcolor(2);
   int a,b,c,d,e,f,j,k;
   int ch[30];int num[30];
   char dd;
   int i=0;
   Question();
   AnswerPaper();
   cout<<"\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n";
   ch[i]=GetVarible();
   while(ch[i]!=121&&ch[i]!=107)
   {
   if(ch[i]>='a'&&ch[i]<='f')
     {num[i]=GetNum();
     clrscr();
     cleardevice();
     Question();
     AnswerPaper();
    for(j=0;j<=i;j++)
    {
     for(k=0;k<j;k++)
     {
      if(ch[k]==ch[j])
      {
	num[k]=num[j];
      }
     }
    }
    cout<<"\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n";
    for(j=0;j<=i;j++)
    {
     switch(ch[j])
     {
      case 97:{switch(num[j])
		{
		 case 1:{outtextxy(404,65,"1");a=1;}break;
		 case 2:{outtextxy(404,65,"2");a=2;}break;
		 case 3:{outtextxy(404,65,"3");a=3;}break;
		 case 4:{outtextxy(404,65,"4");a=4;}break;
		 case 5:{outtextxy(404,65,"5");a=5;}break;
		 case 6:{outtextxy(404,65,"6");a=6;}break;
		 case 7:{outtextxy(404,65,"7");a=7;}break;
		 case 8:{outtextxy(404,65,"8");a=8;}break;
		 case 9:{outtextxy(404,65,"9");a=9;}break;
		 default:{cout<<"Wrong key press";}break;
	        }
	      }break;
      case 98:{switch(num[j])
		{
		 case 1:{outtextxy(484,65,"1");b=1;}break;
		 case 2:{outtextxy(484,65,"2");b=2;}break;
		 case 3:{outtextxy(484,65,"3");b=3;}break;
		 case 4:{outtextxy(484,65,"4");b=4;}break;
		 case 5:{outtextxy(484,65,"5");b=5;}break;
		 case 6:{outtextxy(484,65,"6");b=6;}break;
		 case 7:{outtextxy(484,65,"7");b=7;}break;
		 case 8:{outtextxy(484,65,"8");b=8;}break;
		 case 9:{outtextxy(484,65,"9");b=9;}break;
		 default:{cout<<"Wrong key press";}break;
		}
	      }break;
      case 99:{switch(num[j])
		{
		 case 1:{outtextxy(404,145,"1");c=1;}break;
		 case 2:{outtextxy(404,145,"2");c=2;}break;
		 case 3:{outtextxy(404,145,"3");c=3;}break;
		 case 4:{outtextxy(404,145,"4");c=4;}break;
		 case 5:{outtextxy(404,145,"5");c=5;}break;
		 case 6:{outtextxy(404,145,"6");c=6;}break;
		 case 7:{outtextxy(404,145,"7");c=7;}break;
		 case 8:{outtextxy(404,145,"8");c=8;}break;
		 case 9:{outtextxy(404,145,"9");c=9;}break;
		 default:{cout<<"Wrong key press";}break;
		 }
	       }break;
      case 100:{switch(num[j])
		{
		 case 1:{outtextxy(564,145,"1");d=1;}break;
		 case 2:{outtextxy(564,145,"2");d=2;}break;
		 case 3:{outtextxy(564,145,"3");d=3;}break;
		 case 4:{outtextxy(564,145,"4");d=4;}break;
		 case 5:{outtextxy(564,145,"5");d=5;}break;
		 case 6:{outtextxy(564,145,"6");d=6;}break;
		 case 7:{outtextxy(564,145,"7");d=7;}break;
		 case 8:{outtextxy(564,145,"8");d=8;}break;
		 case 9:{outtextxy(564,145,"9");d=9;}break;
		 default:{cout<<"Wrong key press";}break;
		 }
	        }break;
      case 101:{switch(num[j])
		{
		 case 1:{outtextxy(484,225,"1");e=1;}break;
		 case 2:{outtextxy(484,225,"2");e=2;}break;
		 case 3:{outtextxy(484,225,"3");e=3;}break;
		 case 4:{outtextxy(484,225,"4");e=4;}break;
		 case 5:{outtextxy(484,225,"5");e=5;}break;
		 case 6:{outtextxy(484,225,"6");e=6;}break;
		 case 7:{outtextxy(484,225,"7");e=7;}break;
		 case 8:{outtextxy(484,225,"8");e=8;}break;
		 case 9:{outtextxy(484,225,"9");e=9;}break;
		 default:{cout<<"Wrong key press";}break;
		}
	     }break;
    case 102:{switch(num[j])
		{
		 case 1:{outtextxy(564,225,"1");f=1;}break;
		 case 2:{outtextxy(564,225,"2");f=2;}break;
		 case 3:{outtextxy(564,225,"3");f=3;}break;
		 case 4:{outtextxy(564,225,"4");f=4;}break;
		 case 5:{outtextxy(564,225,"5");f=5;}break;
		 case 6:{outtextxy(564,225,"6");f=6;}break;
		 case 7:{outtextxy(564,225,"7");f=7;}break;
		 case 8:{outtextxy(564,225,"8");f=8;}break;
		 case 9:{outtextxy(564,225,"9");f=9;}break;
		 default:{cout<<"Wrong key press";}break;
		}
	     }break;
	}
      }
      i++;
    }
    else {clrscr();
	  cleardevice();
	  Question();
	  AnswerPaper();
	  cout<<"\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n";
	  cout<<"Wrong key press";
         }
     ch[i]=GetVarible();
   }
   switch(ch[i])
   {case 121:{if(a-b==2&&c+2==d&&4+e==f&&a-c==4&&b-2==e&&2+d==f)
	        cout<<"\n\nYou are right!";
	     else {cout<<"\n\nYou are wrong!"
		   <<"\n\nIf you wanna try again, enter 't'."
		   <<"\n\nOr the problem will be exit."
		   <<"\n\nEnter your decision:  ";
		   cin>>dd;
		   switch(dd)
		   {case 't':mainScreen();break;
		    default:exit;break;
		   }
                   }
	      }break;
   case 107:Key();break;
   default:cout<<"Wrong key press";break;
   }
}
  
void Question()
{
   outtextxy(110,30,"Question");
   int g=36,h=50,k=236,l=250,i,j=40,y,z;
   cout<<"Find the variables \"a,b,c,d,e and f\" within the range of \"1 to 9\"";
   rectangle(g,h,k,l);
   for(i=1;i<=4;i++)
   {y=g+j*i;
   line(y,h,y,l);
   }
   for(i=1;i<=4;i++)
   {z=h+j*i;
    line(g,z,k,z);
   }

   outtextxy(50,65,"a");
   outtextxy(130,65,"b");
   outtextxy(50,145,"c");
   outtextxy(210,145,"d");
   outtextxy(130,225,"e");
   outtextxy(210,225,"f");
   outtextxy(90,65,"-");
   outtextxy(170,65,"=");
   outtextxy(50,105,"-");
   outtextxy(130,105,"-");
   outtextxy(210,105,"+");
   outtextxy(90,145,"+");
   outtextxy(170,145,"=");
   outtextxy(50,185,"=");
   outtextxy(130,185,"=");
   outtextxy(210,185,"=");
   outtextxy(90,225,"+");
   outtextxy(170,225,"=");
   outtextxy(210,65,"2");
   outtextxy(130,145,"2");
   outtextxy(50,225,"4");
}

void AnswerPaper()
{
  outtextxy(440,30,"Answer Paper");
  int n=390,o=50,p=590,q=250,r,s=40,t,u;
   rectangle(n,o,p,q);
   for(r=1;r<=4;r++)
   {t=n+s*r;
   line(t,o,t,q);
   }
   for(r=1;r<=4;r++)
   {u=o+s*r;
    line(n,u,p,u);
   }
   outtextxy(444,65,"-");
   outtextxy(524,65,"=");
   outtextxy(404,105,"-");
   outtextxy(484,105,"-");
   outtextxy(564,105,"+");
   outtextxy(444,145,"+");
   outtextxy(524,145,"=");
   outtextxy(404,185,"=");
   outtextxy(484,185,"=");
   outtextxy(564,185,"=");
   outtextxy(444,225,"+");
   outtextxy(524,225,"=");
   outtextxy(564,65,"2");
   outtextxy(484,145,"2");
   outtextxy(404,225,"4");
}

int GetVarible()
{   
   char ch;
   cout<<"\n\nIf you are sure, Enter 'y' instead of variable.";
   cout<<"\n\nIf you want to see the key, Enter 'k' instead of variable.";
   cout<<"\n\nEnter a variable:   ";
   cin>>ch;
   return ch;
}

int GetNum()
{
    int num;
    cout<<"\nEnter a number for this variable:   ";
    cin>>num;
    return num;
}

void Key()
{
   clrscr();
   cleardevice();
   setcolor(9);
   outtextxy(120,30,"Key");
   char key;
   int g=36,h=50,k=236,l=250,i,j=40,y,z;
   rectangle(g,h,k,l);
   for(i=1;i<=4;i++)
   {y=g+j*i;
   line(y,h,y,l);
   }
   for(i=1;i<=4;i++)
   {z=h+j*i;
    line(g,z,k,z);
   }

   outtextxy(50,65,"5");
   outtextxy(130,65,"3");
   outtextxy(50,145,"1");
   outtextxy(210,145,"3");
   outtextxy(130,225,"1");
   outtextxy(210,225,"5");
   outtextxy(90,65,"-");
   outtextxy(170,65,"=");
   outtextxy(50,105,"-");
   outtextxy(130,105,"-");
   outtextxy(210,105,"+");
   outtextxy(90,145,"+");
   outtextxy(170,145,"=");
   outtextxy(50,185,"=");
   outtextxy(130,185,"=");
   outtextxy(210,185,"=");
   outtextxy(90,225,"+");
   outtextxy(170,225,"=");
   outtextxy(210,65,"2");
   outtextxy(130,145,"2");
   outtextxy(50,225,"4");
   cout<<"\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n";
   cout<<"\n\nIf you want to go back, Enter 'b'. ";
   cout<<"\n\nIf you want to exit, Enter 'x'.";
   cout<<"\n\nEnter a key:   ";
   cin>>key;
   switch(key)
   {
     case 'b':mainScreen();break;
     case 'x':exit;break;
     default:{cout<<"\nWrong key press";delay(2000);Key();}break;
   }
}