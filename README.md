# This is a testing repository.

***

## Instructions

Hi there! You have been selected among the final few applicants. I’ve put together a quick take home test - it should take between 20 minutes and 1 hour. It is testing your attention to detail, and some basic pandas manipulation. This exercise provides absolutely no value to me (I understand some bad employers may use this opportunity to get free work - I’ve already completed this exercise so I can check your work :), and you can check my hire history).

About the data.
3 csv files.
* Download outcome csv here: http://www.sharecsv.com/s/e593dd089bc5aaf6583b5187f96cb48e/outcome_interview.csv
* Download event csv here: http://www.sharecsv.com/s/f9b678bf4a60bafe3f0a4132313e194d/event_interview.csv
* Download fighter csv here: http://www.sharecsv.com/s/4f1b611a0d9f96d7700adba8b387df21/fighter_interview.csv

The outcome csv contains the matchup data for various mixed martial arts fights - including the two fighters involved, the winner, and the event where it took place - all encoded in IDs.
The event csv contains event data for various mixed martial arts events - most importantly the event name. The id corresponds to the event_id in the outcome csv.
The fighter csv contains fighter data for various mixed martial arts fighters - their names and their nationalities. The id corresponds to both fighter1_id and fighter2_id in the outcome csv.

The Exercise:
Using the csv’s you have, I need a pandas dataframe and corresponding exported csv of all the matchups (reminder: matchups are listed in the outcome csv) with ONLY the following columns:

| fighter1_name | fighter2_name | fighter1_nationality | fighter2_nationality | event_name |

**Hint:** you will need to combine data from all three csvs, rename column names, and also get rid of many columns

And last, please make a visualization of your choice showing the distribution of fighters from various nationalities.

Delivery:
The deadline for completion is 11:30PM (23:30) Pacific Standard Time on Wednesday May 22 (will be Thursday for most of your time zones). I will review all entries on Thursday May 23 PST (GMT -8).

Please upload the jupyter notebook and the exported csv to Github (github will be the primary use of code sharing for the job). Please share the link with me when you are done.

Other notes:
The work you will be hired for (not this test, but the real work) will contain betting data (odds, etc.), so anyone with religious objections to such things can ignore this take home test.

Please ping me with any questions.
