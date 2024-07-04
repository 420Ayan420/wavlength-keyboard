# wavelength-keyboard
A custom ortholinear bluetooth mechanical keyboard with a left-sided numpad. Supports low-profile Kalih Choc(olate) switches and has additional dev-connectors for accessing the MCU for other projects such as the [analog gauge based task manager](https://github.com/420Ayan420/analog-task-manager), etc. 

# sessions
## session #1
Completed the layout for the keyboard, I am using ortholinear as it is more comfortable and natural to type on. Using [KLE](http://www.keyboard-layout-editor.com/) (keyboard layout editor) you can open the `layout.json` file to edit/view it to your needs.

![layout image](https://github.com/420Ayan420/wavelength-keyboard/assets/88883638/266ece53-801a-4050-913e-34c41f0f44ee)

## session #2
I have chosen the nrf52840 MCU as it has abundant GPIO pins for all the rows and columns in my switch matrix, it also has built-in bluetooth support. Regarding the I have also chosen the [Choc v1](https://chosfox.com/products/kailh-chocs) switches as they are low profile and have hot-swap sockets.

![image](https://github.com/420Ayan420/wavelength-keyboard/assets/88883638/50d5ae8b-58b7-4289-b9a3-4063d9fa3b90)

## session #3
I have added the antenna and clock circuitry for the MCU. I am also beggining to ponder what slikscreen art I want on my board.

![image](https://github.com/420Ayan420/wavelength-keyboard/assets/88883638/fd1883fc-9f10-48f0-98f0-a71898425b69)

## session #4
I have continued with the MCu circuitry and have added the second clock as per the datasheet, this one took some time as the datasheet is over 600 pages long!

![image](https://github.com/420Ayan420/wavelength-keyboard/assets/88883638/81d2408b-34ca-4b56-a487-ff50f93be84a)
