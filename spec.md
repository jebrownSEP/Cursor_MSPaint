Specification for MS Paint-like Web App (Vue + ThreeJS + Vuetify)

Overview

Develop a simple, MS Paint-like web application utilizing Vue, ThreeJS, and Vuetify, focusing initially on basic pencil drawing functionality, with the second pass adding regular polygons and RGB color fills.

Canvas Behavior

Type: Flat 2D canvas

Dimensions: Dynamically resizable based on window size

Content Scaling: Content scales proportionally with window resize

Zoom/Pan Controls: None

Persistence: Temporary drawings only (cleared upon page reload)

Tools and Functionalities

First Pass:

Pencil Tool:

Color: Black only

Stroke Width: Fixed at 2px

Drawing Behavior: Click-and-drag

Second Pass:

Shape Tool:

Available Shapes: Regular polygons ranging from 3 sides (triangle) to 8 sides (octagon)

Shape Rotation: Fixed orientation (no dynamic rotation)

Drawing Behavior: Initial click represents the polygon center; drag outward to size the shape.

Color Options:

Colors apply simultaneously to both shape outline and fill.

Palette: Predefined basic RGB colors only:

Black

White

Red

Green

Blue

Yellow

Cyan

Magenta

Shape Filling:

Default: Outline only

Optional: User-selectable fill with the same color as the outline

User Interface

Toolbar:

Horizontal toolbar fixed at the top of the screen

Always visible

Contains only essential tools:

Pencil

Shape selection (polygon sides: 3–8)

Basic RGB color selection

Tool Selection:

Single-tool selection mode (activating one tool deactivates any previously active tool)

Technologies

Frontend Framework: Vue.js

3D Library: ThreeJS (used for rendering 2D canvas)

UI Component Framework: Vuetify
