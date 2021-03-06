# Never use !important in your CSS
You know the feeling: you’re trying to fix a UX bug. You’ve been at in for an hour. None of the new styling rules you’re writing seem to be applying properly. Then all of a sudden you remember something - a trick from the dark days of web development. You swore you’d never use it, but just this once you promise yourself. You can’t spend any more time on this task. There are more pressing matters at hand. You crack a Grinch-like smile and  write something truly dastardly… `!important`…

https://media1.giphy.com/media/F9YNadrCjV5sY/giphy.gif

Anyone who’s spent any amount of time writing CSS knows how frustrating it can be at times, especially once your project begins to scale. The unfortunate reality of reaching for this panacea of styling fixes is that it is anything but. `!important` is a band-aid that will only worsen the quality of your project’s CSS over time. What happens the next time you need to write a rule to overwrite *that* rule? You end up with a ‘boy who cried wolf’ situation and your CSS isn’t sure which rules to follow. You can't yell any louder than `!important`. Eventually it’s all noise. 

When the desire to use this faux silver bullet crosses your mind, it’s imperative (dare I say *important*) to check your ego at the door and realize this is a symptom of your CSS not being as well-written as it could have been. Stylesheets need to be written according to the rules of the language - order, inheritance, class / ID hierarchy, etc. Adding `!important`s will only result in the degradation of your project’s styling and give you a house of cards with which to try and build upon in the future.

To those who write this language in a clean and concise fashion, we salute you. To those of us still trying to kick our hacky habits, there is hope. The first step is admitting we have a problem.
