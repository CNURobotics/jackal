^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package jackal_description
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Forthcoming
-----------.
* Merge pull request `#56 <https://github.com/jackal/jackal/issues/56>`_ from jackal/urdf_additions
  Added all extra fender changes
* Added all extra fender changes
* Contributors: Dave Niewinski

* Made minor changes to syntax for kinetic warnings
* Contributors: Dave Niewinski

* Added stereo camera accessory.
* Removed unused variable jackal_description_dir
* Make urdf refer explicitly to jackal_description, rather than relying on current working directory being correct, for easier external includes
* Contributors: Arnold Kalmbach, Tony Baltovski, akalmbach

0.5.1 (2015-02-02)
------------------
* Modified the accessories.urdf.xacro to include both the GPS and mount plate, including standoffs.
* Eliminate rosrun from the xacro wrapper.
* Contributors: BryceVoort, Mike Purvis

0.5.0 (2015-01-20)
------------------
* Add hook for custom URDF insertion to jackal.urdf.xacro.
* Add xacro wrapper script to provide some pre-cooked "configs", especially for simulated Jackal.
* Switch to parameterizing URDF with optenv.
* Add laser bracket STL.
* Contributors: Mike Purvis

0.4.2 (2015-01-14)
------------------

0.4.1 (2015-01-07)
------------------

0.4.0 (2014-12-12)
------------------
* add pointgrey camera
* Removed inertial and geometry of the base_link.
* hector gazebo plugin for gps is added.
* hector gazebo plugin for imu sensor is added
* Contributors: Mike Purvis, spourmehr

0.3.0 (2014-09-10)
------------------
* Add comment about accessory args.
* Add front laser accessory to description.
* Contributors: Mike Purvis

0.2.1 (2014-09-10)
------------------

0.2.0 (2014-09-09)
------------------
* Changed physical and collision properties.
* Fixed inertia parameters. Added imu plugin--not working
* Install launch directory.
* Contributors: Mike Purvis, Shokoofeh

0.1.1 (2014-09-06)
------------------
* Remove unnecessary find packages.
* Contributors: Mike Purvis

0.1.0 (2014-09-05)
------------------
* Updated description with v0.9 hardware changes.
* Contributors: Mike Purvis
