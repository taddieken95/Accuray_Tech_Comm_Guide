# Commonly Used Accuray Terms

> This section will provide clarification on some commonly utilized Accuray terms and acronyms.


## Accuray Terminology

* **Collimation:** The process of shaping a therapeutic beam by using materials which attentuate the radiation. These materials are placed in front of the beam to define the shape of the beam.

* **Collimator:** The device used for collimation. The TomoTherapy machine has two (2) collimating devices: *the Primary Collimator* (including the Integrated Jaw Assembly) and the *Multileaf Collimator (MLC)*. 

* **Collimator Jaws:** A device that opens and closes to allow radiation to pass from the linac to the MLC. The collimator jaws define the initial shape and intensity of the radiation beam (primary collimation) before the beam is modified by the MLC.

* **Common Frame:** The graphical user interface (GUI) framework of the TomoTherapy software. Common to both the Planning Station and the Operator Station, it provides access for frequent tasks such as including system access and security, accessing patient data, viewing embedded online help, and accessing troubleshooting and maintenance tools.

* **Delivery Subsystem:** Operator Station, Status Console, Patient Couch, Gantry Assembly, and Radiation Delivery subsystems.

* **Disease:** Defines the treatment target (for example, prostate, lung, or brain) at a given period of time.

* **Dose Volume:** A type of Image Volume that assigns a dose value to every voxel in a 3-D region; used to calculate isodose lines.

* **Imaging Procedure:** The steps required to operate the delivery subsystem when acquiring TomoImage sets.

* **Importance:** The weighting that the optimization algorithm gives to all parameters associated with a given structure in relation to all other structures included in the plan.

* **Isodose Lines:** Lines drawn over an image that indicated closed contours of constant dose.

* **Isodose Wash:** Semi-transparent colored areas on an image that indicate areas between two (2) specified dose limits. Each voxel in an isodose wash receives an amount of radiation within the limits specified.

* **Jaws:** A device that opens and closes to allow radiation to pass from the linear accelerator to the MLC. The collimator jaws define the initial shape and intensity of the radiation beam before the beam is modified by the MLC.

* **Linac (Linear Accelerator):** A device that uses a number of vacuum cavities, each of which adds energy to an electron beam, accelerating them to high energies in the megavoltage range. The linac directs the high energy electrons to a target, where they collide to produce high-energy photons.

* **Maximum Dose:** A value denoting the highest desired dose level to be delivered to a structure.

* **Maximum Dose Penalty:** A value denoting the weight given by the optimization algorithm in order to meet the maximum dose value.

* **Minimum Dose Penalty:** A value denoting the weight given by the opitmization algorithm to meeting the minimum dose value.

* **Modulation Factor:** Determines the range of intensity values that are allowed in the optimized plan. The modulation factor is calculated from the leaf sinogram, and is defined as the greatest leaf intensity, divided by the average intensity for all non-zero leaves.

* **Multileaf Collimator (MLC):** A device that opens and closes individual leaves to regulate the amount of radiation passing through to the patient.

* **Normalized Dose:** The dose for a given point as a percentage of the reference prescribed dose.

* **On Board Computer (OBC):** Controls the communications on the rotating ring and the DAS.

* **Operator Station:** A workstation that is connected to the Data Server that is used to control and monitor TomoImage set acquisitions and TomoTherapy treatments.

* **Optimization Server:** A calculation server used to optimize treatment plans.

* **Optimized Treatment Planning:** A process in which the appropriate beam pattern, position, and intensity are calculated based on the physician's prescription for how much radiation the tumor should receive.

* **Overlap Priority:** A value denoting the relation of a given structure to other structures of the same tissue type.

* **Ready Position (Couch):** The position of the patient couch (inside the bore of the gantry) as defined by offsets from the actual setup position.

* **Ready State:** A closed state of the safety interlocks, in which the patient is in the ready position (inside the bore of the gantry), interlocks are closed, and the system is ready to initiate irradiation.

* **Region at Risk (RAR):** Sensitive structures where the radiation dose must be minimized.

* **Region of Interest (ROI):** An area of the patient's anatomy encompassing a target (tumor) or any sensitive structure.

* **Registration:** The process (either manual or automatic) of comparing and aligning data sets to yield a correlation between those data sets.

* **TomoImage Set:** A feature of TomoTherapy that produces CT images by reconstructing scan data. Clinicians are able to generate a TomoImage set at any point in the TomoTherapy process, enabling treatment modification, dose verification, and dose reconstruction.

* **Treatment Plan:** Defines a course of treatment for a given Disease. Based on prescription and dose constraints set by the physician.

* **Virtual Fiducial Lines:** Lines that intersect the physical fiducial markers on the Image Viewer that allow the system to align with a known point on the patient's body. Correspond to the (red) moveable lasers on the Laser subsystem.

* **Virtual Isocenter:** The reference point on the Image Viewer that is alligned with the isocentric line and is nominally 70 cm outside the gantry bore. Corresponds to the (green) stationary lasers on the laser subsystem.

* **Voxel:** A three-dimensional pixel.

* **Window / Level:** The range of values representing tissue density, as mapped onto a grayscale image. 



## Accuray Acronyms and Abbreviations

* **BOM**: *Bill of Materials*, a comprehensive list of all the parts and hardware used to create an assembly.

* **ECO**: *Engineering Change Order*, the means through which a change is implemented in Agile (see [this chapter](https://github.com/taddieken95/Accuray_Tech_Comm_Guide/blob/master/Chapter%205:%20ECOs/READme.md) for information regarding ECOs).

* **ECR**: *Engineering Change Request*, the means through which a change is requested in Agile (see [this section](https://github.com/taddieken95/Accuray_Tech_Comm_Guide/blob/master/Chapter%201:%20Doc%20Requests/Section%202:%20ECRs.md) for information regarding ECRs.

* **OBF**: *Out of Box Failure*, a part / assembly that fails when first installed / used.

* **RMA**: *Returned Merchandise Authorization*, a part / assembly returned to the manufacturer for a refund / repair / replacement.

* **NCMR**: *Nonconforming Material Report*, used to detail nonconforming material found during Quality inspection, or during the movement of materials within a warehouse.

* **MLC**: *MultiLeaf Collimator*, controls the shape of the treatment dose (radiation) distributed from the Linear Accelerator.

* **Linac**: *Linear Accelerator*, responsible for creating the treatment dose (radiation).

* **ATR**: *Assembly Test Record*, document used to outline all tests required in an assembly process. Results of test will be recorded within an ATR.

* **WI**: *Work Instruction*, a document that details a method of assembly / testing. This is the standard "instructional" used by manufacturing.

* **SOP**: *Standard of Procedure*, a document that provides an overhead view of how to approach a process at Accuray. These provide guidance / dictate Accuray methodologies, rather than providing details on assembly. If WIs are "instructionals", think of SOPs as "guidelines".

* **PLE**: *Product Line Engineering*, a methodology of managing a group of related projects in an efficeint manner, taking advantage of the similarities of each project and managing their differences.

* **

> Click [here](https://github.com/taddieken95/Accuray_Tech_Comm_Guide/blob/master/Chapter%203:%20Voicing/Section%204:%20Phrases%20and%20Terms%20to%20Avoid.md) to continue to the next section on phrases and terms to avoid, or click [here](https://github.com/taddieken95/Accuray_Tech_Comm_Guide/blob/master/Chapter%203:%20Voicing/READme.md) to return to the chapter overview.
