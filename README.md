# RegisterNumber.net<br>
using System;<br>
namespace Exercises<br>
{<br>
    class RegisterNum<br>
    {<br>
        int regNo;<br>
        static int startNum;<br>
        static RegisterNum()<br>
        {<br>
            startNum = 20210000;<br>
        }<br>
        RegisterNum()<br>
        {<br>
            regNo = ++startNum;<br>
        }<br>
        public static void Main(String[] args)<br>
        {<br>
            for (int i = 0; i < 10; i++)<br>
            {<br>
                RegisterNum Student = new RegisterNum();<br>
                Console.WriteLine("student{0}:{1}", i + 1, Student.regNo);<br>
            }<br>
        }<br>
    }<br>
}<br>

OUTPUT:-
![Screenshot 2022-02-03 121303](https://user-images.githubusercontent.com/98145032/152294126-deefd8d9-aeb7-444e-9628-e11b7e99312a.png)

