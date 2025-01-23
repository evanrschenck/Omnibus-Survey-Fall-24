##Imported CSV file into environment
##install.packages("dplyr")
##data_cleaned <- `Omnibus.Survey.Fall.2024_December.9,.2024_09.11`%>% select(V18,V19,V21,V22,V23,V24,V25,V27,V149,V182,V183,V184,V185,V186,V187,V204,V205,V212,V214,V219)
##renameddata <- data_cleaned %>% rename(Political_Interest = V18, Political_Party = V19, Democratic_Strength = V21, Republican_Strength = V22, Polarization= V23, Liberal_Conservative= V24, Election_Choice= V25, Political_Engagement= V27, Harris_Teleprompter = V149, National_Trust1= V182, National_Trust2= V183, Trust_Others= V184,Control= V185, Treatment_Consequence= V186, Treatment_Norms= V187, Appointment_Power1= V204, Appointment_Power2= V205, Gender= V212, Racial_Identity= V214, Religious_Affiliation= V219)
##renameddata <- renameddata %>% mutate('National_Trust' = paste(National_Trust1, National_Trust2))
##renameddata <- renameddata %>% mutate('Appointment_Power' = paste (Appointment_Power1, Appointment_Power2))
##renameddata <- renameddata %>% select(Appointment_Power, National_Trust, Religious_Affiliation, Racial_Identity, Gender, Treatment_Norms, Treatment_Consequence, Control, Trust_Others, Harris_Teleprompter, Political_Engagement, Election_Choice, Liberal_Conservative, Polarization, Republican_Strength, Democratic_Strength, Political_Party, Political_Interest)
