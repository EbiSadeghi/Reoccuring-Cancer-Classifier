# Reoccuring-Cancer-Classifier
Use machine learning to classify whether or not the cancer will reoccur

There are two types of algorithms here. Support Vector Machine and K-nearest neighbours.

I modified the dataset so that it would be purely comprised of numbers, no strings or ranges of numbers (i.e. 1-5) as indexes.

# Acknowledgments
Code:
This code is heavily based off of Sentdex's algorithm for classifying between benign and malignant cancer
His website has many useful tutorials, and I highly recommend them:
https://pythonprogramming.net/

Data:
Citation Request:
   This breast cancer domain was obtained from the University Medical Centre,
   Institute of Oncology, Ljubljana, Yugoslavia.  Thanks go to M. Zwitter and 
   M. Soklic for providing the data.  Please include this citation if you plan
   to use this database.

1. Title: Breast cancer data (Michalski has used this)

2. Sources: 
   -- Matjaz Zwitter & Milan Soklic (physicians)
      Institute of Oncology 
      University Medical Center
      Ljubljana, Yugoslavia
   -- Donors: Ming Tan and Jeff Schlimmer (Jeffrey.Schlimmer@a.gp.cs.cmu.edu)
   -- Date: 11 July 1988

3. Past Usage: (Several: here are some)
     -- Michalski,R.S., Mozetic,I., Hong,J., & Lavrac,N. (1986). The 
        Multi-Purpose Incremental Learning System AQ15 and its Testing 
        Application to Three Medical Domains.  In Proceedings of the 
        Fifth National Conference on Artificial Intelligence, 1041-1045,
        Philadelphia, PA: Morgan Kaufmann.
        -- accuracy range: 66%-72%
     -- Clark,P. & Niblett,T. (1987). Induction in Noisy Domains.  In 
        Progress in Machine Learning (from the Proceedings of the 2nd
        European Working Session on Learning), 11-30, Bled, 
        Yugoslavia: Sigma Press.
        -- 8 test results given: 65%-72% accuracy range
     -- Tan, M., & Eshelman, L. (1988). Using weighted networks to 
        represent classification knowledge in noisy domains.  Proceedings 
        of the Fifth International Conference on Machine Learning, 121-134,
        Ann Arbor, MI.
        -- 4 systems tested: accuracy range was 68%-73.5%
    -- Cestnik,G., Konenenko,I, & Bratko,I. (1987). Assistant-86: A
       Knowledge-Elicitation Tool for Sophisticated Users.  In I.Bratko
       & N.Lavrac (Eds.) Progress in Machine Learning, 31-45, Sigma Press.
       -- Assistant-86: 78% accuracy

4. Relevant Information:
     This is one of three domains provided by the Oncology Institute
     that has repeatedly appeared in the machine learning literature.
     (See also lymphography and primary-tumor.)

     This data set includes 201 instances of one class and 85 instances of
     another class.  The instances are described by 9 attributes, some of
     which are linear and some are nominal.

5. Number of Instances: 286

6. Number of Attributes: 9 + the class attribute

7. Attribute Information:
   1. Class: no-recurrence-events, recurrence-events
   2. age: 10-19=10, 20-29=20, 30-39=30, 40-49=40, 50-59=50, 60-69=60, 70-79=70, 80-89=80, 90-99=90.
   3. menopause: lt40=1, ge40=2, premeno=3.
   4. tumor-size: 0-4=0, 5-9=1, 10-14=2, 15-19=3, 20-24=4, 25-29=5, 30-34=6, 35-39=7, 40-44=8,
                  45-49=9, 50-54=10, 55-59=11.
   5. inv-nodes: 0-2=0, 3-5=1, 6-8=2, 9-11=3, 12-14=4, 15-17=5, 18-20=6, 21-23=7, 24-26=8,
                 27-29=9, 30-32=10, 33-35=11, 36-39=12.
   6. node-caps: yes=1, no=0.
   7. deg-malig: 1, 2, 3.
   8. breast: left=1, right=0.
   9. breast-quad: left-up=-20, left-low=-10, right-up=20,	right-low=10, central=0.
  10. irradiat:	yes=1, no=0.

8. Missing Attribute Values: (denoted by "?")
   Attribute #:  Number of instances with missing values:
   6.             8
   9.             1.

9. Class Distribution:
    1. no-recurrence-events: 201 instances
    2. recurrence-events: 85 instances
