#include<iostream.h>
#include<conio.h>
#include<fstream.h>
#define MAX 2000
class option
{
private:
 char line[MAX];
public:
void save()
{
clrscr();
char name[15];
cout<<endl;
cout<<"   save as : ";
cin>>name;
ofstream outfile;
outfile.open(name);
outfile<<line;
cout<<endl;
cout<<"  save successfull ";
outfile.close();
}
void text()
{
 cin.getline(line,MAX,'@');
}
};
void main()
{
clrscr();
option a;
char s;
textcolor(LIGHTGREEN);
cout<<endl;
cprintf("                    ÉÍ» º ÉÍÍ» ÍÍËÍÍ ÉÍÍ ÉÍÍ» ÉÍÍ» ÍËÍÍ» "); cout<<endl;
cprintf("                    º º º º  º   º   ÌÍÍ ÌÍÍ¼ ÌÍÍ¹  º  º "); cout<<endl;
cprintf("                    º º º º  º   º   º   º    º  º  º  º "); cout<<endl;
cprintf("                    º ÈÍ¼ ÈÍÍ¼   º   ÈÍÍ º    º  º ÍÊÍÍ¼ "); cout<<endl;
cout<<endl;
textcolor(CYAN);
cprintf("ÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍ");
textcolor(11);
cout<<"         ";
cprintf("INFO : ");
textcolor(LIGHTRED);
cprintf("press '@' to terminate from the text ");
cout<<endl;
textcolor(CYAN);
cprintf("ÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍÍ");cout<<endl;
a.text();
cout<<endl;
cout<<endl;
textcolor(CYAN);
cprintf(" Do you want to save? Y/N ");
cin>>s;
if(s=='y'||s=='Y')
{
a.save();
}
getch();
}
