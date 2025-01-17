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
  

https://www.autodesk.com/learn/ondemand/curated/get-started-with-modeling
