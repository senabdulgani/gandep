# gandep
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

namespace AganiTekTek
    {
    class Class1
        {
        static void Main(string[] args)
            {
            double sayi1, sayi2, toplam, çikar, çarp, böl;
            Console.Write("ilk sayıyı giriniz: ");
            sayi1 =Convert.ToDouble (Console.ReadLine());
            Console.WriteLine("ikinci sayıyyı giriniz: ");
            sayi2 = Convert.ToDouble(Console.ReadLine());
            toplam = sayi1 + sayi2;
            çikar = sayi1 - sayi2;
            çarp = sayi1 * sayi2;
            böl = sayi1 / sayi2;
            Console.WriteLine("{0} ile {1} in toplamı {2} dir.",sayi1,sayi2,toplam);
            Console.WriteLine("{0} ile {1} in farkı {2} dir.",sayi1,sayi2,çikar);
            Console.WriteLine("{0} ile {1} in çarpımı {2} dir.",sayi1,sayi2,çarp);
            Console.WriteLine("{0} ile {1} in bölümü {2} dir.",sayi1,sayi2,böl);
            Console.ReadKey();

            }
        }
    }
