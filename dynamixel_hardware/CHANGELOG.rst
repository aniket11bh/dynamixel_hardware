^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package dynamixel_hardware
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.1 (2023-12-22)
------------------
* Revised control mode changes, added set_joint_params - Rolling (`#65 <https://github.com/aniket11bh/dynamixel_hardware/issues/65>`_)
  * revised control mode changes, added set_params
  * removed unnecessary comment
* Missing comma for setting Position_D_Gain (`#56 <https://github.com/aniket11bh/dynamixel_hardware/issues/56>`_)
  * comment out unused paramter
  * A comma is missing for setting the Position_D_Gain
  ---------
  Co-authored-by: Yutaka Kondo <yutaka.kondo@youtalk.jp>
  Co-authored-by: Kenji Brameld <kenjibrameld@gmail.com>
* Merge pull request `#39 <https://github.com/aniket11bh/dynamixel_hardware/issues/39>`_ from ijnek/ijnek-unused-parameters
  Comment out unused paramter
* comment out unused paramter
* Merge pull request `#31 <https://github.com/aniket11bh/dynamixel_hardware/issues/31>`_ from ijnek/ijnek-unused-parameter-2
  Fix unused parameter (just rolling branch)
* Update dynamixel_hardware/src/dynamixel_hardware.cpp
  Co-authored-by: Yutaka Kondo <yutaka.kondo@youtalk.jp>
* Update dynamixel_hardware/src/dynamixel_hardware.cpp
  Co-authored-by: Yutaka Kondo <yutaka.kondo@youtalk.jp>
* fix unused paramter in rolling branch
* Merge pull request `#25 <https://github.com/aniket11bh/dynamixel_hardware/issues/25>`_ from ijnek/ijnek-new-hardware-interface
  adapt to new hardware interface read and write methods
* Merge pull request `#24 <https://github.com/aniket11bh/dynamixel_hardware/issues/24>`_ from ijnek/ijnek-add-callbackreturn-reference
  fix 'CallbackReturn' does not name a type
* adapt to new hardware interface read and write methods
* fix 'CallbackReturn' does not name a type
* Merge pull request `#20 <https://github.com/aniket11bh/dynamixel_hardware/issues/20>`_ from pdenes/add-extra-params
  Add extra (optional) parameters for joints
* Merge pull request `#19 <https://github.com/aniket11bh/dynamixel_hardware/issues/19>`_ from pdenes/add-dependencies
  Add missing dependencies
* Add missing dependencies
* Add extra (optional) parameters for joints
  This allows to set "Profile_Velocity", "Pofile_Acceleration" and PID values.
* Merge pull request `#17 <https://github.com/aniket11bh/dynamixel_hardware/issues/17>`_ from youtalk/galactic
  Galactic
* Merge pull request `#16 <https://github.com/aniket11bh/dynamixel_hardware/issues/16>`_ from Schnilz/main
  ported to galactic
* ported to galactic
* Merge pull request `#13 <https://github.com/aniket11bh/dynamixel_hardware/issues/13>`_ from youtalk/change-loglevel
  Change log level to ERROR in read/write methods
* change to error level
* Merge pull request `#10 <https://github.com/aniket11bh/dynamixel_hardware/issues/10>`_ from youtalk/joint-id
  Remove joint_ids param and add id params
* remove ids param and add id params
* use return_type
* add reset_command
* add force_set argument
* test velocity control
* fix initial command
* fix write
* export velocity command interface
* add set_control_mode
* Merge pull request `#1 <https://github.com/aniket11bh/dynamixel_hardware/issues/1>`_ from youtalk/velocity-control
  Velocity control
* revert line feed
* add control mode
* check torque on/off error
* implement velocity control
* fix ament_cpplint
* fix use_dummy
* fix initial pose
* refine start
* refine start
* fixing bug
* adjust logging level
* fix read and write
* add logs
* fix copy bug
* log method names
* fix bug
* enable to launch
* add use_dummy\_
* remove readme
* move to subdir
* Contributors: Geoff Sokoll, Kenji Brameld, Lass6230, Nils Schulte, Pal Denes, Yutaka Kondo
