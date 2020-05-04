# Face Shield X
A non-planar PPE design for high speed mass production with large scale multi-axis 3D printers

<img src="/images/face_shield_1.PNG" alt="Face Shield X"
	title="Face Shield X" width="800" />

## Motivation
3D printing is widely being used for producing face shields and other PPE that are in shortage during the Codid-19 pandemic. While design solutions and production instructions are widely available for desktop 3D printers, there is a lack of information for producing the same products with large scale industrial 3D printers such as the ones we are developing at [Ai Build](https://www.ai-build.com/). The goal of this project is to share our knowledge, methods and an open-source design for increasing the efficiency of PPE production by up to 100x. With this technique, a stack of 1200 pieces can be mass manufactured per day per machine without human supervision, in under 60 seconds per piece.

Our design is optimized with the principles below using AiSync software.
* A large extrusion diameter (2-4mm instead of 0.4-0.8mm)
* A continuous toolpath with no breaks
* Variable wall thickness
* Variable layer height
* Non-planar layers

## Hardware requirements
* 2mm nozzle diameter
* 2.5kg/hr throughput (slower extrusion is ok but the production time would be longer than 60 seconds)
* Min 30mm / 45° collision free dive distance on the end-effector

## Printing instructions
* Use PETG
* Print at a low temperature with active cooling for easy breakdown of stacks
* Print one of the support structures in the support folder first
* Then print one of the following files
  * 1x
  * 100x
  * 1200x
  
<img src="/1200x/stack_1200.PNG" alt="1200x"
	title="1200x" width="800" />

## Assembly instructions
* Cut the visor from 0.2mm thick a4 transparent sheets with a laser cutter or by scissors using the template in the visor folder
* Slide in the visor between the two front curves of the 3D printed frame
* This curved design will sit tightly between the ears and the forehead without the need of a rubber band.

## About source files
* The source files are encoded using our favorite, beam lattice specification of 3MF file format, being developed by the [3MF Consortium](https://3mf.io/).
* More information about how to read the source files can be found [here](https://github.com/3MFConsortium/spec_beamlattice/blob/master/3MF%20Beam%20Lattice%20Extension.md).

## Contributing
We welcome owners and producers of compatible 3D printers to fork the repository and make improvements for their own production.

Manufacturers can contact us at info@ai-build.com to get software support for generating machine specific instructions free of charge during the pandemic.

## Disclaimer

Ai Build has no experience of manufacturing medical equipment. This product is neither tested in a clinical environment nor certified for any purpose. The design and methods demonstrated in this project are purely a technological demonstration of large scale multi-axis 3D printing. Ai Build (including its parents, affiliates, officers, directors, employees or agents) does not accept liability for any damages, including but not limited to hardware or software, economic loss, loss of clients or partners, damages to the property, lost or corrupted data, injuries or death.

## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Face Shield X design</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://www.ai-build.com/" property="cc:attributionName" rel="cc:attributionURL">Ai Build</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
