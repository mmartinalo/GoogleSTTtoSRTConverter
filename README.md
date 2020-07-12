# GoogleSTTtoSRTConverter
[![npm version](https://badge.fury.io/js/gstt-to-srt-converter.svg)](https://badge.fury.io/js/gstt-to-srt-converter)

Converts the response from Google Cloud's Speech to text v1 service into SRT format

## Getting Started - User
1. Go to the [deployed version](https://luismayo.github.io/GoogleSTTtoSRTConverter/)
2. Copy the text generated by Google's Speech to text service into the upper text box.
3. Click convert.
4. Now you may be able to copy or download the resulting SRT

## Getting Started - Use as library
1. Install library
`npm i gstt-to-srt-converter`
2. Import the function
`const gstt = require('gstt-to-srt-converter')`
3. Invoke the function with the Google's STT restulr as the only argument
`gstt.convertGSTTToSRT(string);`

## Contributing
Since this is a tiny project we don't have strict rules about contributions. Just open a Pull Request to fix any of the project issues or any improvement you have percieved on your own. Any contributions which improve or fix the project will be accepted as long as they don't deviate too much from the project objectives. If you have doubts about whether the PR would be accepted or not you can open an issue before coding to ask for my opinion
