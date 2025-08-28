# Year Self-Learning University — Leveling System

**Note:** Each *Level* should take **at least 6 months**, with 1 year being a realistic pace for most learners.  
If you already have experience and can dedicate significant time (e.g., daily study blocks, weekend revision), you may progress faster.  
The focus should be **depth and mastery**, not speed.

**Principle:**  

- Books = curriculum  
- Projects = exams  
- Rust is the **primary implementation language** for all software concepts  

---

<!-- TOC -->

- [Year Self-Learning University — Leveling System](#year-self-learning-university--leveling-system)
    - [Table of content](#table-of-content)
    - [Year 1 — Foundations of Computing, Math, and Rust](#year-1--foundations-of-computing-math-and-rust)
    - [Year 2 — Programming, Precalculus, Calculus, and Software Fundamentals](#year-2--programming-precalculus-calculus-and-software-fundamentals)
    - [Year 3 — Advanced Software Engineering and System Foundations](#year-3--advanced-software-engineering-and-system-foundations)
    - [Year 4 — System Design, Distributed Systems, Rust in Action, and DevOps](#year-4--system-design-distributed-systems-rust-in-action-and-devops)
    - [Year 5 — Capstone Year: Software Engineering Masterpiece](#year-5--capstone-year-software-engineering-masterpiece)
    - [Year 6 — Robotics Foundations: Electronics, Hardware, and Embedded Systems](#year-6--robotics-foundations-electronics-hardware-and-embedded-systems)
    - [Year 7 — Robotics Math, Control Theory, and Programming](#year-7--robotics-math-control-theory-and-programming)
    - [Year 8 — Visualization, Simulation, and Machine Learning for Robotics](#year-8--visualization-simulation-and-machine-learning-for-robotics)
    - [Year 9 — Capstone Year: Large-Scale Robotics Project](#year-9--capstone-year-large-scale-robotics-project)
    - [Year 10 — Integration, Research Literacy, and Mastery](#year-10--integration-research-literacy-and-mastery)
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

<!-- /TOC -->
<!-- /TOC -->
## Year 1 — Foundations of Computing, Math, and Rust

- **Books:**  
  - Rust Programming Language — Steve Klabnik & Carol Nichols  
  - Computer Science Illuminated — Nell Dale & John Lewis  
  - Hidden Language of Computer Hardware — Charles Petzold  
  - Basic Math and Pre-Algebra — Mark Zegarelli  
  - Algebra I Workbook — Mary Jane Sterling  
  - SQL for Smarties — Joe Celko  
  - Pro Git — Scott Chacon & Ben Straub  

- **Project:**  
  - CLI calculator, small database-backed app, Rust implementation  

---

## Year 2 — Programming, Precalculus, Calculus, and Software Fundamentals

- **Books:**  
  - Structure and Interpretation of Computer Programs — Abelson & Sussman  
  - Precalculus Mathematics in a Nutshell — George Simmons  
  - Calculus Made Easy — Silvanus Thompson  
  - Calculus — Michael Spivak *(optional depth)*  
  - Grokking Data Structures — Educative.io  
  - Rust: implement DS and small algorithms  

- **Project:**  
  - Rust-based mini project demonstrating data structures and algorithm usage  
  - Simple simulations for calculus concepts  

---

## Year 3 — Advanced Software Engineering and System Foundations

- **Books:**  
  - Head First Design Patterns — Freeman & Robson  
  - Refactoring — Martin Fowler  
  - Introduction to Algorithms (CLRS) — Cormen et al. *(optional depth)*  
  - Computer Systems: A Programmer’s Perspective — Bryant & O’Hallaron  
  - UML Distilled — Fowler  
  - The Pragmatic Programmer — Hunt & Thomas  
  - Software Craftsman — Mancuso  
  - PostgreSQL: Up and Running — Regina Obe & Leo Hsu  
  - Database System Concepts — Silberschatz et al.  

- **Project:**  
  - Build a full Rust library with design patterns, DS, and persistence  
  - Small team collaboration simulation using Git  

---

## Year 4 — System Design, Distributed Systems, Rust in Action, and DevOps

- **Books:**  
  - System Design Interview Vol. 1 & 2 — Alex Xu  
  - Distributed Systems — van Steen & Tanenbaum  
  - Rust in Action — Tim McNamara  
  - Designing Data-Intensive Applications — Martin Kleppmann  
  - Accelerate — Forsgren et al. *(optional)*  
  - Working Effectively with Legacy Code — Feathers  
  - Mythical Man-Month — Brooks *(optional)*  
  - Phoenix Project — Kim et al.  
  - DevOps Handbook — Kim et al.  
  - Continuous Delivery — Humble & Farley  
  - Building Secure and Reliable Systems — Adkins et al.  
  - Web Application Hacker’s Handbook *(optional)*  

- **Project:**  
  - Large-scale Rust system demonstrating distributed system concepts, persistence, DevOps, and security integration  

---

## Year 5 — Capstone Year: Software Engineering Masterpiece

- **Books:**  
  - Art of Project Management — Berkun  
  - Peopleware — DeMarco & Lister  
  - Producing Open Source Software — Fogel  
  - Forge Your Future with Open Source — VM Brasseur  

- **Project:**  
  - **Strictly for a large-scale software project** (1 year)  
  - Must combine DS, algorithms, system design, software engineering, and Rust implementation  
  - Fully documented, deployed, and optionally open-source  

---

## Year 6 — Robotics Foundations: Electronics, Hardware, and Embedded Systems

- **Books:**  
  - Electronics & Hardware Foundations  
  - Exploring Arduino — Jeremy Blum  
  - Getting Started with Raspberry Pi — Richardson & Wallace  
  - Designing Embedded Systems with PIC Microcontrollers — Wilmshurst  
  - Welding Essentials — Galvery & Marlow  
  - Woodworking Basics — Peter Korn  
  - Soldering Made Simple — Mitch Altman  
  - Fusion 360 for Makers — Lydia Sloan Cline  

- **Project:**  
  - Build progressively complex electronics projects  
  - Implement embedded Rust programs  

---

## Year 7 — Robotics Math, Control Theory, and Programming

- **Books:**  
  - Linear System Theory — Wilson Rugh  
  - Robotics, Vision and Control — Peter Corke  
  - Modern Robotics — Lynch & Park  
  - Learning ROS for Robotics Programming — Enrique Fernández et al  
  - Introduction to Autonomous Robots — Correll et al  

- **Project:**  
  - Build robotic systems integrating Rust programming and control theory  
  - Simulate robot motion and control algorithms  

---

## Year 8 — Visualization, Simulation, and Machine Learning for Robotics

- **Books:**  
  - Blender For Dummies — van Gumster  
  - Blender 3D: Noob to Pro *(optional)*  
  - Pattern Recognition and Machine Learning — Bishop  
  - Deep Learning — Goodfellow  
  - Hands-On ML with Scikit-Learn, Keras, TensorFlow — Géron  

- **Project:**  
  - Robotic simulations in 3D using Blender  
  - Train ML models for autonomous robotic behavior  

---

## Year 9 — Capstone Year: Large-Scale Robotics Project

- **Books:**  
  - Fundamentals of Physics — Halliday, Resnick, Walker  
  - Physics for Scientists and Engineers — Serway  
  - Applied Physics — Ewen et al.  
  - How to Write a Lot — Paul Silvia  
  - Craft of Research — Booth et al.  
  - Research Methods for Engineers — Thiel  
  - How to Read and Understand a Scientific Paper — Raff  
  - Scientist’s Guide to Writing *(optional)*  

- **Project:**  
  - **Strictly for a very large-scale robotics + software integration project**  
  - Could span multiple sub-projects (mechanical + electronics + Rust software + ML + visualization)  

---

## Year 10 — Integration, Research Literacy, and Mastery

- **Books:**  
  - Review all prior resources as needed  
  - Optional deep dives into any missing or advanced topics  
  - Focus on system-level thinking, multi-disciplinary integration  

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

   - #### **Electronics & Hardware Foundations**

     - #### Exploring Arduino — Jeremy Blum  

     - #### Getting Started with Raspberry Pi — Matt Richardson & Shawn Wallace  

     - #### Designing Embedded Systems with PIC Microcontrollers — Tim Wilmshurst  

   - #### **Mechanical & Fabrication Skills**

     - #### Welding Essentials — William Galvery & Frank Marlow  

     - #### Woodworking Basics — Peter Korn  

     - #### Soldering Made Simple — Mitch Altman  

     - #### Fusion 360 for Makers — Lydia Sloan Cline  

   - #### **Robotics Math & Control Theory**  

     - #### Linear System Theory — Wilson Rugh  

     - #### Robotics, Vision and Control — Peter Corke  

     - #### Modern Robotics — Kevin Lynch & Frank Park  

   - #### **Robotics Programming & Control**  

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
