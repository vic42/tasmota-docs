# Buttons

Default buttons are logic *high* when not actuated and logic *low* when actuated. They have a *pull-up* resistor enabled on the respective GPIO (logic *high* when unconnected).

* `Button_i` inverts the logic levels.
* `Button_n` removes the pull-up resistor.
* `Button_in` both inverts and removes pull-up.
* `Button_tc` is an ESP32 touch button input.

