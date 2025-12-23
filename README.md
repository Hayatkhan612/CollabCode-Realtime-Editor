# CollabCode-Realtime-Editor


The Challenge: Race Conditions and State Synchronization.


​Challenge: Preventing data loss when two users edit the same line of code simultaneously (Race Conditions).


​Solution: Implemented a 300ms smart-debounce algorithm and a clearTimeout safety switch during file transitions to ensure the latest state is captured before a database write occurs.


​Challenge: Optimizing the DOM for real-time cursor tracking.


​Solution: Used dynamic CSS injection to render remote user cursors, avoiding heavy re-renders of the Monaco Editor instance and maintaining 60fps performance.globally.

Link 🔗 : https://hayatkhan612.github.io/CollabCode-Realtime-Editor/
