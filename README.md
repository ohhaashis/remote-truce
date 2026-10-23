# Remote Truce
A Fire TV app that ends the nightly fight over the remote.

In my hostel, one common-room TV means a nightly argument about what to watch. At home it's the same with family. Remote Truce lets everyone on the couch pick their mood by passing the remote, then suggests three titles that work for the whole group, with a reason for each person.

## Features
- Add up to 4 people: Grandparent, Parent, Teen, Kid, Friend, Me
- Each person picks a mood, passing the remote around
- Language preference: Hindi, English, Tamil, Telugu, Bengali
- AI picks (Gemini) with a per-person reason; family-safe when a kid is watching
- Household memory: remembers past choices and adapts future picks
- Offline fallback picks when the network or API fails
- Fully usable with the TV remote: arrows, select, Back = undo

## Built with
Kotlin (Fire OS / Android WebView shell), HTML, CSS, JavaScript, Gemini API, localStorage.

## Run it
1. Open the project in Android Studio and let Gradle sync.
2. Optional: add a Gemini API key in `app/src/main/assets/index.html` → `CONFIG.API_KEY`.
3. Run on a Fire TV device (via ADB) or an Android TV emulator.

## License
MIT
