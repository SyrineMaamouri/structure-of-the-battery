# structure-of-the-battery
please, I'm trying to develop a small application based on batteries and files in C ++ at the same time.
then I have a function that returns the 1st "top" only the battery.  I do not know how here is a little trying and thanks 
corrected me

// the structure
struct C {
 int val;
char visibil;
};

struct battery{
C *top ;
battery* next;
};

// la fonction
int som(battery *p){
if(p!=NULL){ 
 C* c=p->top;
}
return p;
}
