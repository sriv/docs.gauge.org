GAUGE-IntelliJ-001 : Gauge API Not Started
------------------------------------------

.. code-block:: text

    Could not start gauge api: Could not find executable in PATH or GAUGE_ROOT. Gauge is not installed.

This can occur because of following reasons :

- Gauge is not installed
- Gauge is installed at custom location and ``custom_install_location/bin`` is not in ``PATH``.

To Solve this :

- If gauge is not installed, :ref:`install gauge <installing_gauge_recomd_options>`.
- If gauge is installed at custom location, add ``custom_install_location/bin`` to ``PATH``
- On custom installation location Set ``GAUGE_ROOT`` to ``custom_install_location``
- Restart Intellij