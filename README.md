
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>wpd website</title>
    <style>
*{
    padding:0;
    margin:0;
    color:black;
}
#navbar{
    height:60px;
    background-color: #4F4F4F;
    text-color:white;

}
#navbar a {
    color:white;
}
 button{
    Text-Color: white;
     
 }
#logo{
    background-color: #dbc92;
     fontsize:25px;
}
a{
    margin-right:200px; text-decoration:none;
}
body{
    font-family:arial,san-serif;
    line-height:1.6;
    background-color:#ffdab9;
    text-color: #000000; 
}
header{
    color:#4afaa2;
    padding:20px;
    color:#4afaa2;
}
header.container{
    max-width:1200px;
    margin:0 auto;
    padding:o 20px;
    display: flex;
    justify-content:space-between;
    align-items:center;
}
header h1{
    font-size:2rem;
}
nav ul{
    list-style-type:none;
    display:flex;
}
nav ul li{
    margin-right:20px;

}
nav ul li a{
    text-color: #2f4f4f; /* Dark Slate Gray */

    text-decoration:none;
    font-weight:bold;
    font-size:1rem;
}
section{
    padding:40px;
}
section h2{
    font-size:1.8rem;
    margin-border:20px;
}

section ul li{
    font-size:1.1rem;
    margin-bottom:10px;
}
    p {
        font-weight: bold;
        font-size: 25px;
        text-color: #000000; 
        margin-top:0;
        padding:0;

    }
   
img {
    display: block;         
    margin-left: auto;      
    margin-right: auto;     
    max-width: 100%;       
     height: auto;  
}
    footer {
        background-color: #333;
        color: white;
        text-align: center;
        padding: 10px 0;
        position: fixed;
        width: 100%;
        bottom: 0;
    }
    h1, h2,h3 {
        color: #10be67;
    }
    #variable{
        padding: 20px;
        margin: 20px;
        background-color: black;
        border-radius: 8px;
    }
    #quote {
        background-color: #f9f9f9;
        padding: 20px;
        text-align: center;
        border: 2px solid #ddd;
        margin: 20px 0;
        font-style: italic;
    }
    
    blockquote p {
        font-size: 1.2em;
        font-weight: bold;
    }
    
    blockquote footer {
        font-size: 1em;
        color: #555;
    }
    </STYLE>
</head>
<body>
 <h1> <center> learn creativity from coding.</center></h1>
    <div id="navbar">
        <a  href="c study material.html" target="_blank" id="logo">c study material</a>
       <a href="HOME.HTML" target="_blank">HOME</a>
        <a href="PROJECT.HTML" target="_blank">Projects</a>
       <a href="CONTACT.HTML" target="_blank">Contact us</a>
       <input placeholder="search.in">
       <button> Search</button>
       </div>
     <section id="topics">
        <div class="container">
        <h2>topics covered</h2>
        <ul>
            <li><a href="introduction-to-c.html"target="_blank"> introduction to c </a> </li>
            <li><a href="variables-and-data-types.html" target="_blank">variable and data types </a></li>
            <li><a href="control.html" target="_blank">control statements(if-else,switch case)</a></li>
            <li> <a href="loop.html">loops(for,while,do-while)</a></li>
            <li> <a href="f.html"target="_blank">functions</a></li>
            <li> <a href="array.html" target="_blank">array and strings</a></li>
            <li><a href="structure.html"target="_blank">structures and unions</a></li>
            <li>  <a href="file.html" target="_blank">file handing </a></li>
            <li> <a href="memory.html" target="_blank">memory management </a></li>
        </ul>
    </div>
 </section>
            <h1 style="text-align:center;">  introduction to c programming  </h1>
            <h2> What is C? </h2>
            <p> <i> C is a general-purpose programming language created by Dennis Ritchie at the Bell Laboratories in 1972.

                It is a very popular language, despite being old. The main reason for its popularity is because it is a fundamental language in the field of computer science.
                
                C is strongly associated with UNIX, as it was developed to write the UNIX operating system.
                
                </i></p>
                <h2> Why Learn C?  </h2>
                <p> <ul>
                    <li>It is one of the most popular programming languages in the world</li>
                    <li>If you know C, you will have no problem learning other popular programming languages such as Java, Python, C++, C#, etc, as the syntax is similar.</li>
                    <li>C is very fast, compared to other programming languages, like Java and Python</li>
                    <li>C is very versatile; it can be used in both applications and technologies
                   </li></ul>
                    </p>
                    <h2> Difference between C and C++ ? </h2> <br>
                        <p><i>
                            <ul>
                                <li> c++ was developed as an extension of C, and both languages have almost the same syntax</li>
                                <li> The main difference between C and C++ is that C++ supports classes and objects, while C does not.
                                </li>
                            </ul>
                        </i></p><hr>
                        <h2>  Get Started With C  </h2> <br>
                        <p>
                            <i> To start using C, you need two things: </i>
                            <ul>
                                <li>
                                    A text editor, like Notepad, to write C code
                                </li>
                                <li> A compiler, like GCC and turbo c to translate the C code into a language that the computer will understand</li>
                            </ul>   <hr>                     
                        </p>
                        <h2>  structure of c programming is as follows:- </h2> <br>
                        <img src="https://media.geeksforgeeks.org/wp-content/uploads/20221219163357/Structure-of-C-Program.png"alt="img of c">
                        </p>
                        <h3 style="text-align:center;">Features of C Programming Language   </h3> <br>
                        <i> The main features of C language include low-level access to memory, a simple set of keywords, and a clean style, these features make C language suitable for system programming like an operating system or compiler development.</i></p>
                        <h2>  What are the Most Important Features of C Language? <h2><br>
                            <i> Here are some of the most important features of the C language:</i>
                            <ol>
                                <li> Procedural Language</li>
                                   <li> Fast and Efficient</li>
                                   <li> Procedural Language</li>
                                    <li>Fast and Efficient</li>
                                    <li> General-Purpose Language</li>
                                      <li>  Rich set of built-in Operators</li> 
                                      <li> Libraries with Rich Functions</li>
                                      <li> Middle-Level Language</li>
                                       <li> Portability</li>   
                                       <li>Easy to Extend</li>                           
                                </ol>
                        </p>
                        <img src="https://media.geeksforgeeks.org/wp-content/uploads/20200214125122/Features-of-C-Programming-Language.jpg" alt="img" height="500px"width="500px">
                        <hr>
                        <h2> Advantages of c are as follows:- </h2> <br>
                        <p>
                            <ol>
                                <li> Efficiency: C is a fast and efficient language that can be used to create high-performance applications.</li>
                                <li> Portability: C programs can be compiled and run on a wide range of platforms and operating systems.</li>
                                <li> Low-level access: C provides low-level access to system resources, making it ideal for systems programming and developing operating systems.</li>
                               <li> Large user community: C has a large and active user community, which means there are many resources and libraries available for developers.</li>
                               <li> Widely used: C is a widely used language, and many modern programming languages are built on top of it.</li>
                            </ol>
                        </p><hr>
                        <h2 style="text-align:center;">  Compiling a C Program: Behind the Scenes </h2> <br><p>
                        <i> The compilation is the process of converting the source code of the C language into machine code. As C is a mid-level language, it needs a compiler to convert it into an executable code so that the program can be run on our machine.</i>
                         <br> <i> The C program goes through the following phases during compilation:-</i><br>
                         <img src="https://media.geeksforgeeks.org/wp-content/uploads/20230404112946/Compilation-Process-in-C.png" alt="img">    
                    </p>
                    <h2>What is Algorithm | Introduction to Algorithms</h2>
                    <h3> <un>Definition of Algorithm </un></h3>
                    <blockquote>
                    <p> <i> The word Algorithm means ” A set of finite rules or instructions to be followed in calculations or other problem-solving operations ” 
                        Or 
                        ” A procedure for solving a mathematical problem in a finite number of steps that frequently involves recursive operations”.</i></p>
                        Therefore Algorithm refers to a sequence of finite steps to solve a particular problem.   
                    </blockquote>
                       <img src="https://media.geeksforgeeks.org/wp-content/cdn-uploads/20191016135223/What-is-Algorithm_-1024x631.jpg"alt="img">
                       <h2>What is the need for algorithms?</h2>
                       <p>
                        <ol>
                            <li> Algorithms are necessary for solving complex problems efficiently and effectively. </li>
                               <li> They help to automate processes and make them more reliable, faster, and easier to perform.</li>
                              <li> Algorithms also enable computers to perform tasks that would be difficult or impossible for humans to do manually.</li>
                              <li> They are used in various fields such as mathematics, computer science, engineering, finance, and many others to optimize processes, analyze data, make predictions, and provide solutions to problems.</li>

                            </ol>
                       </p>
                       <h2>What are the Characteristics of an Algorithm?</h2>
                       <img src="https://media.geeksforgeeks.org/wp-content/cdn-uploads/20191016135220/Characteristics-of-an-Algorithm-1024x630.jpg" alt="img">
                       <h2>Flowchart In Programming </h2>
                       <p> <i> A flowchart is a diagrammatic representation of an algorithm. A flowchart can be helpful for both writing programs and explaining the program to others.

                       </i></p>
                       <h2> example of algorithm with flowchart is as follows :-</h2>
                       <img src="https://engineerstutor.com/wp-content/uploads/2018/08/1-7.jpg" alt="img">
                       <img src="https://engineerstutor.com/wp-content/uploads/2018/08/17-2.jpg" alt="img">
                        <section id="variables"
                        <h2>Variables in C</h2>
                        <p>In C, a variable is a storage location identified by a name that contains data which can be modified during program execution. The data in a variable can be of different types such as integer, float, character, etc.</p>
                        <h3>Example:</h3>
                        <pre>
                int age = 25; // Integer variable
                float salary = 50000.50; // Float variable
                char grade = 'A'; // Character variable
                        </pre>
                    </section>
                    
                    <section id="quote">
                        <blockquote>
                            <p>“Take Risks In Your Life… If You Win, You Can Lead! If You Lose, You Can Guide!”</p>
                            <p>- Swami Vivekananda</p>
                        </blockquote>
                    </section>
                    
                    <footer>
    <p>&copy; 2025 Learn C Programming. All Rights Reserved. Designed by Dhanya Kamra</p>
</footer>

                    
   
</body>
</html>