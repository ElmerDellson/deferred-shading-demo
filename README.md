# Deferred Shading Demo with SSAO and DOF

A demo of deferred shading, Screen Space Ambient Occlusion and Depth Of Field. Originally made as a project in the course EDAN35 High Performance Computer Graphics at LTH. accumulate_lights, DOF_shader, SSAO_shader, SSAO_blur_shader, fill_gbuffer and parts of resolve deferred were implemented by me (and my project partner).

A video demonstrating the major features can be seen here: https://www.youtube.com/watch?v=eQC-1Hqubd8&ab_channel=ElmerDellson

Full source code for this project can be found here: https://github.com/ElmerDellson/deferred-shading-full

# Controls
Move with WASD, look around by clicking and dragging with the mouse.

(Runs worse than it should since the base code for the project was set up to store depth non-linearly. This made certain depth comparisons break, until we transformed the depth values to linear view space (at high cost). The issue was known, but the time for the project ran out.)
