# Project-Curvetopia

The "Curvetopia" project is an innovative journey into the realm of 2D curves, with a focus on transforming and enhancing the visual and structural qualities of curves in Euclidean space. The primary objective is to develop a robust process that takes raster images of line art and converts them into a series of connected cubic Bézier curves. These curves are then regularized, symmetrical, and completed to form aesthetically pleasing and mathematically consistent shapes.

The project is divided into three core tasks:

Regularizing Curves: This task involves identifying and refining basic geometric shapes such as straight lines, circles, ellipses, rectangles, rounded rectangles, regular polygons, and star shapes within a set of curves. The aim is to standardize these shapes while distinguishing between regular and irregular forms. This process is particularly relevant for hand-drawn shapes and doodles, where the challenge lies in maintaining the essence of the original drawing while enhancing its regularity.

Exploring Symmetry in Curves: This task delves into the symmetry of closed curves, starting with reflection symmetry, where the goal is to identify lines of symmetry that divide a shape into mirrored halves. The project also explores how different sequences of Bézier curves can produce symmetrical shapes. The challenge here is to recognize symmetry even when the curves are represented differently, ensuring that identical Bézier curves can be fitted to symmetrical points.

Completing Incomplete Curves: This task focuses on addressing the issue of planarization, where overlapping portions of curves are removed, leaving gaps or incomplete shapes. The project aims to create algorithms that can naturally complete these curves, taking into account varying levels of occlusion. This includes cases where shapes are fully contained within another, partially contained but still connected, or completely disconnected due to occlusion. The goal is to achieve smooth, regular, and symmetrical completions that restore the integrity of the original shapes.

For visualization, the project utilizes SVG format, allowing the curves to be rendered in a web browser. The evaluation of the project is based on the regularization and symmetry of the curves, as well as the effectiveness of the curve completion algorithms. The use of SVG and rasterization techniques ensures that the results are not only mathematically sound but also visually appealing.

Overall, "Curvetopia" is an ambitious project that combines mathematical precision with artistic creativity, offering a comprehensive approach to transforming and beautifying 2D curves. The project holds significant potential for applications in computer graphics, design, and any field that involves the manipulation and enhancement of line art and shapes.
