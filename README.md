# CalendarPickerJetPackCompose
Kotlin file with Reimplementation of Calendar Date Picker made by Crane

https://github.com/android/compose-samples/tree/main/Crane/app/src/main/java/androidx/compose/samples/crane/calendar

Usage:

CalendarPicker:
```
CalendarPicker(date = dropDrownDate,
                                      headerBackColor = headerBackColor,
                                      headerTextColor = headerTextColor,
                                      headerButtonsBackColor = headerButtonsBackColor,
                                      selectedDayBackColor = selectedDayBackColor,
                                      onDayClicked = { newDate ->                                          
                                          onDayClicked(newDate)
                                      })
 ```                                  
CalendarDropDown:
```
CalendarDropDown(label = "Fecha de Registro",
                                               paddingValues = PaddingValues(horizontal = 6.dp),
                                               textFieldColors = this@MainScreenComposables.textFieldColors(),
                                               editorWidth = 220.dp,
                                               headerBackColor = Color.Blue,
                                               headerTextColor = Color.White,
                                               headerButtonsBackColor = Color.Green,
                                               selectedDayBackColor = Color.Green,
                                               date = date,

                              ){ newDate ->
                                  date = newDate
                              }
```

Show video in youtube.

[![Show video in youtube.](https://img.youtube.com/vi/r2m9KNps4NY/hqdefault.jpg)](https://www.youtube.com/watch?v=r2m9KNps4NY)


Regards!
