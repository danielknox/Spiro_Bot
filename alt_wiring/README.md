# Alt Wiring

SpiroBot's existing wiring is extremely simple (he's a beginner robot after-all!). Your likely thinking that if you could change the speed of its motors, then you could generate some more interesting effects.
To do this, you need to add a rheostat to the circuit. A rheostat in this kind of application is quite an inefficient way of controlling motor speed, but it will do for our needs.

Alt_Circuit.png provides the required schematic for speed control. As you can see we have added in an additional component, this is a potentimeter (a device who's resistance changes as you rotate a knob). The value of this component needs to be quite low (around 5K) -- 10K is much to big!
If your potentimeter has three outputs, you will need to run a wire to one of the outside and the middle pins (you can ignore the third pin), otherwise a two pin variety can just be wired up. The direction of this component doesn't matter.

 
