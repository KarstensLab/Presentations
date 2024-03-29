Presentation by Lisa Karstens, PhD at the virtual useR2021 conference.   

Slides with a script of the presentation: [pdf](https://github.com/KarstensLab/Presentations/blob/main/useR2021/Microshades_presentation_UseR_2021.pdf) [html](https://karstenslab.github.io/Presentations/useR2021/Microshades_presentation_UseR_2021.html).   

[Link to repository](https://karstenslab.github.io/microshades)  

Abstract:    
Approximately 300 million people in the world have Color Vision Deficiency (CVD). When creating figures and graphics with color, it is important to consider that individuals with CVD will interact with this material, and may incorrectly perceive information associated with color. Multiple CVD friendly color palettes are available in R, however they are limited to 8 different colors. When working with complex data, such as microbiome data, this is insufficient. To overcome this limitation, we created the microshades R package, designed to provide custom color shading palettes that improve accessibility and data organization.    

The microshades package includes two crafted color palettes, microshades_cvd_palettes and microshades_palettes. Each color palette contains six base colors with five incremental light to dark shades, for a total of 30 available colors per palette type that can be directly applied to any plot. The microshades_cvd_palettes contain colors that are universally CVD friendly. The individual microshades_palettes are CVD friendly, but when used in conjunction with multiple microshades_palettes, are not universally accessible.   

The microshades package also contains functions to aid in data visualization such as creating stacked bar plots organized by a data-driven hierarchy. To further assist users with data storytelling, there are functions to sort data both vertically and horizontally based on ranked abundance or user specification. The accessibility and advanced color organization features help data reviewers and consumers notice visual patterns and trends in data easier. Examples of microshades in action are available on our website, for both microbiome and other datasets.  

