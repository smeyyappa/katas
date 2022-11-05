# O'Reilly Architectural Katas - Fall 2022
![heyBlue](https://user-images.githubusercontent.com/109451719/199656722-1a06c980-d90c-44ed-833e-47203d987dd8.jpg)
## **Premise** <br />
  Inspired by the extraordinary acts of heroism displayed by both individual community members and first responders during 9/11, EcoSchool co-founder, John Verdi, wanted to build a platform that could bring police officers and communities together with a shared purpose.
## **Vision of Hey Blue!** <br />
  The HeyBlue App Project is a sustained effort that facilitates moments of meaningful connection between police officers and members of their community by offering intentional opportunities for individuals to meet and share positive experiences. These positive interactions turn into points that the individual can use to purchase items and the police officer can donate to a non-profit or family in need.
  Community members actively seek out police officers at special events to have a positive interactions (Selfies). Local businesses pledge $1 per selfie uploaded to social media and the proceeds go to a local family.
  
Authors:
  - Sakthivel Ganesamoorthy
  - Anil Talapragada
  - [Subramanian Meyyappan](https://www.linkedin.com/in/subramanian-meyyappan/)
 
 
## **Business Requirements** <br />

Hard Requirements:
 
  - Actors - Civilan, Officers, Charity, Business
  - Connections between actors
    
    - Civilian <-> Officers
    - Officers -> Charity
    - Civilian -> Business
   
   - Location Tracking.
   - Selfie upload to Hey Blue Social Media.
   - Opt In / Opt Out of notifications.
   - Tracking Engagement
   - Only one connection / officer within 24 hours.
   - Connections between civilian and officer within a 10 feet distance.
   - Only a civilian can initiate a connection.
   - Bells and Whistles and an inspiring quote when a succesful connection is made.
   - Citiziens can link only one email address / phone number.
   - Track points usage /Civilian and /Officer.
   - Officer location is automatically turned off after 15 minutes.
   - Officers profile visibility should be limited for civilians to only number of successful connections made.
   - Allow the application to track and group participation by zip code.
  
 Long Term Recommendation:
 
  - Use machine learning to perform sentiment analysis on the data to gain insights into
    
     - Interactions trend
     - Behaviour analysis
     - Business Rewards Variations
     - Benefitial Charities right usage of rewards. 
   
   ## **The Strategy** <br />
   
   Microservices architecture is tailor-made for DevOps with its services-based approach that allows organizations to break down the application into smaller services. This enables delivery teams to tackle individual services as separate entities—ultimately simplifying the development, testing, and deployment. We beleive the role microservices plays in DevOps includes streamlining the DevOps process and increasing productivity and quality of the application while moving developments to a flexible architecture. This leads to the development of cloud-native applications that are capable of fulfilling the demand from Hey Blue!.
   
  Oure strategy is to seperate the hard requirements into capabilities which will break the application into smaller independent services. We are confident that all the capabilities can be built simultaneously in an agile model, with incremental product releases.
  
  ## **Architecture Decision Records** <br />
  
  You can find the ADR's [here](https://github.com/smeyyappa/katas/tree/main/Architectural%20Decision%20Records)
  
  
    
   
  
