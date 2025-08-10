# Narrative Visualization Essay

## Messaging

Heavier vehicles with larger engines get worse fuel economy. The visualization shows 8-cylinder cars averaging 14 MPG while 4-cylinder cars achieve 28+ MPG—double the efficiency.

## Narrative Structure

Martini glass structure: three guided scenes (the stem) followed by free exploration (the glass). Viewers learn the core message first, then explore on their own.

## Visual Structure

Consistent scatterplot across all scenes. 

Position shows weight vs MPG, color shows cylinders, size shows displacement. 

Yellow annotations highlight key insights. 

Dark theme makes data pop. 

Same layout throughout helps viewers focus on the story, not the interface.

## Scenes

1. **Overview**: Full dataset showing weight-MPG correlation
2. **Cylinders**: Highlights 4 vs 8-cylinder contrast
3. **Outliers**: Shows best/worst performers
4. **Explore**: User controls axes and filters

Ordered from general to specific to prepare users for exploration.

## Annotations

Yellow callout boxes with title and description. 2-3 per scene, changing to support each scene's message. 

Scene 1 explains trends, Scene 2 compares cylinders, Scene 3 identifies extremes. 

## Parameters

- `scene`: Current scene (0-3)
- `xField`/`yField`: Axis variables
- `highlight`: Which cars to emphasize
- `exploreUnlocked`: Blocks exploration until scenes viewed
- `currentData`: Filtered dataset

## Triggers

- **Navigation**: Next/Back buttons change scenes
- **Restart**: Returns to Scene 1
- **Exploration**: Dropdowns for axes and cylinder filter (explore mode only)
- **Hover**: Shows car details tooltip

Affordances: Disabled buttons gray out, "Next" becomes "Explore Mode" on last scene, controls appear only when available.
