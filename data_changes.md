# Changes made to the dataset

The original and primary dataset for this project is taken from [here](https://www.kaggle.com/ksb357/military-hollywood-collaboration-database). In this document we track the changes made to the dataset.

## Change 2: March 23rd, 2021

1. We added IMDB ids those movies and TV shows that are not yet there after March 20th, 2021 by looking at the offical document released by the US [Department of Defence](https://drive.google.com/file/d/1NeDVYu_gvEhtdQVtSFPRIapHDxJx6842/view).

2. We added dates those movies and TV shows that are not yet there by looking at the offical document released by the US [Department of Defence](https://drive.google.com/file/d/1NeDVYu_gvEhtdQVtSFPRIapHDxJx6842/view).

3. For the movies and TV shows that were never produced, we write **NA** in the IMDB title field.

4. We merged/deleted the rows of the following movies and TV shows as they represent the same movie/TV show.

   1. BATTLEGROUND
   2. 84 CHARLIE MOPIC
   3. JAG: THE PROMISED LAND
   4. NUMB3RS: ALL'S FAIR
   5. CAPTAIN PHILLIPS
   6. TRANSFORMERS
   7. TRANSFORMERS 2
   8. TRANSFORMERS 3

5. We added additional text from the the offical document released by the US [Department of Defence](https://drive.google.com/file/d/1NeDVYu_gvEhtdQVtSFPRIapHDxJx6842/view) for the following movies.

   1. THE TUSKEGEE AIRMEN: Added year for the FILM and added additional text about the TV movie in seperate rows
   2. MAGNUM PI: Created a second row as the support was provided for a single episode that aired in two part

6. Other changes
   1. THUNDER RUN: Added Remarks from the official document.

## Change 1: March 20th, 2021

We added IMDB ids to the movies and the TV shows for which we could find without ambiguity.
