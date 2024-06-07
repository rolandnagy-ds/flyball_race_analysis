### Wild_Runners_Flyball_Team_base_data.xlsx

Table with basic data of all (51) WRFT dogs, updated by the WRFT trainer whenever a new dog joins the team.

Here's what you should know about columns:

- leader: identifier of the dog's handler [code consisting of 2 letters and 6 digits]
- name: the dog's name
- breed: the breed of the dog
- gender: the gender of the dog [male, female]
- sex: the state of the sex [sexual, castrated]
- birthday_date: the dog's date of birth [in YYYY-MM-DD format]
- chip_number: ID of the dog's chip [14-digit number]
- ulna_length: the length of the dog's forearm (ulna), which is the jumping height
required to determine
hurdle_height: the required jumping height for the dog in competitions

### FLYBALLCZ_race_data.xlsx

This document contains on 12 sheets the results of all the 2023 competitions organized in the Czech Republic in which WRFT participated. These scoreboards were saved by the WRFT coach after each race according to the following logic:

- he named the sheet after the competition
- on each sheet, he inserted a line at the top in which he wrote down the name of the competition, the location and date 

A competition may include several sheets if the competition took place in several rings simultaneously.

Here's what you should know about columns:
- (not named): the number of races in the race
- Divize: division number
- kdy: race date, format: [HH:MM:SS]
- kdo: the name of the team whose data for that race is shown in the row
- s kým: the name of the opposite team
- celkem: the team’s total runtime
- V/P/R: sign for Win (Vítězství), Loss (Prohra), Tie (Remíza)
- překážky: height of hurdle
- jméno columns: name of the dog for that specific relay
- 1.pes, 2.pes, 3.pes, 4.pes columns: part-time of the dog for that specific relay
-	the [‘vbehl’, ‘mimo’] values indicates errors that was committed by the dogs within running: vbehl = ’ran in’ error, mimo = ’outside’ error
-	start: starting time of the dog running in 1st position
	- the change-time variables can contain zero values, indicating early starts
 - stříd. columns: changeover time for a dog running in a given position
	- ‘chyba’ value means early starts too, but less than the machine can calculate
	- ’ok’ values means nearly perfect change times

### EFC_race_data.xlsx

This document contains the results of the European Flyball Championships 2023 on 4 sheets. These scoreboards were saved by the WRFT coach after the tournament according to the following logic:

- the name of the sheet is the ring number and the day number
- at the top of each sheet, he inserted a line to record the ring number, the venue and the date of the tournament

The columns are as follows:
- (not named): the number of races in the race
- Division: division number
- when: race date, format: [HH:MM:SS]
- who: the name of the team whose data for that race is shown in the row
- with who: the name of the opposite team
- total time: the team’s total runtime
- W/L/T: Win, Loss, Tie
- Hurdles: height of hurdle
- name columns: name of the dog for that specific relay
- 1.dog, 2.dog, 3.dog, 4.dog columns: part-time of the dog for that specific relay
- start: starting time of the dog running in 1st position
- chng columns: changeover time for a dog running in a given position

Note that on the second sheet, in the columns containing the dog run times and the changeover times, for some reason the textual information about errors appears in Czech.
