**Unit 4: SCILAB Applications in Dynamic Systems and Control** <span
id="4"></span> 
**Now that you are familiar with the theory behind modeling, analyzing,
and optimizing dynamic systems, you will learn to simplify the process
using a computational tool known as SCILAB.  You have used SCILAB in
ME101.  This tool will not only save time but also help us achieve
accurate results.  Much of controller design involves complex
mathematical calculations that can be handled through mathematical
computation tools like SCILAB, MATLAB, MathCAD, and Maple.  MATLAB users
who are not familiar with SCILAB can used a tool in SCILA,B which
converts MATLAB codes to SCILAB codes.  In this unit, you will learn how
to use SCILAB to convert systems from one mathematical form to another
using simple commands.  You will also learn to use the SCILAB scripting
tool to analyze these systems.  We will conclude by discussing design
controller parameters and using SCILAB to examine whether these control
actions generate desired responses.**

**Unit 4 Time Advisory**  
This unit should take you 18 hours to complete.

☐    Subunit 4.1: 3 hours

☐    Subunit 4.2: 2 hours

☐    Subunit 4.2.1: 0.5 hour

☐    Subunit 4.2.2: 0.5 hour

☐    Subunit 4.2.3: 0.5 hour

☐    Subunit 4.2.4: 0.5 hour

☐    Subunit 4.3: 4 hours

☐    Subunit 4.3.1: 1 hour

☐    Subunit 4.3.2: 1 hour

☐    Subunit 4.3.3: 1 hour

☐    Subunit 4.3.4: 1 hour

☐    Subunit 4.4: 2.5 hours

☐    Subunit 4.4.1: 0.5 hour

☐    Subunit 4.4.2: 0.5 hour

☐    Subunit 4.4.3: 0.5 hour

☐    Subunit 4.4.4: 0.5 hour

☐    Subunit 4.4.5: 0.5 hour

☐    Subunit 4.5: 4 hours

☐    Subunit 4.5.1: 1 hour

☐    Subunit 4.5.2: 1 hour

☐    Subunit 4.5.3: 1 hour

☐    Subunit 4.5.4: 1 hour

☐    Subunit 4.6: 2.5 hours

**Unit4 Learning Outcomes**  
Upon successful completion of this unit, students will be able to:

-   Migrate from MATLAB to SCILAB.
-   Analyze first- and second-order systems using SCILAB.
-   Generate response and analyze response results using SCILAB.
-   Identify and design controllers using SCILAB.
-   Solve controller design through an example using SCILAB.

**4.1 SCILAB versus MATLAB Review** <span id="4.1"></span> 
**Note: SCILAB review is optional.  The review will cover a tool in
SCILAB that converts MATLAB codes to SCILAB codes.  If you already know
SCILAB, go to section 4.2.  **

-   **Reading: Utah State University: Gilberto Urroz’s “SCILAB Notes and
    Functions: MATLAB and SCILAB”**
    Link: Utah State University: Gilberto Urroz’s “[SCILAB Notes and
    Functions: MATLAB and SCILAB
    Comparisons](http://www.neng.usu.edu/cee/faculty/gurro/Software_Calculators/Scilab_Docs/SCILAB_Notes&Functions.htm)”
    (PDF)  
        
     Instructions: Please click on and read the PDF titled “MATLAB and
    SCILAB Comparisons.”  The information will help current MATLAB users
    migrate easily to SCILAB.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.2 First-Order System Analysis Using SCILAB** <span id="4.2"></span> 
**4.2.1 First-Order System in SCILAB** <span id="4.2.1"></span> 
-   **Reading: Indian Institute of Technology: Dr. Aditya Sengupta’s
    “Control Systems with SCILAB: A Simple First Order System”**
    Link: Indian Institute of Technology: Dr. Aditya Sengupta’s
    “[Control Systems with SCILAB: A Simple First Order
    System](http://scilab.in/FrCRITMumbai)” (PDF)  
                  
     Instructions: Please click the link and open the PDF file titled
    “Control Systems with SCILAB.”  Please read slide 2, titled “A
    Simple First Order System.”  In this slideshow, Dr. Sengupta
    explains how to create first-order systems in SCILAB.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.2.2 Simulating the system** <span id="4.2.2"></span> 
-   **Reading: Indian Institute of Technology: Dr. Sengupta’s “Control
    Systems with SCILAB: Simulating the System”**
    Link: Indian Institute of Technology: Dr. Sengupta’s “[Control
    Systems with SCILAB: Simulating the
    System](http://scilab.in/FrCRITMumbai)” (PDF)  
                  
     Instructions: Please click the link and open the PDF file titled
    “Control Systems with SCILAB.” Read slides 3 through 5, titled
    “Simulating the System.”   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.2.3 Root Locus of Simple Systems using SCILAB** <span
id="4.2.3"></span> 
-   **Reading: Indian Institute of Technology: Dr. Sengupta’s “Control
    Systems with SCILAB: Root Locus”**
    Link: Indian Institute of Technology: Dr. Sengupta’s “[Control
    Systems with SCILAB: Root Locus](http://scilab.in/FrCRITMumbai)”
    (PDF)  
                  
     Instructions: Please click the link and open the PDF file titled
    “Control Systems with SCILAB.”  Please read slide 6, titled “Root
    Locus.”  In this slideshow, Dr. Sengupta demonstrates how to
    generate the root locus for first-order systems in SCILAB.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.2.4 Bode Plot of Simple Systems using SCILAB** <span
id="4.2.4"></span> 
-   **Reading: Indian Institute of Technology: Dr. Sengupta’s “Control
    Systems with SCILAB: Bode Plot”**
    Link: Indian Institute of Technology: Dr. Sengupta’s “[Control
    Systems with SCILAB: Bode Plot](http://scilab.in/FrCRITMumbai)”
    (PDF)  
                  
     Instructions: Please click the link and open the PDF file titled
    “Control Systems with SCILAB.”  Please read slide 7 titled, “Bode
    Plot” for Dr. Sengupta’s explanation of how to generate a Bode plot
    for first-order systems in SCILAB.     
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.3 Second Order System Analysis using SCILAB** <span
id="4.3"></span> 
**4.3.1 Second Order Overdamped Systems in SCILAB** <span
id="4.3.1"></span> 
-   **Reading: Indian Institute of Technology: Dr. Sengupta’s “Control
    Systems with SCILAB: Second Order Systems—Overdamped”**
    Link: Indian Institute of Technology: Dr. Sengupta’s “[Control
    Systems with SCILAB: Second Order
    Systems—Overdamped](http://scilab.in/FrCRITMumbai)” (PDF)  
                  
     Instructions: Please click the link and open the PDF file titled
    “Control Systems with SCILAB.”  Read slides 8 through 11, titled
    “Second Order Systems—Overdamped.”    
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.3.2 Second-Order Underdamped Systems in SCILAB** <span
id="4.3.2"></span> 
-   **Reading: Indian Institute of Technology: Dr. Sengupta’s “Control
    Systems with SCILAB: Second Order Systems—Underdamped”**
    Link: Indian Institute of Technology: Dr. Sengupta’s “[Control
    Systems with SCILAB: Second Order
    Systems—Underdamped](http://scilab.in/FrCRITMumbai)” (PDF)  
                  
     Instructions: Please click the link and open the PDF file titled
    “Control Systems with Scilab.”  Please read slides 12 through 13,
    titled “Second Order Systems—Underdamped.”    
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.3.3 Second-Order Undamped Systems in SCILAB** <span
id="4.3.3"></span> 
-   **Reading: Indian Institute of Technology: Dr. Sengupta’s “Control
    Systems with SCILAB: Second Order Systems—Undamped”**
    Link: Indian Institute of Technology: Dr. Sengupta’s “[Control
    System with SCILAB: Second Order
    Systems—Undamped](http://scilab.in/FrCRITMumbai)” (PDF)  
                  
     Instructions: Please click the link and open the PDF file titled
    “Control Systems with SCILAB.”  Please read slides 14 through 15,
    titled “Second Order Systems—Undamped.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.3.4 Second-Order Critically Damped Systems in SCILAB** <span
id="4.3.4"></span> 
-   **Reading: Indian Institute of Technology: Dr. Sengupta’s “Control
    Systems with SCILAB: Second Order Systems—Critically Damped”
    Presentation.**
    Link: Indian Institute of Technology: Dr. Sengupta’s “[Control
    Systems with SCILAB: Second Order Systems—Critically
    Damped](http://scilab.in/FrCRITMumbai)” (PDF)  
                  
     Instructions: Please click the link and open the PDF file titled
    “Control Systems with SCILAB.”  Please read slides 16 through 17,
    titled “Second Order Systems—Critically Damped.”   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.4 Response and Analysis of Systems using SCILAB** <span
id="4.4"></span> 
**4.4.1 State Space Representation of Systems in SCILAB** <span
id="4.4.1"></span> 
-   **Reading: Indian Institute of Technology: Dr. Sengupta’s “Control
    Systems with SCILAB: State Space—Representation”**
    Link: Indian Institute of Technology: Dr. Sengupta’s “[Control
    Systems with SCILAB: State
    Space—Representation](http://scilab.in/FrCRITMumbai)” (PDF)  
                  
     Instructions: Please click the link and open the PDF file titled
    “Control Systems with SCILAB.”  Please read slide 22, titled “State
    Space—Representation.”     
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.4.2 State Space Simulation of Systems in SCILAB** <span
id="4.4.2"></span> 
-   **Reading: Indian Institute of Technology: Dr. Sengupta’s “Control
    Systems with SCILAB: State Space—Simulation”**
    Link: Indian Institute of Technology: Dr. Sengupta’s “[Control
    Systems with SCILAB: State
    Space—Simulation](http://scilab.in/FrCRITMumbai)” (PDF)  
                  
     Instructions: Please click the link and open the PDF file titled
    “Control Systems with SCILAB.”  Please read slides 23 through 25,
    titled “State Space—Simulation.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.4.3 Nyquist Plot of Systems in SCILAB** <span id="4.4.3"></span> 
-   **Reading: Indian Institute of Technology: Dr. Sengupta’s “Control
    Systems with SCILAB: Nyquist Plot”**
    Link: Indian Institute of Technology: Dr. Sengupta’s “[Control
    Systems with SCILAB: Nyquist Plot](http://scilab.in/FrCRITMumbai)”
    (PDF)  
                  
     Instructions: Please click the link and open the PDF file titled
    “Control Systems with SCILAB.”  Please read slide 32, titled
    “Nyquist Plot.”   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.4.4 Steady State Error of Systems in SCILAB** <span
id="4.4.4"></span> 
-   **Reading: Indian Institute of Technology: Dr. Sengupta’s “Control
    Systems with SCILAB: Steady State Error”**
    Link: Indian Institute of Technology: Dr. Sengupta’s “[Control
    Systems with SCILAB: Steady State
    Error](http://scilab.in/FrCRITMumbai)” (PDF)  
                  
     Instructions: Please click the link and open the PDF file titled
    “Control Systems with SCILAB.”  Please read slides 41 through 42,
    titled “Steady State Error.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.4.5 Root Locus of Systems in SCILAB** <span id="4.4.5"></span> 
-   **Reading: Indian Institute of Technology: Dr. Sengupta’s “Control
    Systems with SCILAB: Root Locus”**
    Link: Indian Institute of Technology: Dr. Sengupta’s “[Control
    Systems with SCILAB: Root Locus](http://scilab.in/FrCRITMumbai)”
    (PDF)  
                  
     Instructions: Please click the link and open up the PDF file titled
    “Control Systems with SCILAB.”  Please read slides 43 through 46,
    titled “Root Locus.”   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.5 Controller Design and Analysis Using SCILAB** <span
id="4.5"></span> 
**4.5.1 Proportional Controller in SCILAB** <span id="4.5.1"></span> 
-   **Reading: Indian Institute of Technology: Dr. Sengupta’s “Control
    Systems with SCILAB: A Proportional Controller”**
    Link: Indian Institute of Technology: Dr. Sengupta’s “[Control
    Systems with SCILAB: A Proportional
    Controller](http://scilab.in/FrCRITMumbai)” (PDF)  
                  
     Instructions: Please click the link and open the PDF file titled
    “Control Systems with SCILAB.”  Please read slides 48 through 53,
    titled “A Proportional Controller.”   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.5.2 Proportional Integral (PI) Controller in SCILAB** <span
id="4.5.2"></span> 
-   **Reading: Indian Institute of Technology: Dr. Sengupta’s “Control
    Systems with SCILAB: A PI Controller”**
    Link: Indian Institute of Technology: Dr. Sengupta’s “[Control
    Systems with SCILAB: A PI
    Controller](http://scilab.in/FrCRITMumbai)” (PDF)  
                  
     Instructions: Please click the link and open up the PDF file titled
    “Control Systems with SCILAB.”  Please read slides 55 through 58,
    titled “A PIController.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.5.3 Proportional Derivative (PD) Controller in SCILAB** <span
id="4.5.3"></span> 
-   **Reading: Indian Institute of Technology: Dr. Sengupta’s “Control
    Systems with SCILAB: A PD Controller”**
    Link: Indian Institute of Technology: Dr. Sengupta’s “[Control
    Systems with SCILAB: A PD
    Controller](http://scilab.in/FrCRITMumbai)” (PDF)  
                  
     Instructions: Please click the link and open the PDF file titled
    “Control Systems with SCILAB.”  Please read slides 58 through 61,
    titled “A PDController.”   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.5.4 Proportional Integral Derivative (PID) Controller in SCILAB**
<span id="4.5.4"></span> 
-   **Reading: Indian Institute of Technology: Dr. Sengupta’s “Control
    Systems with SCILAB: A PID Controller”**
    Link: Indian Institute of Technology: Dr. Sengupta’s “[Control
    Systems with SCILAB: A PID
    Controller](http://scilab.in/FrCRITMumbai)” (PDF)  
                  
     Instructions: Please click the link and open the PDF file titled
    “Control Systems with SCILAB.”  Please read slides 62 through 64,
    titled “A PIDController.”   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.6 Example of System Dynamics and Control using SCILAB** <span
id="4.6"></span> 
-   **Reading: Indian Institute of Technology: Dr. Sengupta’s “Control
    Systems with SCILAB: An Example”**
    Link: Indian Institute of Technology: Dr. Sengupta’s “[Control
    Systems with SCILAB: An Example](http://scilab.in/FrCRITMumbai)”
    (PDF)  
        
     Instructions: Please click the link and open the PDF file titled
    “Control Systems with SCILAB.”  Please read slides 33 through 40,
    titled “An Example.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.


