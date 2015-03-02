---
layout: default
title: "ME401: Dynamic Systems & Controls"
course_description: "An exploration of the behavior of physical systems as well as the physics of individual components and the interactions between them. Topics include modeling dynamic systems, Laplace Transform Methods for Solving Differential Equations, transfer functions, stability, feedback, proportional—integral—derivative controllers, and applications of computer simulation in control."
next: ../Unit04
previous: ../Unit02
---
**Unit 3: Control Systems Design** <span id="3"></span> 
**Every dynamic system has a control (corrective) action for a desired
response.  For instance, a car’s cruise control can help you drive at a
given velocity.  A dynamic system cannot be designed completely without
incorporating some form of controller.  Feedback Controllers (i.e.
proportional (P), derivative (D), integral (I), or combinations thereof,
like PI, PD, or PID) are commonly used in the industry.  These
controllers are commonly designed in time-domain.  SCILAB should be used
wherever appropriate to prevent errors in hand calculations and to
validate calculations elsewhere.**

**Unit 3 Time Advisory**  
This unit should take you 31 hours to complete.

☐    Subunit 3.1: 13 hours

☐    Subunit 3.1.1: 1.5 hours

☐    Subunit 3.1.2: 1.5 hours

☐    Subunit 3.1.3: 1.5 hours

☐    Subunit 3.1.4: 2 hours

☐    Subunit 3.1.5: 2 hours

☐    Subunit 3.1.6: 2.5 hours

☐    Subunit 3.1.7: 2 hours

☐    Subunit 3.2: 10 hours

☐    Subunit 3.2.1: 2.5 hours

☐    Subunit 3.2.2: 2.5 hours

☐    Subunit 3.2.3: 2.5 hours

☐    Subunit 3.2.4: 2.5 hours

☐    Subunit 3.3: 8 hours

☐    Subunit 3.3.1: 2 hours

☐    Subunit 3.3.2: 3 hours

☐    Subunit 3.3.3: 3 hours

**Unit3 Learning Outcomes**  
Upon successful completion of this unit, students will be able to:

-   Identify how dynamic systems are controlled.
-   Identity feedback control and various types.
-   Identify how controllers are designed for dynamic systems.

**3.1 Control of Dynamic Systems** <span id="3.1"></span> 
**3.1.1 Controlled Systems** <span id="3.1.1"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “An Introduction to
    Control Systems: What is a Control System?”**
    Link: Bucknell University: Dr. Mastascusa’s “[An Introduction to
    Control Systems: What is a Control
    System?](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/Intro/Intro1.html#WhatIsAControlSystem)”
    (HTML)  
      
     Instructions: Please click the link and read the section titled
    “What is a Control System?”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.1.2 Components of Controlled Systems** <span id="3.1.2"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “Control System
    Components”**
    Link: Bucknell University: Dr. Mastascusa’s “[Control System
    Components](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/Help_Summaries/BlockDiagHelp.html)”
    (HTML)  
      
     Instructions: Please click the link and read the section titled
    “Control System Components.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.1.3 Feedback Control Systems** <span id="3.1.3"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “An Introduction to
    Control Systems: Why Use Feedback Control?”**
    Link: Bucknell University: Dr. Mastascusa’s “[An Introduction to
    Control Systems: Why Use Feedback
    Control?](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/Intro/Intro1.html)”
    (HTML)  
      
     Instructions: Please click the link and read the section titled
    “Why use Feedback Control?”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.1.4 Examples of Control Systems** <span id="3.1.4"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “An Introduction to
    Control Systems: Example/ Experiment”**
    Link: Bucknell University: Dr. Mastascusa’s “[An Introduction to
    Control Systems: Example/
    Experiment](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/Intro/Intro1.html#Example1)”
    (HTML)  
        
     Instructions: Please click the link and read the section titled
    “Example/ Experiment.”  Please read all four experiments.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.1.5 Closed-Loop Systems** <span id="3.1.5"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “An Introduction to
    Control Systems: Getting the Closed Loop Transfer Function”**
    Link: Bucknell University: Dr. Mastascusa’s “[An Introduction to
    Control Systems: Getting the Closed Loop Transfer
    Function](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/Intro/Intro1.html)”
    (HTML)  
      
     Instructions: Please click the link, scroll down, and read the
    section titled “Getting the Closed Loop Transfer Function.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.1.6 First-Order Controlled Systems** <span id="3.1.6"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “A Simulator for
    First Order, Closed Loop Systems”**
    Link: Bucknell University: Dr. Mastascusa’s “[A Simulator for First
    Order, Closed Loop
    Systems](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/Problems/InteractiveSimulators/Simulator1OrdClLoop.htm)”
    (HTML)  
      
     Instructions: Please click the link and read the section titled “A
    Simulator for First Order, Closed Loop Systems.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.1.7 Second-Order Controlled Systems** <span id="3.1.7"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “A Simulator for
    Second Order, Closed Loop Systems”**
    Link: Bucknell University: Dr. Mastascusa’s “[A Simulator for Second
    Order, Closed Loop
    Systems](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/Problems/InteractiveSimulators/Simulator2OrdClLoop.htm)”
    (HTML)  
      
     Instructions: Please click the link and read the section titled “A
    Simulator for Second Order, Closed Loop Systems.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.2 Feedback Control Systems** <span id="3.2"></span> 
**3.2.1 Proportional (P) Controllers** <span id="3.2.1"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “Proportional
    Control Systems: What Is a Proportional Control System?”**
    Link: Bucknell University: Dr. Mastascusa’s “[Proportional Control
    Systems: What Is a Proportional Control
    System?](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/Intro/Intro2.html)”
    (HTML)  
        
     Instructions: Please click the link and read the section “What Is a
    Proportional Control System?”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.2.2 Integral (I) Controllers** <span id="3.2.2"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “Integral Control
    Systems: What Is an Integral Control System?”**
    Link: Bucknell University: Dr. Mastascusa’s “[Integral Control
    Systems: What Is an Integral Control
    System?](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/Intro/Intro3.html)”
    (HTML)  
        
     Instructions: Please click the link and read the section titled
    “What Is an Integral Control System?”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.2.3 PID Controllers** <span id="3.2.3"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “PID Controllers”**
    Link: Bucknell University: Dr. Mastascusa’s “[PID
    Controllers](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/BookIndex.htm)”
    (HTML)  
        
     Instructions: Please click the link and read the section titled
    “PID Controllers.”   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.2.4 On-Off Controllers** <span id="3.2.4"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “Control Systems
    Introduction: On-Off Control Systems”**
    Link: Bucknell University: Dr. Mastascusa’s “[Control Systems
    Introduction: On-Off Control
    Systems](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/Intro/IntroNotes/IntroNote_VeryBasic.html)”
    (HTML)  
        
     Instructions: Please click the link and open up the webpage read
    the section titled “Control Systems Introduction: On-Off Control
    Systems.”   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.3 Design of Control Systems** <span id="3.3"></span> 
**3.3.1 Controller Design Based on Frequency Response** <span
id="3.3.1"></span> 
-   **Reading: University of Wisconsin-Madison: Dr. Duffie’s “Lecture
    28: Design Using Frequency Response”**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**3.3.2 Controller Design Based on Compensation Techniques** <span
id="3.3.2"></span> 
-   **Reading: University of Wisconsin-Madison: Dr. Duffie’s “Lecture
    29: Compensation”**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**3.3.3 Overall Controller Design** <span id="3.3.3"></span> 
-   **Reading: University of Wisconsin-Madison: Dr. Duffie’s “Lecture
    30: Control Design”**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)


