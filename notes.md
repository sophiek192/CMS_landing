// Selectors - Name tag for HTML elements - What elments to style
// Properties - Style attributes - E.g colour/margin
// Values - e.g red, 25%


Simple Selectors:
- Tag Name:
- Id: Can give things id e.g <p=id=para1>
=> Then in the style tag, target it
#para1 {
    font-weight: bold;
    font-size: 130%
}
=> Can apply to different element, as long as they have the same class
- Class:

// Different selectors share the same design property
h1, h2, p {
    background-colour: Cornsilk
}

Ways to add CSS:
// Internal -
// External -
To link => ADD LINK =>
<link rel="stylesheet" href="mystyle.css"> => Adopt style defined in this file

// Inline - 