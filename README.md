# FOSSEE Optimization Toolbox for Scilab

A toolbox that provides mixed integer linear programming, quadratic programming, non linear programming, and integer nonlinear programming tools in Scilab through the Symphony, CLP, BONMIN, CBC, and IPOPT  libraries.

Tested with Symphony 5.6.10, Ipopt 3.12.4 and Scilab 5.5.2

## To Download
1. [Visit the link
   `http://atoms.scilab.org/toolboxes/FOT/`](http://atoms.scilab.org/toolboxes/FOT/)
2. Select the linux or windows version as per your platform.
3. Extract the files.

## To use
1. In Scilab, change the working directory to the root directory of the repository
2. Run `exec loader.sce` in the scilab console.
3. The Toolbox is now ready, to see help type `help FOSSEE Optimization Toolbox` in console.
4. The demos are in `Demos folder`.
5. To run a demo type `exec <name of function>.dem.sce`
6. Test cases are in `tests folder`.

## To build
1. If you have updated the source code then you need to build it again to see the changes.
2. To build it first unlink the toolbox by executing the following command `ulink`.
3. Then type `exec builder.sce` to run the builder. {Prerequisites: In windows you need Visual Studio}
4. Now just run `exec loader.sce` in the scilab console. It will be ready to use.
