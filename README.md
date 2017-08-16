# ECO 5375 - Forecasting (Fall 2017)
Forecasting Course at Southern Methodist University

# General Information 

There will be two mid-term exams, a double-point homework assignment due in lieu of a final exam, homework assignments, and class attendance. The weights of each of these items are as follows: mid-term exams (30% each), homework assignments (30%), and class attendance (10%). I will be assigning a maximum of 10 points for class attendance - 10 points for no unexcused absences, 8 points for 1 or 2 absences, and 6 points for more than 2 absences. After 4 or more absences in class attendance, I reserve the right to administratively drop the student from the class. My policy is to drop the lowest homework score you have before forming a homework average to be used in calculating your overall average in the class. The empirical project due in lieu of a final exam will be a double-point (20 points) assignment that will be included in the homework part of your grading scale. (The usual homework problems are valued at 10 points each.) Finally, you must obtain a doctor's letter if you are to be excused from any exams or homework assignments due to illness.

# Textbook for the Course

I am going to be relying more on classroom presentations and pdf handouts to teach this course than on any one textbook. I have not found any textbook that closely enough matches the topics that I think are important for this course. However, there is a nice open source (free) book that can serve as a useful supplementary textbook for this course. It is Forecasting Principles and Practice (FPP) by Rob. J. Hyndman and George Athanasopoulos. You can find it at the website https://www.otexts.org/fpp. In particular, if you are interested in learning some R programming language you should run some of the R programs that are detailed in the FPP book.

__Some other sources:__

* @cryer/chan:2008
* @diebold:2007
* @hyndman/athanasopoulos:2017


# Important Dates to Remember

* First Day of Class: ~~Tuesday, August 23~~. <span style="color:red">Monday, August 28</style>
* Labor Day Holiday: Monday, September 4
* Fall Break: Monday - Tuesday, October 10-11
* Last Day to Drop a Class: Friday, November 3
* No Classes on Wednesday, November 23
* Thanksgiving Break: Thursday - Friday, November 23-24
* Last Day of Class: Tuesday, December 1
* When double-point homework assignment is due (in lieu of final exam): Monday, December 4 by 5:00 pm. Assignment can be turned in at my office or to my mailbox in the 301 Office Suite in Umphrey Lee Building.

# Grading 

__My grading scale__ in this course is as follows:

* A: 92-100; 
* A-: 90-91; 
* B+: 88-89; 
* B: 82-87; 
* B-: 80-81; 
* C+: 78-79; 
* C: 72-77; 
* C-: 70-71; 
* D+: 68-69; 
* D: 62-67; 
* D-: 60-61; 
* F: 0-59.


With respect to homework exercises, students can confer with each other with respect to programming advice and discussion of basic ideas but in the final analysis each student is expected to write up his/her own homework answers and not make copies of others' homework. Copying someone else's homework to hand in as one's own work is a violation of the SMU Honor Code and will be dealt with according to the rules of the SMU Honor Code. It is important to know that the homework assignments are very important in that the basic ideas covered by them invariably show up on the mid-term and final exams. If you know you are going to be missing a class on the day a homework exercise is due, hand in your homework __in advance__ to receive full credit for your work.

Any homework that is handed in late will be given a one letter grade reduction for each day of tardiness. It is my policy to drop your lowest exercise score before calculating your exercise average.

Students will be excused from taking the mid-term exam or the final exam only with a note from a physician, or in the case of a death in the family, with a note from a parent or guardian. Even with an excused absence, either of these exams must eventually be taken before a course grade will be assigned to the student.

If you must miss a class due to legitimate circumstances beyond your control, be sure and contact me __beforehand__ so that I will know of your circumstances. If excused, I will correspondingly excuse you from any QQ that is given that day. I want to emphasize that diligent attendance in this course is essential because a lot of the course material presented in class will be from my personal class notes and can't be found in any textbook per se. __Note:__ After 4 unexcused class absences, I reserve the right to administratively drop students from the class.

# Topics

1. [Introduction to Course](L01.html)
	A.  Focus of this Course: Time Series Forecasting
	B.  Field of Forecasting is meeting the Market Test
	C.  Definitions of Time Series, Point Forecasts, and Prediction Interval Forecasts
	D.  Evaluation of Competing Forecasting Accuracy
		i. Forecasting Accuracy Measures
		ii. Naïve Forecasting Methods as Benchmarks
	E.  Example: The Plano City Manager Planning Problem  
	
+ __Reference:__ Class Notes, SAS programs, and Chapters 1 and 2, FPP.  

2. [A Brief Introduction to SAS](L02.html)
	A.  APPS.SMU and Accessing Computer Programs on SMU's Virtual Server - Downloading Citrix Receiver
	B.  Introduction to SAS (SAS = Statistical Analysis System)
		i. Program Editor in SAS 9.4
		ii. Data Steps and Procedure Steps
		iii. Log and Listing Files
	C.  Inputting Data
		i. Direct Input
		ii. Infile Statement  
		
+ __References:__ Class Notes  
	
3. [Salient Characteristics of Time Series Data](L03.html)
	A.  Trend, Seasonal, Cycle, Irregular Components
	B.  Y = T + S + C + I (Additive Decomposition)
	C.  log(Y) = T + S + C + I (Multiplicative Decomposition)
	D.  A Stylized Decomposition of a Time Series
	E.  Importance of knowing which components are in your time series  
	
+ __References:__ Class notes, SAS programs, and Chapter 6, FPP  
	
4. [Brief Interlude on the Detection of Seasonality, Trend, and Cycle](L04.html)
	A.  Trend Tests: Hirsch, et. al. Non-parametric test, HAC Non-Parametric Tests of Mean of Differences and Time Trend tests
	B.  Seasonality Tests: Buys-Ballot Plots, Friedman's Non-parametric test, and F-Test in DTDS model
	C.  Cycle: The Autocorrelation Function and Box-Pierce-Ljung Portmonteau Test
	D.  Example: Plano Sales Tax Revenue Data
	
+ __References:__ Class notes and SAS programs
	
5. [A Beginning Time Series Model: The Stable Seasonal Pattern Model](L05.html)
	A.  Determination of Seasonal Proportions
	B.  Test of Equal Proportions
	C.  Estimation of Trend
	D.  Example: Plano Sales Tax Revenue Data  
	
+ __References:__ Class Notes  
	
6. [A First Generation Forecasting Model - The Deterministic Trend/Deterministic Seasonal (DTDS) Model](L06.html)
	A.  The Simple Trend Model - A Deterministic Trend
	B.  Trend Model with Seasonal Dummies
	C.  DTDS plus Autocorrelated Errors
	D.  Example: Plano Sales Tax Revenue Data
	E.  Tests for Trend and Seasonality - F-tests  
	
+ __References:__ Class Notes, SAS programs, and Chapter 5, FPP  

7. [A Sophisticated Time Series Decomposition Model: The Unobserved Components Model](L07.html) <!-- #  (Proc UCM in SAS) -->
	A.  Three Unobservable Components
        i. Trend  
        ii. Seasonal  
        iii. Cycle
	B.  Test of the Significance of the Components
	C.  Example: Airline Passenger Data
	D.  Forecasting the Airline Passenger Data
	
+ __References:__ Class Notes and SAS programs
	
8. [Some Important Concepts Leading up to Box-Jenkins Modeling](L08.html)
    A.  Mean, Variance, and Autocorrelation in Time Series
    B.  Definition of Covariance Stationarity
    C.  Example of a Stationary Time Series: the AR(1) model
        i. AR(1) Time Series Model  
        ii. Mean, Variance, Autocovariance, and Autocorrelation  
        iii. The Special Case of $\phi$ = 1. The Random Walk model  
        iv. The Random Walk Model in not Stationary  
        v. Differing Prediction Profiles for the two cases: Do Stock Prices follow a Random Walk?    
        
+ __References:__ Class Notes, SAS program RW_IBM_data.sas, and Chapter 8, FPP  
  
9. [Box Jenkins Models for Stationary, Non-Seasonal Time Series](L09.html)
    A.  Some Simple Box-Jenkins Models and Their Properties  
        i. ARMA(0,0) 
        ii. MA(1) 
        iii. AR(1) 
        iv. ARMA(1,1) 
        v. General Notation 
        vi. Concepts of Stationarity and Invertibility 
	B.  Identification Tools  
        i. Autocorrelation Function (ACF)  
        ii. Partial Autocorrelation Function (PACF)  
	C.  Pattern Table  
	D.  Sample Counterparts  
	E.  Information Criteria  
	F.  P/Q Box  
	G.  Overfitting Exercises  
	H.  Example: Lead Production Data 
	
+ __References:__ Class Notes, SAS programs, and Chapter 8, FPP
	
10. [Box-Jenkins Models - Forecasting for Stationary, Non-Seasonal Time Series](L10.html)
	A.  Minimum MSE Forecasting
	B.  Various Forecast Profiles
	C.  Example: The Forecast Profile and Confidence Intervals for the Lead Production Data

+ __References:__ Class Notes, SAS programs, and Chapter 8, FPP
	
11. [Box-Jenkins Models for Non-Seasonal, Stochastically-Trending Time Series](L11.html)
    A.  Taking the First Difference to Control for Stochastic Trends 
    B.  Taking, On Occasion, Second Differences of the Data 
    C.  Augmented Dickey-Fuller Tests for Unit Roots: To Difference or Not To Difference? 
    D.  Example: The Dow Jones Index 
    E.  Forecasting Levels Based on Forecasts of Differences 
    F.  The Log Transformation and how to use it 
	
+ __References:__ Class Notes, RW_Data_and_Differencing.sas, other SAS programs, and Chapter 8, FPP
	
12. [Box-Jenkins Models for Seasonal, Stochastically-Trending Time Series](L12.html)
	A.  Year-over-Year Differencing
	B.  Year-over-Year Differencing Combined with First Differencing
	C.  The Multiplicative Class of Box-Jenkins Models
	D.  The ACFs and PACFs of Multiplicative Seasonal Models
	E.  Examples: Airline Passenger Data and Electricity Production Data
	F.  Testing for Seasonal Differencing  
	
+ __References:__ Class Notes, SAS Programs, and Chapter 8, FPP  
	
13. [Exponential Smoothing - An Old Favorite](L13.html) <!-- # (Proc ESM) -->
	A.  Simple Exponential Smoothing (No Trend, No Seasonality)
	B.  Double (Brown) Exponential Smoothing (Trend, No Seasonality)
	C.  Additive Seasonal Exponential Smoothing (No Trend, Seasonality)
	D.  Winters Additive Method (Trend, Seasonality)
	E.  Plano Sales Tax Revenue Data - An experiment showing the importance of
Determining the presence or absence of trend in your time series data  

+ __References:__ Class Notes, SAS programs, and Chapter 7, FPP  
	
14. [Searching for an Extra Variable to Help Us Forecast: VARs](L14.html) <!-- # (Proc VARMAX) -->
	A.  Be careful: The Spurious Regression Problem
	B.  The Transfer Function Model
	C.  The Equal-Lag Length Vector Autoregressive Model
	D.  System-Wide Goodness of Fit Measures to Help Choose the Lag-Length
	E.  Using Out-of-Sample Forecasting Experiments to Detect Useful "Extra" Variables for use in Forecasting a Variable of Interest
	F.  Diebold-Mariano Test for Significant Differences in Forecasting Accuracies
	G.  Example: The "Series M" Data Set  
	
+ __References:__ Class Notes, SAS programs, and Chapter 9, FPP  
	
15. [Combining Forecasts](L15.html)
	A.  Combination Forecasting
		i. Some Basic Theorems on Diversification of Forecasts
		ii. Nelson Combination Method
		iii. Granger-Ramanathan Combination Method
		iv. Combinations with Time-Varying Weights
	B.  Application to Economic Time Series
	
+ __References:__ Class Notes and SAS programs

# Lecture Schedule

* [Aug 21, 2017](S01.html): ~~Review of Course Outline and Focus of Course~~
* [Aug 23, 2017](S01.html): ~~Some Basic Concepts, Apps.smu, and Introduction to SAS~~
* [Aug 28, 2017](S01.html): Some Practice with SAS programming
* [Aug 30, 2017](S01.html): Salient Characteristics of Time Series Data
* [Sep  4, 2017](S01.html): Detection of Seasonality, Trend, and Cycle in Time Series Data
* [Sep  6, 2017](S01.html): Detection of Seasonality, Trend, and Cycle in Time Series Data continued.
* [Sep 11, 2017](S01.html): The Stable Seasonal Pattern Model
* [Sep 13, 2017](S01.html): The Stable Seasonal Pattern Model continued.
* [Sep 18, 2017](S01.html): Deterministic Trend/Deterministic Season Model
* [Sep 20, 2017](S01.html): Deterministic Trend/Deterministic Season Model continued.
* [Sep 25, 2017](S01.html): Unobserved Components Model
* [Sep 27, 2017](S01.html): Unobserved Components Model continued.
* [Oct  2, 2017](S01.html): _Review for Mid-term I exam_
* [Oct  4, 2017](S01.html): __Mid-term I exam__
* [Oct  9, 2017](S01.html): Fall Break
* [Oct 11, 2017](S01.html): Important Concepts Leading up to Box-Jenkins Modeling
* [Oct 16, 2017](S01.html): Important Concepts Leading up to Box-Jenkins Modeling continued.
* [Oct 18, 2017](S01.html): Box-Jenkins Modeling
* [Oct 23, 2017](S01.html): Box-Jenkins Modeling continued.
* [Oct 25, 2017](S01.html): Box-Jenkins Modeling continued.
* [Oct 30, 2017](S01.html): Box-Jenkins Modeling continued.
* [Nov  1, 2017](S01.html): Box-Jenkins Modeling continued.
* [Nov  6, 2017](S01.html): Exponential Smoothing
* [Nov  8, 2017](S01.html): Searching for an Extra Variable to Help us Forecast
* [Nov 13, 2017](S01.html): Searching for an Extra Variable to Help us Forecast continued.
* [Nov 15, 2017](S01.html): Searching for an Extra Variable to Help us Forecast continued.
* [Nov 20, 2017](S01.html): Combination Forecasting
* [Nov 27, 2017](S01.html): _Review for Mid-term II exam_
* [Nov 29, 2017](S01.html): __Mid-term II exam__
* Double-Point Homework in lieu of final exam due at 5, 2017:00 pm on Monday, December 4 in my office or mailbox.

# References
