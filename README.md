# Deferred Shading Demo

A demo of deferred shading, SSAO and DOF. Originally made as a project in the course EDAN35 High Performance Computer Graphics at LTH. accumulate_lights, DOF_shader, SSAO_shader, SSAO_blur_shader, fill_gbuffer and parts of resolve deferred implemented by me (and my project partner). 

(Runs worse than it should since the base code for the project was set up to store depth non-linearly. This made certain depth comparisons break, until we transformed the depth values to linear view space. The issue was known, but the time for the project ran out.)
