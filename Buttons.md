# Buttons

Default buttons are logic *HIGH* when not actuated and logic *LOW* when actuated. They have a *pull-up* resistor enabled on the respective GPIO (logic *HIGH* when unconnected). A button is signalled in Tasmota upon **release** (a *rising edge* of the GPIO voltage by default). That way the duration of a button press can be recognized and acted upon.

!!! info "Available button components"

* `Button`    Default button
* `Button_i`  Button with inverted logic levels
* `Button_n`  Button without internal pull-up resistor enabled
* `Button_in` Inverted button without internal pull-up
* `Button_tc` ESP32 touch button input

# Switches

Default switches are logic *HIGH* when active. Tasmota reads `1` or `ON` when the respective GPIO is logic *HIGH* (+3.3V). They have a *pull-up* resistor enabled on the respective GPIO (logic *HIGH* when unconnected). A Switch is signalled in Tasmota upon state change, i.e. a transistion from logic *HIGH* to logic *LOW* or from logic *LOW* to *HIGH*, respectively.

!!! info "Available switch components"

* `Switch`    Default switch
* `Switch_n`  Switch without internal pull-up resistor enabled

