## Modeling

### Components and Bodies
- all parts are laid out as components
- can save new extrusions as different components, group them, and paste duplicates
- in data panel of project, can reference external components
- body is a single container for a **contiguous** 3D shape
- container can have multiple bodies, but no joints or motion between them
- copy and pasted bodies are not linked (but components are)

### Sketching
- sketches are underlying geometry that support 3D solid/surface/t-spline
- starts on an initial plane, then shape -> modify -> add constraints
- automatic contraints (such as bound to origin) when snapped to point in grid
- before extruding to 3D shape, sketch must be closed profile (no gaps and shaded in blue)
- fillet can be used to round corners (on intersection of two straight lines)
- make sure to close any lines removed from fillets

### Constraints
- defined sketches have some dimensional or positional relationship with other sketch features (i.e. moving edges in space that you don't want to do)
- undefined sketches are blue, fully defined are black lines
- use constraints to define the sketch
  - horizontal/vertical lines
  - tangent for rounded corners
  - sketch dimension for number dimensions
  - etc.
- construction lines can be used to make sure everything is in line, midpoint and center to the origin
- use coincident to line up the endpoints of construction lines (dashed) with perimiter (black) lines
  - now when modifying perimeter, construction lines also adjust
- make sure to add dimensions to fully define the sketch

### Extruding solid bodies
- can extrude/create a solid body from a sketch
- "symmetric" to add solid to both sides
- can extrude "thin" features which is like a wall/border of the sketch to protrude off it
- hold on object to see all hidden geometry
- if new extrusion overlaps with existing, it switches to cut so it removes from the solid
- to have the cut remove any material in future, "extend to all"
- "symmetric" to get both sides on that plane

### Modify solid bodies with press/pull
- press and pull, fusion automatically opens dialog

### Add fillets to solid bodies

https://www.autodesk.com/learn/ondemand/curated/get-started-with-modeling
