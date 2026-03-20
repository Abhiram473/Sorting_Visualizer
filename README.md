# SORT.EXE — Algorithm Visualizer

A clean, minimalist sorting algorithm visualizer. Watch 7 classic sorting algorithms come to life with color-coded animations and real-time statistics.

## Algorithms (7)

| Algorithm | Best | Average | Worst | Space | Stable |
|-----------|------|---------|-------|-------|--------|
| Bubble Sort | O(n) | O(n²) | O(n²) | O(1) | ✓ |
| Selection Sort | O(n²) | O(n²) | O(n²) | O(1) | ✗ |
| Insertion Sort | O(n) | O(n²) | O(n²) | O(1) | ✓ |
| Merge Sort | O(n log n) | O(n log n) | O(n log n) | O(n) | ✓ |
| Quick Sort | O(n log n) | O(n log n) | O(n²) | O(log n) | ✗ |
| Heap Sort | O(n log n) | O(n log n) | O(n log n) | O(1) | ✗ |
| Shell Sort | O(n log n) | O(n^1.3) | O(n²) | O(1) | ✗ |

## Features

- **7 sorting algorithms** with smooth, color-coded animations
- **Real-time stats** — comparisons, array accesses, and elapsed time
- **Adjustable array size** (10–150 elements)
- **Variable speed** (1–200ms delay)
- **Pause / Resume** at any point
- Minimal dark UI — no clutter, just the sort

## Color Legend

| Color | Meaning |
|-------|---------|
| Dark gray | Unsorted |
| Blue | Comparing |
| Pink | Swapping |
| Yellow | Pivot (Quick Sort) |
| Green | Sorted |

## Quick Start
```bash
git clone https://github.com/Abhiram473/Sorting_Visualizer.git
cd Sorting_Visualizer
open index.html
```

Or visit the live demo: https://abhiram473.github.io/Sorting_Visualizer/

## How to Use

1. Pick an algorithm from the top row
2. Adjust array size and delay with the sliders
3. Hit **Start**
4. Use **Pause / Resume** to step through
5. **Reset** to generate a new random array

## Tech Stack

Pure HTML5 / CSS3 / JavaScript — no dependencies, no build step.  
Fonts: Space Grotesk + Space Mono (Google Fonts).

---

Made with 💜 by Abhiram
