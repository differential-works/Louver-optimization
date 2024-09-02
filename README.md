# Louver optimization template
![image](https://github.com/differential-works/Louver-optimization/blob/main/240902_Louver%20optimization_ani.gif) 

This repository contains a Grasshopper script that uses Ladybug to analyze the direct sunlight impact on a free-form canopy with adjustable louvres. The script allows users to generate canopy louvres, adjust their density, rotation, and angle, and directly observe the effect of shading below the canopy. Users can also customize the location and specific day of the year for accurate sunlight analysis. The Human plugin is used for enhanced visualization.

## Requirements & Installation
- Rhino 7 or later with Grasshopper
- Ladybug
- Weaverbird
- Human

## Grasshopper Definition
The script is organized into the following sections:
1. Louver Parameters: Set parameters for louvre density, rotation, and angle. These adjustments allow for fine-tuning of the shading performance.
2. Louver Generation: Use Weaverbird for mesh operations to create and refine the louvre geometry. This section ensures that the louvres are correctly visualized and functional.
3. Location and Date: Use Ladybug components to set the location and date, ensuring the analysis reflects real-world conditions.
4. Sunlight Analysis: Use Ladybug components to simulate sunlight based on the specified location and date. Evaluate the effectiveness of the louvres in providing shade.
5. Visualization: Use the Human plugin for enhanced visualization of the canopy louvres and shading effects.

![image](https://github.com/differential-works/Louver-optimization/blob/main/GH_Canvas.png)

## Contributing
We welcome contributions to improve the script! If you encounter any issues or have suggestions for enhancements, please feel free to reach out to us. Contact us at: hello@differential.works.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
Special thanks to the creators of Ladybug (Mostapha Sadeghipour Roudsari), Weaverbird (Giulio Piacentino), and Human (Andrew Heumann) for their powerful plugins that make this script possible.
