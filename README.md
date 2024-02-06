# CrochetPARADE

**!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!**

**The repository is hosted at:**

[https://codeberg.org/crochetparade/CrochetPARADE](https://codeberg.org/crochetparade/CrochetPARADE)

**!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!**

**!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!**

**!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!**

**!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!**

Author: Svetlin Tassev

CrochetPARADE (Crochet PAttern Renderer, Analyzer, and DEbugger) is a platform that allows users to create, visualize, and analyze both 2D and 3D crochet patterns.

The project is hosted at:

[https://www.crochetparade.org/](https://www.crochetparade.org/)


## OVERVIEW

CrochetPARADE uses a custom language grammar that allows users to define stitches and stitch patterns. The CrochetPARADE  grammar aims  to ensure accuracy and precision in the crochet pattern instructions, avoiding the ambiguities encountered with instructions in plain English. The code parses and checks any user provided pattern for correctness and then creates a virtual model of the project, which is then rendered in 3D.

After rendering a pattern, users can review ('debug') the final project's shape and make adjustments. The platform identifies overly loose or tight stitches, enabling users to replace them with more suitable ones before crocheting, thus reducing the need for blocking.

CrochetPARADE's export feature allows users to generate an SVG image that shows stitch connections and identifies stitches by their type, row number, and position within a row. The SVG pattern shows the same information as standard crochet diagrams and can be used as a guide when crocheting. Users can also export projects to 3D files that can be imported in <a href="https://www.blender.org">Blender</a> for further manipulation and visualization.


CrochetPARADE includes interactive features such as the ability to rotate, zoom, and pan the 3D view, as well as animating the pattern creation process, which can help in visualizing how stitches attach to each other. Additional features include highlighting and hiding selected stitches, and changing yarn thickness and color. Users can access stitch information by hovering over stitches in the 3D view.

CrochetPARADE performs all calculations locally on your device, ensuring that no data is collected to a central server or transmitted over the internet. As a side effect, the platform can be sluggish on old hardware. Models of patterns involving (tens of) thousands of stitches can take minutes or more to calculate.



## GOALS AND POSSIBLE APPLICATIONS

   * The main goal of CrochetPARADE is to facilitate crochet project design and execution.
   
   * Patterns created with CrochetPARADE can be easily shared,
ensuring they are free from ambiguities or typographic mistakes.
Creators can simply copy and paste the pattern text to share it,
and others can use the CrochetPARADE platform to render the shared text into a model of the pattern exactly as intended by the pattern author.
                
   * CrochetPARADE can be used in education to teach crocheting but also programming skills, since the CrochetPARADE grammar follows rules similar to those of real programming languages.
               
   * The virtual models created by CrochetPARADE can be imported in 3D modelling and CGI software. Picture an animated movie where characters
wear crochet hats and sweaters that match real-world crochet projects.

   * It is probably inevitable that the grammar along with the renderer can allow AI to learn how to write correct crochet instructions of complicated patterns (beyond simple amigurumi) based on general project descriptions.
   
## LICENSE AND COPYRIGHT

   * The website and all of its computational components are free and open source and are released under the <a href="https://www.gnu.org/licenses/gpl-3.0.en.html#license-text">GPLv3 license</a>. This ensures that the platform will be free and open to all in perpetuity.
   * The showcase patterns are either in the public domain (as specified in the pattern description) or are created by the author and are released in the public domain.
   * This user manual which includes a description of the CrochetPARADE grammar is released under the <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons BY-NC-SA</a> license. The grammar itself cannot be copyrighted and, as any language, is in the public domain.</li>
    
## ACKNOWLEDGEMENTS

CrochetPARADE uses the following libraries: <a href="https://svgjs.dev/">SVG.js</a> and
    <a href="https://threejs.org/">three.js</a>.

