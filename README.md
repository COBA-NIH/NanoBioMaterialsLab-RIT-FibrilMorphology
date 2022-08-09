# Gaborski lab fiber segmentation project

This DBP repo includes materials for segmenting fibers segmented by migrating cells in images provided by [Tom Gaborski's lab](http://www.gaborskilab.org/) at RIT.

This repo contains two approaches to solving the central problem posed by this data: how to segment deposited fibers accurately.

These images are challenging to segment because:
* The fibers are heterogeneous in brightness
* Most tools are built to identify cells or other round-ish shapes. We need to be able to segment fibers, which form very irregular shapes
* We'd like one solution that can work well across multiple fiber types, which often look different from each other

The first approach (Initial_solution_CellProfiler) was created by Pearl Ryder and uses a CellProfiler pipeline to segment fibronectin images.
The second approach (Revised_solution_CellProfiler_ilastik) was created by Melissa Gillis and Rebecca Senft and involves combining a CellProfiler pipeline with a machine learning model built in ilastik.

More details can be found for both approaches on their respective blogposts:
  * [Thinking like an Image Analyst](https://carpenter-singh-lab.broadinstitute.org/blog/thinking-image-analyst-part-i-project-overview-and-data-import) by Pearl Ryder
  * Customizing a Model for Fiber Segmentation (coming soon) by Melissa Gillis
