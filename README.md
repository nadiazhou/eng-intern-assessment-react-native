# Overview
Hi! 
This is my official stopwatch. I've detailed below the files included:  

**src > components**
`App.tsx` - main component that renders the stopwatch and handles its functionality
`StopWatch.tsx`  - central component that renders the stopwatch, lap list, and button displays
`StopWatchButton.tsx` - consists of the Start, Pause, and Resume buttons
`LapButton.tsx` - button to indicated new lap time
`ResetButton.tsx` - button to reset timer and lap list
`FastestLap.tsx` - indexes fastest lap time
`SlowestLap.tsx` - indexes slowest lap time

**src > styles**
`styles.ts` - global stylesheet 

`Stopwatch.test.js` - functionality tester (edited)

## Demo (Expo - IOS Iphone 14)

https://github.com/Shopify/eng-intern-assessment-react-native/assets/86628372/77b585e4-8d43-4467-bfa2-42f114c71650

## Features
The following features have been implemented:

- The stopwatch starts when the user presses 'Start'
- The stopwatch stops when the user presses 'Stop'
- The stopwatch resumes counting when the user presses 'Resume'
- The stopwatch pauses when the user presses 'Pause'
- When paused or stopped, the user can choose to press 'Reset' which starts the timer back at 00:00:00
- The stopwatch keeps track of lap times
- The stopwatch identifies the fastest and slowest lap times

I have also modified a few of the test cases to accommodate the specific flow I've designed. Any changes have been indicated as comments.

A bit of insight: 
When designing the UI, I took heavy inspiration from the timer that exists in the IOS clock app. I find its design very intuitive and user-friendly, and for that reason, I've taken into account the user flow when designing a stopwatch of my own. I've included additional features to my stopwatch such as fastest and slowest lap time, which is  indicated by font colour (red - slowest, green - fastest). The lap times are ordered from most recent first. The lap time button itself is also disabled (dulled out) when the timer isn't running, as one should not be able to record lap times at that time.

## Testing 
![Image 2024-01-28 at 6 30 AM](https://github.com/Shopify/eng-intern-assessment-react-native/assets/86628372/a730aa05-2b20-4b8c-ac3d-dbc027245379)
