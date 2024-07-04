# wavelength-keyboard
A custom ortholinear bluetooth mechanical keyboard with a left-sided numpad. Supports low-profile Kalih Choc(olate) switches and has additional dev-connectors for accessing the MCU for other projects such as the [analog gauge based task manager](https://github.com/420Ayan420/analog-task-manager), etc. 

# sessions
## session #1
Completed the layout for the keyboard, I am using ortholinear as it is more comfortable and natural to type on. Using [KLE](http://www.keyboard-layout-editor.com/) (keyboard layout editor) you can open the `layout.json` file to edit/view it to your needs.
![keyboard layout](https://github.com/[420ayan420]/[wavelength-keyboard]/blob/[main]/layout.png?raw=true)

## session #2
I have chosen the nrf52840 MCU as it has abundant GPIO pins for all the rows and columns in my switch matrix, it also has built-in bluetooth support. Regarding the I have also chosen the [Choc v1](https://chosfox.com/products/kailh-chocs) switches as they are low profile and have hot-swap sockets.
