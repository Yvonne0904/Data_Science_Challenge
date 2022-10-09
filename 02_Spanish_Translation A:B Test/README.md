## Challenge Description

Spain-based users have a much higher conversion rate than any other Spanish-speaking country. 

Spain and LatAm country manager suggested that one reason could be translation. All Spanish- speaking countries had the same translation of the site which was written by a Spaniard. They agreed to try a test where each country would have its one translation written by a local.

After they run the test however, they are really surprised cause the test is negative. I.e., it appears that the non-localized translation was doing better!

## Tasks

- Confirm that the test is actually negative. That is, it appears that the old version of the site with just one translation across Spain and LatAm performs better
- Explain why that might be happening. Are the localized translations really worse?
- If you identified what was wrong, design an algorithm that would return FALSE if the same problem is happening in the future and TRUE if everything is good and the results can be trusted.

## Data

### Table1: test_table

- User_id
- date
- source
- device
- Browse_language
- Ads_channel
- browser
- conversion
- test

### Table2: user_table

- User_id
- sex
- age
- Country 

