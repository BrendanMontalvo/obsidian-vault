Most elements are "block level" elements by default
- They have a width of 100% of their parent
- They have a height of 0
- The height grows to match the content
- They stack one on top of the other
New tags
- height
- width
Try to avoid setting heights because the box will auto fit the content that is being put inside of it without the height set. If you set the height, content can spill out because the height is now a rigid number.
<Strong>Margins</strong>
- margin-left
- margin-right
- margin-top
- margin-bottom
-Margins are like adding empty space but no background on the outside.

Margins accept a set width, but you can also use the `auto` keywrd.

`Auto` will automatically place all the available space on that side.

<Strong>Shorthand margin property</strong>
Example:
`margin: 10px 20px 30px 40px`
Order: Top right bottom left

Example 2:
`margin: 10px`
- will use 10px for all sides.

Example 3:
`margin: 10px 20px`
- will use top and bottom for 10 and left and right for 20.

Example 4:
`margin: 25px 10px 15px`
- first is top, second is left and right, third is bottom

<strong> Auto Shorthand </strong>
- Can use `auto` margin with shorthand for right and left but not top and bottom.



 