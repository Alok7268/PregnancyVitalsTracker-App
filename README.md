 Tech Stack: 
● Language: Kotlin 
● UI: Jetpack Compose 
● Architecture: MVVM 
● Database: Room 
● State Management: StateFlow or LiveData
Main Screen: Display a list of vitals logs using LazyColumn. 
Add Vitals Dialog: A floating "Add Vitals" button to open a Jetpack Compose Dialog. 
Vitals Entry Form: Dialog should ask for: 
● Blood Pressure (Sys/Dia) 
● Heart Rate 
● Weight 
● Baby Kicks Count 
Submit Button: On click, the entry should be saved in Room Database and the list should 
auto-update. 
Live Updates: The main screen should reflect changes immediately using 
LiveData/StateFlow.
