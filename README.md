# Student Organizer App

Level 2 assignment - Modern Android App Development with Kotlin.
A 5 screen Student Organizer built with Jetpack Compose and Navigation Compose.

## Screens
- Dashboard (`dashboard`) - stats, active courses, urgent deadlines, FAB
- Assignments (`assignments`) - filter (All / Pending / Completed), list, FAB
- Profile (`profile`) - student header, academic stats, quick actions
- Settings (`settings`) - dark mode, notifications, default start screen
- Add Assignment (`add_assignment`) - form with validation, back arrow

## Custom composables (Components.kt)
AppBar, BottomBar, CourseInfo, AssignmentCard, StudentProfile, AssignmentForm

## Notes
- No database or network, all data is sample data / UI state
- Navigation routes are in a sealed class (`Screen.kt`)
- Demo video: `demo.mp4`
