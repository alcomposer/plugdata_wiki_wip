## Audio

<img width="249" alt="Screenshot 2022-09-03 at 17 06 06" src="https://user-images.githubusercontent.com/44585538/188276594-98e281ba-3676-4976-bac0-67c0f6dc5de0.png">

The [adc~] and [dac~] objects are used to handle audio IO, both in the standalone and the plugin version. Make sure DSP is enabled, and the master volume is on.
<img width="400" alt="Screenshot 2022-09-03 at 17 09 39" src="https://user-images.githubusercontent.com/44585538/188276858-ef84c757-0054-415c-9aca-9d8f85bd8a12.png">

If you are using the standalone and you don't get any audio IO, check your audio settings in the settings panel.

<img width="500" alt="Screenshot 2022-09-02 at 14 09 45" src="https://user-images.githubusercontent.com/44585538/188276795-1308f265-3b2a-4402-ba45-0a63baf45cf7.png">


## Communicating with the DAW

<img width="300" alt="Screenshot 2022-09-02 at 14 09 45" src="https://user-images.githubusercontent.com/44585538/188276719-6cc7449c-ff67-4304-b403-1a3a1e8d5fc6.png">

The [param] object is used to send/receive DAW automation. It takes one argument, the index of the parameter you want to send/receive. You can also create a [param] object from the automation panel.

<img width="549" alt="Screenshot 2022-09-03 at 17 14 49" src="https://user-images.githubusercontent.com/44585538/188277015-a59f899c-dbe5-40e4-8d74-8b2d2bb87953.png">

The [playhead] object can be used to receive information about the current position of the DAW's playhead. It also passes on various other information, such as BPM, time signature, loop status and more.

For more information about [param] and [playhead], right click on the object and select "Help".


