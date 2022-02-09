# hoursUpdate
A python program used to update volunteering hours of members in a community service club.
Though specifically intended for use by the Green Hope Red Cross Club, the code could be easily adapted for integration in different organizations. The program is developed to utilize two workbooks: a club roster and an attendance sheet.

The application automatiacally adds 0.5 hours to each attendee upon submission of an attendance form. In addition, the application has built-in intelligence to ignore spacing/capitalization variances and compare differences in spelling. Example: attendee accidentally submits name as "Honny Apple   Seed ". Program ignores capitaliztion and spacing differences. Instead observes correctly spelled name in member list database and outputs following information: [johnnyappleseed hohnnyappleseed 93.33% similarity]
