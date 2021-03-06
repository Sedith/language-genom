# GenoM language package for Atom

This package provides syntax highlighting in Atom for the GenoM .gen description files.

The Generator of Modules GenoM is a tool to design real-time software architectures. It encapsulates software functions inside independent components. GenoM is more specifically dedicated to complex on-board systems, such as autonomous mobile robots or satellites, that require:

- The integration of heterogeneous functions with different real-time constraints and algorithm complexities (control of sensors and actuators, data processings, task planification, etc.).
- An homogeneous integration of these functions in a control architecture which requires coherent and predictable behaviors (starting, ending, error handling), and standard interfaces (configuration, control flow, data flow).
- The management of parallelization, physical distribution and portability of the functions. Simple procedures to add, modify or (re)use the functions by non-specialists

GenoM generates the source code of components by using:

- A generic template, common for all components. This guarantees that all components share the same consistent behaviour. The template itself is not part of GenoM, so that different template kind can be developped easily.
- A formal description of the components interface. This description is based on a simple language using OMG IDL for data types definitions and a custom syntax for the description of a more detailed component model.

The project is released under an open-source, BSD-like license.

For more details, sources and documentation, see <https://git.openrobots.org/projects/genom3>.

_TODO: add language definition to the readme_
