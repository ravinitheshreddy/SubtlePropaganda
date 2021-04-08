# Changes made to the dataset

The original and primary dataset for this project is taken from [here](https://www.kaggle.com/ksb357/military-hollywood-collaboration-database). In this document we track the changes made to the dataset.

## Change 2: March 23rd, 2021

1. We added IMDB ids those movies and TV shows that are not yet there after March 20th, 2021 by looking at the offical document released by the US [Department of Defence](https://drive.google.com/file/d/1NeDVYu_gvEhtdQVtSFPRIapHDxJx6842/view).

2. We added dates those movies and TV shows that are not yet there by looking at the offical document released by the US [Department of Defence](https://drive.google.com/file/d/1NeDVYu_gvEhtdQVtSFPRIapHDxJx6842/view).

3. For the movies and TV shows that were never produced, we write **Never Made** in the IMDB title field.

4. For those movies and TV shows that we were not able to identify on the internet even with the help of the offical document released by the US [Department of Defence](https://drive.google.com/file/d/1NeDVYu_gvEhtdQVtSFPRIapHDxJx6842/view), the IMDB IDs are left empty.

5. We merged/deleted the rows of the following movies and TV shows as they represent the same movie/TV show.

   1. BATTLEGROUND
   2. 84 CHARLIE MOPIC
   3. JAG: THE PROMISED LAND
   4. NUMB3RS: ALL'S FAIR
   5. CAPTAIN PHILLIPS
   6. TRANSFORMERS
   7. TRANSFORMERS 2
   8. TRANSFORMERS 3
   9. WHISKEY TANGO FOXTROT

6. We added additional text from the offical document released by the US [Department of Defence](https://drive.google.com/file/d/1NeDVYu_gvEhtdQVtSFPRIapHDxJx6842/view) for the following movies.

   1. THE TUSKEGEE AIRMEN: Added year for the FILM and added additional text about the TV movie in seperate rows
   2. MAGNUM PI: Created a second row as the support was provided for a single episode that aired in two part

7. We changed the status of the following films after looking at the offical document released by the US [Department of Defence](https://drive.google.com/file/d/1NeDVYu_gvEhtdQVtSFPRIapHDxJx6842/view).

   1. WAR OF THE WORLDS: From _RCV_ to _APP_.
   2. WAR PARTY: From _RCV_ to _OTH_, as the film crew withdrew request.
   3. YEAR IN THE LIFE, A: From _RCV_ to _DEN_.
   4. FLYING BLIND: From _RCV_ to _DEN_.
   5. GARDENS OF STONE: From _RCV_ to _APP_.
   6. MEGAFORCE: From _RCV_ to _APP_.
   7. SWEETWINE & TYREE: From _RCV_ to _DEN_.
   8. MYSTIC NIGHTS & PIRATE FIGHTS: From empty to _APP_.

8. We removed the text "No File" from the remarks as it indicates only whether DoD currently has a file with them or not and "No Record of Film being made/produced" or similar meaning sentences from the remarks of those movies that have the IMDB ID. The list is as below.

   1. 1ST FORCE
   2. 3RD DEGREE
   3. 50/50
   4. ADVENTURES OF MARY-KATE & ASHLEY
   5. AIRPOWER VIETNAM, THE REAP TOP GUN
   6. AMAZING GRACE AND CHUCK
   7. AMELIA EARHART: THE FINAL FLIGHT
   8. AMERICA, YOU'RE TOO YOUNG TO DIE
   9. ANGEL IN GREEN
   10. ANGEL'S FLIGHT
   11. B.R.A.T. PATROL, THE
   12. BIRDY
   13. BRIDGE TO THE SUN
   14. BUFFALO SOLIDERS
   15. CODE 3
   16. CONTACT
   17. DESERT STORM- THE MOVIE
   18. DESTINY
   19. DISTANT THUNDER
   20. FLIGHT DECK
   21. FLIGHT TO NOWHERE
   22. FLYING BLIND
   23. GOLDENEYE
   24. GREAT IMPOSTOR, THE
   25. HEALTH CLUB
   26. IN COUNTRY
   27. IN THE LINE OF DUTY, STANDOFF AT MARION
   28. INTERCEPTOR
   29. JAG
   30. JAG, JINX
   31. JAG, ACT OF TERROR
   32. JAG, ANGELS 30
   33. JAG, KING OF THE GREENIE BOARD
   34. JAG, RULES OF ENGAGEMENT
   35. JAG, FORCE RECON
   36. JAG, TIGER, TIGER
   37. JAG, INNOCENCE
   38. JEREMY'S EGG
   39. LARGER THAN LIFE
   40. LE NOUVEAU MONDE
   41. LIFE FLIGHT
   42. MAC AND ME
   43. MY FATHER, MY SON
   44. NAVY BLUE AND GOLD
   45. OPERATION DUMBO DROP
   46. OUTBREAK
   47. PASS THE AMMUNITION
   48. PEREZ FAMILY, THE
   49. PIONEER CHRISTMAS
   50. PSYCHE FILES
   51. PUPPET MASTERS
   52. PURPLE HEARTS
   53. RECOVERY
   54. RETREADS
   55. ROBOJOX
   56. RUSSKIES
   57. SAIGON
   58. SHEPHERD, THE
   59. STAND, THE
   60. SUBMARINE PIRATE
   61. THE ADVENTURES OF MARK AND BRIAN, THE ADVENTURES OF MARK AND BRIAN IN FATHERHOOD
   62. THE ADVENTURES OF MARK AND BRIAN, MARK AND BRIAN'S ARMY ADVENTURE
   63. THE AMERICAN DREAM CONTEST
   64. THE ANG, AMERICA'S HIDDEN STRENGTH
   65. THE GRAND TOUR
   66. THE HAUNTING OF SARAH HARDY
   67. THE HIJACKING OF THE ACHILLE LAURO
   68. THE Q STREET
   69. THE SPEED OF LIGHT
   70. TIME TO TRIUMPH, A
   71. TRIP WIRE
   72. TURKEY SHOOT
   73. TWISTER'S REVENGE
   74. VON METZ INCIDENT, THE

9. We have corrected spellings of the words in the remarks section. However, this correction is not exhaustive.

10. Other changes
    1. THUNDER RUN: Added Remarks from the official document.

## Change 1: March 20th, 2021

We added IMDB ids to the movies and the TV shows for which we could find without ambiguity.
