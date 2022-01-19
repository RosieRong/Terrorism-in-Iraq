# Terrorism-in-Iraq
Data analytics of the development and changes of terrorism in Iraq using the Global Terrorism Database from 1970 to 2017. The goal of the project is to identify the effect of historical events on the terrorist activities in Iraq. 

# Data
The dataset used in this project is from the Global Terrorism Database (GTD). GTD is developed and maintained by researchers at the National Consortium  for the Study of Terrorism and Responses to Terrorism (START). The data source can be accessed through the link: https://www.start.umd.edu/gtd/
This dataset contains 18,192 records of worldwide terrorist attacks with 36 features for each attack. The key features included in uploaded csv file that is used for this project include:

  "eventid": Distinguished event ID for each attack
  "iyear": Years ranging from 1970 to 2017
  "extended": If the attack lasted over 24 hours (binary value 0 and 1)
  "country_txt": Country names where the attacks took place
  "region_txt": The continental region where the attacls took place
  "success": If the attack is successful (binary value 0 "and 1)
  "suicide": If the attack is a suicidal attack (binary value 0 and 1)
  "attacktype1_txt": Type of attack (eg: assasination, facility/infrastructure attack, etc.)
  "targtype1_txt": Type of target attacked (eg: private citizens&property, military, etx.)
  "gname": Names of the terrorist groups
  "weaptype1_txt": Type of weapons used (eg: explosive, firearm, etc.)
  "weapsubtype1_txt": Detailed subtype of weapons used (eg: rifle/shotgun, pipe bomb, etc.)
  "nkill": Number of people killed in the attack
  "nkillus": Number of US citizens killed in the attack
  "nwound" Number of people wounded in the attack
