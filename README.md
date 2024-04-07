# The 'Mapping Warbler Song' Project
In this project, we'll band together as a class to measure and map song characteristics of a single species, the Prairie Warbler, across the eastern US. This could reveal regional song dialects or even hidden subspecies - who knows! To do this, we'll use the hundreds of song recordings available via the Cornell Laboratory of Ornithology's Macaulay Library website. Most of those songs were recorded and submitted by citizen scientists, often as part of eBird checklists. We'll use simple tools (laptops, web browsers, and rulers) to collect several different measurements of each sonogram, pool our data, and map the results to see what the data tell us. While this analysis can't reveal WHY these patterns occur (e.g., learned dialects or local evolution), it may reveal some new questions that are worth exploring! The Prairie Warbler has only one known subspecies that occurs in south Florida. This is a continuing project and our early results from 2023 suggest some interesting geographical variation in song characteristics. Most interesting was the fact that they did not match up with known subspecies boundaries. This year we'll increase our sample size and try to confirm this observation!

## Overview
Each group will be assigned 100 song recordings from a Prairie Warbler song database downloaded from the Macaulay Library. As a group, you will view the sonogram for each song, take 4 measurements, and record your data in your assigned spreadsheet. Then we'll combine all the class data into one database and map the results.

## Phase 1: Learn about Prairie Warbler, get your data file, and start taking measurements
0. Look up Prairie Warbler in your field guide (or online) and take a look at the species' range map and the comments about their vocalizations. Here is a quote from the "Birds of the World" account about subspecies found within the species: "Geographic variation is slight, with increasing body size and duller (grayer rather than greener) dorsal color on peninsular Florida. Mitochondrial DNA sequences show evidence of significantly restricted gene flow between subspecies but there is no evidence of substantial phylogenetic divergence (Buerkle 1997, 1999), suggesting a recent split." Two subspecies exist, including one in "coastal south Florida" (Setophaga discolor paludicola) and one inhabiting the rest of the eastern United States (Setophaga discolor discolor).
1. Get your group letter from your instructor (a letter between A and J) and make a word document titled "Questions - Group [group letter].docx" replacing "[group letter]" with your group letter.
2. In a web browser, go to https://www.macaulaylibrary.org/ and enter Prairie Warbler in the search box to start viewing sonograms for the species. View several examples of the species' sonograms. Look for variation among individuals. Is there a property of the song that you think would be interesting to measure? Put your answer in Question 1 of the Phase 1 questions document. Use the 'filters' in the Macaulay website to limit your selection to 1) audio by clicking the speaker button in the header, and play around with other options by clicking "More filters" and checking boxes. Download a spreadsheet (csv file) for the resulting data by clicking "export". Close the file. (Note: we won't actually use this data as we already have a downloaded version for the class in the "blank_data_files" folder.) 
3. Go to the folder "blank_data_files" on the GitHub site (https://github.com/mikeallen-eco/mapping_warblers/tree/main/blank_data_files). Click on the csv file corresponding with your group letter. In the upper right of the screen, you'll see a button marked "Raw". Right click (or control click) on the button and choose "Download Linked File". Question 2 in your word document: How many rows does it have? How many columns?
4. Open your group csv file in a spreadsheet software of your choice. Make the columns wider if needed. (Tip: you may want to paste its contents into a Google Sheets document so that data collection can be easily shared among group members.) 
5. Now it is time to start making measurements on your assigned sonograms. Paste the first URL in the "link" column into a web browser. It will look something like this: https://macaulaylibrary.org/asset/110249
6. Is a Prairie Warbler song clearly visible on the sonogram (sometimes you have to play it first to see)? If not, write NA in the measurement columns and leave a note in the "skip_notes" column (saying why you skipped it) and move on to the next one. If there is a clear song, use a ruler to make your first measurement on the first song you encounter in the sonogram. See the image in the "prawar_data" folder on GitHub (https://github.com/mikeallen-eco/mapping_warblers/blob/main/prawar_data/prawar_example_song_%20492010421.png) for a detailed example of how to take the measurements. Briefly, the measurements are:
num_sylables = the number of syllables ('notes') in the song.
freq_range_mm = the range of frequencies covered by the entire song in mm (measured with ruler)
middle_syl_height_mm = the range of frequencies covered by the middle syllable in mm (measured with ruler)
duration_mm = the length of the song in mm (measured with ruler)
two_khz_mm = the length of 2 kHz on the scale bar in mm (measured with ruler)
two_sec_mm = the length of 2 seconds on the scale bar in mm (with ruler)
Notes: Measurements of the length of 2 kHz and 2 seconds will be used to convert the units of your other measurements later on (from mm to kHz or seconds). You may find that if you don't zoom in on your browser that these measurements don't change from one song to the next. If the sonogram is not clear, there is no song, or if it seems to be the wrong species (Field Sparrows are occasionally mislabeled as Prairie Warblers - ask the instructor if you suspect this), then enter NA in the measurement fields and enter a note into the "skip_notes" field.
7. Repeat this process for each link in the data file. Be sure to save your data file. You can stop partway and finish later. Be sure to email yourself the data or otherwise back it up safely.
8. Once you are done collecting all your measurements, send the completed data file to michael ( d o. t ) allen (at) rutgers ( dot ) edu.

## Phase 2: make maps and plots summarizing our collective results
9. Download and install RStudio and R (see here: )
15. Open the RStudio project again. Next, open the "mapping_prawar2.Rmd" file and follow the instructions to create maps and graphs summarizing the class measurements. Plots will be saved to your "my_output" folder.
16. Write a mini scientific paper with the following sections (~1 paragraph each, can be short paragraphs!): introduction, methods, results, discussion, literature cited (at least 2 primary references). Include the three maps we created as figures 1-3 with proper captions. Split up the writing among group members. Note: these "papers" can be relatively rough as we are writing them primarily in class. Turn it in via email with all group member names on it.
