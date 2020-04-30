# ILI9341
The driver code for ILI9341 screen on TM4C123. [Link to the part](https://www.amazon.com/HiLetgo-240X320-Resolution-Display-ILI9341/dp/B073R7BH1B/ref=sr_1_1_sspa?dchild=1&keywords=ili9341&qid=1588215738&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUExQVBWNlBVT0VBTENJJmVuY3J5cHRlZElkPUEwNjAzMTk3MkI2RlFDSVVZRDRXSCZlbmNyeXB0ZWRBZElkPUExMDM2MTY1TEdQM1o4NjlKOUc2JndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==)

## Pinouts
Refer to the inline documentation

## Initialization
Initialize SPI to send commands to the LCD, and call the method `ILI9341_InitR(INITR_BLACKTAB)` to initialize the screen.