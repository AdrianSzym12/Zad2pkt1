# Zad2pkt1
{
            Console.WriteLine("Zadanie n!");
            Console.Write("Podstaw Liczbe za n= " );
            long liczba = long.Parse(Console.ReadLine());
            long wynik= liczba;

            for(long i=1; i < liczba; i= i+1)
            {
                wynik = wynik * (liczba - i);

            }
            Console.WriteLine("Wynik n!= "+ wynik);
}
