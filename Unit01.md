---
layout: default
title: "ME401: Dynamic Systems & Controls"
course_description: "An exploration of the behavior of physical systems as well as the physics of individual components and the interactions between them. Topics include modeling dynamic systems, Laplace Transform Methods for Solving Differential Equations, transfer functions, stability, feedback, proportional—integral—derivative controllers, and applications of computer simulation in control."
next: ../Unit02
previous: ../Intro
---
**Unit 1: Dynamic Systems** <span id="1"></span> 
**Unit One will introduce dynamic systems.  Dynamic systems are
mathematically modeled as differential equations representing various
components and the interactions between them.  As all dynamic systems
are represented mathematically, this unit will first review differential
equations and Laplace transforms matrices in order to help you better
understand controller design, which we will cover in subsequent
chapters.  After we have completed our math review, we will learn how to
represent dynamic systems in various forms.  You will discover that the
analysis of dynamic systems is usually performed in either time-domain
or frequency-domain.  You will also learn how to represent dynamic
systems in transfer function using Laplace transforms.  **

**Unit 1 Time Advisory**  
This unit should take you 32 hours to complete.

☐    Subunit 1.1: 12 hours

☐    Subunit 1.1.1: 1 hour

☐    Subunit 1.1.2: 1 hour

☐    Subunit 1.1.3: 2.5 hours

☐    Subunit 1.1.4: 2 hours

☐    Subunit 1.1.5: 2 hours

☐    Subunit 1.1.6: 2 hour

☐    Subunit 1.1.7: 1.5 hours

☐    Subunit 1.2: 11 hours

☐    Subunit 1.2.1: 3 hours

☐    Subunit 1.2.2: 3 hours

☐    Subunit 1.2.3: 2.5 hours

☐    Subunit 1.2.4: 2.5 hours

☐    Subunit 1.3: 4 hours

☐    Subunit 1.3.1: 2 hours

☐    Subunit 1.3.2: 2 hours

☐    Subunit 1.4: 5 hours

☐    Subunit 1.4.1: 1 hour

☐    Subunit 1.4.2: 1.5 hours

☐    Subunit 1.4.3: 1.5 hours

☐    Subunit 1.4.4: 1 hour

**Unit1 Learning Outcomes**  
Upon successful completion of this unit, students will be able to:

-   Define dynamic systems and types.
-   Identify how mechanical, thermal, fluid, and electrical systems are
    modeled.
-   Develop and review the required mathematical background for dynamic
    systems and control.
-   Identify the characteristics of first- and second-order dynamic
    systems.

**1.1 Dynamic Systems: Introduction and Modeling** <span
id="1.1"></span> 
**1.1.1 Introduction to Dynamic System and Controls.** <span
id="1.1.1"></span> 
-   **Reading: Georgia Tech University: Dr. Sadegh’s “Introduction to
    System Dynamics and Control”**
    Link: Georgia Tech University: Dr. Sadegh’s “[Introduction to System
    Dynamics and
    Control](http://www.me.gatech.edu/nader.sadegh/ME3015/)” (PDF)  
        
     Instructions: Please click and read the PDF titled “Introduction to
    System Dynamics and Control” under “Selected Lecture Notes.”   
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.1.2 Examples of Dynamic Systems** <span id="1.1.2"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “An Introduction to
    System Dynamics—First Order Systems: The System and Some Examples”**
    Link Bucknell University: Dr. Mastascusa’s “[An Introduction to
    System Dynamics—First Order Systems: The System and Some
    Examples](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/SysDyn/SysDyn1.html#TheSystem)”
    (HTML)  
        
     Instructions: Please click the link, open the webpage, and read the
    section titled “The System—And Some Examples.”   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.1.3 Mechanical Systems** <span id="1.1.3"></span> 
-   **Reading: Georgia Tech University: Dr. Sadegh’s “Mathematical
    Modeling of Mechanical Systems”**
    Link: Georgia Tech University: Dr. Sadegh’s “[Mathematical Modeling
    of Mechanical
    Systems](http://www.me.gatech.edu/nader.sadegh/ME3015/)” (PDF)  
        
     Instructions: Please click and read the PDF titled “Mathematical
    Modeling of Mechanical Systems” under “Selected Lecture Notes.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.1.4 Fluid Systems** <span id="1.1.4"></span> 
-   **Reading: Georgia Tech University: Dr. Sadegh’s “Mathematical
    Modeling of Fluid Systems”**
    Link: Georgia Tech University: Dr. Sadegh’s “[Mathematical Modeling
    of Fluid Systems](http://www.me.gatech.edu/nader.sadegh/ME3015/)”
    (PDF)  
        
     Instructions: Please click and read the PDF titled “Mathematical
    Modeling of Fluid Systems” under “Selected Lecture Notes.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.1.5 Electrical Systems** <span id="1.1.5"></span> 
-   **Reading: Georgia Tech University: Dr. Sadegh’s “Mathematical
    Modeling of Electrical Systems”**
    Link: Georgia Tech University: Dr. Sadegh’s “[Mathematical Modeling
    of Electrical
    Systems](http://www.me.gatech.edu/nader.sadegh/ME3015/)” (PDF)  
      
     Instructions: Please click and read the PDF titled “Mathematical
    Modeling of Electrical Systems” under “Selected Lecture Notes.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.1.6 Linear Dynamic Systems** <span id="1.1.6"></span> 
-   **Reading: University of California at Berkeley: Dr. Hedrick’s
    “General Properties: Properties of Linear Time Invariant Systems”**
    Link: University of California at Berkeley: Dr. Hedrick’s “[General
    Properties: Properties of Linear Time Invariant
    Systems](http://www.me.berkeley.edu/ME237/notes2.html)” (PDF)  
        
     Instructions: Please click and open the PDF titled “General
    Properties” and then scroll down and read the section “Properties of
    Linear Time Invariant Systems.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.1.7 Non-Linear Dynamic Systems** <span id="1.1.7"></span> 
-   **Reading: University of California at Berkeley: Dr. Hedrick
    “Nonlinear System Properties”**
    Link: University of California at Berkeley: Dr. Hedrick “[Nonlinear
    System Properties](http://www.me.berkeley.edu/ME237/notes2.html)”
    (PDF)  
        
     Instructions: Please click and open the PDF titled “General
    Properties” and then scroll down and read the section “Nonlinear
    System Properties.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.2 Mathematical Background** <span id="1.2"></span> 
*Note: Once you understand different types of dynamic systems, we will
review the mathematics that we will use throughout this course.  We will
take a look at differential equations, Laplace transforms, matrices, and
linearization of non-linear dynamic systems.  This review will help us
better understand how to convert dynamic systems from one form of
mathematical representation to another.  This section is optional.  You
can go to section 1.3 if you are already familiar with the math.  *

**1.2.1 Differential Equations** <span id="1.2.1"></span> 
-   **Lecture: Khan Academy: Differential Equations: “Introduction to
    Differential Equations,” “Separable Differential Equations,” “First
    Order Homogenous Equations,” and “Second Order Homogenous
    Equations”**
    Link: Khan Academy: Differential Equations: “[Introduction to
    Differential
    Equations](https://www.khanacademy.org/math/differential-equations/first-order-differential-equations/differential-equations-intro/v/what-is-a-differential-equation),”
    (YouTube) “[Separable Differential
    Equations](https://www.khanacademy.org/math/differential-equations/first-order-differential-equations/separable-equations/v/separable-differential-equations?playlist=Differential%20Equations),”
    (YouTube) “[First Order Homogenous
    Equations](http://www.khanacademy.org/video/first-order-homegenous-equations?playlist=Differential),”
    (YouTube) and “[Second Order Homogenous
    Equations](http://www.khanacademy.org/video/2nd-order-linear-homogeneous-differential-equations-1?playlist=Differential)”
    (YouTube)  
        
     Also available in:  
     [iTunes
    U](http://deimos3.apple.com/WebObjects/Core.woa/Browse/khanacademy.org-dz.4627308527?i=2038751373)
    (Introduction to Differential Equations)  
     [iTunes
    U](http://deimos3.apple.com/WebObjects/Core.woa/Browse/khanacademy.org-dz.4627309667?i=1392347891)
    (Separable Differential Equations)  
     [iTunes
    U](http://deimos3.apple.com/WebObjects/Core.woa/Browse/khanacademy.org-dz.4627309703?i=1098211639)
    (First Order Homogenous Equations)  
     [iTunes
    U](http://itunes.apple.com/us/podcast/2nd-order-linear-homogeneous/id391036091?i=86817945)
    (Second Order Homogenous Equations)  
        
     Instructions: Please watch these videos to familiarize yourself
    with differential equations and relevant examples.   
      
     Watching these videos should take approximately 45 minutes.  
      

    Terms of Use: These videos are licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 United States
    License](http://creativecommons.org/licenses/by-nc-nd/3.0/).  They
    are attributed to the Khan Acadamey.

-   **Reading: Masachussetts Institute of Technology OpenCourseWare:
    Herbert Gross’s “Lecture 1: The Concept of a General Solution”**
    Lecture: Masachussetts Institute of Technology OpenCourseWare:
    Herbert Gross’s [“Lecture 1: The Concept of a General
    Solution”](http://ocw.mit.edu/resources/res-18-008-calculus-revisited-complex-variables-differential-equations-and-linear-algebra-fall-2011/part-ii/lecture-1-the-concept-of-a-general-solution/) (YouTube)  
      
     Instructions: Watch this the lecture.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/).It is
    attributed to the Massachusetts Institute of Technology, and the
    original version can be found
    [here](http://ocw.mit.edu/courses/mechanical-engineering/2-007-design-and-manufacturing-i-spring-2009/related-resources/drawing_and_sketching/#Isometric_Drawing).

**1.2.2 Laplace Transforms** <span id="1.2.2"></span> 
-   **Lecture: Khan Academy: Differential Equations: “Laplace
    Transform,” Laplace Transform to Solve an Equation,” and “Inverse
    Laplace Examples”**
    Link: Khan Academy: Differential Equations: “[Laplace
    Transforms](http://www.khanacademy.org/video/laplace-transform-1?playlist=Differential)”
    (YouTube), “[Laplace Transform to Solve an
    Equation](http://www.khanacademy.org/video/laplace-transform-to-solve-an-equation?playlist=DifferentialEquations)”
    (YouTube), and “[Inverse Laplace
    Examples](http://www.khanacademy.org/video/inverse-laplace-examples?playlist=DifferentialEquations)”
    (YouTube)  
        
     Also available in:  
     [iTunes
    U](http://itunes.apple.com/us/podcast/laplace-transform-1/id391036091?i=86817954)
    (Laplace Transforms)  
     [iTunes
    U](http://itunes.apple.com/us/podcast/laplace-transform-to-solve/id391036091?i=86817924)
    (Laplace Transforms to Solve an Equation)  
     [iTunes
    U](http://itunes.apple.com/us/podcast/inverse-laplace-examples/id391036091?i=86817956)
    (Inverse Laplace Examples)  
        
     Instructions: Please watch these videos to familiarize yourself
    with Laplace transforms and take a look at some relevant
    examples.   
      
     Watching these videos should take approximately 45 minutes.  
      
     Terms of Use: These videos are licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 United States
    License](http://creativecommons.org/licenses/by-nc-nd/3.0/).  They
    are attributed to the Khan Academy.

-   **Reading: Masachussetts Institute of Technology OpenCourseWare:
    Herbert Gross’ “Lecture 7: Laplace Transforms”**
    Lecture: Masachussetts Institute of Technology OpenCourseWare:
    Herbert Gross’ [“Lecture 7: Laplace
    Transforms”](http://ocw.mit.edu/resources/res-18-008-calculus-revisited-complex-variables-differential-equations-and-linear-algebra-fall-2011/part-ii/lecture-7-laplace-transforms/) (YouTube)  
      
     Instructions: Watch this lecture.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/).It is
    attributed to the Massachusetts Institute of Technology, and the
    original version can be found
    [here](http://ocw.mit.edu/resources/res-18-008-calculus-revisited-complex-variables-differential-equations-and-linear-algebra-fall-2011/part-ii/lecture-7-laplace-transforms/).

-   **Reading: Wikipedia: “Laplace Transform”**
    Link: Wikipedia: [“Laplace
    Transform”](https://resources.saylor.org/archived/wp-content/uploads/2013/04/ME401-1.2.2-LaplaceTransform.pdf) (PDF)  
      
     Instructions: You should be aware of the extensive tabulations of
    Laplace transform tables compiled here and in other references
    available on the Internet.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-ShareAlike 3.0 United
    States](http://creativecommons.org/licenses/by-sa/3.0/us/). It is
    attributed to Wikipedia, and the original version can be found
    [here](http://en.wikipedia.org/wiki/Laplace_transform).

**1.2.3 Matrices** <span id="1.2.3"></span> 
-   **Lecture: Khan Academy: Linear Algebra: “Introduction to Matrices”
    and “Matrices to Solve Systems of Equations”**
    Link: Khan Academy: Linear Algebra: “[Introduction to
    Matrices](https://www.khanacademy.org/math/algebra/algebra-matrices/Basic_matrix_operations/v/introduction-to-the-matrix)”
    (YouTube) and “[Matrices to Solve Systems of
    Equations](http://www.khanacademy.org/video/matrices-to-solve-a-system-of-equations?playlist=LinearAlgebra)”
    (YouTube)  
        
     Also available in:  
     [iTunes
    U](http://deimos3.apple.com/WebObjects/Core.woa/Browse/khanacademy.org-dz.4627308977?i=1836306754)
    (Introduction to Matrices)  
     [iTunes
    U](http://itunes.apple.com/us/podcast/matrices-to-solve-system-equations/id391035777?i=86817812)
    (Matrices to Solve Systems of Equations)  
        
     Instructions: Please watch these videos to familiarize yourself
    with matrices and to take a look at some examples.   
      
     Watching these videos should take approximately 30 minutes.  
      
     Terms of Use: These videos are licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 United States
    License](http://creativecommons.org/licenses/by-nc-nd/3.0/).  They
    are attributed to the Khan Academy.

**1.2.4 Transfer Functions** <span id="1.2.4"></span> 
-   **Reading: University of Wisconsin-Madison: Dr. Duffie’s “Lecture
    06: Transfer Functions”**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**1.3 Dynamic System Order and Types** <span id="1.3"></span> 
*Note: The order of a dynamic system is governed by the order of the
differential equation representing the dynamic system.  Higher-order
differential equations are more complex to solve; hence, one should use
computational tools like SCILAB to solve them.*

**1.3.1 First-Order Dynamic Systems** <span id="1.3.1"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “First Order System
    Descriptions”**
    Link: Bucknell University: Dr. Mastascusa’s “[First Order System
    Descriptions](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/StudyGuides/UsefulInfo/1stOrderTF.htm)”
    (HTML)  
        
     Instructions: Please click the link and read the section titled
    “First Order System Descriptions.”    
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.3.2 Second-Order Dynamic Systems** <span id="1.3.2"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “An Introduction to
    Dynamics—Second Order System”**
    Link Bucknell University: Dr. Mastascusa’s “[An Introduction to
    Dynamics—Second Order
    System](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/SysDyn/SysDyn2.html#Introduction)”
    (HTML)  
        
     Instructions:  Please click and read the entire webpage.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.4 Characteristics of Second-Order Dynamic Systems** <span
id="1.4"></span> 
**1.4.1 Impulse Response** <span id="1.4.1"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “An Introduction to
    System Dynamics—Second Order Systems: Impulse Response”**
    Link: Bucknell University: Dr. Mastascusa’s “[An Introduction to
    System Dynamics—Second Order Systems: Impulse
    Response](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/SysDyn/SysDyn2.html#ImpulseResponse)”
    (HTML)  
        
     Instructions: Please click the link and read the section titled
    “Impulse Response.”    
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.4.2 Overshoot vs. Damping Ratio** <span id="1.4.2"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “An Introduction to
    System Dynamics—Second Order Systems: Overshoot in Second Order
    Systems”**
    Link: Bucknell University: Dr. Mastascusa’s “[An Introduction to
    System Dynamics—Second Order Systems: Overshoot in Second Order
    Systems](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/SysDyn/SysDyn2.html#OvershootvsDampingRatio)”
    (HTML)  
        
     Instructions: Please click the link and read the section titled
    “Overshoot in Second Order Systems.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.4.3 Step Response** <span id="1.4.3"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “An Introduction to
    System Dynamics—Second Order Systems: Step Response of Second Order
    Systems”**
    Link: Bucknell University: Dr. Mastascusa’s “[An Introduction to
    System Dynamics—Second Order Systems: Step Response of Second Order
    Systems](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/SysDyn/SysDyn2.html#StepResponse)”
    (HTML)  
        
     Instructions: Please click the link and read the section titled
    “Step Response in Second Order Systems.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.4.4 Pole Location** <span id="1.4.4"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “System
    Dynamics—The Effect of Pole Location on Response”**
    Link: Bucknell University: Dr. Mastascusa’s “[System Dynamics—The
    Effect of Pole Location on
    Response](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/SysDyn/SysDyn2PoleLocation.html)”
    (HTML)  
        
     Instructions: Please click the link and read the section titled
    “System Dynamics—The Effect of Pole Location on Response.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.  
      


