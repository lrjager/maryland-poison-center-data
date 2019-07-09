# Maryland Poison Center (MPC) data CODEBOOK
## Leah Jager
### 7/7/2019

These variable definitions are my best attempt to describe what the variables are measuring based on information on the [Maryland Poison Center website](https://www.mdpoison.com/).  I will update these descriptions as I discover more information.
 
* `fileNo` : id number for county/year combination
* `County` : county name, from 24 Maryland county (or county equivalents)
* `Year` : year of exposure data, from 2006-2018

Overall exposure data:

* `Totalhumanexposures` : total number of human exposures
* `AnimalExposures` : total number of animal exposures
* `InformationCalls` : total number of information calls

Exposures by age:

* `Age_Under12mo` : number of exposures for children under 12 months of age
* `Age_1yr` : number of human exposures for children aged 1 year
* `Age_2yr` : number of human exposures for children aged 2 years
* `Age_3yr` : number of humanexposures for children aged 3 years
* `Age_4yr` : number of human exposures for children aged 4 years
* `Age_5yr` : number of human exposures for children aged 5 years
* `Age_6-12yr` : number of human exposures for children aged 6 through 12 years
* `Age_13-19yr` : number of human exposures for children aged 13 through 19 years
* `Age_20-59yr` : number of human exposures for adults aged 20 through 59 years (only available for 2010+, before 2010 only a general adult category)
* `Age_Over60yr` : number of human exposures for adults 60 years or older (only available for 2010+, before 2010 only a general adult category)
* `Age_Adult` : number of human exposures for adults (older than 19)
* `Age_Unknown` : number of human exposures with unknown age
* `Age_UnknownAdult` : number of human exposures for adult (older than 19) with unknown age
* `Age_UnknownChild` : number of human exposures for child (19 or younger) with unknown age

Exposure by reason: (Intentional, Unintentional, Other, and subcategories)

* `Intentional` : number of exposures where the exposure was intentional
    * `Intentional_Abuse` : number of intentional exposures due to abuse of substance
    * `Intentional_Misuse` : number of intentional exposures due to misuse of substance
    * `Intentional_SuspectedSuicide` : number of intentional exposures due to suspected suicide attempt
    * `Intentional_Unknown` : number of intentional exposures where the reason is unknown
    
    
* `Unintentional` : number of exposures where the exposure was unintentional
    * `Unintentional_Bite.Sting`: number of unintentional exposures due to animal bite or sting
    * `Unintentional_Environmental` : number of unintentional exposures due to environmental circumstances (such as air quality or lead paint)
    * `Unintentional_FoodPoisoning` : number of unintentional exposures due to food poisoning
    * `Unintentional_General` : number of unintentional exposures due to general circumstances ?? not sure what this means
    * `Unintentional_Misuse` : number of unintentional exposures due to misuse of product
    * `Unintentional_Occupational` : number of unintentional exposures due to workplace circumstances
    * `Unintentional_TherapeuticError` : number of unintentional exposures due to therapeutic errors (double-doses, wrong medicines taken, etc)
    * `Unintentional_Other.Unknown` : number of unintentional exposures where the reason is unknown
    
* `OtherReason` : number of exposures where the exposure was not intentional or unintentional, such as an adverse reaction to a drug or malicious exposure
    * `Other_AdverseReaction.Drug` : number of other exposures due to an adverse reaction to a drug
    * `Other_AdverseReaction.Food` : number of other exposures due to an adverse reaction to a food
    * `Other_AdverseReaction.Other` : number of other exposures due to an adverse reaction to a substance other than food or a drug
    * `Other_Contamination.Tampering` : number of other exposures due to contamination of or tampering with the substance
    * `Other_Malicious` : number of other exposures due to malicious behavior on the part of someone else? not sure what this means exactly
    * `Other_Withdrawal` : number of other exposures due to withdrawal
    * `Other_Other.Unknown` : number of other exposures where the reason is unknown

Site where exposure was managed:

* `ManageSite_HealthcareFacility` : number of exposures managed in a health care facility
* `ManageSite_OnSite.NonHealthcareFacility` : number of exposures managed on site in a place that was not a health care facility, such as in the patient's home
* `ManageSite_Other.Unknown` : number of exposures where management was not on site or in a health care facility or where the management site is unknown
* `ManageSite_RefusedReferral` : number of exposures where patient refused a referral to a health care facility 

Medical outcome of exposure:

* `MedOutcome_Death` : number of exposures that resulted in patient death
* `MedOutcome_MajorEffect` : number of exposures that resulted in a major effect
* `MedOutcome_MinorEffect` : number of exposures that resulted in a minor effect
* `MedOutcome_ModerateEffect` : number of exposures that resulted in a moderate effect
* `MedOutcome_NoEffect` : : number of exposures that resulted in a no effect
* `MedOutcome_Other.Unknown` : number of exposures where the outcome is unknown


