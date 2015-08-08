# score-element
A web component that I mainly use to pick a numeric score value from a predefined numeric range. The numeric range can be set by choosing a start and an end value. You can also define a step size (default is 1) and decimal precision (default is 0). The selected value can be get or set via the selected property. It uses the <a href="https://github.com/Protoss78/paper-button-group">paper-button-group</a> web component to generate the required paper-buttons. One button per calculated step is created.

Example:

```html
<div>
  <score-element selected="{{select1}}"></score-element>
  <score-element start="5" end="15"></score-element>
  <score-element start="0.5" end="2.0" step="0.1" decimals="1"></score-element>
</div>
```

Available Style Variables:
```
--button-score-color:         Defines the background color of the button
--text-score-color:           Defines the text color of the button
--hover-score-color:          Defines the background color of the button in hover state
--hover-text-score-color:     Defines the text color of the button in hover state
--selected-score-color:       Defines the background color of the button in selected state
--selected--text-score-color: Defines the text color of the button in hover state
```

A working example can be found in the <a href="http://protoss78.github.io/score-element/">demo application</a>
