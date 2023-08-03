# NonFlipCalendar
using outlook account and powebi to implement it.

# Interface Preview:
v1.0
![v1 0](https://github.com/zionnoizy/NonFlipCalendar/assets/54279382/f2ac43e5-3fa4-4066-ba51-8b3320add261)

v2.0
![Capture](https://github.com/zionnoizy/NonFlipCalendar/assets/54279382/2b76127c-c70c-483a-8c90-bfd47979afc0)

# Introduction:
This is a project for showing the time able for meeting toom Panama and Monaco. It contains designed with correct time with each day meeting. It will show upcoming five working days included Monday to Friday.

# Table Name Explain:
Table Name: Calendar (2), Calendar (3)
Calendar (2) is for room Panama 
Calendar (3) is for room Monaco 
Table Name: CurrentWeekTable
Explain: It show upcoming five working days from today and it will associated with “WeekOfBegin, WeekOfEnd, TUE, WED, THUR”. +0 means today, +4 means five weekday later. The DAX use WEEKDAY() to calculate only the weekday. This table also doing some calculation with first working day schedule. These columns are: FindSubjectIfTodayMeetingExist , FindTodayStartTime, FindTodayEndTime, It will be using for testing purpose only in this case.
Table Name:  London%20E14%209NN?unitGroup=metric&key=V9LWLG3S9MAGNPMUY985ZTPRE&contentType=js
Explain: this is open source with 1000 times data refresh time to retrieve temperature in London E14 9NN. It will be temperature.
Table Name: TIMING
Explain: important table, the column Date&Time is all associate with all date and schedule in rest of the table. Be careful before rename the “Date&Time”.

# Limitation: 
If user make an appointment on the same day, it will show at the top of the table without doing sorting for timing.

# Reference:
[Use Power BI to create a dynamic/live meeting room schedule – NateChamberlain.com](https://natechamberlain.com/2018/02/11/use-power-bi-to-create-a-dynamic-live-meeting-room-schedule/)https://natechamberlain.com/2018/02/11/use-power-bi-to-create-a-dynamic-live-meeting-room-schedule/
[https://tech-peanuts.com/2020/05/22/using-power-bi-to-report-bookings-events/](https://tech-peanuts.com/2020/05/22/using-power-bi-to-report-bookings-events/)https://tech-peanuts.com/2020/05/22/using-power-bi-to-report-bookings-events/
