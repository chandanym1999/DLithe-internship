# DLithe-internship
Assignment during Online Internship with Dlithe(www.dlithe.com)
                       

Project Name- MALNUTRITION ASSESSMENT

         An attempt to identify malnutrition like IUGR , MARASMUS and KWASHIORKOR using machine learning.
         
        
DATASET:
        
        Dataset named pem.csv which was created by me, contains 13 attributes(13 column) which intern helps to find out the malnutrition.
        
        The attributes are -  1.id
                              2.age_inmonths
                              3.birth_weight
                              4.appetite
                              5.edema
                              6.skin_changes
                              7.phychomotor_changes
                              8.serum_albumin_level
                              9.abdomen
                              10.organomegaly
                              11.subcutaneous_fat
                              12.present_weight
                              13.diagnosis
                   
        1.id - it just gives the serial number to the rows.
        
        2.age_inmonths - it gives the age of the patients in months.
        
        3.birth_weight - it gives the weight of the baby during birth.
        
        4.appetite - hunger for food in an individual, it can be, i)varacious - appetite more than normal.
                                                                  ii)poor - appetite below normal.
                                                                  iii)good - appetite normal.
                                                                  
        5.edema - swelling caused by excess fluid trapped in your body tissue, it can i)present - edema present.
                                                                                      ii)negative - edema not present.
                                                                                      
        6.skin_changes - any changes in appearance of the skin, it can be, i)dry_scaly - skin is dry and the texture would be like fish scale.
                                                                           ii)dermatosis - any other alternation in skin like redness which doesn't cause inflamation.
                                                                           iii)no - no skin changes.
                                                                           
        7.phychomotor_changes - behaviuoral changes, it can be, i)irritable - 
                                                                ii)lethargic - feeling dull in all the activities.
                                                                iii)no - no any changes.
       
        8.serum_albumin_level - it measures the amount of protein in individuals blood. It can vary from 3.4 to 5.4g/dL.
        
        9.abdomen - it access the abdomenal changes, it can be, i)distended - abdomen swollen.
                                                                ii)normal - abdomen normal.
                                                              
        10.organomegaly - here we access major abdomenal organs including spleen, liver, kidney etc., it can be, i)yes - increased in size
                                                                                                                 ii)no - normal.
                                                                                                                 
        11.subcutaneous_fat - fatty tissue present beneath the skin. here we are accessing subcutaneous fat using calipers, usually it is accessed between the age group of 0-10                               age and its values varies from 0 to 30.
        
        12.present_weight - present weight of the individual.
        
        13.diagnosis - 
                      
                     a) IUGR - It stands for intra uterine growth retardation. It refers to a condition in which an unborn baby is smaller than it should be because it is not                                  growing at a normal rate inside the womb. First 50 entries in dataset denotes IUGR i.e fron id 1 to 50. The main parameter to identify this                                      malnutrition is the birth weight, which will be below 2.5. 
                     
                     b)MERASMUS - It is a form of malnutrition. It happens when the intake of nutrients and energy is too low for a person’s needs. It leads to wasting, or                                         the loss of body fat and muscle. A child with marasmus may not grow as children usually do. Next 50 entries denotes MERASMUS i.e from id 51 to                                   100. The parameter to identify this malnutrition will be
                     
                     c)KWASHIORKOR - It is a malnutrition produced by a severely inadequate amount of protein in the diet.
