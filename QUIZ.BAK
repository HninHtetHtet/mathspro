#include<iostream.h>
#include<conio.h>
#include<graphics.h>
#include<dos.h>
#include<process.h>
void Question();
void pic();
void main()
{
   clrscr();
   int d=DETECT,m;
  initgraph(&d,&m,"c:\\turboC3\\bgi");
  settextstyle(6,0,1);
  Question();

  }

void Question()
{ int ans;
  clrscr();
  cleardevice();
  setcolor(10);
  outtextxy(20,30,"4 criminals are caught and are to be punished. The judge ");
  outtextxy(0,50,"allows them to be freed if they can slove a puzzle. If they do ");
  outtextxy(0,70,"not, they will be hung. They agreed.");
  outtextxy(20,90,"The 4 criminals are lined up on some steps (shown in picture).");
  outtextxy(0,110,"They are all facing in the same direction. A wall separates the");
  outtextxy(0,130,"fourth man from the otherr three.");
  outtextxy(0,150,"So to summarise:");
  outtextxy(0,170,"Man1 can see Man2 and Man3.");
  outtextxy(0,190,"Man2 can see Man 3.");
  outtextxy(0,210,"Man3 can see none of the others.");
  outtextxy(0,230,"Man4 can see none of the others.");
  outtextxy(20,250,"The criminals are wearing hats. They are told taht there are");
  outtextxy(0,270,"two white hats and tow black hats. The men initially don't know ");
  outtextxy(0,290,"what color of the hat they are wearing. They are told to shout ");
  outtextxy(0,310,"the color of the hat that they are wearing as soon as they know for ");
  outtextxy(0,330,"certain what color it is.");
  outtextxy(20,350,"They are not allowed to turn round or move. They are not allowed ");
  outtextxy(0,370,"to talk to each other. They are not allowed to take their hats off.");
  outtextxy(0,400,"Who is the first person to shout out.");
  cout<<"\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n"
      <<"If you want to see the picture, enter '6'";
  cout<<"\n\nEnter your answer:";
  cin>>ans;
  switch(ans)
  {
    case 1:{cout<<"\nWrong Answer.";delay(2000);}break;
    case 2:{cout<<"\nYor're right.";delay(2000);}break;
    case 3:{cout<<"\nWrong Answer.";delay(2000);}break;
    case 6:{pic();}break;
    default:{Question();}break;
  }
  
}
 
void pic()
{  int ans;
   clrscr();
   cleardevice();
   line(50,300,150,300);
   line(150,300,150,330);
   line(150,330,250,330);
   line(250,330,250,360);
   line(250,360,450,360);
   rectangle(340,250,360,360);
   setcolor(6);
   circle(100,255,5);
   outtextxy(100,200,"1");
   line(100,260,100,290);
   line(100,265,90,275);
   line(100,265,110,275);
   line(100,290,90,300);
   line(100,290,110,300);
   circle(200,285,5);
   outtextxy(200,230,"2");
   line(200,290,200,320);
   line(200,295,190,305);
   line(200,295,210,305);
   line(200,320,190,330);
   line(200,320,210,330);
   circle(300,315,5);
   outtextxy(300,260,"3");
   line(300,320,300,350);
   line(300,325,290,335);
   line(300,325,310,335);
   line(300,350,290,360);
   line(300,350,310,360);
   circle(400,315,5);
   outtextxy(400,260,"4");
   line(400,320,400,350);
   line(400,325,390,335);
   line(400,325,410,335);
   line(400,350,390,360);
   line(400,350,410,360);
   setfillstyle(1,0);
   setcolor(7);
   fillellipse(100,250,8,5) ;
   fillellipse(300,310,8,5);
   setfillstyle(1,7);
   setcolor(7);
   fillellipse(400,310,8,5);
   fillellipse(200,280,8,5);
   cout<<"\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n"
  <<"If you want to go to question, enter '6'\nor if you enter '8' you will be exit";
  cout<<"\n\nEnter decision:";
  cin>>ans;
  switch(ans)
  {
    case 6:{Question();}break;
    case 8:exit;break;
    default:{pic();}break;
  }
}