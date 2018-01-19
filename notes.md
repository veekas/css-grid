# CSS Grid Notes

- rows/columns called *tracks*
- *explicit* grid:
  + solid, dashed in Firefox inspector
  + code explicitly gives sizing info
- *implicit* grid:
  + dotted line in Firefox inspector
  + code **does not** explicitly give sizing info, but instead these grid elements are formed by default
- percentages cause problems because of `grid-gap`, use `fr` instead
- *`fr`*: fractional units, which represent all the space left after the items are laid out
- `auto-fill` is cool for responsive layouts
