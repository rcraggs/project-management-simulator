# Adding a new event

1. Add a description of the event to the "Execution Events" section
2. In the `::execution_scene_end_of_day` scene add the event_? suffix with corresponding random number
3. Add a `var_event_??_happened:  false` value to the early declarations.
4. Create (copy) a scene for `execution_scene_test_event_{tmp_event}`
5. Write the logic for the event in the scene and then back in the main event scene if necessary


