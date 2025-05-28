# I'm Zain Kadhem!

Welcome to my portfolio! I’m **Zain Kadhem**, a Computer Science student at **Arizona State University**, graduating in **December 2025**. With a strong academic foundation and diverse technical experience, I am committed to leveraging my knowledge in **software engineering** to create impactful and efficient solutions.



## About Me

I am currently a **Computer Science** major and involved in multiple academic and professional societies, such as the **Software Developers Association (SoDA)**, **IEEE**, and **CodeDevils**. My hands-on experience includes roles in quality assurance, network administration, and software development, which have equipped me with a versatile skill set in the tech industry.

I am particularly passionate about software development, data structures, algorithms, and systems architecture, and I am skilled in **C++**, **C#**, **Java**, **JavaScript**, **Python**, and **SQL**.


## Skills & Tools

- **Programming Languages**: C++, C#, Java, JavaScript, Python, MATLAB, SQL, Shell Scripting, x86 Assembly
- **Frameworks & Tools**: Microsoft Azure, Arduino, Database Management Systems, Linux (Ubuntu), HTML/CSS
- **Core Competencies**: Data Structures & Algorithms, Debugging, Teamwork, Network Security, Software Development



## Education

- **Bachelor of Science in Computer Science**  
  **Arizona State University** - Tempe, AZ  
  **Expected Graduation**: December 2025



## Interests

When I'm not coding, I enjoy playing with my dog, weightlifting, Brazilian Jiu-Jitsu, fishing, and exploring new places.




```cpp
struct Zain {
    string pronouns = "He/Him";
    string bio = "I'm a Computer Science student and a passionate software engineer.";
    vector<string> code = {"C++", "Java", "Python", "JavaScript"};
    vector<string> askMeAbout = {"software engineering", "data structures", "systems architecture"};
    
    struct Technologies {
        struct FrontEnd {
            vector<string> js = {"React.js"};
            vector<string> css = {"Tailwind", "Bootstrap"};
        } frontEnd;
        
        struct BackEnd {
            vector<string> languages = {"Node.js", "Spring Boot"};
        } backEnd;
        
        vector<string> databases = {"MySQL", "PostgreSQL"};
        vector<string> misc = {"Git", "Azure"};
    } technologies;

    string funFact = "The first computer “bug” was an actual real-life bug.";
};

// Example instantiation
Zain zainProfile;
