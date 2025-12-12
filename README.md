## Bird Song Classifier — Confusion Matrix (Front-end Only)

This simple web app visualizes a confusion matrix for a three-class "Bird Song Classifier" (Sparrow, Robin, Blue Jay). You can adjust prediction counts, load presets, and see how accuracy, precision, recall, and F1 change live.

### Run

Just open the file in any modern browser:

```bash
$BROWSER /workspaces/MachineLearningFinal/index.html
```

Or double-click index.html.

### Features
- Interactive 3×3 confusion matrix with heat coloring
- Editable counts for each actual→predicted pair
- Dynamic metrics: overall accuracy and per-class precision/recall/F1
- Preset scenarios: Balanced, Noisy Recording, Rare Blue Jay
- Randomize and Reset buttons

### Why this topic?
Bird songs are a fun domain for audio ML. The confusion matrix helps explain how often the classifier mixes up species, especially when recordings are noisy or one species is rare.

### Notes
- No libraries or backend required; pure HTML/CSS/JS.
- Feel free to change classes or presets inside index.html to fit your project.