# Funny-and-Interactive-Circuit
Arduino based interactive circuit.
In a world full of unpredictable humans, we created a solution: the Mood Detector 3000™ — a snarky little machine that doesn’t just sense your distance, it senses your vibe.

This is not your average blinking LED project. No sir. This is a judgmental box of wires powered by Arduino, that:

Uses an ultrasonic sensor to measure how close you are,

Runs your distance through its Mood Algorithm™ (a bunch of if-else conditions),

Then delivers passive-aggressive comments on a bright LCD screen,

While flashing LEDs and screaming through a buzzer, because why not?

It’s basically a therapist.
Except cheaper.
And meaner.
And made of plastic.

COMPONENTS USED:Arduino UNO,Ultrasonic sensor,i2c icd,led,active buzzer

Mood Detection Logic

More than 100 cm away
➤ “Why so shy? Come back!”
➤ No lights, no beeps. It’s sad.

50–100 cm away
➤ “Hmm, you look calm... for now.”
➤ Green LED lights up. Buzzer is quiet.

20–50 cm away
➤ “You good? You seem nervous.”
➤ LCD stares at you. Arduino is suspicious. No lights. It’s watching.

Less than 20 cm away
➤ “ALERT: Angry human approaching! Shield me!”
➤ Red LED flashes. Buzzer screams. Arduino panics.
➤ And maybe, just maybe, you question your life decisions.
