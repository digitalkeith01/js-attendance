# Attendance Viewer

### This is a simple attendance viewer used with a Google form. 

How to use:
1. Create a Google form with data stored in Google sheet
2. After attendance data entered, copy the data from Google sheet and then paste to this HTML form

Details in following article:
https://digitalkeith01.medium.com/heavy-workload-to-create-an-attendance-system-1e0b9ab35655

### Additional Gatherings "attendanceViewerAdditonal.html"

One more field is added to the form. Please move the new column "Is it Additional?" to the right of date in data worksheet:

1. Timestamp (Created by system)
2. Date [Date]
3. ***Is it Additional? [Single Radiobox] ***
4. Group [Selection]
5. Participants [Text]
6. New Comer [Text]

For normal gethering, just leave the "Is it Additional?" empty. If it is clicked, that gethering is "Additional", the attendance is counted if the participant absent in any normal gathering.
