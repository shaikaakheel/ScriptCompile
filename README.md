# ScriptCompile
To Compile Script Task &amp; Script Component  from SSIS packages

using ScriptCompile;
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp
{
    class Program
    {
        static void Main(string[] args)
        {
            Aakheel a = new Aakheel(@"C:\Users\AShaik\Package.dtsx");
            Console.ReadLine();
        }
    }
}

