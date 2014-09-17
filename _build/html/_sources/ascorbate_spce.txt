Ascorbate standard curve
=========================================


Reagents & Equipment
----------------------------

* CheapStat with adapter ver A
* Pine screen printed carbon electrode
* 0.1M KCl solution in distilled or deionized water [#f1]_ 
* Ascorbate [#f2]_
* Micropipettes
* Microcentrifuge tubes
* Deionized or distilled water


Cyclic voltammetry parameters
---------------------------------

* Start: 200 mV 
* Stop: 900 mV
* Slope: 50 mV/sec
* Sample rate: 5 mV/sample
* Cycles: 1

  
Method
-------------------------------

* Prepare a fresh stock of 100 mM ascorbate in 0.1M KCl. [#f3]_ 
* Dilute in 0.1M KCl to make a 1 mM ascorbate solution. [#f4]_ 
* Using 1 mL microcentrifuge tubes, prepare the following standard solutions of ascorbate

============================ ========================== ==========================
Ascorbate concentration (mM) Volume of 1mM stock (mL)   Volume of 0.1M KCl (mL)
============================ ========================== ==========================
          0.1                           0.10                       0.9
          0.2                           0.20                       0.8
          0.3                           0.30                       0.7
          0.4                           0.40                       0.6
============================ ========================== ==========================


* Connect the screen printed adapter ver A to the CheapStat and insert a screen printed electrode 
* Pipette 50 uL of 0.1M KCl onto the screen printed electrode
* Take a background reading, save data
* Next, pipette 50 uL of the first 0.1 mM ascorbate standard onto the screen printed electrode and run a measurement. 
* Repeat for all ascorbate concentrations, taking a new background reading between each ascorbate measurement.


Sample data
-------------

.. figure:: _static/ascorbate_spce_cheapstat.png
   :align:  center

.. figure:: _static/ascorbate_standards.png
   :align:  center

* Cyan = 0.1 mM ascorbate
* Red = 0.2 mM 
* Green = 0.3 mM 
* Blue = 0.4 mM    
 
Data Analysis
-----------------

To create a standard curve, subtract the background values from the data. Determine the current at 600mV for all samples. Plot a graph of ascorbate concentration (x-axis) versus measured current. 


.. figure:: _static/ascorbate_spce_linear_plot.png
   :align:  center


.. rubric:: Footnotes

.. [#f1] To prepare 500 mL of a 0.1M KCl solution: transfer 33 mL of 3M KCl stock (LabChem Part # LC18795-1) into a 500 mL volumetric flask. Fill to line with distilled or deionized water. Place stopper in flask and invert several times to mix.
.. [#f2] LabChem (www.labchem.com). Part # LC11530-9. $29.30 for 100 g.
.. [#f3] Example: 0.176g ascorbate in 10mL of 0.1M KCl = 100 mM stock
.. [#f4] Example, 100uL of 100mM ascorbate stock in 10 mL of 0.1M KCl = 1mM solution