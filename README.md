# hoursUpdate
A python program used to update volunteering hours of members in a community service club.
Though specifically intended for use by the Green Hope Red Cross Club, the code could be easily adapted for different organizations. The code is adapted to use the 'Red Cross Club 2021-22 Hours.xlsx' and 'Nov Monthly Meeting Attendance (Responses).xlsx" files. Choosing to use different databases of members will result in a need to adjust the code. 

The program will use a member list database and an attendance database to add 0.5 hours to each attendee. It will account for any spaces or capitalization variances. In addition, to account for potential spelling errors, the program will list all names with a 70% or greater similarity to names from the opposing database. This enables the user to manually enter data if spelling errors occur. Example: [johnnyappleseed johnnyappelseed 93.33% similarity]
