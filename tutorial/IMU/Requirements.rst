*************************
Application Requirements
*************************

.. contents:: Contents
    :local:
    
.. sectionauthor:: Joseph S Motyka <jmotyka at aceinna.com>


Development of an application requires system level requirements that describe the purpose of the
application.  These requirements provide a guide for product development.  For the IMU application,
the following were selected:

    1. Measure acceleration, angular-rate, local magnetic-field, and sensor temperature data

    2. Generate an output message consisting of the following:
    
       a. A relative time measurement (both integer and decimal values)
       b. Acceleration readings in :math:`[g]`
       c. Rate-sensor readings in [°/s]
       d. Magnetic-field readings in :math:`[G]`
       e. Sensor temperature readings in [°C]

    3. Provide the data at user-selectable output data-rates (ODR) up to 200 Hz

