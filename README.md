using System;
using System.Collections.Generic;
using System.Text;

namespace ConsoleApp1
{
    class Card
    {
        string Rank { get; set; }
        string Suit { get; set; }
        int Value { get; set; }

        public override string ToString()
        {
            return Rank + " " + Suit;
        }

        public card(string rank, string suit, int value)
        {
            Rank = rank;
            Suit = suit;
            Value = value;
        }
    }
}
