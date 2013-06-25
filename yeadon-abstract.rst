Estimating the Inertia of the Human Body with Python

Jason K. Moore, UC Davis
Christopher Dembia, Stanford

Jason received his PhD from UC Davis in Mechanical and Aeronautical Engineeering
and is currently a researcher at the Institute for Transportation studies.
Chrispther is currently a graduate student at Stanford.

moorepants@gmail.com, cld72@cornell.edu

The Yeadon human body segment inertia model is a widely used method in the
biomechanical field that allows scientists to get quick and reliable estimations
of mass, mass location, and inertia estimates of any human body. The model is
formulated around a collection of stadia solids that are defined by a series of
width, perimeter, and circumference measurements. This talk will detail a Python
software package that implements the method and exposes a basic API for its use
within other code bases. The package also includes a text based user interface
and a graphical based user interface, both of which will be demonstrated. The
GUI is implemented with MayaVi and allows the user to manipulate the joint
angles of the human and instantaneously get inertia estimates for various poses.
Researchers that readily need body segment and human inertial parameters for
dynamical model development or other uses, should find this package useful for
quick interactive results. We will demonstrate the three methods of using the
package, cover the software design, show how the software can be integrated into
other packages, and demonstrate a non-trivial example of computing the inertial
properties of a human seated on a bicycle.

Source code: https://github.com/fitze/yeadon
Documentation: http://pythonhosted.org/yeadon/
Paper: https://github.com/fitze/humaninertiapaper (in preparation)
Website:
http://biosport.ucdavis.edu/research-projects/bicycle/bicycle-parameter-measurement/yeadon
Public Speaking Example: http://youtu.be/oKbaHCGK94E
