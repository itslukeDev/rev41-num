# Rev41 Keyboard Config

Discovery notes: (idk what I'm doing so I'm jotting down what I figure out) 

For the layouts in `reviung41_num.keymaps`,
the positions of the keys are for readability,
ultimately it is just an array.

Their indices line up with the transform map in
`reviung_num_overlay.drsi`, which is also an array
that has been formatted for readibities sake.
Which I think is just to position the keys on zmk.studio


`reviung_num_layout.dtsi` contains another array of
53 `key_physical_attrs`, which also align with the
previous 2 arrays.
This one maps the read outs from the physical pins to
their index in the array.