---
layout: default
title: "ME401: Dynamic Systems & Controls"
course_description: "An exploration of the behavior of physical systems as well as the physics of individual components and the interactions between them. Topics include modeling dynamic systems, Laplace Transform Methods for Solving Differential Equations, transfer functions, stability, feedback, proportional—integral—derivative controllers, and applications of computer simulation in control."
next: ../Unit03
previous: ../Unit01
---
**Unit 2: Analysis of Dynamic Systems** <span id="2"></span> 
**Unit Two builds on the material covered in Unit One by asking you to
analyze dynamic systems with respect to their responses to various input
signals.  Systems can be subjected to constant or varying inputs. 
Therefore, an understanding of how these systems react to various inputs
is crucial to designing the appropriate controllers.  The characteristic
equations of dynamic systems convey significant information regarding
the system’s poles and zeros.  The response of a dynamic system in time
and frequency domain is used to determine whether a system is stable,
marginally stable, or unstable.  Once the system is analyzed for
stability, appropriate controllers can be designed for the desired
response.**

**Unit 2 Time Advisory**  
This unit should take you 30 hours to complete.

☐    Subunit 2.1: 6 hours

☐    Subunit 2.1.1: 3 hours

☐    Subunit 2.1.2: 1 hour

☐    Subunit 2.1.3: 2 hours

☐    Subunit 2.2: 11 hours

☐    Subunit 2.2.1: 1 hour

☐    Subunit 2.2.2: 1.5 hours

☐    Subunit 2.2.3: 1.5 hours

☐    Subunit 2.2.4: 1.5 hours

☐    Subunit 2.2.5: 1 hour

☐    Subunit 2.2.6: 2.5 hours

☐    Subunit 2.2.7: 2 hours

☐    Subunit 2.3: 12 hours

☐    Subunit 2.3.1: 1.5 hours

☐    Subunit 2.3.2: 1.5 hours

☐    Subunit 2.3.3: 2 hours

☐    Subunit 2.3.4: 1.5 hours

☐    Subunit 2.3.5: 1.5 hours

☐    Subunit 2.3.6: 1.5 hours

☐    Subunit 2.3.7: 1.5 hours

☐    Subunit 2.3.8: 1 hour

**Unit2 Learning Outcomes**  
Upon successful completion of this unit, students will be able to:

-   Analyze dynamic systems in time-domain.
-   Analyze dynamic systems in frequency-domain.
-   Identify stability of dynamic systems for controller design.

**2.1 Analysis and Response of Dynamic Systems in Time-Domain** <span
id="2.1"></span> 
**2.1.1 Response of Systems** <span id="2.1.1"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “An Introduction to
    System Dynamics—Second Order Systems: A Note on System Responses”**
    Link: Bucknell University: Dr. Mastascusa’s “[An Introduction to
    System Dynamics—Second Order Systems: A Note on System
    Responses](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/SysDyn/SysDyn2.html)”
    (HTML)  
        
     Instructions: Please click the link, scroll down, and read the
    section titled “A Note on System Responses.”     
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.1.2 Steady State Error (SSE)** <span id="2.1.2"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “Steady State Error
    in Control Systems: Control System Design: What is SSE?”**
    Link: Bucknell University: Dr. Mastascusa’s “[Steady State Error in
    Control Systems: Control System Design: What is
    SSE?](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/Design/Perf1SSE.htm#What)”
    (HTML)  
      
     Instructions: Please click the link, scroll down, and read the
    section titled “What is SSE.”     
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.1.3 Root-Locus** <span id="2.1.3"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “An Introduction to
    the Root Locus Techniques”**
    Link: Bucknell University: Dr. Mastascusa’s “[An Introduction to the
    Root Locus
    Techniques](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/RootLocus/RLocus1A.html)”
    (HTML)  
        
     Instructions: Please click the link and read this entire
    webpage.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.2 Analysis and Response of Dynamic Systems in Frequency-Domain**
<span id="2.2"></span> 
**2.2.1 Bode Plots** <span id="2.2.1"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “Bode Plots: Why
    Bode Plots?” and “Bode Plots: What are Bode Plots?”**
    Link: Bucknell University: Dr. Mastascusa’s “[Bode Plots: Why Bode
    Plots?](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/Freq/Freq5.html#Why)”
    (HTML) and “[Bode Plots: What Are Bode
    Plots?](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/Freq/Freq5.html#What)”
    (HTML)  
      
     Instructions: Please click the link and read the sections titled,
    "Why Bode Plots?" and "What are Bode Plots?"  
      
     Please note that Bode's name, which is of Dutch origin, is
    occasionally written with an accent at the end: Bode'.  The name is
    pronounced *Boh-dee* in English.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.2.2 Bode Plot of First-Order Systems** <span id="2.2.2"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “Bode Plots: Bode
    Plots for First Order Systems”**
    Link: Bucknell University: Dr. Mastascusa’s “[Bode Plots: Bode Plots
    for First Order
    Systems](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/Freq/Freq5.html)”
    (HTML)  
        
     Instructions: Please click the link and read the section titled
    “Bode Plots for First Order Systems.” In this reading, Dr.
    Mastascusa introduces the concept of using Bode plots to analyze the
    frequency response of first-order dynamic systems.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.  
      

**2.2.3 Concept of Decibels** <span id="2.2.3"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “Bode Plots:
    Decibels and More”**
    Link: Bucknell University: Dr. Mastascusa’s “[Bode Plots: Decibels
    and
    More](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/Freq/Freq5.html)”
    (HTML)  
        
     Instructions: Please click the link, scroll down, and read the
    section titled “Decibels and More.”  In this reading, Dr. Mastascusa
    introduces you to the concept of decibels and how decibels are used
    to analyze dynamic systems using frequency response.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.2.4 Bode Plot of Second-Order Systems** <span id="2.2.4"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “Bode Plots: Bode
    Plots for Second Order Systems”**
    Link: Bucknell University: Dr. Mastascusa’s “[Bode Plots: Bode Plots
    for Second Order
    Systems](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/Freq/Freq5.html)”
    (HTML)  
        
     Instructions: Please click the link, scroll down, and read the
    section titled “Bode Plots for Second Order Systems.”  In this
    reading, Dr. Mastascusa introduces you to Bode plots as used in
    analyzing the frequency response of second-order dynamic systems.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.2.5 Bode Plot for Large Systems** <span id="2.2.5"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “Bode Plots: Bode
    Plots for Larger Systems—Examples”**
    Link: Bucknell University: Dr. Mastascusa’s “[Bode Plots: Bode Plots
    for Larger
    Systems—Examples](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/Freq/Freq5.html#Examples)”
    (HTML)  
        
     Instructions: Please click the link and read the section titled
    “Bode Plots for Larger Systems—Examples.”  In this reading, Dr.
    Mastascusa introduces the use of Bode plots in analyzing the
    frequency response of large dynamic systems.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.2.6 Nyquist Plots** <span id="2.2.6"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “Nyquist Plots:
    What is a Nyquist Plot?”**
    Link: Bucknell University: Dr. Mastascusa’s “[Nyquist Plots: What is
    a Nyquist
    Plot](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/Freq/Freq6.html#What)?”
    (HTML)  
        
     Instructions: Please click the link and read the section titled
    “What is a Nyquist Plot?”  In this reading, Dr. Mastascusa
    introduces the use of Nyquist plots in analyzing the frequency
    response of dynamic systems.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.2.7 Gain Margin** <span id="2.2.7"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “Nyquist Stability:
    Gain Margin”**
    Link: Bucknell University: Dr. Mastascusa’s “[Nyquist Stability:
    Gain
    Margin](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/Freq/Nyquist4.html#GainMargin)”
    (HTML)  
        
     Instructions: Please click the link and read the section titled
    “Gain Margin.”  In this reading, Dr. Mastascusa introduces the
    concept of gain margin and how the concept can be used in analyzing
    dynamic systems using frequency response.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.3 Stability of Dynamic Systems** <span id="2.3"></span> 
*Note: The location of the poles and zeros and the values of phase and
gain margins have a bearing on a system’s stability.  Many researchers
and scientists have discussed various stability criteria in both time
and frequency domains.  SCILAB is a great tool for plotting and
analyzing these systems.*

**2.3.1 Relative Stability** <span id="2.3.1"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “Relative
    Stability”**
    Link: Bucknell University: Dr. Mastascusa’s “[Relative
    Stability](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/Freq/Nyquist4.html)”
    (HTML)  
        
     Instructions: Please click the link and read the entire webpage.
     In this reading, Dr. Mastascusa introduces the concept of relative
    stability and explain how it can be used to analyze systems during
    controller design.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.3.2 Bode Plots for Stability Determination** <span
id="2.3.2"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “Nyquist Stability:
    Using Bode Plots to Evaluate Stability”**
    Link: Bucknell University: Dr. Mastascusa’s “[Nyquist Stability:
    Using Bode Plots to Evaluate
    Stability](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/Freq/Nyquist3.html)”
    (HTML)  
        
     Instructions: Please click the link and read the entire webpage.
     In this reading, Dr. Mastascusa introduces Bode plots and explains
    how they are used to evaluate relative stability in order to analyze
    systems during controller design.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.3.3 Gain for Stability Using Bode Plot** <span id="2.3.3"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “Determining Gain
    Value for Stability from a Bode Plot”**
    Link: Bucknell University: Dr. Mastascusa’s “[Determining Gain Value
    for Stability from a Bode
    Plot](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/StudyGuides/UsefulInfo/NyquistGainForStabilityBode.html)”
    (HTML)  
      
     Instructions: Please click the link and read the section titled
    “Determining Gain Value for Stability from a Bode Plot.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.3.4 Phase for Stability Using Bode Plot** <span id="2.3.4"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “Relative
    Stability: Interpreting Phase and Gain Margin on a Bode Plot”**
    Link: Bucknell University: Dr. Mastascusa’s “[Relative Stability:
    Interpreting Phase and Gain Margin on a Bode
    Plot](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/Freq/Nyquist4.html#InterpretingOnBode)”
    (HTML)  
      
     Instructions: Please click the link and read the section titled
    “Interpreting Phase and Gain Margin on a Bode Plot.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.3.5 Nyquist Stability Criterion** <span id="2.3.5"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “The Nyquist
    Stability Criterion: Applying the Nyquist Stability Criterion”**
    Link: Bucknell University: Dr. Mastascusa’s “[The Nyquist Stability
    Criterion: Applying the Nyquist Stability
    Criterion](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/Freq/Nyquist2.html#Applying)”
    (HTML)  
      
     Instructions: Please click the link and read the section titled
    “Applying the Nyquist Stability Criterion.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.3.6 Gain for Stability Using Nyquist Plot** <span
id="2.3.6"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “Determining Gain
    Value for Stability from a Nyquist Plot”**
    Link: Bucknell University: Dr. Mastascusa’s “[Determining Gain Value
    for Stability from a Nyquist
    Plot](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/StudyGuides/UsefulInfo/NyquistGainForStability.htm)”
    (HTML)  
        
     Instructions: Please click the link and read this webpage.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.3.7 Phase Margin** <span id="2.3.7"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “Relative
    Stability: Phase Margin”**
    Link: Bucknell University: Dr. Mastascusa’s “[Relative Stability:
    Phase
    Margin](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/Freq/Nyquist4.html#PhaseMargin)”
    (HTML)  
        
     Instructions: Please click the link and read the section titled
    “Phase Margin.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.3.8 Effect of Poles and Zero on Stability** <span
id="2.3.8"></span> 
-   **Reading: Bucknell University: Dr. Mastascusa’s “Relative
    Stability: Gain Margin”**
    Link: Bucknell University: Dr. Mastascusa’s “[Relative Stability:
    Gain
    Margin](http://www.facstaff.bucknell.edu/mastascu/econtrolhtml/Freq/Nyquist4.html#GainMargin)”
    (HTML)  
      
     Instructions: Please click the link and open up the webpage read
    the section titled “Gain Margin.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.


