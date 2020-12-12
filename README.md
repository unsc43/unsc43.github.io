# unsc43.github.io
GitHub Portfollio 
--------------------------------
Below holds the Code.
----------------------------




--GUI Code--
---- Trivia Game GUI ----
//{{Game.cs}}\\
using System;
using System.Collections.Generic;
using System.Text;
using static System.Console;
namespace Trivia_game_1._0
{
    class game
    {
     string gamerQuiz = "trivia game";
        public void Game()
        {
            //system
            Title = gamerQuiz;
            WriteLine("Welcome to " + gamerQuiz);
            WriteLine("__________Gamer Quiz by Noah Rivera!__________");
            WriteLine("Try and guess the correct awnser for a point each awnser gives 1 point try getting all 4");
            WriteLine("Instructions- - -");

            Play();
            ReadKey();



 
        }
        public void Play()
        {
            // Gamer time :)
            TriviaItem item1 = new TriviaItem();
            TriviaItem item2 = new TriviaItem();


        }

    }
}

//{{Game.Cs}}\\
using System;
using System.Collections.Generic;
using System.Text;
using System.Threading.Tasks.Dataflow;

namespace Trivia_game_1._0
{
    class TrivaItem
    {

        public static readonly string question1;

        //questions - side notes ( I did try and attempt to fix this through the self check but still came across issues. )
        public static string Getquestion()

        {
            return question1;

        }

        // couldn't get the public static string ReadLine (); code to work with my program and if possible would like further explination in class.
        public string question = "What is the firt FPS game ever made";
        public string answer = "Maze war";

        public string questionTwo = "What was the first Video Game ever?";
        public string answerTwo = "Pong";

        public string questionThree ="How many types of game developers are there" ;
        public int answerThree = 4;

        public string questionFour = "Is the RPG Genere of games the most popular? true or false?";
        public string answerFour = "False";

        public string BonusQuestion = "Is halo the best game ever? true or false?";
        public string BonusAwnswer = "True";


    }
    
}
//{{Program.cs}}\\

using System;

namespace Trivia_game_1._0
{
    class Program
    {
        static void Main(string[] args)
        {
            game currentGame = new game();
            currentGame.Play();

        }
    }
}
------------------------------------------------
//{{Player.cs}}\\
using System;
using System.Collections.Generic;
using System.Text;

namespace Trivia_game_1._0
{
    class Player
    {
        //player code
        public string Name = "Player 1";
        
        public int Score = 0;

        string playerInput = Console.ReadLine();

        public Player(string name)
        {
            Name = name;
            Score = 0;

        }
    }
}
----Adopt an Insect assignment----
//{{Program}}\\
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace zoom1GroupCode
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello World!");
            Console.ReadKey(true);


        }
    }



}

//{{Player}}\\
using System;
using System.Collections.Generic;
using System.Runtime.CompilerServices;
using System.Text;

namespace zoom1GroupCode
{
    class Player
    {
        // Attributes
        public string Type;
        public int Age;
        public int Height;
        // Methods
        public void Move() {
            //Do stuff

        }

    }
}

//{{Insect}}\\
using System;
using System.Collections.Generic;
using System.Drawing;
using System.Security.Cryptography.X509Certificates;
using System.Text;

namespace zoom1GroupCode
{
    class Insect
    {
        // Attributes
        public string Type;
        public string Color;
        public Boolean CanFly;
        // Methods
        public void MakeSound() { 
         // noises here
        }
        


    }
}

//{{Place}}\\
using System;
using System.Collections.Generic;
using System.Text;

namespace zoom1GroupCode
{
    class Place
    {
        //Attributes
        public string Location;
        public Boolean Building;
        public Boolean IsOpen;
        //Methods
        public void AllowCustomers()  {
            //buy things
}

    }
}
