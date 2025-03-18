# js-simple-timer

A *simple timer* to count down the remaining time to something. Written in **JavaScript** for a website. 

It consists of a function that takes in **id** the name of the *timer class*, for example `'.timer'`, and takes in **deadline** the date the timer ends, for example `'2025-03-26'`.
The timer file can be used as a module for this purpose in the main file it should be imported in this way:
`import timer from './modules/timer';`

*Attention, since modules are not supported in the browser, to use it you need to build the project with WebPack.*
