# ion-radio

Radios are generally used as a set of related options inside of a group, but they can also be used alone. Pressing on a radio will check it. They can also be checked programmatically by setting the `checked` property.

An `ion-radio-group` can be used to group a set of radios. When radios are inside of a [radio group](../radio-group), only one radio in the group will be checked at any time. Pressing a radio will check it and uncheck the previously selected radio, if there is one. If a radio is not in a group with another radio, then both radios will have the ability to be checked at the same time.




<!-- Auto Generated Below -->


## Properties

#### checked

boolean

If true, the radio is selected. Defaults to `false`.


#### color

string

The color to use from your Sass `$colors` map.
Default options are: `"primary"`, `"secondary"`, `"tertiary"`, `"success"`, `"warning"`, `"danger"`, `"light"`, `"medium"`, and `"dark"`.


#### disabled

boolean

Indicates that the user cannot interact with the control.


#### mode

string

The mode determines which platform styles to use.
Possible values are: `"ios"` or `"md"`.


#### name

string

The name of the control, which is submitted with the form data.


#### value

string

the value of the radio.


## Attributes

#### checked

boolean

If true, the radio is selected. Defaults to `false`.


#### color

string

The color to use from your Sass `$colors` map.
Default options are: `"primary"`, `"secondary"`, `"tertiary"`, `"success"`, `"warning"`, `"danger"`, `"light"`, `"medium"`, and `"dark"`.


#### disabled

boolean

Indicates that the user cannot interact with the control.


#### mode

string

The mode determines which platform styles to use.
Possible values are: `"ios"` or `"md"`.


#### name

string

The name of the control, which is submitted with the form data.


#### value

string

the value of the radio.


## Events

#### ionBlur

Emitted when the radio button loses focus.


#### ionFocus

Emitted when the radio button has focus.


#### ionRadioDidLoad

Emitted when the radio loads.


#### ionRadioDidUnload

Emitted when the radio unloads.


#### ionSelect

Emitted when the radio button is selected.


#### ionStyle

Emitted when the styles change.



----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*
