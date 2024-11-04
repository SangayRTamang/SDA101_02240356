Initialization: When the ToggleButton is created, it checks localStorage to see if a state is already saved. If it’s "on", this.isOn is set to true; otherwise, it's false.

Rendering the Button: The updateButton method sets the button text (ON or OFF) and background color (green for ON and red for OFF) based on this.isOn.

Toggling State: The toggle method inverts this.isOn, updates the localStorage with the new state, calls updateButton to reflect the change, and dispatches the "toggle-changed" custom event with the new state in detail.

Event Listener: At the bottom, an event listener on <toggle-button> listens for the "toggle-changed" event and logs the new state in the console.