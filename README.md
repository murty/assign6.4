public abstract class sample(){
integer rollno;
string name;
integer regn;
display()
}
class exam extends sample()
{
public void display()
{
system.out.println("rollno is"+e.rollno);
system.out.println("name is"+e.name);
system.out.println("regn is"+e.regn);
}
}
class prior(){
public static void main(string[] args)
{
exam e=new exam;
e.rollno=25;
e.name="murty";
e.regn=225;
e.display();
}
}
