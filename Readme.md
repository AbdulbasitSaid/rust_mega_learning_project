# Self-University Roadmap

**Note:** Each *Level* should take **at least 6 months**, with 1 year being a realistic pace for most learners.  
If you already have experience and can dedicate significant time (e.g., daily study blocks, weekend revision), you may progress faster.  
The focus should be **depth and mastery**, not speed.

---

## Table of content
<!-- TOC -->

- [Self-University Roadmap](#self-university-roadmap)
    - [Table of content](#table-of-content)
    - [Disciplines and books](#disciplines-and-books)
        - [Code and Craft](#code-and-craft)
            - [The Rust Programming Language — Steve Klabnik & Carol Nichols](#the-rust-programming-language--steve-klabnik--carol-nichols)
            - [Rust in Action — Tim McNamara](#rust-in-action--tim-mcnamara)
        - [Computing Fundamentals](#computing-fundamentals)
            - [Computer Science Illuminated — Nell Dale & John Lewis](#computer-science-illuminated--nell-dale--john-lewis)
            - [The Hidden Language of Computer Hardware and Software — Charles Petzold](#the-hidden-language-of-computer-hardware-and-software--charles-petzold)
            - [Structure and Interpretation of Computer Programs — Harold Abelson & Gerald Jay Sussman](#structure-and-interpretation-of-computer-programs--harold-abelson--gerald-jay-sussman)
            - [Computer Systems: A Programmer’s Perspective — Bryant & O’Hallaron](#computer-systems-a-programmers-perspective--bryant--ohallaron)
        - [Mathematical Thinking](#mathematical-thinking)
            - [Basic Math and Pre-Algebra For Dummies — Mark Zegarelli](#basic-math-and-pre-algebra-for-dummies--mark-zegarelli)
            - [Algebra I Workbook For Dummies — Mary Jane Sterling](#algebra-i-workbook-for-dummies--mary-jane-sterling)
            - [Precalculus Mathematics in a Nutshell — George Simmons](#precalculus-mathematics-in-a-nutshell--george-simmons)
            - [Calculus Made Easy — Silvanus P. Thompson](#calculus-made-easy--silvanus-p-thompson)
            - [Calculus — Michael Spivak optional, for depth](#calculus--michael-spivak-optional-for-depth)
            - [D Math Primer for Graphics and Game Development — Fletcher Dunn & Ian Parberry](#d-math-primer-for-graphics-and-game-development--fletcher-dunn--ian-parberry)
        - [Data Structures and Algorithms](#data-structures-and-algorithms)
            - [Grokking Data Structures — [Educative.io course/book]](#grokking-data-structures--educativeio-coursebook)
            - [Head First Design Patterns — Eric Freeman & Elisabeth Robson](#head-first-design-patterns--eric-freeman--elisabeth-robson)
            - [Refactoring — Martin Fowler](#refactoring--martin-fowler)
            - [Grokking Algorithms — Aditya Bhargava](#grokking-algorithms--aditya-bhargava)
            - [Introduction to Algorithms CLRS — Thomas Cormen et al. for rigorous depth if needed](#introduction-to-algorithms-clrs--thomas-cormen-et-al-for-rigorous-depth-if-needed)
        - [Data and Persistence](#data-and-persistence)
            - [Database System Concepts — Silberschatz, Korth, Sudarshan](#database-system-concepts--silberschatz-korth-sudarshan)
            - [SQL for Smarties — Joe Celko](#sql-for-smarties--joe-celko)
            - [Designing Data-Intensive Applications — Martin Kleppmann](#designing-data-intensive-applications--martin-kleppmann)
            - [PostgreSQL: Up and Running — Regina Obe & Leo Hsu](#postgresql-up-and-running--regina-obe--leo-hsu)
        - [Software Engineering](#software-engineering)
            - [Pro Git — Scott Chacon & Ben Straub](#pro-git--scott-chacon--ben-straub)
            - [UML Distilled — Martin Fowler](#uml-distilled--martin-fowler)
            - [The Pragmatic Programmer — Andrew Hunt & David Thomas](#the-pragmatic-programmer--andrew-hunt--david-thomas)
            - [The Software Craftsman — Sandro Mancuso](#the-software-craftsman--sandro-mancuso)
            - [Software Engineering at Google — Titus Winters et al](#software-engineering-at-google--titus-winters-et-al)
            - [Working Effectively with Legacy Code — Michael Feathers](#working-effectively-with-legacy-code--michael-feathers)
            - [Accelerate — Nicole Forsgren, Jez Humble, Gene Kim optional](#accelerate--nicole-forsgren-jez-humble-gene-kim-optional)
            - [The Mythical Man-Month — Frederick Brooks optional](#the-mythical-man-month--frederick-brooks-optional)
        - [Systemic Thinking](#systemic-thinking)
            - [System Design Interview Vol. 2 — Alex Xu](#system-design-interview-vol-2--alex-xu)
            - [System Design Interview Vol. 1 — Alex Xu](#system-design-interview-vol-1--alex-xu)
            - [Distributed Systems — Maarten van Steen & Andrew Tanenbaum](#distributed-systems--maarten-van-steen--andrew-tanenbaum)
        - [DevOps and Security Fundamentals](#devops-and-security-fundamentals)
            - [The Phoenix Project — Gene Kim, Kevin Behr, George Spafford](#the-phoenix-project--gene-kim-kevin-behr-george-spafford)
            - [The DevOps Handbook — Gene Kim et al](#the-devops-handbook--gene-kim-et-al)
            - [Continuous Delivery — Jez Humble & David Farley](#continuous-delivery--jez-humble--david-farley)
            - [Building Secure and Reliable Systems — Heather Adkins et al. Google SRE](#building-secure-and-reliable-systems--heather-adkins-et-al-google-sre)
            - [Web Application Hacker’s Handbook optional, security deep dive](#web-application-hackers-handbook-optional-security-deep-dive)
        - [Scientific Method for Engineers](#scientific-method-for-engineers)
            - [The Craft of Research — Wayne Booth et al](#the-craft-of-research--wayne-booth-et-al)
            - [Keeping a Lab Notebook — Howard Kanare](#keeping-a-lab-notebook--howard-kanare)
            - [How to Write a Lot — Paul Silvia](#how-to-write-a-lot--paul-silvia)
            - [Research Methods for Engineers — David V. Thiel](#research-methods-for-engineers--david-v-thiel)
        - [Research Literacy](#research-literacy)
            - [How to Read and Understand a Scientific Paper — Jennifer Raff](#how-to-read-and-understand-a-scientific-paper--jennifer-raff)
            - [The Scientist’s Guide to Writing — Stephen Heard optional](#the-scientists-guide-to-writing--stephen-heard-optional)
        - [Physics and Applied Physics](#physics-and-applied-physics)
            - [Fundamentals of Physics — Halliday, Resnick, Walker](#fundamentals-of-physics--halliday-resnick-walker)
            - [Physics for Scientists and Engineers — Raymond A. Serway](#physics-for-scientists-and-engineers--raymond-a-serway)
            - [Applied Physics — Dale Ewen, Neill Schurter, P. Erickson](#applied-physics--dale-ewen-neill-schurter-p-erickson)
        - [Robotics and Mechatronics](#robotics-and-mechatronics)
            - [Electronics & Hardware Foundations](#electronics--hardware-foundations)
            - [Exploring Arduino — Jeremy Blum](#exploring-arduino--jeremy-blum)
            - [Getting Started with Raspberry Pi — Matt Richardson & Shawn Wallace](#getting-started-with-raspberry-pi--matt-richardson--shawn-wallace)
            - [Designing Embedded Systems with PIC Microcontrollers — Tim Wilmshurst](#designing-embedded-systems-with-pic-microcontrollers--tim-wilmshurst)
            - [Mechanical & Fabrication Skills](#mechanical--fabrication-skills)
            - [Welding Essentials — William Galvery & Frank Marlow](#welding-essentials--william-galvery--frank-marlow)
            - [Woodworking Basics — Peter Korn](#woodworking-basics--peter-korn)
            - [Soldering Made Simple — Mitch Altman](#soldering-made-simple--mitch-altman)
            - [Fusion 360 for Makers — Lydia Sloan Cline](#fusion-360-for-makers--lydia-sloan-cline)
            - [Robotics Math & Control Theory](#robotics-math--control-theory)
            - [Linear System Theory — Wilson Rugh](#linear-system-theory--wilson-rugh)
            - [Robotics, Vision and Control — Peter Corke](#robotics-vision-and-control--peter-corke)
            - [Modern Robotics — Kevin Lynch & Frank Park](#modern-robotics--kevin-lynch--frank-park)
            - [Robotics Programming & Control](#robotics-programming--control)
            - [Learning ROS for Robotics Programming — Enrique Fernández et al](#learning-ros-for-robotics-programming--enrique-fern%C3%A1ndez-et-al)
            - [Introduction to Autonomous Robots — Nikolaus Correll et al](#introduction-to-autonomous-robots--nikolaus-correll-et-al)
            - [Visualization & Simulation](#visualization--simulation)
            - [Blender For Dummies — Jason van Gumster](#blender-for-dummies--jason-van-gumster)
            - [Blender 3D: Noob to Pro optional](#blender-3d-noob-to-pro-optional)
        - [Machine Learning Foundations](#machine-learning-foundations)
            - [Pattern Recognition and Machine Learning — Christopher Bishop](#pattern-recognition-and-machine-learning--christopher-bishop)
            - [Deep Learning — Ian Goodfellow et al](#deep-learning--ian-goodfellow-et-al)
            - [Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow — Aurélien Géron](#hands-on-machine-learning-with-scikit-learn-keras-and-tensorflow--aur%C3%A9lien-g%C3%A9ron)
        - [Project Management & Open Source](#project-management--open-source)
            - [The Art of Project Management — Scott Berkun](#the-art-of-project-management--scott-berkun)
            - [Peopleware — Tom DeMarco & Timothy Lister](#peopleware--tom-demarco--timothy-lister)
            - [Producing Open Source Software — Karl Fogel](#producing-open-source-software--karl-fogel)
            - [Forge Your Future with Open Source — VM Brasseur](#forge-your-future-with-open-source--vm-brasseur)
    - [Level Structure](#level-structure)
        - [Level 1 — Foundations of Computing and Math](#level-1--foundations-of-computing-and-math)
        - [Level 2 — Programming, Precalculus, and SICP](#level-2--programming-precalculus-and-sicp)
        - [Level 3 — Data Structures and Design Patterns](#level-3--data-structures-and-design-patterns)
        - [Level 4 — Algorithms and Deeper Math](#level-4--algorithms-and-deeper-math)
        - [Level 5 — Systems and Databases](#level-5--systems-and-databases)
        - [Level 6 — Software Engineering Practice](#level-6--software-engineering-practice)
        - [Level 7 — System Design and Distributed Systems](#level-7--system-design-and-distributed-systems)
        - [Level 8 — DevOps and Security](#level-8--devops-and-security)
        - [Level 9 — Research and Scientific Practice](#level-9--research-and-scientific-practice)
        - [Level 10 — Physics and Applied Physics](#level-10--physics-and-applied-physics)
        - [Level 11–13 — Robotics and Mechatronics](#level-1113--robotics-and-mechatronics)
        - [Level 14 — Machine Learning](#level-14--machine-learning)
        - [Level 15 — Project Management and Capstone](#level-15--project-management-and-capstone)

<!-- /TOC -->

## Disciplines and books

1. ### **Code and Craft**  

   - #### The Rust Programming Language — Steve Klabnik & Carol Nichols  

   - #### Rust in Action — Tim McNamara  

1. ### **Computing Fundamentals**  

   - #### Computer Science Illuminated — Nell Dale & John Lewis  

   - #### The Hidden Language of Computer Hardware and Software — Charles Petzold  

   - #### Structure and Interpretation of Computer Programs — Harold Abelson & Gerald Jay Sussman  

   - #### Computer Systems: A Programmer’s Perspective — Bryant & O’Hallaron  

1. ### **Mathematical Thinking**  

   - #### Basic Math and Pre-Algebra For Dummies — Mark Zegarelli  

   - #### Algebra I Workbook For Dummies — Mary Jane Sterling  

   - #### Precalculus Mathematics in a Nutshell — George Simmons  

   - #### Calculus Made Easy — Silvanus P. Thompson  

   - #### Calculus — Michael Spivak *(optional, for depth)*  

   - #### 3D Math Primer for Graphics and Game Development — Fletcher Dunn & Ian Parberry  

1. ### **Data Structures and Algorithms**  

   - #### Grokking Data Structures — [Educative.io course/book]  

   - #### Head First Design Patterns — Eric Freeman & Elisabeth Robson  

   - #### Refactoring — Martin Fowler  

   - #### Grokking Algorithms — Aditya Bhargava  

   - #### Introduction to Algorithms (CLRS) — Thomas Cormen et al. *(for rigorous depth if needed)*  

1. ### **Data and Persistence**  

   - #### Database System Concepts — Silberschatz, Korth, Sudarshan  

   - #### SQL for Smarties — Joe Celko  

   - #### Designing Data-Intensive Applications — Martin Kleppmann  

   - #### PostgreSQL: Up and Running — Regina Obe & Leo Hsu  

1. ### **Software Engineering**  

   - #### Pro Git — Scott Chacon & Ben Straub  

   - #### UML Distilled — Martin Fowler  

   - #### The Pragmatic Programmer — Andrew Hunt & David Thomas  

   - #### The Software Craftsman — Sandro Mancuso  

   - #### Software Engineering at Google — Titus Winters et al  

   - #### Working Effectively with Legacy Code — Michael Feathers  

   - #### Accelerate — Nicole Forsgren, Jez Humble, Gene Kim *(optional)*  

   - #### The Mythical Man-Month — Frederick Brooks *(optional)*  

1. ### **Systemic Thinking**  

   - #### System Design Interview Vol. 2 — Alex Xu  

   - #### System Design Interview Vol. 1 — Alex Xu  

   - #### Distributed Systems — Maarten van Steen & Andrew Tanenbaum  

1. ### **DevOps and Security Fundamentals**  

   - #### The Phoenix Project — Gene Kim, Kevin Behr, George Spafford  

   - #### The DevOps Handbook — Gene Kim et al  

   - #### Continuous Delivery — Jez Humble & David Farley  

   - #### Building Secure and Reliable Systems — Heather Adkins et al. (Google SRE)  

   - #### Web Application Hacker’s Handbook *(optional, security deep dive)*  

1. ### **Scientific Method for Engineers**  

   - #### The Craft of Research — Wayne Booth et al  

   - #### Keeping a Lab Notebook — Howard Kanare  

   - #### How to Write a Lot — Paul Silvia  

   - #### Research Methods for Engineers — David V. Thiel  

1. ### **Research Literacy**  

   - #### How to Read and Understand a Scientific Paper — Jennifer Raff  

   - #### The Scientist’s Guide to Writing — Stephen Heard *(optional)*  

1. ### **Physics and Applied Physics**  

   - #### Fundamentals of Physics — Halliday, Resnick, Walker  

   - #### Physics for Scientists and Engineers — Raymond A. Serway  

   - #### Applied Physics — Dale Ewen, Neill Schurter, P. Erickson  

1. ### **Robotics and Mechatronics**  

   - #### *Electronics & Hardware Foundations*  

   - #### Exploring Arduino — Jeremy Blum  

   - #### Getting Started with Raspberry Pi — Matt Richardson & Shawn Wallace  

   - #### Designing Embedded Systems with PIC Microcontrollers — Tim Wilmshurst  

   - #### *Mechanical & Fabrication Skills*  

     - #### Welding Essentials — William Galvery & Frank Marlow  

     - #### Woodworking Basics — Peter Korn  

     - #### Soldering Made Simple — Mitch Altman  

     - #### Fusion 360 for Makers — Lydia Sloan Cline  

   - #### *Robotics Math & Control Theory*  

     - #### Linear System Theory — Wilson Rugh  

     - #### Robotics, Vision and Control — Peter Corke  

     - #### Modern Robotics — Kevin Lynch & Frank Park  

   - #### *Robotics Programming & Control*  

     - #### Learning ROS for Robotics Programming — Enrique Fernández et al  

     - #### Introduction to Autonomous Robots — Nikolaus Correll et al  

   - #### *Visualization & Simulation*  

     - #### Blender For Dummies — Jason van Gumster  

     - #### Blender 3D: Noob to Pro *(optional)*  

1. ### **Machine Learning Foundations**  

   - #### Pattern Recognition and Machine Learning — Christopher Bishop  

   - #### Deep Learning — Ian Goodfellow et al  

   - #### Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow — Aurélien Géron  

1. ### **Project Management & Open Source**  

   - #### The Art of Project Management — Scott Berkun  

   - #### Peopleware — Tom DeMarco & Timothy Lister  

   - #### Producing Open Source Software — Karl Fogel  

   - #### Forge Your Future with Open Source — VM Brasseur  

---

## Level Structure

### Level 1 — Foundations of Computing and Math

- *Books*: Computer Science Illuminated, Hidden Language of Computer Hardware, Basic Math, Algebra I  
- *Project*: Build a simple CLI calculator, document learning in a lab notebook  

### Level 2 — Programming, Precalculus, and SICP

- *Books*: SICP, Precalculus Mathematics in a Nutshell, Calculus Made Easy  
- *Project*: Scheme or Python project implementing higher-order functions  

### Level 3 — Data Structures and Design Patterns

- *Books*: Grokking Data Structures, Head First Design Patterns, Refactoring  
- *Project*: Implement a small library (data structures + design patterns)  

### Level 4 — Algorithms and Deeper Math

- *Books*: Grokking Algorithms, CLRS (optional depth), 3D Math Primer  
- *Project*: Visualization of algorithm performance (graphs, 3D demos)  

### Level 5 — Systems and Databases

- *Books*: Computer Systems: A Programmer’s Perspective, Database System Concepts, SQL for Smarties, PostgreSQL Up and Running  
- *Project*: Build a small database-backed application  

### Level 6 — Software Engineering Practice

- *Books*: Pro Git, UML Distilled, Pragmatic Programmer, Software Craftsman, SE at Google, Legacy Code, Accelerate (optional), Mythical Man-Month (optional)  
- *Project*: Refactor and scale an existing project collaboratively  

### Level 7 — System Design and Distributed Systems

- *Books*: System Design Interview Vol. 1 & 2, Distributed Systems  
- *Project*: Design and document a scalable service architecture  

### Level 8 — DevOps and Security

- *Books*: Phoenix Project, DevOps Handbook, Continuous Delivery, Google SRE, Web App Hacker’s Handbook (optional)  
- *Project*: Deploy and secure a production-grade service  

### Level 9 — Research and Scientific Practice

- *Books*: Craft of Research, Keeping a Lab Notebook, How to Write a Lot, Research Methods for Engineers, How to Read a Scientific Paper  
- *Project*: Write a short technical research paper with reproducible results  

### Level 10 — Physics and Applied Physics

- *Books*: Fundamentals of Physics, Physics for Scientists and Engineers, Applied Physics  
- *Project*: Simulate a physical system (mechanics, circuits, etc.)  

### Level 11–13 — Robotics and Mechatronics

- *Books*: Arduino, Raspberry Pi, PIC Microcontrollers, Welding, Fusion 360, Linear System Theory, Modern Robotics, ROS, Blender  
- *Projects*: Build progressively complex robotic systems (starting with Arduino bots, leading to autonomous robot simulations and physical builds)  

### Level 14 — Machine Learning

- *Books*: Bishop, Goodfellow, Géron  
- *Project*: Train, evaluate, and deploy a custom ML model in a real-world task  

### Level 15 — Project Management and Capstone

- *Books*: Project Management, Peopleware, Producing OSS, Forge Your Future  
- *Project*: Large-scale open source or robotics project, fully documented and released  

---

**Principle:** Books are the *curriculum*. Projects are the *exams*.  
