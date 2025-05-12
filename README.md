# Reverse Engineering Android Game 

- Decompiled an existing APK using http://www.javadecompilers.com/apk 
- Created a new Android Studio project from scratch.
- Migrated all necessary Java classes, XML layouts, resources, and assets from the decompiled APK into the new project.
- Analyzed and understood the game logic
- Encountered and resolved a critical bug:
    - The URL defined in `strings.xml` contained a hidden **zero-width character**, which caused a `FileNotFoundException`.
    - I manually cleaned the URL by retyping it to remove the invisible character.

Final result: Successfully rebuilt, fixed, and ran the game with full functionality restored.
And the city was: Michigan according.