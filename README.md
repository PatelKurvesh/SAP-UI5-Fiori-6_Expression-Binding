# SAP-UI5-Fiori-6_Expression-Binding
<b>I.M.P Point:- Define [data-sap-ui-xx-bindingSyntax="complex"] in index.html.</b>

If you want to bind the value to the control on some condition or expression is called expression binding.

Expression binding in SAP UI5 is used to bind properties or expressions to an HTML control.

Syntax = "{= condition}"

"{= $expression ? true : false}"

Ex:- 
1) value="{= ${/cardata/star} > 3.00 ? 'Pass':'Fail'}" 

2) enabled="{= ${/cardata/star} > 3.00 ? true:false}"

3) value="{= ${/cardata/price} * 1.2 }"