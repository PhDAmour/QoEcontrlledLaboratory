

1. Title of Database:  
QoE controlled laboratory dataset (QoEcontrolledLab).

Updated December 16, 2017 by L.Amour, S. Souihi and A. Mellouk:
Paris Est Créteil University -France-.

2. Sources:
   (a)  Lamine Amour, Sami Souihi, Said Hoceini, Abdelhamid Mellouk:
          An Open Source Platform for Perceived Video Quality Evaluation. Q2SWinet@MSWiM: 
		  pages 139-140. . November 2015. 
		
  (b)	Lamine Amour, Sami Souihi, Said Hoceini, Abdelhamid Mellouk:
          A Hierarchical Classification Model of QoE Influence Factors. WWIC 2015: 
		  pages 225-238, May 2015.
		

   (b) Lamine Amour, email: lamine.amour@u-pec.fr
   (c) January 2018
   
   
3. Past Usage:

   (1) Y. B. Youssef, A. Mellouk, M. Afif and S. Tabbane: Video Quality Assessment Based 
       on Statistical Selection Approach for QoE Factors Dependency," 2016 IEEE Global 
	   Communications Conference (GLOBECOM), pages 1-6, December 2016.


4. Relevant Information:

   -- These data are the results of a controlled laboratory testbed, where the 
       Absolute Category Rate (ACR) method is used with Mean Opinion Score (MOS) ratting 
	   level. 62 testers particpated to build this dataset.   
      
   -- The attributes are (dontated by Lamine Amour, lamine.amour@u-pec)
   
     (1)  id_video
     
     (2)  content
     
     (3)  norm_bitrate	
     
     (4)  complexity	
     
     (5)  complexity_class	
     
     (6)  resolution	
     
     (7)  caching	
     
     (8)  bitrate_video	
     
     (9)  framerate_video
     
     (10)  dropped_video	
     
     (11)  bitrate_audio	
     
     (12)  dropped_audio
     
     (13)  begin_time	
     
     (14)  screen_size	
     
     (15)  id_user	
     
     (16)  age_user	
     
     (17)  sex_user	
     
     (18)  mos

	
    -- Each variable belongs to a category of factros as bellow:    
      - Video content analysis results (2 to 6)
      - VLC player indicators (QoA) (7 to 13)
      - Device characteristics  (QoD)(14)
      - User's profil (QoU) (15 to 17) 
      - User's MOS scoe(18)		  
             
5. Number of Instances : 

                class 1 (MOS = 1): 138 
	        class 2 (MOS = 2): 100
	        class 3 (MOS = 3): 103 
		class 4 (MOS = 4): 132
		class 5 (MOS = 5): 89

6. For Each Attribute:

	All attributes are digit except, video content type ("content")  user gender ("sex_user") and 
	device screen size ("screen_size")

	NOTES: 
         - 18st (MOS) Mean Opinion Scroe that a tester will give at the end of each video view.
	  
		   5 -> Excellent
		   
		   4 -> Good
		   
		   3 -> Fair
		   
		   2 -> Poor
		   
		   1 -> Bad
	


