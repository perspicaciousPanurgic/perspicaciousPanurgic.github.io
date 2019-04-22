## Logan Williams's Portfolio!

As a recent graduate from SNHU’s computer science program I have been well prepared to enter a career in software development. My coursework has taught me how to collaborate in a team environment and communicate with stakeholders. Technical skills such as software design, database management, data structures, algorithms and security were also developed. While this program has helped me very much it has also opened my eyes to how much I have left to learn.

This portfolio exists to demonstrate what I have learned. First, a recorded code review about a program I wrote in C++ which allows the user to play Farkle in a command line prompt. Second, a rewrite of the C++ Farkle game in the Go programming language. Before this project I had never used Go and no prior course at SNHU had incorporated it. Not only did I rewrite the program in Go but I also redesigned it using test driven design (TDD) techniques. This improved the efficiency and stability of the program while teaching allowing me to practice TDD. 

In order to demonstrate the database management skills I have gained this portfolio includes a mongoDB database file with a simple REST style API used to query it. The API allows the user to search for an airport using the four-letter ICAO identifier or by the city name. This project showcases my ability to manipulate data, design a database, implement a RESTful API and create useful indexes to make queries more efficient. 

### [Informal Code Review](https://github.com/perspicaciousPanurgic/codeReview)

In this recorded code review I evaluate a program written for a previous class assignment. Written in C++ the program allows the user to play a dice game, commonly known as Farkle, via command line prompt. The purpose of this recording is to demonstrate my ability to informally summarize the function of the code, critique errors in design or implementation and propose improvements.

### [Software Design & Engineering](https://github.com/perspicaciousPanurgic/FarkleGo)

This link points to a Go program which allows you to play a game of Farkle through a command line terminal. The original version was written in C++. I enhanced this project by rewriting the entire program in the Go programming language using test-driven development (TDD) techniques. Since Go does not utilize classes it will required me to redesign core aspects of the program. This project demonstrates my ability to learn new a programming language, apply object-oriented programming paradigms in a language not specifically designed to support them and apply TDD techniques. 

During this project I learned to think of each statement in terms of its inputs and outputs first. Until the expected inputs and outputs are defined you cannot efficiently write the logic required to transform the inputs to the appropriate outputs. This helped me design a simpler and more efficient program than the original C++ version. 

### [Algorithm & Data Structures](https://github.com/perspicaciousPanurgic/FarkleGo)

This link points to a Go program which allows you to play a game of Farkle through a command line terminal. The original version was written in C++. I enhanced this project by making the underlying algorithms and data structures more efficient. For example, in the original C++ program there were 3 different arrays used to track the dice in play. In this Go version I reduced this down to a single array without losing any functionality. 

The greatest challenge I faced during this project was learning Go. This was my first attempt to write anything in the Go language so it took quite a while before I was comfortable with the language. An advantage to this process though was it really helped me step outside my comfort zone. Since I could not simply fall back on something that I used in the past so it forced me to critically evaluate exactly what I was trying to do before writing a single line of code.

### [Database](https://github.com/perspicaciousPanurgic/FindAirport)

This link points to a mongoDB database and python code created to query it using REST api principles. The API allows the user to search the database for an airport using either the ICAO airport identifier or by city. This demonstrate my ability to create and query a noSQL database such as MongoDB as well as create useful indexes and queries. 

To accomplish this project, I first had to figure out how to convert the raw data into a format which mongo import would recognize. To do this I used MicroSoft Excel to convert the original airports.dat file into comma separated value (.csv) format and added a header line. Once this was accomplished mongo import was able to easily convert it into a usable collection. Once this was accomplished, I wrote a simple API to query the database using Python through the MongoDB’s mongod utility. When this API is run the user may query the database by navigating to the following addresses in a browser :

http://127.0.0.1:8080/aviation/findAirport/icao 

http://127.0.0.1:8080/aviation/findAirport/city
