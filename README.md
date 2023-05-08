Download Link: https://assignmentchef.com/product/solved-uwee572-lab4-90o-hybrid-design-at-2-4-ghz
<br>
The area occupied by microwave deviced on a PCB is often related to the cost of the product.  For other applications, the size of the final product such as a cell phone, dictates the PCB area on which microwave circuits must be fabricated.  To overcome this restriction, the commonly used technique is to deform the shape of a device while keeping the S-parameter unchanged.  One example of the 180 hybrid is shown below.

The design of a practical microwave circuit requires tuning/adjustment from the ideal TL model.  One example is a 90<sup>o</sup> hybrid shown below.  The left figure is a traditional layout using the ideal TL model .  At four corners we have a T-junction with different TL impedance.  This requires the edge trimming (mitering) as well as the adjustment of the TL length.  To simplify the design process we can use the modified 90<sup>o</sup> hybrid which is shown in the right figure.  This model has four identical T-junctions.

The purpose of this lab is to become familiar with the layout modification technique.  It is important to note that when the layout is changed, the function of the device (Sparameters at the designed frequency) should not change too much.

The 90 deg hybrids will be for the final project as shown below.  It will save your time if you complet a good layout design in HW4.

<h2>90<sup>o</sup> hybrid</h2>

<h2>Use of the 90<sup>o</sup> hybrid for the final project</h2>

<h1>1. Objectives</h1>

To design, construct, and test a 90<sup>o</sup> hybrid operating at <strong>2.4 GHz.</strong>  <strong><u> Make sure to allocate</u> <u>at least 7 mm of microstrip TL for each SMA connector</u></strong>.  All discontinuities such as TL steps must be included in the simulations.  The simulation based on the circuit model in ED seems to be accurate up to 2 GHz range.  Beyond 3 GHz, the EM simulation is needed to verify the performance. The EM simulations must be conducted to check the performance of the circuit model.

<h2>Required layout of the 90 deg hybrid</h2>

<strong>The important design goals </strong>

<ul>

 <li>difference between |S21| and |S31| is within 0.5 dB at the designed freq.</li>

 <li>difference between |S24| and |S34| is within 0.5 dB at the designed freq.</li>

 <li>Phase difference between S21 and S31 is within +-2.5 deg of 90 at the designed freq.</li>

</ul>

Aim for 87.5 to 92.5 deg

<ul>

 <li>Isolation: |S14|, and |S23| should be less than -20 dB at the designed freq.</li>

</ul>

<strong>The secondary design goals </strong>

Port matching condition: |S11|, |S22|, |S33|, and |S44| should be less than -20 dB at the designed freq.

The Edge taper for SMA connectors is not needed for simulations.

<h1>2. Software</h1>

Software: Ansoft ED (Circuit and EM simulations)

<ol start="3">

 <li><strong> Supplies </strong>PCB substrate</li>

</ol>

Roger Duroid 5870, Dielectric constant=2.33,  Thickness=1.57mm (62.0 mil).

<h1>4. 90 hybrid</h1>

90 degree hybrid is a simple 3 dB coupler with 0<sup> o</sup> or 90<sup>o</sup> phase difference between two output ports.  The S-parameter of this four-port device is shown below.




<ol start="5">

 <li><strong> Design Procedures</strong></li>

</ol>

<h1>Step1: Circuit Simulations</h1>

Using ED, calculate the width and length of the TLs.  The effective dielectric constant depends on the characteristic impedance.

Using ED, design a hybrid with the following characteristics. The simulation must be done for the expected layout pattern including 90 degree bend and T-sections. You may use the optimization function to optimize the length.  See ED Optimization tutorial.

<strong>Important:  The final layout should not have any gaps.  Make sure all TLs are connected correctly. </strong>

Center freq.=<strong>2.4</strong> GHz

Port 1 excitation: Phase(S21)-Phase(S31)=90<sup>o</sup>, Mag(S21)=Mag(S31)=-3dB.

Port 4 excitation: Phase(S24)-Phase(S34)=90<sup>o</sup>, Mag(S24)=Mag(S34)=-3dB.

All ports should be matched.

Port1 excitation: Plot S11, S21, S31, and S41 from 1 to 6 GHz.

Port4 excitation: Plot S44, S24, S34, and S14 from 1 to 6 GHz. Isolation: Plot S23 and S14 from 1 to 6 GHz.

<h1>Step 2:  Circuit Layout</h1>

Make sure to add <strong>your name</strong>, <strong>10 mm</strong> <strong>reference scale</strong>, and other information such as the designed frequency in your layout.

This can be done in AutoCAD if you can use it. Export and save it as an AutoCAD file.

Leave enough TL length for SMA connectors (<strong>at least 7 mm is needed</strong>).  Make sure each port has the same TL length from the 190 hybrid to keep the phase difference the same.

<strong>Not needed in this HW:</strong> Also the edge must be taper to accomodate the narrow center pin (See the layout by Ani).

<h1>6. EM simulations of the hybrid (Required in 2020)</h1>

The EM simulation of your design is required.  However, you don’t need to revise the design and optimize the performance based on the EM simulations.  Do the EM simulations of your layout and compare the results obtained from the circuit simulations with that of EM simulations. Attach results in the report. To learn EM simulations, see the Designer tutorial.

<h1>7.  Analysis and Discussions</h1>

If the EM simulation data is significantly different from the expected values, explain the reason.

<h1>8.  HW Problem (Required in 2020)</h1>

<strong>A four-port network is shown below.  Obtain the 4×4 [S] parameters using the even- and odd-mode technique.</strong> You may use ED (ideal TL model) for checking your answers.  However, the method to obtain [S] parameters must be shown and the simulation alone will not be sufficient.

Note: The center point of the right side is connected to the ground.

<strong>The following items must be included with your lab notebook.</strong>

<ol>

 <li>Title and name</li>

 <li>Objectives and Introduction</li>

 <li>Simulations data from Designer</li>

 <li>Circuit layout</li>

 <li>EM simulation data</li>

 <li>Discussion and conclutions</li>

</ol>

<h1>Appendix I Quadrature hybrid</h1>

Quadrature hybrid is a simple 3 dB coupler with 90<sup>o</sup> phase difference between two output ports.  The S-parameter of this four-port device is shown below.

<h2>Different 90<sup>o</sup> hybrid layout option</h2>

The sector section can be reduced to compensate the parasitic impedance.

<h1>Examples of Non-Circular 180 degree Hybrid</h1>