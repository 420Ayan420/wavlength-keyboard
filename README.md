# wavelength-keyboard
A custom ortholinear bluetooth mechanical keyboard with a left-sided numpad. Supports low-profile Kalih Choc(olate) switches and has additional dev-connectors for accessing the MCU for other projects such as the [analog gauge based task manager](https://github.com/420Ayan420/analog-task-manager), etc.

![449329724_1714771669294222_836213951578030492_n](https://github.com/user-attachments/assets/d7d2f9a1-bdfb-4f14-8cf9-4316ccfec542)
![449798093_1847726172374343_1543262829728991966_n](https://github.com/user-attachments/assets/73575ad7-87a8-4bc9-826e-b8514ea001c4)

# keyboard layout
I am using ortholinear as it is more comfortable and natural to type on, I am also using a left-sided numpad making mouse positionining more comfortable. Using [KLE](http://www.keyboard-layout-editor.com/) (keyboard layout editor) you can open the `layout.json` file to edit/view it to your needs.

![layout image](https://github.com/420Ayan420/wavelength-keyboard/assets/88883638/266ece53-801a-4050-913e-34c41f0f44ee)

# hardware
I have chosen the nrf52840 MCU as it has abundant GPIO pins for all the rows and columns in my switch matrix, it also has built-in bluetooth support. Regarding the I have also chosen the [Choc v1](https://chosfox.com/products/kailh-chocs) switches as they are low profile and have hot-swap sockets.

