[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/Protoss78/score-element)

# score-element
A web component that I mainly use to pick a numeric score value from a predefined numeric range. The numeric range can be set by choosing a start and an end value. You can also define a step size (default is 1) and decimal precision (default is 0). The selected value can be get or set via the selected property. It uses the <a href="https://github.com/Protoss78/paper-button-group">paper-button-group</a> web component to generate the required paper-buttons. One button per calculated step is created.

Example:
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="../paper-styles/paper-styles.html">
    <link rel="import" href="score-element.html">
    <style>
      score-element {
        --hover-score-color: var(--paper-light-green-200);
        --selected-score-color: var(--paper-light-green-500);
        --selected--text-score-color: white;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<score-element selected="{{select1}}"></score-element>
<score-element start="0.5" end="2.0" step="0.1" decimals="1"></score-element>
<score-element class="green" start="0.5" end="2.0" step="0.1" decimals="1" ltr></score-element>
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
