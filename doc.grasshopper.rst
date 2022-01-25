************************************
Robot Motion with RRC in Grasshopper
************************************

.. figure:: example-robot-motion-with-rrc.png
    :figclass: figure
    :class: figure-img img-fluid

.. figure:: example-grasshopper-script.png
    :figclass: figure
    :class: figure-img img-fluid

This example demonstrates a movement for an ABB robot using the COMPAS RRC 
python API from Grasshopper.

To run the example:

* Run `python -m compas_rhino.install` to install compas packages to Rhino and 
  Grasshopper. See `COMPAS - Rhino (Windows and Mac) <https://compas.dev/compas/latest/gettingstarted/rhino.html>`_
  for more details.
* Start the robot where the RRC driver is installed
* Start ROS driver using Docker (see example ``docker-compose.yml`` below)
* Open ``grasshopper_script.ghx`` in Grasshopper

For more details, check the `COMPAS RRC Start <https://github.com/compas-rrc/compas_rrc_start>`_ repository.

.. literalinclude:: docker-compose.yml
    :language: yaml
